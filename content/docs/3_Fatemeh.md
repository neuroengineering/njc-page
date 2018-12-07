+++
title = "Multimodal Image Processing Application"
description = "by Fatemeh Nejatbakhsh"
bref = "by Fatemeh Nejatbakhsh"
draft = false
weight = 200
+++

<h3 class="section-head" id="h-get-started"><a href="#h-get-started">
<i>Multimodal Image Processing Application</i>.
<br> <br>

Date: 29.12.2018 <br>

</a></h3>
<p>
Our recent talk happened on the 29th of November. We had a pleasure of hosting Fatemeh Nejatbakhsh, who who was a recent a Visiting Researcher at <i>Columbia University</i> (where she worked with Prof. Gregory C Sharp) and is a PhD candidate at Department of Neurology of <i>Ludwig-Maximilian Universität</i> in Munich. Our speakers interest consists of developing medical devices but also methods for biomedical image processing, she is also passionate about: vestibular system, brain imaging and cognitive studies.

We started the evening by networking and a short introduction to our website and the speaker. From there, Fatemeh smoothly took over and introduced us to her background. She invited the students to cooperate with the wonderful groups she had a pleasure to work with before Prof. Dr. Nassir Navab.

<figure>
  <p align="center">        
  <img alt="Image" height="533" src="/img/Fatemeh/F1.JPG" width="750">
    </p>
  <figcaption>
    Our speaker Fatemeh right before her talk!
  </figcaption>
</figure>


Due to our variant backgrounds, Fatemeh had to start her talk from the basics. She quickly explained the division of medical image processing into: structural and physiological. Then our speaker decided to proceed with detailed description of the first class. In structural imaging human body can be compared to cars or building, that can be split into several different, smaller structures. Each structure could have a pre-defined role.

The next big question that emerged: <i>how do we actually do it?</i> Fatemeh prepared the outlook of a general pipeline of image processing, that consisted of:

<u>a. Data acquisition</u>
Part of the process consisting of the acquisition of data and its import/load. Main challenge of this procedure is a transfer of a different types of data together.

<u>b. Analysis</u>, that could be split into 3 subparts: <br>
preprocessing <br>
processing <br>
post-processing <br>

We then focused on preprocessing. First step, that comes before the analysis: you have to decide what kind of analysis you are going to perform and deal with characteristic problems, such as: distortion or noise. Then, you need to compare your results with the Reference: Fixed Image, that can be understood as a template, that you pick before the analysis.
In here, you deal with an optimization problem: trying to minimize the difference between voxels of your dataset and the reference. We also briefly went thought an introduction to inter-subject (with different modalities) and intra-subject registration (between different subjects).

We then proceed to our first interactive demonstration: live introduction to <i>3D slicer</i>.
<i>3D slicer</i> is an open source software, that you can easily download. It is also fully compatible with Python. To start with image analysis you can: pick your direction or pick the intensity. From there we moved to a demo, based on actual brain images. Fatemeh proved that you need experience to understand how that kind of images should be processed.


<figure>
  <p align="center">        
  <img alt="Image" height="533" src="/img/Fatemeh/F3.JPG" width="750">
    </p>
</figure> <br>


<u>c. Test and validation</u><br>
Perhaps the most important step, in which you compare your outcome of the project to what is expected from yo, with the use of already defined validation/measurement scores.


From there it felt like a natural point to look at some of Fatemeh’ work, her PhD project. To do so she had to explain briefly the importance of Endolymphatic hydrops in the inner ear. We got introduced to Meniere’s disease, which is a sickness caused by overproduction of the endolymph and perilymph within the inner ear, that causes hearing loss and vertigo. Due to the different density of the ear fluids, patients get different signals to the brain, which ends with loss in hearing and balance problems. During her PhD she had to deal with sets of data from patients with different types of inner ear problems.

Her main source of data consisted of MRI brain scans, that were used by our speakers to specify which type of vestibular syndromes the patients were struggling with. The data consisted of a lot of obstacles: mainly low resolution. The final task was a generation of automatic script, that will provide a full analysis of the problem described above. How to distinguish between a normal and dilated shape of inner ear? Atlas based analysis!

Such methodology is based on landmark positions that have to be picked on every picture, without knowing how to transform them from one image to the other. The more deformed the data is, the more landmarks you need to place in order to get the comparable results. Instead of dealing with such hideous approach by hand, Fatemeh did what we all do in 2nd decade of 21st century – train machine learning methods, in order to automatize the landmark placements. Her method focused on building a probabilistic model based on the atlas. The comparison between the original data and the segmentation results was performed, allowing the speaker to obtain a statistical measure.


<figure>
  <p align="center">        
  <img alt="Image" height="533" src="/img/Fatemeh/F5.JPG" width="750">
    </p>
  <figcaption>
    Quick shot during the talk.
  </figcaption>
</figure><br>



After that, we realized that Fatemeh had more for us: the <b>functional imagining</b> introduction begun. fMRI does not look at the structure of the brain instead, it focuses on the function. The method is based on the BOLD effect – after brain, activation comes to the higher oxygenation of the same area. This allows researches to find the reactive part of the brain: what “lights up” when you move your leg?

This method also deals with typical for a medical image processing problems such as: noise removal, motion correction. Due to which the preprocessing, first level analysis, spatial normalization and smoothing have to be performed. Fatemeh presented for us a brief introduction of the use of Independent Component Analysis on time series of the voxels in fMRI. Thanks to which she could find the appropriate activity.

Additionaly, we looked at a General Linear Model for processing the fMRI data. Such a model has to be fitted - how to define the line that would model your time series? With the use of regressor generation, that aims to come up with a design matrix that models the expected fMRI response at any voxel as a linear combinations of columns.

Due to limited time of the talk and beginner attendees we had to skip few of more detailed methods, that can be still found in the slides:<br>
- Autocorrelation in Time Series <br>
- Durbin Watson Statistics <br>
- White Noise and Prewhitening <br>
- How to Remove the Noise Effect <br>

We nevertheless got a great last look at: <br>
1) Planning your future projects: <br>
- any project you do → start by defining a pipeline for your project, <br>
- divide the project appropriately <br>
- connect the phases <br>
- always discuss with the others <br>
2) Introduction to the recent publication about: Brain entropy and human intelligence

Further information can be found in our references.
We would like to Thank Fatemeh one more time for the talk!

<figure>
  <p align="center">        
  <img alt="Image" height="533" src="/img/Fatemeh/F2.JPG" width="750">
    </p>
</figure><br>



<b>Resources:</b> <br>
presentation: <br>
https://drive.google.com/file/d/1Yfzj65qX6EdHpVEb3sZiojSdzxABr2IB/view?usp=sharing  

Prof. Nassir Navab website::
http://www.professoren.tum.de/en/navab-nassir/

Prof. Gregory C Sharp:
https://gray.mgh.harvard.edu/people-directory/translational/75-gregory-c-sharp-phd  

<b> References: </b> <br>

[0] A Kernel Machine-based fMRI Physiological Noise Removal Method, Xiaomu Song et al. Magn Reson Imaging. 2014; 32(2): 150–162.

[1] Temporal correlation compensation (whitening) of the fMRI data using Akaike Information Criterion, Ricardo Maximiano et al. Bioengineering, 2011

[2] A qualitative test of the balloon model for BOLD-based MR signal changes at 3T, Toralf Mildner et al. Magnetic Resonance in Medicine 46(5). 2011

[3] Using nonlinear models in fMRI data analysis: Model selection and activation detection, Thomas Deneux, Neuroimage 2006

[4] Methodological challenges and solutions in auditory functional magnetic resonance imaging, Jonathan E. Peelle, Front Neurosci 2014

[5] Functional Imaging of Auditory Cortex in Adult Cats using High-field fMRI, Trecia A. Brown et al. Visualized Exoeriments 2014

[6] Image Registration Timothy Fox et al. PET CT in Radiotherapy Treatment Planning 2008

[7] Rigid and non-rigid image registration and its association with mutual information Fookes Clinton B, et al.: a review.Research Concentration in Computer Vision and Automation. Queensland University of Technology, 2002

[8] Numerical methods for image registration, Jan Modersitzki et al. Oxford Scholarship Online: September 2007

[9] Segmentation of human brain using structural MRI, magnetic resonance imaging , Gunther Helms 2016

[10] Visualization of endolymphatic hydrops and correlation with audio-vestibular functional testing in patients with definite Meniere's disease, Young JoonSeo, Elsevier 2013

[11] Recurrent peripheral vestibulopathy: Is MRI useful for the diagnosis of endolymphatic hydrops in clinical practice? Arnaud Attye et al. Euro. Rad. 2016

[12] Tie, Y., Rigolo, L., Shriver, S., Golby, A. Assessing Language Dominance using Task-free fMRI for Pre-surgical Planning. 16th Annual Meeting of the Organization for Human Brain Mapping, Barcelona, Spain, 2010a.

[13] Tie, Y., Wu, W., Rigolo, L., Shriver, S., Golby, A. Pre-surgical Language Mapping using Resting-state fMRI. 40th Annual Meeting of Society of Neuroscience, San Diego, USA. 2010b.
