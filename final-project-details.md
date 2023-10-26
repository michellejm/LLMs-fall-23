# Final Project

### Key dates:

* Nov 12: Proposal due
* Nov 13: 1:1 meeting to discuss plan (Zoom)
* Nov 27: Proof of concept due
* Nov 27-Dec 4: Get & give feedback from peers
* Dec 4: Email Michelle to say what format your poster will be
* Dec 11: "poster" session

### Overview
Your final project should incorporate both the technical and social aspects of LLM’s, though the balance is up to you. The shape of the project will depend on your goals for the course and how you want to shape your own portfolio. 

All projects will have a proposal, a proof of concept, and a final presentation. 

### Proposal

The **proposal** should contain:

* A description of the product you will create.
   * If this is a written paper, say that and then explain how you anticipate using a LLM like ChatGPT or BERT to support your claims.
   * If this is more of a project, explain what format you expect it to take (a site on the commons, a tool that you build locally and then share on GitHub, etc.
* A statement of the question or issue that this project addresses.
   * What are the social implications/questions/challenges that you will explore. The social implications do not need to fit into the buckets we have covered this semester. The goal is to identify some ways that your project (as you make it, or as a more fully developed project) touches on the issues that LLMs raise. 
* Identify what kind of language model you will be working with.
   * Will you use ChatGPT to collect data, fine tuning BERT to make predictions, or creating an n-gram model?
   * Be clear about why this model is the best choice for your project/to collect your data
* State how it will be made public (i.e., a website, post to GitHub, submit to a conference or journal, etc.)
* Timeline identifying each of the steps you have to complete by when.
   * Is what you have planned reasonable in 4 weeks? 

We will discuss your **proposal** at the 1:1 meeting on **November 13**. 

These will be conducted via Zoom. In this meeting, we will agree on what is reasonable to create in one month and flag any outstanding issues. 

### Proof of Concept

The **proof of concept** is due **November 27**. 

This is simply the most bare bones version of your project. It might not work, it might have missing pieces, you might only have data and no analysis, but you should have something beginning to resemble the project we agreed on. The purpose of this intermediate step is to be sure you are on the right path and to get feedback on this very rough draft.

**Projects**
* Some functioning code
* Placeholders for anything not done that describe as best you can what will go in the placeholder
* A description of how you will improve it with sketches of what you anticipate the final to be.

**Papers**
* Data collected
* Analysis plan
* Rough idea of what you want to say about it and why it matters


### Peer Feedback 
The week of **November 27 - December 4**, you will work in groups of 3 to give **peer feedback**. 

This feedback can be delivered via video, writing, or you can coordinate synchronous feedback sessions. There are three goals with this step:
1. Get feedback on your project to improve it
2. See other people's projects to get a sense of what else is possible
3. Practice giving and receiving constructive criticism

The feedback is essential to the project because it is extremely difficult to make something good without getting a variety of different inputs. This is especially true in all technical matters where there's a long tradition of people thinking that they've designed comprehensive systems only to realize that it has major blind spots. 

But feedback is also hard to give. Here are a few tips:

**Giving**
* Be intellectually generous by truly spending some time with the project and trying to understand where the author is coming from.
* Frame your feedback within the goals of the project. If you have feedback on the goals, that's a different conversation.
* Be clear and specific. It's fine to _start_ a sentence with "hmm, this doesn't resonate with me". Feedback is figuring out what exactly isn't resonating and being specific about it.
   * "It doesn't make sense" is less valuable than "I understood up to this point and stopped understanding after that"
   * "It doesn't feel useful" is less valuable than "I see the utility of doing X, and I don't see the goal behind Y"
* Describe problems, not solutions. The most valuable part of feedback is your perspective. The author likely knows the project better and can see more solutions
* Consider it from another angle. Are there voices missing? Ideas that haven't been covered? Ask if the author has considered them. They might have -- and decided not to include for #reasons. But you also bring fresh eyes and a totally different perspective.
* Stay objective. The feedback should address their project, not what you want their project to be. This is harder than it sounds.
* Be ready to explain your thinking. Feedback almost always needs clarification.
* Never ever make it personal. Feedback is just a stage in the process of a project, it's not about people.

**Receiving**
* Feedback can feel personal. It almost never is. Assume that the goal of the reviewer is to make your project better. This has nothing to do with the quality of your final work, and less than nothing to do with you and your relationship to that person. It's a step in the process of making projects better. 
* Direct your reviewer towards areas you've struggled with or think might be weak spots.
* Set boundaries if there is anything you are absolutely not ready for help with.
* Ask for clarification if you don't understand. Even if you think you do, but have any doubt.

### Final Presentation

The format of the **final presentations on December 11**.

We will do a [poster session](https://en.wikipedia.org/wiki/Poster_session). This can take a lot of shapes and it is completely up to you. We will divide the class into two sections (A & B). Group A will present for 50 mins while Group B meanders and vice versa. We will invite people from across the department.

The room will have tall tables in it where you can set up your laptop. Some suggestions:
* Walk visitors through your project or website
* [Make a poster](https://guides.nyu.edu/posters) about your paper
* Make a slideshow that you walk visitors through
* Record a video of something happening that you talk over for visitors
* Make [a Figma](https://www.figma.com/) that you navigate visitors through

Please create whatever you will feel most comfortable talking to small groups of 1-4 people about for about 5-10 minutes at a time.


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

#### More inspiration

**Projects**
* [This is the Stanford NLP Course final projects](https://web.stanford.edu/class/cs224n/project.html). These projects are a full semester long done by a group of students. Use this to find topic ideas - not project ideas - they are all too big for 4 weeks.

**Datasets**
* [Kaggle NLP Data](https://www.kaggle.com/datasets?tags=13204-NLP)
* [Fake news challenge](https://github.com/FakeNewsChallenge/fnc-1)
* [Quora question pairs](https://www.kaggle.com/c/quora-question-pairs)
* [Yelp](https://www.yelp.com/dataset)
* [Amazon Reviews](https://snap.stanford.edu/data/web-Amazon.html)
* [Cornell Movie Dialogues](http://www.cs.cornell.edu/~cristian/Cornell_Movie-Dialogs_Corpus.html)
* [Stanford question answering](https://rajpurkar.github.io/SQuAD-explorer/)
* [Enron emails](https://aws.amazon.com/de/datasets/enron-email-data/)
* [Jeopardy](https://www.reddit.com/r/datasets/comments/1uyd0t/200000_jeopardy_questions_in_a_json_file/)


* [A very large and comprehensive list](https://github.com/niderhoff/nlp-datasets)
* [The Huggingface datasets](https://huggingface.co/datasets)
