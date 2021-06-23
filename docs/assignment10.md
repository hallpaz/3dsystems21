
** LABORATORY CLASS 10: Neural Radiance Fields (NeRF) **

In this class, we will learn about *Neural Radiance Fields* a technique that allows us to synthesize novel views of a scene from a sparse set of input views. This algorithm uses an implicit function representation of a scene encoded in a fully connected deep network, which takes a 5D coordinate vector of position and viewing direction as input, and outputs the volume density and radiance. We'll learn how to use PyTorch3D to represent and render implicit surfaces and also how to reproduce results similar to NeRF's on Google Colab.

**The goals of this practice are the following:**

-   Understand how to represent implicit surfaces using deep neural networks.
-   Understand some techniques to render implicit surfaces
-   Learn how to implement a "NeRF-like" pipeline using PyTorch3D

## Instructions and submission:

You are not required to deliver anything as assignment this time. We recommend you study the references below and ask us any questions if you have doubts. 

<a href="https://colab.research.google.com/github/hallpaz/3dsystems21/blob/main/assignments/LabClass10.ipynb" target="_blank"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>


## References

1. Ben Mildenhall, Pratul P. Srinivasan, Matthew Tancik, Jonathan T. Barron, Ravi Ramamoorthi, & Ren Ng (2020). [NeRF: Representing Scenes as Neural Radiance Fields for View Synthesis](https://www.matthewtancik.com/nerf). In ECCV.
2. Frank Dellaert. NeRF Explosion 2020 ([personal blog post](https://dellaert.github.io/NeRF/))
3. [Volumetric Reconstruction in Pytorch3D](https://youtu.be/MOBAJb5nJRI). An Introduction to PyTorch3D, SIGGRAPH Asia 2020 course.
4. Hallison da Paz and Luiz Velho. [Machine Learning for New Media](https://www.visgraf.impa.br/Data/RefBib/PS_PDF/tr-03-2021/tr-03-2021.pdf). Technical Report TR-03-2021, VISGRAF Lab - IMPA, 2021.
5. Matthew Tancik: Neural Radiance Fields for View Synthesis
<iframe width="560" height="315" src="https://www.youtube.com/embed/dPWLybp4LL0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>