# Towards Accessible Improved Generative Adversarial Networks

The first goal of this project is to implement GANs as desribed first in:
> [*Generative Adversarial Networks*, I. J. Goodfellow et al. , Jun 2014.](https://arxiv.org/abs/1406.2661)

GANs were vastly improved since then, with architectural changes, or changing the loss function and our goal is to
provide detailed notebooks about those main improvements.
The notebooks themselves won't go too much in detail about the theory or our results, which is why we also wrote a guide summarizing everything,
with first some theory and them some experiments, all in one place.

We also wanted to show some issued that can occur when training GANs and how to solve those common problems, such as *mode collapse* for instance.

Here is a list of present notebooks and what you will find in them:

|Notebook name| Content |
|---|---|
|* GAN *| Implementation of the original GAN paper|
|* Conditional GAN *| Implementation of conditional GAN |
|*Strong X *| Example of having either a strong generator or a strong discriminator |
|* DCGAN *| Implementation of DCGAN |
|* Conditional DCGAN *| Implementation of conditional DCGAN |
|* Kernel size of NxN *| Use of various kernel sizes |
|* Minibatch discrimination *| Implementation of minibatch discrimination |
|* Experience replau *| Implementation of experience replay |
|* Noisy labels *| Implementation of noisy labels |
|* Virtual Batch Normalization *| Implementation of Virtual Batch Normalization |
|* WGAN with gradient penalty *| Implementation of Wasserstein GAN with gradient penalty |

## Technology used

For this project, we used the following libraries :
 - Tensorflow 2 

