# bgp-hijacks-final-project
# Installation Dependencies
- scipy:  pip install scipy 
- bgpstream: brew install bgpstream
- pybgypstream: pip install pybgpstream
- NetworkX: pip install networkx

# How to run our code 
- Open jupyter notebook. Run through all the cells in order.
- SKIP code cell #3, which contains the code that trains on 7 days of data. It is extremely slow.
  Instead, run code cell #4 to import pickle, SKIP code cell #4, and run code cell #5 to load the
  dictionary and graph that we already generated after training the data. This allows you to skip 
  step of rerunning the training code.
- SKIP CODE CELL #7 as well which runs extremely slow. This cell draws the global view of the graph
  which has already been generated in jupyter notebook.
- The rest of the cells can be run through normally. 


