# PageRank

# TASK 1: THE POWER METHOD
I implemented the ```WebGraph.power_method``` function in ```pagerank.py``` for computing the pagerank vector.

# Part 1
I ran the program on the ```small.csv.gz``` graph which is the example graph from the Deeper Inside Pagerank paper. For my implementation, I get the following output.
```
$ python3 pagerank.py --data=./small.csv.gz --verbose
DEBUG:root:computing indices
DEBUG:root:computing values
INFO:root:rank=0 pagerank=6.0257e-01 url=4
INFO:root:rank=1 pagerank=4.6414e-01 url=6
INFO:root:rank=2 pagerank=3.4544e-01 url=5
INFO:root:rank=3 pagerank=1.9498e-01 url=2
INFO:root:rank=4 pagerank=9.9210e-02 url=3
INFO:root:rank=5 pagerank=8.9347e-02 url=1
```
