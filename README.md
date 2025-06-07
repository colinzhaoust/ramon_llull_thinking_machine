# Ramon Llull's Thinking Machine of Idealization
This is the Github repo for Ramon Llull's Thinking Machine of Idealization 

## Ramon Llull's Thinking Machine
[Ramon Llull's Thinking Machine](https://gwern.net/doc/borges/1937-borges-raymondllullsthinkingmachine.pdf) was invented at the end of the thirteenth century as an instrument of philosophical investigation with multiple rotatable discs of concepts to generate logical combinations as an answer to theological questions.

<p align="center">
  <img src="assets/diagram.jpg" width="550" title=" An illustration of Ramon Llull's Thinking Machine." alt=" An illustration of Ramon Llull's Thinking Machine.">
</p>

In this project, we aim to create vibe research paper titles in a Ramon Llull's Thinking Machine way, i.e., change the "A" in the figure to "LLM". The generated paper titles and outlines can potentially serve as a baseline for [automated idea generation](https://arxiv.org/abs/2409.04109) and [AI research outcome prediction](https://arxiv.org/pdf/2506.00794).

## The Holy Discs:
At the current stage of the project, we identify three discs of concepts:

Theme (A): some themes of research direction, e.g., few-shot.

Domain (B): some domains of tasks people work on, e.g., argument mining.

Architecture (C): some architecture of the research, e.g., Mamba

There are other components to make sure control the expressions:

Template: a template to organize the idea, e.g., Comparing C1 and C2 in B under A

Prompt: a prompt to ask the LLM to polish a template into a research paper title.

## Sources of the concept discs
A seed set from the authors experience.


## Demo
You can check **./main.ipynb** or copy the generated prompt to the Chatbot Web Interface.

## To-dos:
1. Fetch the components from experts and OpenReview data;
2. Create advanced templates and use co-occurrence to steer the sampling;
3. Add fancy punchlines within A,B,C or as a separate D, e.g., xxx is all you need

## Discussion
1. **Important** The quality and the completeness of an idea is orthoganal to if it can be covered by this Ramon Llull's Thinking Machine of Idealization since given the same A+B+C. the angles and depth of the analysis and findings can be very different.
2. This tool is not designed to DDoS the conference review system or detect if certain papers are AI-generated.


## Research Questions and Analysis
R1. The precision and recall of the generated ideas with the actual *CL or ML Conference papers;
R2. How much novelty can we get from these ideas (human annotation);
R3. What are patterns of the out-of-box ideas in the conferences beyond the Ramon Llull's thinking machine.

A1: Self-evolve Ramon Llull's thinking machine;
A2: The variance of the out-of-box ideas in the conferences vs. the in-box generatable ideas;
A3: How to classify trivial/meaningful doable/undoable ideas generated?
A4: Analyze the paradigm shift (research trends) through the years with this tool


## Interested?
If you would like to contribute your concept words or there is any suggestion, you are welcome to open an issue or send me an [email](mailto:xinranz3@andrew.cmu.edu), I will respond to that as soon as possible.