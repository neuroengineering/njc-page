+++
title = "Hierarchical Temporal Memory"
description = "by Connor Leahy"
bref = "by Connor Leahy"
draft = false
weight = 200
+++

<h3 class="section-head" id="h-get-started"><a href="#h-get-started">
<i>Hierarchical Temporal Memory</i> given by Connor Leahy.
<br> <br>
Date: 7.11.2018

</a></h3>
<p>
On 7th of November we had the pleasure to host our first guest of the winter semester - Connor Leahy. Connor is a passionate Computer Science student at TUM. Most of his knowledge is self-taught, in his free time he loves reading about Machine Learning, Neuroscience, Statistics, and Philosophy. He has recently started working at Max Planck Institute of Psychiatry, where he is developing a system to automatically detect dendritic spines with images from two-photon microscopy.  He is one of the organizers of PyData Munich[add hyperlink] and Kaggle Munich[add hyperlink].  As he said himself, his main interest is “Intelligence, not just an artificial intelligence!”

<figure>
  <p align="center">
  <img alt="Image" height="533" src="/img/Connor/connor_3.jpg" width="750">
    </p>
</figure>

Connor gave us a high level overview of the concept of Hierarchical Temporal Memory (HTM), a technology of artificial intelligence that was inspired by the human neocortex.  Our speaker suggested, that we should try to create theories about the brain, that have a new perspective. We already deal with huge amount of data, but limit ourselves to just few ideas.

What is innovative about HTM is the idea behind it. It is based on the neocortex and is able to explain cortical columns, microcolumns and the impact which the activation of distal dendritesr  of a particular microcolumn have on such microcolumn. The author of the method, Jeff Hawkins, suggests that possibly there is an underlying universal algorithm in the neocortex that we should use while creating artificial intelligence.


In order to push the research in a direction different from Deep Learning, in 2004 Hawkins founded his company Numenta Inc., whose research focuses on HTM. The ultimate goal of the company is to solve the human brain by looking at a consistently simplified model, or eventually become a General Artificial Intelligence by reverse-engineering the only best model we have of the brain. All this without distractions from non-biological techniques.

Connor presented us the topic, starting from a brief anatomical perspective and going through the basic units of HTM models and the idea of working with sparse matrices as neuronal activity representation. He then guided us through algorithms on which HTM relies:

Connor started his presentation by a brief anatomical introduction and broaden the perspective later on. He introduced us to the basic units of HTM models and idea of working with sparse matrices as neuronal activity representation. He then guided us through algorithms, based on which HTM works:

* Spatial pooling: only limited amount of  matrix columns being set to 1 at the time
* Temporal pooling: the cell is put into predictive state in the next iteration

<br>
<figure>
  <p align="center">
  <img alt="Image" height="533" src="/img/htm.jpg" width="450">
    </p>
</figure>


Connor finished his talk by briefly mentioning recent developments, without going into details about specific architectures. He did not forget to provide us with resources, that you can find at the bottom of this post. Given the quality of the presentation that he provided us with, it was of no surprise that it was followed by a long discussion session. The talk was given to an audience which mainly consisted of first-semester students of the Neuroengineering master program of TUM, with most of the students having a strong background in Computer Science or Electrical Engineering.  Due to that, the focus shifted to the the basic principle of HTM and its use cases, with novelty detection being highlighted, as we looked for applications that are already being utilized in industry.

Discussion topics covered:

* failed usage of HTM in image classification, which lead to discussion about retina image processing
* similarities between HTM and pattern recognition algorithms rather than predictive model
* HTM having no supervised learning algorithm

Some of the students were highly skeptical about trying to model the brain's functions solely by modeling the neocortex, but after all, that is not the ultimate goal of HTM. It is not supposed to be an ultimate, full framework yet! We also got curious about reasoning behind the HTM, assuming that there have to be more than the 6 microscopically distinguishable layers in the neocortex. In response to why HTM theorizes that the neocortex has to have more than 6 layers, Connor argued that this assumption is made for functional reasons, due to time reasons, he was however not able to provide further details.

<figure>
  <p align="center">
  <img alt="Image" height="533" src="/img/Connor/connor_2.jpg" width="750">
    </p>
</figure>

In summary, the question of applying HTM to image classification, or in a wider sense any form of supervised learning, was a question which elicited fairly many questions. The possibility of implementing neuronal plasticity, especially in a way which does not require back-propagation, such as in the Leabra-framework, seems to be an intriguing future possibility for HTM. Instantiating reward systems would not only open up a wide range of novel applications, but also enrich the modeling of the neocortex in a biologically plausible manner.


But after all this it turned out that for this evening there is one more surprise! One of our organizer Yagmur, that had an opportunity of attending the Neuroscience 2018  conference in San Diego, found Jeff Hawkins himself! As our event was happening, she got to share that with the author of the idea himself, that asked us to provide him with our questions!


We would like to thank our speaker once again!


<figure>
  <p align="center">
  <img alt="Image" height="533" src="/img/Connor/connor_yy.jpg" width="750">
    </p>
  <figcaption>
    Yagmur attending Neuroscience 2018 conference in San Diego, found Jeff Hawkins himself!
  </figcaption>
</figure>


<b>Resources:</b> <br>
presentation: <br>
https://drive.google.com/file/d/1m0rKf09NcF15GYza7Iwfuj64ADdvGxpI/view?usp=sharing

Additional resources provided by Connor: <br>
[1] Mountcastle, V. B. (1978): "An Organizing Principle for Cerebral Function: The Unit Model and the Distributed System” <br>
[2] Hawkins, Ahmad (2016): “Why Neurons Have Thousands of Synapses, A Theory of Sequence Memory in Neocortex” <br>
[3] Hawkins, Ahmad, Cui (2017): “A Theory of How Columns in the Neocortex Enable Learning the Structure of the World” <br>
[4] Hawkins, Lewis, Purdy, Klukas, and Ahmad (2018): “A Framework for Intelligence and Cortical Function Based on Grid Cells in the Neocortex” <br>

</p>
