

# Large Language Models and Chat GPT

**Time:** Mondays 6:30-8:30pm

**Room:** 5417

**Instructor**: Michelle McSweeney

**Email**: [michelleamcsweeney@gmail.com](mailto:michelleamcsweeney@gmail.com)

**Course Site**: [https://github.com/michellejm/LLMs-fall-23](https://github.com/michellejm/LLMs-fall-23)

**Slack**: ask for invite

_This syllabus is subject to change based on the goals of the individuals in the class and where the conversation takes us._


## Description

Large language models (LLMs) such as ChatGPT and Bard have demonstrated an uncanny ability to interpret and generate text, and with that, the potential to revolutionize industries and reshape society. However, their complexity makes them difficult to understand, often hiding their implicit assumptions. This course introduces students to the development and use of LLMs in natural language processing (NLP), covering fundamental topics in probability, machine learning, and NLP that make LLMs possible. With this technical foundation in view, students will explore the social and ethical implications of LLMs, including privacy, bias, accountability, and their impact on creative production, education, and labor. By the end of the course, students will have a solid understanding of the basic technical foundations and will be able to contribute to conversations on the social and ethical implications of LLMs. 

Note: An introductory level familiarity with Python is required.


## Objectives

By the end of this course, you will be able to:



* Build an n-gram model and explain their limitations
* Explain the role of tokenization in NLP
* Explain what a word vector is and understand how they are calculated
* Fine tune a LLM for a specific task
* Explain the basics of how a Neural Network works
* Explain what a transformer model is and when to use them
* Contextualize the role of reinforcement learning in modern LLM’s
* Hold and justify your thoughts and opinions about:
    * Labor, production, creativity, and ownership of products created with LLM’s
    * The risk to privacy with LLM’s
    * The relative importance and implications of the biased responses and toxicity that LLM’s produce
    * The dangers and limitations related to hallucinations by LLM’s
    * The role of LLM’s in human relationships 


## Materials

There is no required textbook for this course, but a few rather helpful resources depending on what direction you want to take your final project.



* Technical
    * Jurafsky and Martin, 2023. [Speech and Language Processing](https://web.stanford.edu/~jurafsky/slp3/)
    * Nielsen, 2019. [Neural Networks and Deep Learning](http://neuralnetworksanddeeplearning.com/)
    * Hugging Face [NLP Course](https://huggingface.co/learn/nlp-course/chapter1/1)
* Social
    * Future of Life Institute, 2023. [Pause Giant AI Experiments: An Open Letter](https://futureoflife.org/open-letter/pause-giant-ai-experiments/)
    * Saravia.[ An Overview of Troubling Trends in Machine Learning Scholarship](https://dair.ai/posts/An_Overview_of_Troubling_Trends_in_Machine_Learning_Scholarship/)
    * Tegmark, 2018. Life 3.0: [Being Human in the Age of Artificial Intelligence](https://www.penguinrandomhouse.com/books/530584/life-30-by-max-tegmark/). (lecture on [YouTube](https://www.youtube.com/watch?v=oYmKOgeoOz4))


## Design of this course

This course takes 2 approaches to understanding the role of Large Language Models (llm’s): technical and social. The primary goal of this course is to equip you with the technical foundation necessary to have an informed yet critical opinion about the role of large language models in society and develop that opinion in conversation with your peers. These two parts are equally important.


### Social

Every other week (S), we will discuss one area of social importance. The areas I’ve selected are significant, but not comprehensive (this selected topics may change before the start of the semester, survey depending). 

Everyone will do the readings and participate in the discussion. The discussion will be lead by 3 students (everyone will lead one time). If it is your group’s week, you will work with your group to deep dive into a topic. Please use the Slack channel for your topic to discuss and post any additional readings/watchings/listenings you've found particularly insightful. There are assigned readings for everyone, but when it is “your” week, the expectation is that you will go beyond those readings and consume a variety of opinions about the topic at hand. The group work part of it is to have a conversation before the class session to discuss what you have found, what you have been thinking about, and the biggest questions and issues that are still unanswered. Pay particular attention to the assumptions you make in order to reach any opinions you hold. 

After the class discussion, the “lab” is to write a 1-3 paragraph opinion about the topic. This opinion should be posted either on the CUNY Commons, a personal website, or your Github. The purpose of the post is to record your thoughts on the topic for both your future self and as part of a portfolio of work on LLM’s. While we often think of portfolios as showing technical skill, being able to demonstrate that you have an informed opinion on the social implications of LLM’s is just as important. 


### Technical

Every other week will cover a technical aspect of LLM’s. This is an extremely rapid pace, but should give you a good, high-level understanding of how these models work. We will not going into the math beyond probability. After each technical lesson, there is a lab. Except for the first one (on prompt engineering), all of the labs are designed to be completed in Python. The Jupyter Notebooks for them will be posted on Github. 

It is possible to simply copy-paste the labs, though I don’t recommend this. At each step, be sure you understand why we are completing that step – even if you do not understand what the code itself does. Read the instructions and then manually copy the code into your own notebook. Test it to see what it does. Recommendations for testing code will be posted on Github. 

The goal of the lab is to understand how LLM’s work and how to use them, not to make you a better programmer, so do worry about being able to write the code yourself. Likewise, do not worry about understanding the syntax (though if that is your interest, by all means, go for it). 

**Your code and short written summary of what you did should be posted either on the CUNY Commons, a personal website, or your Github.**


### Final Project

Your final project should incorporate both the technical and social aspects of LLM’s, though the balance is up to you. The shape of the project will depend on your goals for the course and your own portfolio. 

All projects will have a proposal, a proof of concept, and a final presentation. 

The proposal should contain:

* A description of the product you will create. If this is a written paper, that’s easy enough. If it is an LLM-powered project, this will have to be more detailed.
* A statement of the question or issue that this project addresses. What are the social implications/questions/challenges that you will explore. Even the most technical project will have social implications.
* Identify what kind of language model you will be working with. I.e., a base model, fine tuned model, etc. 
* State how it will be made public (i.e., a website, conference, journal, etc.)
* Timeline identifying each of the steps you have to complete by when.

We will discuss your **proposal** at the 1:1 meeting on **November 13**. These will be conducted via Zoom. In this meeting, we will agree on what is reasonable to create in one month and flag any outstanding issues. 

The **proof of concept** is due **November 27**. This is simply the most bare bones version of your project. It might not work, it might have missing pieces, but you should have something beginning to resemble the project we agreed on. The purpose of this intermediate step is to be sure you are on the right path and to get feedback on this very rough draft.

The week of **November 27 - December 4**, you will work in groups of 3 to give **peer feedback** on your projects. This feedback can be delivered via video, or you can coordinate synchronous feedback sessions. 

The format of the **final presentations on December 11**. The format will be decided by majority vote. 


#### Technical Projects

Primarily technical projects that leverage LLM’s to solve a problem, answer a question, create a product, etc. will likely take the form of a website in some way. Such projects should also have a written component that addresses the potential social or political implications related to the project. The final artifact must be public facing in some way. 

Some examples adopted from [this Medium post](https://towardsdatascience.com/10-exciting-project-ideas-using-large-language-models-llms-for-your-portfolio-970b7ab4cf9e):

* A cover letter generator that takes user input and feeds it into a prompt template, which is then passed to the ChatGPT API, and the response returned to the user. This could be a Github repo with the necessary code, a few examples of what it can produce, and a ReadMe that explores the implications of having ChatGPT write cover letters. If you want to go above and beyond, possibly add a GUI wrapper to make it easy to use,
* A personalized chatbot could be a Github repo with the code you used to fine tune the LLM, the training data, examples of what it can produce, and a ReadMe that explores the implications of creating customized Chatbots. 
* A podcast summarizer could be a Github repo with the code you used to prepare the transcripts and to analyze them, a few examples of what it can produce, and a ReadMe that explores the implications of such summaries – including the benefits and what can go wrong. 
* Etc.


#### Social Projects

Primarily social projects that explore a topic or question will likely take the form of a research paper (though alternative proposals are welcome!). As part of the exploration, they should engage in a systematic way with an LLM either to demonstrate behavior, validate claims, or otherwise support the arguments being made. 

Some examples include:

* Explore how toxicity does or does not have damaging effects on society. Write a paper bringing together current research and thinking about the effects of toxicity and use prompt engineering to systematically validate those claims or work through a series of toxicity prompts in different models. Make this paper public by publishing on a website or submitting to a conference.
* Trace the history of bias in machine learning in a written paper that will either be published to a website or submitted to a conference/journal. Explore various dimensions of bias in one or more base models, or fine tune a model to be more or less biased. 
* Explore what authorship and/or copyright mean in a world where LLM’s are trained on large swaths of data from the internet. Generate writing in the style of a specific author as an example. 
* Etc.


## Grading


<table>
  <tr>
   <td>Technical Labs
   </td>
   <td>20%
   </td>
  </tr>
  <tr>
   <td>Social Labs
   </td>
   <td>20%
   </td>
  </tr>
  <tr>
   <td>Leading discussion 
   </td>
   <td>10%
   </td>
  </tr>
  <tr>
   <td>Final project, feedback, and presentation
   </td>
   <td>50%
   </td>
  </tr>
</table>


All grades are based on completion. 


## Schedule


<table>
  <tr>
   <td>
   </td>
   <td><strong>Date</strong>
   </td>
   <td><strong>Topic</strong>
   </td>
   <td><strong>Lab (due following Sunday)</strong>
   </td>
  </tr>
  <tr>
   <td>1
   </td>
   <td>Aug 28
   </td>
   <td>Introduction to course, N-grams

   </td>
   <td>Prompt Engineering ChatGPT
   </td>
  </tr>
  <tr>
   <td>
   </td>
   <td>Sept 4
   </td>
   <td>LABOR DAY - no class
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>2 (T)
   </td>
   <td>Sept 11
   </td>
   <td>Tokenization & word vectors
   </td>
   <td>N-grams & Tokenization 
   </td>
  </tr>
  <tr>
   <td>3 (S)
   </td>
   <td>Sept 18
   </td>
   <td>Bias & Toxicity
   </td>
   <td>Bias or Toxicity
   </td>
  </tr>
  <tr>
   <td>
   </td>
   <td>Sept 25
   </td>
   <td>YOM KIPPUR - no class
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>4 (T)
   </td>
   <td>Oct 2
   </td>
   <td>Word Vectors & maybe Neural Networks
   </td>
   <td>Word vectors
   </td>
  </tr>
  <tr>
   <td>
   </td>
   <td>Oct 9
   </td>
   <td>INDIGENOUS PEOPLES DAY - no class
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>5 (T)
   </td>
   <td>Oct 10
   </td>
   <td>Classes follow a Monday schedule - but we will <strong>not </strong>meet
<p>
None
   </td>
   <td><strong>None</strong>
   </td>
  </tr>
  <tr>
   <td>6 (S)
   </td>
   <td>Oct 16
   </td>
   <td>Privacy, copyright and intellectual property
   </td>
   <td>Privacy or Copyright
   </td>
  </tr>
  <tr>
   <td>7 (T)
   </td>
   <td>Oct 23
   </td>
   <td>Transformers & Attention
   </td>
   <td>BERT
   </td>
  </tr>
  <tr>
   <td>8 (S)
   </td>
   <td>Oct 30
   </td>
   <td>Labor & Creative production
   </td>
   <td>Labor or Creative Production
   </td>
  </tr>
  <tr>
   <td>9 (T)
   </td>
   <td>Nov 6
   </td>
   <td>Fine Tuning
   </td>
   <td>Fine Tuning
<p>
Project Idea due 11/12
   </td>
  </tr>
  <tr>
   <td>10
   </td>
   <td>Nov 13
   </td>
   <td>1:1 Meetings via Zoom
   </td>
   <td>Project Proposal due 11/19
   </td>
  </tr>
  <tr>
   <td>11 (S)
   </td>
   <td>Nov 20
   </td>
   <td>Hallucinations & Misinformation
   </td>
   <td>Hallucinations or Misinformation
   </td>
  </tr>
  <tr>
   <td>12 (T)
   </td>
   <td>Nov 27
   </td>
   <td>Performance Evaluation
   </td>
   <td>Project
   </td>
  </tr>
  <tr>
   <td>13 (S)
   </td>
   <td>Dec 4
   </td>
   <td>Emergent Behaviors and Performance
   </td>
   <td>Project
   </td>
  </tr>
  <tr>
   <td>14
   </td>
   <td>Dec 11
   </td>
   <td>Presentations 
   </td>
   <td>Revisions
   </td>
  </tr>
  <tr>
   <td>15
   </td>
   <td>Dec 18
   </td>
   <td>Final versions due
   </td>
   <td>
   </td>
  </tr>
</table>



## Readings

_Please complete readings listed for each date before the class session. Some topics specify how many to read. For technical topics, they all cover the same things at various levels of math and detail. For social topics, there are a lot of voices raising a lot of good points, I’ve only scratched the surface here._

_Coding System:_

**_Technical:** Most math, typically the most in-depth and detailed explanation_

**_Mid-level**: Getting this right is hard, some of these will be more technical than others_

**_Intuitive**: Where possible, I’ve tried to find an intuitive explanation that has minimal math. _

**_Canonical**: Some articles are transformational or famous or becoming part of the canon - even if you don’t finish these, you should be aware of them._


August 28

* Fill out the survey

* Referenced readings
    * Anthropic, 2023. [Claude's Constutition](https://www.anthropic.com/index/claudes-constitution)
    * Carlsmith, 2021. [Is Power-Seeking AI an Existential Risk?](https://arxiv.org/abs/2206.13353)
    * Chomsky, Roberts, and Wartmull, 2023. [Noam Chomsky: The False Promise of ChatGPT](https://www.nytimes.com/2023/03/08/opinion/noam-chomsky-chatgpt-ai.html?unlocked_article_code=pnmBGNiEj2AJJqPZ7dhRiRoNHKGFi0VA_zbipybVujK--YxV0qU3faEk80LbyCoQy3_h9X8VlIC0sgztkQa73tagVxt5CUY2AtEr97R9XQYNTPvqYBFRm5GkbyqQc3cimJ8K7pcf9nkTBYKtEqB1UiNrT2RkGoIflWJlnyXNV8JW1YLeO7S8E8P2fWnnlLho1wl1_hEYME8xFBrACbYatR2lQaF47lneUDb6ceVepThXSBuJtIGt8iwC_zFGMlgM53gJsbw5qZCWWyGBcBIMM30OFKzlM88VHH1Jy9kxvwdF0kvs1mp94BObG7j8mBUaOX7P7_2hzOQYjLiATtBf4_w&smid=url-share). NYTimes.
    * Kocijana, et al., 2023. [The Defeat of the Winograd Schema Challenge](https://arxiv.org/pdf/2201.02387.pdf)
    * Merchant, 2023. [Column: Afraid of AI? The startups selling it want you to be](https://www.latimes.com/business/technology/story/2023-03-31/column-afraid-of-ai-the-startups-selling-it-want-you-to-be). LATimes
    * OpenAI, 2016. [Faulty Reward Functions](https://openai.com/research/faulty-reward-functions)
    * OpenAI, 2017. [Learning from Human Preferences](https://openai.com/research/learning-from-human-preferences)
    * Roose, 2023. [Inside the White-Hot Center of A.I. Doomerism](https://www.nytimes.com/2023/07/11/technology/anthropic-ai-claude-chatbot.html?unlocked_article_code=PSg3AyNc2eeAj4ovwwOc24JLEbuP5ujoKBAZXA_B6_ISnxZUgxZy_YSEGrrM96TbgkXBMFJhjdeVwi_ttol1GiarS9DOph-rktl7bj7Y1DryW2F4MyOgoZ-dixfCJMgijJyJOuqFSqsvNpVJnqTlc5-BzJ1mmG1PC7xwnqeykd0Bzc0InpayGSQUYXdaFPRYhp3A2FFyxl5trPa4G7t1gW_6CdPmQPTQ3wn4x27iE6y0QxhvtO4XfK5MjLcCV-7raJJl23GGECADworc0DaTH7w9p04gYPJNGESE-2Fz4hPSxA5kaNSvZ6ynEa26pjt5KFof4Z69IU_vlchrXwA0OmxiyYct5pOY&smid=url-share). NYTimes.
    * Tegmark, 2023. [The 'Don't Look Up' Thinking That Could Doom Us With AI](https://time.com/6273743/thinking-that-could-doom-us-with-ai/). Time.
    * Vaswani, et al., 2017. [Attention is all you need](https://arxiv.org/abs/1706.03762)



September 11 (T) Tokenization and word vectors (and rest of n-grams)


* N-grams **_Read one _**
    * (Technical) Jurafsky & Martin, 2023**. **[N-gram Language Models](https://web.stanford.edu/~jurafsky/slp3/3.pdf) 
    * (Mid-level) Nguyen, 2020. [N-gram language models Part 1](https://medium.com/mti-technology/n-gram-language-model-b7c2fc322799) and [Part 2](https://medium.com/@seismatica/n-gram-language-models-70af02e742ad) (Medium)
    * Machine Learning TV, 2018. [NLP: Understanding the N-gram language models](https://www.youtube.com/watch?v=GiyMGBuu45w) (YouTube)
    * (Intuitive) Srinidhi, 2019. [Understanding Word N-grams and N-gram Probability in Natural Language Processing](https://towardsdatascience.com/understanding-word-n-grams-and-n-gram-probability-in-natural-language-processing-9d9eef0fa058) (Medium)
* Tokenization **_Read one _**
    * (Technical) Jurafsky & Martin, 2023**.**[Most detailed explanation](https://web.stanford.edu/~jurafsky/slp3/2.pdf) (Jurafsky & Martin)
    * (Mid-level) Hugging Face, 2023. [Tokenizers](https://huggingface.co/learn/nlp-course/chapter2/4?fw=pt) 
* Tokenization [Byte Pair Encoding](https://www.youtube.com/watch?v=HEikzVL-lZU) (Hugging Face)


September 18 (S) Bias and Toxicity **_Read three_**



* (Canonical) Bender, et al., 2021.[On the Dangers of Stochastic Parrots: Can Language Models Be Too Big? 🦜](https://dl.acm.org/doi/10.1145/3442188.3445922)
* (Canonical) Gehmen, et al., 2020. [REALTOXICITYPROMPTS: Evaluating Neural Toxic Degeneration in Language Models](https://arxiv.org/pdf/2009.11462.pdf)
* Hugging Face, 2022. [Evaluating Bias.](https://huggingface.co/blog/evaluating-llm-bias)
* Firth, 2023. [Language models might be able to self-correct biases](https://www.technologyreview.com/2023/03/20/1070067/language-models-may-be-able-to-self-correct-biases-if-you-ask-them-to/)—if you ask them. MIT Tech Review.
* Open AI, 2019. [AI Safety needs social scientists. ](https://openai.com/research/ai-safety-needs-social-scientists) ([full paper is here](https://distill.pub/2019/safety-needs-social-scientists/))
* _There’s a lot written on this topic - please explore_

October 2 (T) Word Vectors & Neural Networks

* Word Vectors **_Read one_**
    * (Technical) Jurafsky & Martin, 2023**.[ Vector semantics and embeddings](https://web.stanford.edu/~jurafsky/slp3/6.pdf)**. 
    * (Mid-level) Espejel, 2022. [Getting Started with Embeddings.](https://huggingface.co/blog/getting-started-with-embeddings) (Hugging Face)

* Neural Networks  **_Watch both of these BEFORE doing the reading_**
    * (Intuitive & Mid) 3Blue1Brown, 2017. [But what is a neural network? | Chapter 1, Deep learning](https://www.youtube.com/watch?v=aircAruvnKk) 
    * (Intuitive & Mid) 3Blue1Brown, 2017. [Gradient descent, how neural networks learn | Chapter 2, Deep learning](https://www.youtube.com/watch?v=IHZwWFHWa-w&list=RDCMUCYO_jab_esuFRV4b17AJtAw&index=2) 
    * _Optional _(Intuitive & Mid) 3Blue1Brown, 2017. [What is backpropagation really doing? | Chapter 3, Deep learning](https://www.youtube.com/watch?v=Ilg3gGewQ5U&list=RDCMUCYO_jab_esuFRV4b17AJtAw&index=3) 
* Neural Network introduction **_Read one_**
    * (Technical) Jurafsky & Martin, 2023**. **[Neural Networks and Neural Language Models](https://web.stanford.edu/~jurafsky/slp3/7.pdf)
    * (Mid-level) Zhou, 2022. [Machine Learning for Beginners: An Introduction to Neural Networks](https://victorzhou.com/blog/intro-to-neural-networks/) ( ignore the coding)
    * (Intuitive) Shipyard. [A Basic Introduction To Neural Networks](https://pages.cs.wisc.edu/~bolo/shipyard/neural/local.html) (U Wisconsin-Madison)

October 10 - No class meeting - only lab

October 16 (S) Privacy, copyright and intellectual property **_Read three_**

* Rahman & Santacana, 2023. [Beyond Fair Use: Legal Risk Evaluation for Training LLMs on Copyrighted Text](https://genlaw.github.io/CameraReady/57.pdf).
* Potter, 2023.[ If ChatGPT wrote it, who owns the copyright? It depends on where you live, but in Australia it’s complicated](https://theconversation.com/if-chatgpt-wrote-it-who-owns-the-copyright-it-depends-on-where-you-live-but-in-australia-its-complicated-202516).
* Kim, et al., 2023. [ProPILE: Probing Privacy Leakage in Large Language Models](https://arxiv.org/abs/2307.01881)
* White House, 2023. [Blueprint for an AI Bill of Rights.](https://www.whitehouse.gov/ostp/ai-bill-of-rights/)
* (Canonical) Carlini, 2020.[ Privacy Considerations in Large Language Models](https://ai.googleblog.com/2020/12/privacy-considerations-in-large.html). (Google)

October 23 (T) Transformers and attention



* Transformers **_Read one_**
    * (Technical) Jurafsky & Martin, 2023. [Transformers and Pretrained Language Models.](https://web.stanford.edu/~jurafsky/slp3/10.pdf)
    * (Mid-level) Muller, 2022. [BERT 101 🤗 State Of The Art NLP Model Explained](https://huggingface.co/blog/bert-101) (Hugging Face)
    * (Intuitive) Google, 2022. [Transformers, explained: Understand the model behind GPT, BERT, and T5](https://www.youtube.com/watch?v=SZorAJ4I-sA)
* Attention
    * (Mid-level) Cristina, 2022. [The Attention Mechanism from Scratch (Sections 1 & 2 - ignore the coding](https://machinelearningmastery.com/the-attention-mechanism-from-scratch/)
    * (Technical, Canonical) Vaswani et al., 2017. [Attention is all you need.](https://arxiv.org/abs/1706.03762)
    * (Summary) Fierro, 2020. [Attention is all you need - summary](https://dair.ai/posts/attention-is-all-you-need/)
    * (Intuitive) Google, 2023. [An overview of the Attention Mechanism.](https://www.youtube.com/watch?v=fjJOgb-E41w)

October 30 (S) Labor & Creative production

* Labor **_Read two_**
    * Eloundou, et al., 2023. OpenAI [GPTs are GPTs: An Early Look at the Labor Market Impact Potential of Large Language Models](https://arxiv.org/abs/2303.10130)
    * May 7, 2023, The Economist. [Your job is (probably) safe from artificial intelligence](https://www.economist.com/finance-and-economics/2023/05/07/your-job-is-probably-safe-from-artificial-intelligence) *Note that you don't need a subscription - just an account to read this)*
    * Lohr, April 10, 2023. NYTimes [A.I. Is Coming for Lawyers, Again](https://www.nytimes.com/2023/04/10/technology/ai-is-coming-for-lawyers-again.html)
    * Klinova & Korinek, Aug 17, 2023. Brookings. [Unleashing possibilities, ignoring risks: Why we need tools to manage AI’s impact on jobs](https://www.brookings.edu/articles/unleashing-possibilities-ignoring-risks-why-we-need-tools-to-manage-ais-impact-on-jobs/)
    * O'Reilly & Zahidi, Sept 2023. World Economic Forum. [Jobs of Tomorrow: Large Language Models and Jobs](https://www3.weforum.org/docs/WEF_Jobs_of_Tomorrow_Generative_AI_2023.pdf)

November 6  (T) Fine Tuning (and RAG)
* Retrieval Augmented Generation (RAG) **Read both**
   * (All) Martineau, IBM, 2023. [Retrieval Augmented Generation (RAG)](https://research.ibm.com/blog/retrieval-augmented-generation-RAG)
   * (All) Hotz, 2023. [RAG vs Finetuning — Which Is the Best Tool to Boost Your LLM Application?](https://towardsdatascience.com/rag-vs-finetuning-which-is-the-best-tool-to-boost-your-llm-application-94654b1eaba7)

* Fine Tuning **Read one**
   * (Technical) Jurafsky & Martin, 2023 [Fine Tuning and Masked Language Models](https://web.stanford.edu/~jurafsky/slp3/11.pdf)
  *  (Mid-level) Hugging Face, 2023. [NLP Course: Fine Tuning a Masked Language Model](https://huggingface.co/learn/nlp-course/chapter7/3?fw=tf)
   * (Intuitive) Talebi, Sept 2023. [Fine Tuning Large Language Models](https://towardsdatascience.com/fine-tuning-large-language-models-llms-23473d763b91)
 
* Fine Tuning in research **Further reading**
   * Gira, et al., 2022. [Debiasing Pre-Trained Language Models via Efficient Fine-Tuning](https://aclanthology.org/2022.ltedi-1.8/)



November 20 (S) Hallucinations and Misinformation
* Overviews
   * Tam, 2023. [A Gentle Introduction to Hallucinations in Large Language Models](https://machinelearningmastery.com/a-gentle-introduction-to-hallucinations-in-large-language-models/)
   * GDELT Project, 2023. [Understanding Hallucination In LLMs: A Brief Introduction](https://blog.gdeltproject.org/understanding-hallucination-in-llms-a-brief-introduction/)
   * Chen [LLM Misinformation Group](https://llm-misinformation.github.io/)
   * Goldstein, et al, 2023. [Forecasting potential misuses of language models for disinformation campaigns—and how to reduce risk](https://cyber.fsi.stanford.edu/io/news/forecasting-potential-misuses-language-models-disinformation-campaigns-and-how-reduce-risk)
* Commentary **Read at least one** 
   * Hsu, Thompson, Feb 2023, NYTimes. [Disinformation Researchers Raise Alarms About A.I. Chatbots](https://www.nytimes.com/2023/02/08/technology/ai-chatbots-disinformation.html
   * Metz, Apr 2023, NYTimes [What Makes A.I. Chatbots Go Wrong?](https://nytimes.com/2023/03/29/technology/ai-chatbots-hallucinations.html)
* Research **Read at least one**
   * Chen & Shu, 2023. [Can LLM-Generated Misinformation Be Detected?](https://arxiv.org/abs/2309.13788)
   * Pan, et al., 2023. [On the Risk of Misinformation Pollution with Large Language Models](https://arxiv.org/abs/2305.13661)
   * Zhou, et al., 2023. [Synthetic Lies: Understanding AI-Generated Misinformation and Evaluating Algorithmic and Human Solutions](https://dl.acm.org/doi/fullHtml/10.1145/3544548.3581318)
   


November 27 (T) Performance Evaluation

December 4 (S) Emergent behavior and performance



* [https://www.nytimes.com/2023/02/16/technology/bing-chatbot-transcript.html](https://www.nytimes.com/2023/02/16/technology/bing-chatbot-transcript.html)
    * The podcast version hard fork [https://www.nytimes.com/2023/02/24/podcasts/hard-fork-bing-reddit-meta.html](https://www.nytimes.com/2023/02/24/podcasts/hard-fork-bing-reddit-meta.html) 
