<p align="center">
  <img alt="Live-Poll Logo" src="https://user-images.githubusercontent.com/37160523/189640245-3337401f-2b84-4e95-86ce-bc61a1fc9e7e.jpg" height="220" />
  <h3 align="center">Community Detection Datasets</h3>
  <p align="center">Networks used in my bachelor thesis</p>
</p>

# Community detection network datasets

This repo includes all graphs/networks that were used in my bachelor thesis *Louvain-initialized Genetic Algorithms for Community Detection in Complex Networks* from  the 28th of August 2022. It is not published yet but probably will be soon.

> Feel free to use these filtered networks in your work, e.g. for experimental evaluation. The whole purpose of this repo is to allow for reproducibility and comparability. Please do include a link to this repo though and also link to the original source, e.g. to [SNAP](https://snap.stanford.edu/data/com-Youtube.html) for many graphs (see below).


## Origin

Only `speyer-web` is a graph that I constructed on my own. All other networks originate from external sources, but were **filtered** as described in the thesis. No copyright infringement is intended, we just include the files here for reproducibility and for other authors to compare results with those obtained in the thesis. Please open an issue if you want me to remove a specific dataset.

- The `ca-astroph`, `com-youtube`, `ego-facebook` and `email-eu-core` are from [SNAP](https://snap.stanford.edu/data/).

```
Jure Leskovec and Andrej Krevl. SNAP Datasets: Stanford Large Network Dataset Collection. June 2014. http://snap.stanford.edu/data
```

- The `hep-ph-citations` graph stems from the data mining competition KDD Cub in 2003. It can be found [here](https://www.cs.cornell.edu/projects/kddcup/datasets.html) under task I (citation prediction task), no. 4. Or directly download the compressed tar [here](https://www.cs.cornell.edu/projects/kddcup/download/hep-th-citations.tar.gz).

```
KDD Cup 2003 - Datasets. 09/04/2003. url: https://www.cs.cornell.edu/projects/
kddcup/datasets.html (visited on 06/21/2022).
```


- The `lehnerer` graph is the third graph from Simon Lehnerer used in his paper ["Community Detection in Complex Networks using Genetic Algorithms"](https://dl.gi.de/handle/20.500.12116/28981).

```
Lehnerer, S., (2018). Community Detection in Complex Networks using Genetic Algorithms. In: Becker, M. (Hrsg.), SKILL 2018 - Studierendenkonferenz Informatik. Bonn: Gesellschaft für Informatik e.V.. (S. 35-46).
```

- `speyer-web` is a self-made webgraph starting from the website [speyer.de](https://speyer.de). Edges denote which website link to other websites via anchor links (`a` HTML tag, `href` attribute). The file presented here is only a very small subset of the original graph. The full dataset can be downloaded on the Internet Archive [here](https://archive.org/details/speyer-web-graph) (and I include a more detailed description over there). Cite this graph as follows (or similarly):

```
Dominic Plein. speyer-web network. 2022-08-28. https://archive.org/details/speyer-web-graph.
```
