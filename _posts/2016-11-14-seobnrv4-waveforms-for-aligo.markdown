---
layout: post
title:  "SEOBNRv4 Waveforms for aLIGO"
date:   2016-11-14 02:00:00 +0100
categories: News
---

<figure>
<center>
<img src="https://www.sciencenews.org/sites/default/files/2016/02/main/blogposts/context_gravwaves_free.jpg" align="middle" alt="BBH" style="width: 500px;"/></center>
<figcaption><center><b>A merging black-hole binary</b> [figure linked from sciencenews.org]</center></figcaption>
</figure>

For the past more than 12 months, my research focus in the Albert Einstein Institute (AEI, Potsdam-Golm) was to develop an improved effective-one-body model of spinning, nonprecessing binary black holes for the era of gravitational-wave astronomy with the advanced LIGO. After tons of work with my collaborators, **here it is, finally!**

As you know, in September of 2015 the first ever gravitational-wave event in human history was captured by the aLIGO detectors in its first observing run (O1) [see [this post](http://friendshao.github.io/news/2016/02/11/we-have-detected-gravitational-waves.html)]. Late this year, after some upgrading, aLIGO is starting its second observing run (O2). Our new waveform model (SEOBNRv4) was developed for O2, and hopefully, other future runs as well.

SEOBNRv4 is based on numerous early efforts of EOBNR models, and recent data of numerical relativity. All these inputs come from a large community that has been working for years (decades in some case), aiming to provide useful contribution to the gravitational-wave science. For search and parameter estimation of gravitational-wave events, an accurate waveform model is essential. Besides the theoretical input from post-Newtonian calculation that goes into EOB dynamics, SEOBNRv4 is calibrated to a large number of numerical-relativity simulations. These simulations cover a large parameter space of mass ratio and black-hole spins. The faithfulness of SEOBNRv4 to the whole catalog of numerical-relativity simulations is better than 99%, that is crucial for aLIGO science.

SEOBNRv4 has been implemented in the LIGO Algorithm Library ([LAL](https://wiki.ligo.org/DASWG/LALSuite)). Please use it and enjoy it!

More details can be found in our paper [[arXiv:1611.xxxxx](https://arxiv.org/abs/1611.03703)].

<figure>
<img src="http://friendshao.github.io/img/v4wf.png" align="middle" alt="waveform" style="width: 700px;"/>
<figcaption><center><b>Example - An inspiral-merge-ringdown waveform from SEOBNRv4</b></center></figcaption>
</figure>
