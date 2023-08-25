## Prompt Engineering Lab
LLM's and ChatGPT | Fall 2023 | McSweeney | CUNY Graduate Center


**Due:** September 10


### Background
The purpose of this lab is to become familiar with ChatGPT, explore the basics of prompting, and systematically explore what ChatGPT can do. You do not need the premium subscription to complete this lab. 

Most LLM's are text completion models. They are designed to complete sentences that a user has started. ChatGPT can follow instructions, answer questions, label data (and more). This lab only applies to GPT-style models. 

For a more comprehensive introduction, see Shei, 2023. [Best practices for prompt engineering with OpenAI API](https://help.openai.com/en/articles/6654000-best-practices-for-prompt-engineering-with-openai-api)

**Prompting types**
* **Zero-shot prompting**: Asking the model a question or giving it an instruction without any examples to work from
* **Few-shot prompting**: Giving the model a few examples to learn from before asking the question or giving the instruction
* **Chain of thought prompting**: Illustrating the reasoning process to solve a problem

**Key ideas**
* **Be specfic**: Be very clear and specific about what exactly you want the model to do, what the instructions and context are, and be as literal as possible.
* **Specify the output**: Be clear about exactly what you are expecting the final result to be. If you want a csv, specify how exactly you want it formatted. If you want a poem, specify how long it should be and in what format if any.
* **Request for rather than against**: 
* **Act as if**: It is sometimes more successful to assign a persona to a GPT model. For example, "You are an expert in scuba diving and have taught scuba diving all over the world. Explain to me how to prepare my gear for my first dive." Check out [this very creative list of experts](https://www.learnprompt.org/act-as-chat-gpt-prompts/) for more ideas.
* **Use delimiters**: Put instructions at the beginning of the prompt, and use ### or """ to separate the instruction and context 


### Part 1 Define your problem
Write, in natural language, for yourself, what you want ChatGPT to do for you. For example, it can write you a packing list or ideas for dinners, a college admissions essay, or the [perfect break-up song in the style of Phil Collins](https://www.thisamericanlife.org/339/break-up). It can fill out forms for you, answer emails, and 

I will use the example of writing the description for DATA 78000: Large Language Models and ChatGPT. 


