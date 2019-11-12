==================
Anscombe's quartet
==================

A dataset scrapped from the famous `Graphs in Statistical Analysis`_ by F. J. Anscombe (1973).

This project is applies D3js v4 on this sample of data in order to learn the basics of this library.

Files
-----

- data/anscombe.txt   reproduction of  the original data set
- data/txt2tsv.py     script to generate table from original data set
- data/anscombe.tsv   data set

- viz/0-tables.html   table "visualisation" generated using d3.js_


.. _Graphs in Statistical Analysis: http://iihm.imag.fr/blanch/teaching/infovis/readings/1973-Anscombe-Graphs_in_Stats.pdf
.. _d3.js: http://d3js.org


Files
-----

You have to run a web server, even for local development. To do so, you can use -for example- python:

- python3 -m http.server
- and then go to http://localhost:8000. You can also use node, see the d3.js documentation.
