


#### Quiz 1  (ungraded)
Up to this point you have understood the big picture of Agents, what they are and how they work. It’s time to make a short quiz, since **testing yourself** is the best way to learn and [to avoid the illusion of competence](https://www.coursera.org/lecture/learning-how-to-learn/illusions-of-competence-BuFzf). This will help you find **where you need to reinforce your knowledge**.

This is an optional quiz and it’s not graded.

##### Q1: What is an Agent?
Which of the following best describes an AI Agent?
- [ ] A system that only processes static text and never interacts with its environment. 
- [x] An AI model that can reason, plan, and use tools to interact with its environment to achieve a specific goal. (This definition captures the essential characteristics of an Agent.)
- [ ] A chatbot that answers questions without any ability to perform actions. 
- [ ] A digital encyclopedia that provides information but cannot perform tasks.

##### Q2: What is the Role of Planning in an Agent?
Why does an Agent need to plan before taking an action?
- [ ] To memorize previous interactions. 
- [x] To decide on the sequence of actions and select appropriate tools needed to fulfill the user’s request. (Planning helps the Agent determine the best steps and tools to complete a task.)
- [ ] To generate random actions without any purpose. 
- [ ] To translate text without any additional reasoning.

##### Q3: How Do Tools Enhance an Agent’s Capabilities?
Why are tools essential for an Agent?
- [ ] Tools are redundant components that do not affect the Agent’s performance. 
- [x] Tools provide the Agent with the ability to execute actions a text-generation model cannot perform natively, such as making coffee or generating images. (Tools enable Agents to interact with the real world and complete tasks.)
- [ ] Tools are used solely for storing memory. 
- [ ] Tools limit the Agent to only text-based responses.

##### Q4: How Do Actions Differ from Tools?
What is the key difference between Actions and Tools?

- [x] Actions are the steps the Agent takes, while Tools are external resources the Agent can use to perform those actions. (Actions are higher-level objectives, while Tools are specific functions the Agent can call upon.)
- [ ] Actions and Tools are the same thing and can be used interchangeably. 
- [ ] Tools are general, while Actions are only for physical interactions. 
- [ ] Actions require LLMs, while Tools do not.

##### Q5: What Role Do Large Language Models (LLMs) Play in Agents?
How do LLMs contribute to an Agent’s functionality?

- [ ] LLMs are used as static databases that store information without processing input. 
- [x] LLMs serve as the reasoning ‘brain’ of the Agent, processing text inputs to understand instructions and plan actions. (LLMs enable the Agent to interpret, plan, and decide on the next steps.)
- [ ] LLMs are only used for image processing and not for text. 
- [ ] LLMs are not used.

##### Q6: Which of the Following Best Demonstrates an AI Agent?
Which real-world example best illustrates an AI Agent at work?
- [ ] A static FAQ page on a website. 
- [x] A virtual assistant like Siri or Alexa that can understand spoken commands, reason through them, and perform tasks like setting reminders or sending messages. ( This example includes reasoning, planning, and interaction with the environment.)
- [ ] A basic calculator that performs arithmetic operations. 
- [ ] A video game NPC that follows a scripted set of responses.


—-

#### Quiz 2 (ungraded)
**help you reinforce key concepts you’ve just learned**.
This quiz covers Large Language Models (LLMs), message systems, and tools; essential components for understanding and building AI agents.

##### Q1: Which of the following best describes an AI tool?
- [ ] A process that only generates text responses
- [x] An executable process or external API that allows agents to perform specific tasks and interact with external environments (Tools are executable functions that agents can use to perform specific tasks and interact with external environments.) 
- [ ]  A feature that stores agent conversations

##### Q2: How do AI agents use tools as a form of “acting” in an environment?
- [ ] By passively waiting for user instructions
- [ ] By only using pre-programmed responses
- [x] By asking the LLM to generate tool invocation code when appropriate and running tools on behalf of the model (Agents can invoke tools and use reasoning to plan and re-plan based on the information gained.)

##### Q3: What is a Large Language Model (LLM)?
- [ ] A simple chatbot designed to respond with pre-defined answers
- [x] A deep learning model trained on large amounts of text to understand and generate human-like language
- [ ]  A rule-based AI that follows strict predefined commands

##### Q4: Which of the following best describes the role of special tokens in LLMs?
- [ ] They are additional words stored in the model’s vocabulary to enhance text generation quality
- [x] They serve specific functions like marking the end of a sequence (EOS) or separating different message roles in chat models
- [ ]  They are randomly inserted tokens used to improve response variability

##### Q5: How do AI chat models process user messages internally?
- [ ] They directly interpret messages as structured commands with no transformations
- [x] They convert user messages into a formatted prompt by concatenating system, user, and assistant messages
- [ ] They generate responses randomly based on previous conversations



 