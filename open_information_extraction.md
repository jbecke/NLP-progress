# Open Information Extraction

Open information extraction (OpenIE) is the task of extracting a machine-readable representation of information in the form of n-ary propositions from text. Most works narrow this definition to a specific schema of (subject, predicate, object) 3-tuples. For example, an OpenIE system may parse "The cat is in the hat" to (the cat, is in, the hat).


## Systems

This section contains influential systems/papers since the start of the field.

* [Stanford Open IE](https://nlp.stanford.edu/software/openie.html): GPL or proprietary available as part of [Stanford Core NLP](https://stanfordnlp.github.io/CoreNLP/). Attempts to produce maximally shortened extractions.
* [OpenIE-X](https://knowitall.github.io/openie/) ([v4](https://github.com/knowitall/openie), [v5](https://github.com/dair-iitd/OpenIE-standalone), [allen institute version](https://github.com/allenai/openie-standalone)). 
* From University of Washington
  * [TextRunner](http://turing.cs.washington.edu/papers/ijcai07.pdf) - One of the earliest papers addressing open information extraction
  * [Reverb](http://reverb.cs.washington.edu/) - Improved the extraction to better form the tuple of (argument, relation, argument)
  * [OLLIE](https://knowitall.github.io/ollie/) - Addressed the issue of misleading propositions and non-verb mediated relations
* [CSD-IE](https://ieeexplore.ieee.org/document/6693511/) - Generation of nested contractions which is especially effective in sentences using subordinating clauses
* [PropS](http://u.cs.biu.ac.il/~stanovg/props.html): Syntax Based Proposition Extraction
* [ClausIE](https://www.mpi-inf.mpg.de/departments/databases-and-information-systems/software/clausie/) - Formed a strong relation between grammatical clauses, propositions, and OIE extractions by defining seven grammatical patterns
* [ReNoun](http://www.aclweb.org/anthology/D14-1038) - Used predominantly for noun-mediated relations.

## 35M Sentence-Tuple Pairs

This dataset contains OpenIE-4 bootstrapped data  

| Model           | AUC |  Paper / Source |
| ------------- | :-----:| --- |
| Low supervision (Søgaard and Goldberg, 2016) | 95.57 | [Neural Open Information Extraction](https://arxiv.org/pdf/1805.04270.pdf) |
| Suzuki and Isozaki (2008) | 95.15 | [Semi-Supervised Sequential Labeling and Segmentation using Giga-word Scale Unlabeled Data](https://aclanthology.info/pdf/P/P08/P08-1076.pdf) | 

[Go back to the README](README.md)
