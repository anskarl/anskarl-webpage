+++
title = "Probabilistic Event Calculus for Event Recognition"
draft = false
date = "2016-10-08T23:07:22+03:00"
comments = false
noauthor = true 
share = true
+++

Anastasios Skarlatidis<sup>1,2</sup>, Georgios Paliouras<sup>1</sup>, Alexander Artikis<sup>3,1</sup> and George A. Vouros<sup>2</sup>

<sup>1</sup>Institute of Informatics and Telecommunications, NCSR "Demokritos"</br>
<sup>2</sup>Department of Digital Systems, University of Piraeus</br>
<sup>3</sup>Department of Maritime Studies, University of Piraeus</br>

>***Abstract*** 
>
>Symbolic event recognition systems have been successfully applied to a variety of application domains, extracting useful information in the form of events, allowing experts or other systems to monitor and respond when significant events are recognised. In a typical event recognition application, however, these systems often have to deal with a significant amount of uncertainty. In this paper, we address the issue of uncertainty in logic-based event recognition by extending the Event Calculus with probabilistic reasoning. Markov Logic Networks are a natural candidate for our logic-based formalism. However, the temporal semantics of the Event Calculus introduce a number of challenges for the proposed model. We show how and under what assumptions we can overcome these problems. Additionally, we study how probabilistic modelling changes the behaviour of the formalism, affecting its key property, the inertia of fluents. Furthermore, we demonstrate the advantages of the probabilistic Event Calculus through 
examples and experiments in the domain of activity recognition, using a publicly available dataset for video surveillance.



### Download
[Paper (PDF)](/publications/papers/paper-TOCL15.pdf)

#### Knowledge base files, dataset and evaluation results

Composite event definitions and the Markov Logic Netoworks formatted version of the dataset can be downloaded from [here](https://users.iit.demokritos.gr/~anskarl/pub/mlnec/MLN-EC_CAVIAR-20130319-00_07_20.tar.bz2) ([md5](https://users.iit.demokritos.gr/~anskarl/pub/mlnec/MLN-EC_CAVIAR-20130319-00_07_20.tar.bz2.md5)).

### BibTex

```bibtex
@article{PEC-ER-TOCL15,
  author = {Skarlatidis A., Paliouras G., Artikis A. and Vouros G.},
  title = {{Probabilistic Event Calculus for Event Recognition}},
  journal = {ACM Transactions on Computational Logic},
  issue_date = {April 2015},
  volume = {16},
  number = {2},
  month = feb,
  year = {2015},
  issn = {1529-3785},
  pages = {11:1--11:37},
  articleno = {11},
  numpages = {37},
  url = {http://doi.acm.org/10.1145/2699916},
  doi = {10.1145/2699916},
  acmid = {2699916},
  publisher = {ACM},
  address = {New York, NY, USA},
  keywords = {Events, machine learning, probabilistic inference, uncertainty},
} 

```