# addplot
Stata module to add twoway plot objects to an existing twoway graph

`addplot` adds twoway plot objects to an existing twoway graph.
This is useful if you want to add objects such as titles or extra data points
to a twoway graph after it has been created. Most of what `addplot` can do can
also be done by rerunning the original graph command including additional
options or plot statements. `addplot`, however, might be useful if you have to
modify a graph for which you cannot rerun the original command, for example,
because you only have the graph file but not the data that were used to create
the graph. Furthermore, `addplot` can do certain things that would be difficult
to achieve in a single graph command (e.g. customizing individual subgraphs
within a by-graph). `addplot` also provides a substitute for some of the
functionality of the graph editor.

See for a paper on `addplot` see:

> Jann, Ben (2015). A note on adding objects to an existing twoway graph.
> The Stata Journal 15(3): 751-755.
> DOI: [10.1177/1536867X1501500308](https://doi.org/10.1177/1536867X1501500308).

To install `addplot` from the SSC Archive, type

    . ssc install addplot, replace

in Stata. Stata version 9 or newer is required.

---

Installation from GitHub:

    . net install addplot, replace from(https://raw.githubusercontent.com/benjann/addplot/main/)

---

Main changes:

    17aug2021 (version 1.0.2)
    - option -nodraw- added
    - addplot released on GitHub

    25sep2014 (version 1.0.1)
    - addplot released on SSC

