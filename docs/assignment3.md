# Loading and Visualizing ShapeNet Data

In this assignment, we will load and visualize some models of the ShapeNet dataset. 

The goals of this practice are the following:

* Learn about the ShapeNet dataset
* Understand the challenges in building a dataset useful for machine learning
* Experiment with PyTorch3D DataLoaders
* Visualize 3D models using Plotly 

1.  Load ShapeNet and R2N2 datasets
2.  Visualize ShapeNet on Plotly
3.  Visualize Batch of R2N2
4.  Change Texture in Plotly
5.  Report about the challenges in dataset creation (ImageNet vs ShapeNet?)
6.  Search about the categories in the dataset

## Instructions:
If you’re using Google Colab, you just need to have a google account and an associated Google Drive. Make a copy of the notebook located below and modify it as requested.

In case you’re choosing to work locally in your machine you must set Anaconda or a `venv` virtual environment, and install the necessary libraries. Create a folder in your Google Drive or in your machine’s workspace. Copy to your drive folder or download the following notebook:

[Assignment 3 Notebook](https://colab.research.google.com/github/hallpaz/3dsystems21/blob/main/assignments/Assignment3.ipynb)
<a href="https://colab.research.google.com/github/hallpaz/3dsystems21/blob/main/assignments/Assignment3.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

1. You'll need to download a small subset of the required datasets to complete this task. 
	2. SHAPENET
	3. R2N2
2. Follow the instructions in the notebook for completing the assignment.
3. If you want, you can build auxiliary .py scripts and call them from your notebook, for organizational purposes.

### Submission for IMPA students
The assignment is due on ~~TBA~~ 2021 at 11:59pm (GMT-3).

IMPA students that are regularly enrolled in the program should send their assignments before the due date to [hallpaz@impa.br](mailto:hallpaz@impa.br) with a copy to [lvelho@impa.br](mailto:lvelho@impa.br). Late delivers will be consider subject to a lower score.

The submission email should be sent with the subject “Assignment 3 - [first-name] - [last-name]”. The assignment can be structured and sent in two ways:

1. If your whole solution is implemented in the same notebook as the one provided for the assignment, then you can send just the .ipynb file as the solution. 
2. If parts of your implementation were done in auxiliary .py scripts, then you must send both the final notebook and the scripts inside a .zip file.
*The organization of the code will also be considered in the evaluation.*

### For remaining students:
For students that are enrolled as “Aluno de Curso Livre” you must not send your assignment to us, since we’ll not be able to evaluate them due to the large number of students and lack of resources from our side.

For students following the course on this modality, we recall that all assignments will be corrected/solved during the Lab classes. Therefore, students must evaluate themselves by comparing our corrections with their solutions. Students taking the writing exam at the end of the semester will be expected to have solved all the assignments.

### References:
[1] [ShapeNet: An Information-Rich 3D Model Repository](https://arxiv.org/pdf/1512.03012.pdf)

<!--stackedit_data:
eyJoaXN0b3J5IjpbMzk4MTYxNDY1LDExNDc1MzQ3OTksLTY4Mz
k1ODc0OF19
-->