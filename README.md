# AICS-project-2024
It's a public repository to store my project for my master course *Artificial Intelligence: Cognitive Systems*. In this course, we have learned about grouded language, computer vision and human-robot interaction. 

For my course project, I want to explore if interactive learning can improve spatial reasoning in Visual Question Answering (VQA) tasks. I am intended to utilize CLEVR dataset and realize an online, incremental learning approach.

However, I encountered practical implementation challenges, such as the mismatch between batch-encoded inputs and item-specific human corrections in natural language. So the focus of the project has a little conversion, I mainly compare the results of different architectural choices and training strategies.

Basic structure:

`code/`: for *aics_project.ipynb*, the main jupyter notebook supporting my project

`notes/`: for my old submissions; here *old_project.ipynb* includes the results with *max_program_length* = 3

`paper/`: for my course report and later presentation 

*The CLEVR dataset is available on the mlt gpu, so I don't upload here.
