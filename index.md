# EDGQA

## What is EDGQA?

EDGQA is a QA system over knowledge bases based on Entity-Description Graphs (EDGs). 
Currently EDGQA has been implemented for DBpedia, tested on LC-QuAD 1.0 and QALD-9.
More information is detailed in [our paper](https://link.springer.com/chapter/10.1007/978-3-030-88361-4_8).

![Untitled](index.assets/Untitled.png)

The above figure shows SPARQL (a. and c.) and EDG (b. and d.) on two exemplar natural language questions. The dashed line connects a description to an intermediate entity. The types of nodes and edges of EDG is defined as follows.

![Untitled-2](index.assets/Untitled-2.png)

By generating such EDGs, questions are represented as a combination of entities and their description, providing a structure for understanding and answering complex questions. More information are detailed in our paper.

## Downloads

- [GitHub repo release](https://github.com/HXX97/EDGQA/releases)
- [v0.1.1 source code(zip)](https://github.com/HXX97/EDGQA/archive/refs/tags/0.1.1.zip)
- [v0.1.1 source code (tar.gz)](https://github.com/HXX97/EDGQA/archive/refs/tags/0.1.1.tar.gz)

For any questions, feel free to [launch an issue](https://github.com/HXX97/EDGQA/issues) on GitHub or send an e-mail.

## Experiments

QA performance on LC-QuAD 1.0 and QALD 9.

![Untitled-3](index.assets/Untitled-3.png)

## Citations

```latex
@inproceedings{Hu2021edg,
  author    = {Xixin Hu and
               Yiheng Shu and
               Xiang Huang and
               Yuzhong Qu},
  editor    = {Andreas Hotho and
               Eva Blomqvist and
               Stefan Dietze and
               Achille Fokoue and
               Ying Ding and
               Payam M. Barnaghi and
               Armin Haller and
               Mauro Dragoni and
               Harith Alani},
  title     = {EDG-Based Question Decomposition for Complex Question Answering over
               Knowledge Bases},
  booktitle = {The Semantic Web - {ISWC} 2021 - 20th International Semantic Web Conference,
               {ISWC} 2021, Virtual Event, October 24-28, 2021, Proceedings},
  series    = {Lecture Notes in Computer Science},
  volume    = {12922},
  pages     = {128--145},
  publisher = {Springer},
  year      = {2021},
  url       = {https://doi.org/10.1007/978-3-030-88361-4\_8},
  doi       = {10.1007/978-3-030-88361-4\_8},
}
```

*Last update: 2021/10*
