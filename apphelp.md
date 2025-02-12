## Steps to ensure your access token is added to app.py AND/OR run locally on Docker (2/12/2025)

1. Ensure the following, [1) you cloned the First_agent Space to your HuggingFace Space, 2) you created an Access Token in your HuggingSpace user profile. (Settings/Access Tokens) 3) Not sure if needed, but I made sure I got access to Meta's Llama 3.2 language models & evals (Shows in Settings/Gated Repositories section) may take 1+hours].
2. Start editing your app.py file, and at the top add this import:
    import os
3. I added a few different models in comments in the below code. In the area of app.py code where model is defined, replace with this code:
  ```
  # model_id='deepseek-ai/DeepSeek-R1-Distill-Qwen-32B',
  # model_id='Qwen/Qwen2.5-Coder-32B-Instruct',
  model_id='meta-llama/Llama-3.2-3B-Instruct',
  custom_role_conversions=None,
  token=os.getenv('HF_TOKEN'),   #https://huggingface.co/docs/smolagents/reference/models#smolagents.HfApiModel
  ```
3. Make sure you have a browser open to your First_agent Space, click on the Settings link. In the Variables and secrets' section, add a new secret by clicking 'New secret'. I named it 'HF_TOKEN', then put your access token (from Step 1) as the value.
4. I tried running the Space, but the service still seemed overloaded. So, I tried running it locally with Docker.
5. Download Docker Desktop (I used the Windows download) and login to Docker.
6. To get the Docker command, make sure your in your First_agent Space and go to app.py file. Click button to the right of settings, then 'Run Locally'. It will give you a link similar to this:
    docker run -it -p 7860:7860 --platform=linux/amd64 -e HF_TOKEN="YOUR_VALUE_HERE" registry.hf.space/yourhfusername-first-agent:latest python app.py
7. Before entering the above command in the Docker Terminal (button at bottom right of Docker Desktop), change youorhfusername to your HuggingFace username  AND  enter your Access Token in the HF_TOKEN area.
8. Open the link locally, 127.0.0.1:7860 and your chatbot should now give you a correct response when you ask something like "What is the time in New York?"
