=======================
Waves in Networks
=======================

-------------------
Aims of the project
-------------------

Consider a network made of edges that can host some wave propagation. We do not care of the physical nature of edges and waves, they might be electrical wires carrying signals or water channels and so on.

We want to study what happens when one or more waves start at same points of the network: their travel, evolution, composition, etc. until some steady or periodic or chaotic state is reached in the whole network (or everithing 
stops if there is a damping factor).

We want to obtain a framework that can be used to test different wave formats, starting points, edge local characteristics etc. and get for instance: 1) computation of some global parameters, 2) the evolution of some points
arbitrarily chosen in the network, 3) suitable visualizations of the network behaviour.

Basic settings:
---------------
* we consider a list of nodes and a dictionary of the edges, that should be possible to import in order to apply the software to different networks
* for each edge we must have: id, endpoints (starting and ending nodes), length, a variable set of parameters that should be used to compute the wave along it (e.g. size, density, etc.)
* a list of functions representing the wave equations; a list of points (that is edge id and displacement on the edge) representing the wave position at t=0
* some parameters to control the runs, the type of output, etc.
* GUI: still to decide if we want a real GUI or just some functions that create graphs and table of numbers

