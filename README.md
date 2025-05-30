# DirectedRicciCurvature
A python library to compute the Ricci curvature on directed graph. This is based on [our paper]([https://arxiv.org/abs/2110.06506](https://link.springer.com/article/10.1007/s00526-020-01809-2)).

---

Description... TBA

# Simple Example
```
#Create a graph with edge weight
nodeset = [0, 1, 2, 3, 4, 5, 6, 7, 8]
G = nx.DiGraph()
G.add_edge(0, 1, weight=0.5)
G.add_edge(0, 8, weight=0.5)
G.add_edge(1, 2, weight=1.0)
G.add_edge(2, 3, weight=0.5)
G.add_edge(2, 8, weight=0.5)
G.add_edge(3, 4, weight=1.0)
G.add_edge(4, 5, weight=0.5)
G.add_edge(4, 8, weight=0.5)
G.add_edge(5, 6, weight=1.0)
G.add_edge(6, 7, weight=0.5)
G.add_edge(6, 8, weight=0.5)
G.add_edge(7, 8, weight=1.0)
G.add_edge(8, 0, weight=1.0)

#Calculate the Ricci curvature
calculate_Ricci_curvature(G, 0.5)

#Drawing graphs
curvature_visualization(G, calculate_Ricci_curvature(G, 0.5))
```

# Contact

See [my homepage](https://researchmap.jp/taikiyamada?lang=en).

# Reference

1. Ryunosuke Ozawa, Yohei Sakurai, Taiki Yamada, "Geometric and spectral properties of directed graphs under a lower Ricci curvature bound", Calculus of Variations and Partial Differential Equations 59(4) 142-177, 2020


# Cite
If you use this code in your research, please considering cite our paper:

```

```
