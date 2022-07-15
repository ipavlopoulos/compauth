# Computational authorship analysis with language modelling

In [prior work](https://dl.acm.org/doi/10.1145/3526242.3526256), we modeled Homeric language and provided empirical findings regarding the authorship nature of the 48 Iliad and Odyssey books. Following this line of work, and considering the current philological views and trends, we break down the two poems further into smaller portions. By employing language modeling we identify outlying passages, indicating reduced linguistic affinity with the main body of the two works and, by extension, potentially different authorship. Our results show that some of the passages isolated as outliers by the language models were also identified as such by human researchers. We further test our methodology and models on texts of similar language and genre created by other authors, namely Hesiod’s “Theogony” and “Work and Days”.

In this repository you will find:
* `analysing_iliad_and_odyssey.ipynb` comprising the code,
* `scored_excerpts.xlsx` comprising the PPL per 600-character long excerpt of the Iliad and the Odyssey,
* `unforeseen_excerpts.xlsx` comprises the fragments of I.2 and O.11 that were found to exceed the upper 95% confidence interval, as this was defined by random sampling excerpts from the remainder of each poem.

If you find this work interesting, please cite us:
```
@article{Pavlopoulos2022,
  author = {Pavlopoulos, John and Konstantinidou, Maria},
  doi = {https://doi.org/10.1007/s42803-022-00046-7},
  month = {7},
  title = {Computational authorship analysis of the homeric poems},
  journal = {International Journal of Digital Humanities}
  year = {2022},
}
```
