# Computational authorship analysis with language modelling

In [prior work](https://dl.acm.org/doi/10.1145/3526242.3526256), we modeled Homeric language and provided empirical findings regarding the authorship nature of the 48 Iliad and Odyssey books. Following this line of work, and considering the current philological views and trends, we break down the two poems further into smaller portions. By employing language modeling we identify outlying passages, indicating reduced linguistic affinity with the main body of the two works and, by extension, potentially different authorship. 

By using a book resolution, in the Iliad, the greatest proximity (least PPL) was observed for Books 11 and 17. The least proximity (highest PPL) was observed for the 4th and 9th Book. In the Odyssey, the 9th and 12th books were the ones least linguistically associated while the 1st and the 16th were the ones most strongly associated with the remaining books.

By using a passage resolution, forty-seven excerpts of 600 characters each were scored above the upper 95% among all other excerpts. Twenty-five were from the Iliad and 22 from the Odyssey.

Further investigation showed that some of the passages isolated as outliers by the language models were also identified as such by human researchers. Please read our paper for more details: https://link.springer.com/article/10.1007/s42803-022-00046-7

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

In this repository you will find:
* __analysing_iliad_and_odyssey.ipynb__ comprising the code,
* __scored_excerpts.xlsx__ comprising the PPL per 600-character long excerpt of the Iliad and the Odyssey,
* __unforeseen_excerpts.xlsx__ comprises the fragments of I.2 and O.11 that were found to exceed the upper 95% confidence interval, as this was defined by random sampling excerpts from the remainder of each poem.
