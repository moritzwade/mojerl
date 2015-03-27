# MoJERL: My own Java Edge Routing Library #

In the course of my master's thesis, I needed to route graph edges in various ways. Because there seemed to be no sensible free libraries, I created _MoJERL_.

  * _MoJERL_ uses _JGraphT_, an open-source Java graph library providing essential data structures and shortest path algorithms to _MoJERL_. (http://jgrapht.sourceforge.net/)
  * _MoJERL_'s edge routing is based on creating a visibility graph of the given 2D scene (using the method by _Overmars and Welzl_) and then finding appropriate edges within that graph.
  * _MoJERL_ is used in a graph layout plugin (named _TeLLTool_ for "Textbook Like Layout Tool") for _Vanted_, an open-source visualization and analysis tool for (mainly biological) networks. (http://vanted.ipk-gatersleben.de/)

Moritz Wade

PS: This project is no longer under active development.