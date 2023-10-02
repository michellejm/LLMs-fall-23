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
* **Request for rather than against**: Make statements in the affirmative (i.e., Write more academically vs. Don't write colloquially)
* **Act as if**: It is sometimes more successful to assign a persona to a GPT model. For example, "You are an expert in scuba diving and have taught scuba diving all over the world. Explain to me how to prepare my gear for my first dive." Check out [this very creative list of experts](https://www.learnprompt.org/act-as-chat-gpt-prompts/) for more ideas.
* **Use delimiters**: Put instructions at the beginning of the prompt, and use ### or """ to separate the instruction and context 

#### The GPT Interfaces
* [ChatGPT](https://chat.openai.com/) The GUI chat interface that most people are familiar with.
* [ChatGPT Playground](https://platform.openai.com/playground) An interface that allows you to set custom parameters for your task
* [ChatGPT API](https://platform.openai.com/docs/guides/gpt) The Automated Programming Interface to make multiple calls. The topic of a future lab.

### Part 1 Define your problem
Write, in natural language, for yourself, what you want ChatGPT to do for you. For example, it can write you a packing list or ideas for dinners, a college admissions essay, or the [perfect break-up song in the style of Phil Collins](https://www.thisamericanlife.org/339/break-up). It can fill out forms for you, answer emails, write essays, etc. 

You can use any writing assignment you like for this lab. If you are stumped trying to think of an example, try having it write a final paper for a course on the ethics of AI. Use the present course for the details. 

Before prompting, try to be as specific as you can about exactly what you are looking for -- what do you expect it to do? How do you think it will perform?

_For this exercise, avoid using code prompts: you want some natural language responses._

### Part 2: The Chat interface

For every step, keep track of your impressions. You don't have to copy the entire text, but after each response, take a few notes on how you think it performed.

1. Put the natural language prompt you wrote for yourself into the ChatGPT Chat Interface.
2. Try to help it get better in a conversation i.e., "write a little more academically" or "be more critical of AI". The context for the "Chat" you are having is stored in this chat's history, allowing it to continue to iterate on your tweaking instructions.
3. Start a new chat. This time be very specific and organized. Organize your prompt to first be a request for a final paper. Tell it how many words you want it to be, and specify the style that you want it to be written in (i.e., written by X type of person). Then enumerate the points you want it to address, being specific about the stance you want it to take. Optionally coach it to improve this essay.
4. Start a new chat. Ths time give it the same prompt you did in step (3), but rather than specifying the style that you want it to be written in, find a piece of writing on the internet that you want it to emulate (i.e., an Atlantic article or NYTimes, etc.). Write the prompt and then put the piece of writing beneath it, separated by ###


### Part 3: The Playground Interface

For every step, keep track of your impressions. You don't have to copy the entire text, but after each response, take a few notes on how you think it performed.

1. You can use the same prompt or a different one here, but it should be simple (i.e., meal planning, packing lists, etc.)
2. First put the prompt into ChatGPT Chat interface. Respond with some modification (i.e., I don't like peppers, please revise your suggestions).
3. Try the same thing in the default Playground interface. In the first message, give the prompt. In the next message, give the modification in the same way you did in the Chat interface. 
4. The Playground is the API playground, so it behaves as the API does. The Chat interface is a wrapper around the GPT models. They do not behave the same way.

### Part 4: Modifying the Playground

For every step, keep track of your impressions. You don't have to copy the entire text, but after each response, take a few notes on how you think it performed.

The purpose of the Playground is to configure the settings for an API. It therefore has controls for how to interact with the model. We'll explore those controls. Note that the chats are not saved here, if you refresh the page, they disappear (and also allegedly not used for training data).

1. You can use the same prompt or a different one here, but it should be creative somehow (i.e., write a 20 word poem, movie summary, etc.)
2. Change the Maximum Length to whatever you think it will need. Note that the token limit for 3.5 is 4096 tokens, which includes the prompt and completion (response). This is about 3000 words, we'll cover this in more detail when we cover tokenization. The Maximum Length controls how many words are used for the completion.
3. First put the prompt into the Playground with the default settings and see what it generates.
4. Change the temperature. Higher will make it more deterministic. Lower will make it more random. Try this in both directions. We will cover this when we cover n-grams. Return Temp to 1.
5. Add some stop sequences. Try a really general one (like "the") to see how the model adjusts to not include it.
6. Change the top_p. This has a similar effect to Temperature, but the way it samples over the posible next words is slightly different. Pay special attention to how it compares to Temperature
7. Change either Frequency Penalty or Presence Penalty. This might not have a large effect with a small prompt, but important to know that they are techniques to make responses less repetative.

### Part 5: Common Applications

For every step, keep track of your impressions. You don't have to copy the entire text, but after each response, take a few notes on how you think it performed.

1. Open the Playground Interface
2. In a new tab, navigate to the [Examples library](https://platform.openai.com/examples) (in the upper left menu bar)
3. Choose an example that is NOT "helpful assistant" (i.e., Socratic Tutor)
4. Write a prompt tailored to the option you chose (i.e., How does computer vision work?)
5. Write the same prompt in the default, helpful assistant interface. Compare these responses.
6. Inspect the Python code at the bottom of the example you chose.
  
  
 **key questions**  Looking at the code, what parameters are being passed, and what changed from the default? What does that indicate about the relationship between the settings of the LLM and user behavior (and/or user belief). 


### Part 6: Coding

For every step, keep track of your impressions. You don't have to copy the entire text, but after each response, take a few notes on how you think it performed.

1. Using either the Chat interface or the Playground interface, ask ChatGPT to write the code for a simple program (i.e., a python program for a bigram language model).
2. If use the Chat interface, refine your request until you are happy with the result. Some things you can ask are:
  1. Perform certain tasks (i.e., "return the probability of the next 5 most common words given a seed word", generate 10 words from a seed word).
  2. Use a specific package you want (i.e., NLTK)
  3. Refactor the code to make it more efficient, comment every step, or if you are new to programming, "rewrite this code without classes")
4. Ask ChatGPT to identify some edge cases that you should test and write the corresponding unit tests. Unit tests are programmatic ways to ensure that your code words.
5. Copy your code into your favorite IDE and run it. Does it work? If not, use ChatGPT to fix it.

### Submission

This lab does not need to be posted to your Github since the purpose was strickly to become familiar with the interface and some options. Please send me your lab notes via email to michellamcsweeney@gmail.com in an format. They do not need to be tidy. I am looking to be sure that you are making good notes for yourself should you decide that you want to do an experiment-style final project. 

### Conclusion

By now, you have a good sense of what the different interfaces do, your options for using ChatGPT, and how to get it to produce better responses. Really we have just scratched the surface and not even touched Chain of Thought Reasoning or some other techniques. Prompt Engineering is everywhere, but if you want to learn more, some good resources are:
* Saravia, 2022. [DAIR Prompting Guide](https://www.promptingguide.ai/introduction/tips)
* Machine Learning Mastery, 2023. [Prompt Engineering for Effective Interaction with ChatGPT](https://machinelearningmastery.com/prompt-engineering-for-effective-interaction-with-chatgpt/)
* Wei, 2022. [Chain-of-Thought Prompting Elicits Reasoning in Large Language Models](https://arxiv.org/abs/2201.11903)



