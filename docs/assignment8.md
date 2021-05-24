
** LABORATORY CLASS 8: DIFFERENTIABLE RENDERING **

In this class, we will learn about *Differentiable Rendering* using rasterization and how PyTorch3D implement it. We''l dive into the concepts we studied about 3D rendering to understand the limitations of traditional rendering for AI Graphics and how we can overcome it. We'll also see how differentiable rendering is an important step to bridge the gap between computer vision and compter graphics.

**The goals of this practice are the following:**

-   Understand what is a differentiable renderer and what we can do with it
-   Understand which parts of the rendering pipeline can be a problem for differentiability
-   Get familiarization with PyTorch3D's differentiable rendering implementation
-   Learn how to setup a renderer with proper attributes in PyTorch3D

## Instructions and submission:

You are not required to deliver anything as assignment this time. We recommend you study the references below and ask us any questions if you have doubts. 


## References

1. PyTorch3d [Renderer Overview](https://pytorch3d.org/docs/renderer)
2. Liu et al, [Soft Rasterizer: A Differentiable Renderer for Image-based 3D Reasoning](https://arxiv.org/abs/1904.01786), ICCV 2019
3. Nikhila Ravi; Jeremy Reizenstein; David Novotny; Taylor Gordon; Wan-Yen Lo; Justin Johnson; Georgia Gkioxari. Accelerating 3D Deep Learning with PyTorch3D. [arXiv:2007.08501](https://arxiv.org/abs/2007.08501), 2020.
4. H. Kato, Y. Ushiku, and T. Harada. [Neural 3D Mesh Renderer](https://hiroharu-kato.com/publication/neural_renderer/). In Proceedings ofthe IEEE Conference on Computer Vision and Pattern Recognition, pages 3907–3916, 2018.
5. M. M. Loper and M. J. Black. [Opendr: An approximate differentiable renderer](https://files.is.tue.mpg.de/black/papers/OpenDR.pdf). In European Conference on Computer Vision, pages 154–169. Springer, 2014.
6. My own experiments on 2020: [https://hallpaz.github.io/3dsystems20/](https://hallpaz.github.io/3dsystems20/)
7. An Introduction to PyTorch3D. SIGGRAPH Asia 2020 course
<iframe width="560" height="315" src="https://www.youtube.com/embed/MOBAJb5nJRI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>