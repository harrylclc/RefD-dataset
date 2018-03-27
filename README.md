# RefD-dataset

This is the data used in "Measuring Prerequisite Relations Among Concepts" (Liang et al., 2015)

## Data Description
This file contains the two datasets used in the paper: the CrowdComp dataset and the Course dataset.

### The CrowdComp Dataset (Talukdar and Cohen, 2012)

The CrowdComp dataset (folder 'CrowdComp') contains five domains: 
- Meiosis
- Public-key Cryptography
- Parallel Postulate
- Newton's Laws
- Global Warming

Each csv file in the folder records the crowdsourcing results of a Human Intelligent Task (HIT) on Amazon Mechanical Turk.

### The Course Dataset

The Course dataset (folder 'Course/') contains two domains: computer science (CS) and mathematics (MATH). For each domain, the file with a filename extension '.edges' contains prerequisite concept pairs. And the file with a filename extension '.edges_neg' contains negative examples for that domain.

Each line of the file is in a format of 'A\tB', representing that B is a prerequisite of A. For example, in 'CS.edges', there is a line 'Network security   Computer network', showing that 'Computer network' is a prerequisite of 'Network security'.

## References
Please cite the following papers if you use this data.
```
@inproceedings{liang2015measuring,
  title={Measuring prerequisite relations among concepts},
  author={Liang, Chen and Wu, Zhaohui and Huang, Wenyi and Giles, C Lee},
  booktitle={Proceedings of the 2015 Conference on Empirical Methods in Natural Language Processing},
  pages={1668--1674},
  year={2015}
}
@inproceedings{talukdar2012crowdsourced,
  title={Crowdsourced comprehension: predicting prerequisite structure in wikipedia},
  author={Talukdar, Partha Pratim and Cohen, William W},
  booktitle={Proceedings of the Seventh Workshop on Building Educational Applications Using NLP},
  pages={307--315},
  year={2012},
  organization={Association for Computational Linguistics}
}
```
If you have any problems, please contact Chen Liang at <cul226@ist.psu.edu>.


## License
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-nc-sa/4.0/). 

![Alt](https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png)
