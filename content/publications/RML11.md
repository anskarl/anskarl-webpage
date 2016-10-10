+++
title = "Probabilistic Event Calculus based on Markov Logic Networks"
draft = false
date = "2016-10-08T22:06:45+03:00"
comments = false
noauthor = true 
share = true
+++


**Anastasios Skarlatidis**<sup>1,2</sup>, **Georgios Paliouras**<sup>1</sup>, **George A. Vouros**<sup>2</sup>, **Alexander Artikis**<sup>1</sup>

<sup>1</sup>Institute of Informatics and Telecommunications, NCSR "Demokritos"
<sup>2</sup>Department of Digital Systems, University of Piraeus

>***Abstract*** 
>
>In this paper, we address the issue of uncertainty in event recognition by extending the Event Calculus with probabilistic reasoning. Markov Logic Networks are a natural candidate for our logic-based formalism. However, the temporal semantics of Event Calculus introduce a number of challenges for the proposed model. We show how and under what assumptions we can overcome these problems. Additionally, we demonstrate the advantages of the probabilistic Event Calculus through examples and experiments in the domain of activity recognition, using a publicly available dataset of video surveillance.

### Downloads

[Paper (PDF)](/publications/papers/paper-RML11.pdf)

The knowledge base source files of a probabilistic event recognition method that employs an [Event Calculus](https://en.wikipedia.org/wiki/Event_calculus) formalism based on [Markov Logic Networks](https://en.wikipedia.org/wiki/Markov_logic_network), are given below:

  * Markov Logic Networks knowledge base files, that include the Discrete Event Calculus domain-independent axioms and the high-level event definitions for the CAVIAR dataset, are available [here](CAVIAR.ProbDEC.tar.gz)
  * The dataset source files of the CAVIAR project are given below:
  	* Original files and a description of the dataset can be found [here](https://homepages.inf.ed.ac.uk/rbf/CAVIARDATA1/)
  	* Dataset files transformed into Event Calculus narrative syntax in Markov Logic Networks and Prolog formats, are available [here](https://users.iit.demokritos.gr/~anskarl/pub/rml11/CAVIAR_Dataset1/)
  * The source code of the scripts that transform the original XML-based CAVIAR dataset into Markov Logic Networks and Prolog formats, are available [here](https://users.iit.demokritos.gr/~anskarl/pub/rml11/CAVIAR_Dataset.Scripts.tar.gz)

### BibTex  
```bibtex
@inproceedings{PEC-MLN-RML11,
  author    = {Anastasios Skarlatidis and Georgios Paliouras and George A. Vouros and Alexander Artikis},
  title     = {Probabilistic Event Calculus Based on Markov Logic Networks},
  booktitle = {RuleML America},
  publisher = {Springer},
  series    = {Lecture Notes in Computer Science},
  volume    = {7018},
  year      = {2011},
  pages     = {155-170},
  ee        = {http://dx.doi.org/10.1007/978-3-642-24908-2_19}
}
```