+++
draft = false
title = "A Probabilistic Logic Programming Event Calculus"
date = "2016-10-08T22:42:34+03:00"
comments = false
noauthor = true 
share = true 
+++

**Anastasios Skarlatidis**<sup>1,2</sup>, **Alexander Artikis**<sup>1</sup>, **Jason Filippou**<sup>1,3</sup> and **Georgios Paliouras**<sup>1</sup>

<sup>1</sup>Institute of Informatics and Telecommunications, NCSR "Demokritos"</br>
<sup>2</sup>Department of Digital Systems, University of Piraeus</br>
<sup>3</sup>University of Maryland, USA </br>

>***Abstract:***
>
>We present a system for recognising human activity given a symbolic representation of video content. The input of our system is a set of time-stamped short-term activities (STA) detected on video frames. The output is a set of recognised long-term activities (LTA), which are pre-defined temporal combinations of STA. The constraints on the STA that, if satisfied, lead to the recognition of a LTA, have been expressed using a dialect of the Event Calculus. In order to handle the uncertainty that naturally occurs in human activity recognition, we adapted this dialect to a state-of-the-art probabilistic logic programming framework. We present a detailed evaluation and comparison of the crisp and probabilistic approaches through experimentation on a benchmark dataset of human surveillance videos.

### Downloads

[Paper (Draft)](https://arxiv.org/pdf/1204.1851v2.pdf)

The modified version of the [CAVIAR dataset](http://homepages.inf.ed.ac.uk/rbf/CAVIARDATA1/), including ProbLog-EC, the high-level event definitions and the event recognition results can be downloaded from [here](https://users.iit.demokritos.gr/~anskarl/pub/ProbLog-EC/TPLP-Data.v2012.11.10-20140312-18_07_29.tar.bz2) (Compressed archive ~0.5G; [md5](https://users.iit.demokritos.gr/~anskarl/pub/ProbLog-EC/TPLP-Data.v2012.11.10-20140312-18_07_29.tar.bz2.md5))

### BibTex 

```bibtex
@article{PLP-EC-TPLP15,
  author    = {Anastasios Skarlatidis and Alexander Artikis and Jason Filipou and Georgios Paliouras},
  title     = {{A Probabilistic Logic Programming Event Calculus}},
  journal   = {{TPLP}},
  volume    = {15},
  number    = {2},
  pages     = {213--245},
  year      = {2015},
  url       = {http://dx.doi.org/10.1017/S1471068413000690},
  doi       = {10.1017/S1471068413000690}
}
```