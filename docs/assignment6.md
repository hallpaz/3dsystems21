**ASSIGNMENT 6**

In this assignment, we will learn to simultaneously compute the extrinsic parameters of a set (bundle) of cameras, given multiple pairs of relative transformations between them. It's an instance of the bundle adjustment problem, which is very important for stereoscopy and 3D reconstruction. We'll use PyTorch3D API to set up an optimization process and minimize the discrepancies between pairs of relative cameras. 

**The goals of this practice are the following:**

-   Get more familiarization with camera representations
-   Use the power of neural networks and gradient descent to solve a classic optimization problem
- 

## Instructions:
If you’re using Google Colab, you just need to have a google account and an associated Google Drive. Make a copy of the notebook located below and modify it as requested.

In case you’re choosing to work locally in your machine you must set Anaconda or a `venv` virtual environment, and install the necessary libraries. Create a folder in your Google Drive or in your machine’s workspace. Copy to your drive folder or download the following notebook:

[Assignment 6 Notebook](https://colab.research.google.com/github/hallpaz/3dsystems21/blob/main/assignments/Assignment6.ipynb)
<a href="https://colab.research.google.com/github/hallpaz/3dsystems21/blob/main/assignments/Assignment6.ipynb" target="_blank"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

1. Follow the instructions in the notebook for completing the assignment.
2. If you want, you can build auxiliary .py scripts and call them from your notebook, for organizational purposes.

### Submission for IMPA students
The assignment is due on ~~TBA~~ 2021 at 11:59pm (GMT-3).

IMPA students that are regularly enrolled in the program should send their assignments before the due date to [hallpaz@impa.br](mailto:hallpaz@impa.br) with a copy to [lvelho@impa.br](mailto:lvelho@impa.br). Late delivers will be consider subject to a lower score.

The submission email should be sent with the subject “Assignment 6 - [first-name] - [last-name]”. The assignment can be structured and sent in two ways:

1. If your whole solution is implemented in the same notebook as the one provided for the assignment, then you can send just the .ipynb file as the solution. 
2. If parts of your implementation were done in auxiliary .py scripts, then you must send both the final notebook and the scripts inside a .zip file.
*The organization of the code will also be considered in the evaluation.*

### For remaining students:
For students that are enrolled as “Aluno de Curso Livre” you must not send your assignment to us, since we’ll not be able to evaluate them due to the large number of students and lack of resources from our side.

For students following the course on this modality, we recall that all assignments will be corrected/solved during the Lab classes. Therefore, students must evaluate themselves by comparing our corrections with their solutions. Students taking the writing exam at the end of the semester will be expected to have solved all the assignments.

### References:
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTUyNzExODA0Myw0NDYwNzQ1OTksMzM5Nj
YzNzI3LDk5NDUyNjA2NCwtMTEwMTQzODgzOV19
-->