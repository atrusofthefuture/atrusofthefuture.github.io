---
layout: post
title: neural style
---

* in which we discuss art, generative and otherwise

![a preliminary example of nerual style transfer with tf.keras](/assets/images/litoria_output_final.jpg)

I've been toying with the idea of generative art for some time now. The unpredictable nature of the final product of a generative algorithm lends a freshness to the thing that is difficult to accomplish in traditional modes. Whether or not it is authentically art is a question I've tried to ignore generally, in favor of experimentation with new techniques and tools.

Enter Tensorflow:

When Google announced that they would be offering a framework for AI that would be accessible to all I was living in Olympia and making initial efforts at studying computer science in earnest. Although at the time I couldn't think of an application for it, the idea stuck in my mind that there are ongoing efforts to make this thing that seems so lofty to the layman -- artificial intelligence -- accessible and readily usable.

In the intervening years many contributors have made this a reality, and one of the collaborations that I have found fruitful in my studies is the Colaboratory.

With a Jupyter Notebook interface running the iPython kernel the Colaboratory gives us a GPU fueled engine for experimentation with cutting-edge AI techniques and tools.

So far I have barely scratched the surface of what I can do, partly due to the fact that I don't have any particular application for many of its functions -- image recognition, natural language processing, etc. But I have been very intrigured by a technique introduced by one Leon Gatys et al called "Neural Style Transfer."

The core concept is that in the process of having an image analyzed for classification -- say, determining if the image is of a dog or a cat -- a number of features are "extracted" from the image. Which features these are depends on the architecture of the particular neural network algorithm chosen. Conveniently for us, these extracted "weights" are available to us at an intermediate stage in the classification process for use in other, more creative pursuits. Like, for example, transferring the "style" of one image onto the "content" of another image.

It's obvious with some examples. Take the image at top: for style we have Paul Cezanne's "Les jouers de carte", and for content an image of a frog.

More on the way. Also check out my repo "tf-nst" for additional examples.
