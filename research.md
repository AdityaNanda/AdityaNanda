### Building neurobiologically plausible models of brain activity

<img src="brain.png" width="450">

Models of brain activity play a crucial role in computational/systems neuroscience. Well-grounded and scientifically accurate models let us make accurate predictions/observations about brain activity and allow us to put putative theories/conjectures about brain function to the test. Building neurobiologicaly plausible models of brain activity requires the generation of surrogate brain activity with certain 'features' or 'properties' of the data preserved.  

Mathematically, the problem of generating multidimensional surrogate data with general constraints is a NP hard problem without any known polynomial-time solution. A majority of my work involves addressing this critical gap and we have developed algorithms that help us generate surrogate timeseries

#### Nullspace method 
<img src="nullspace.png" width="450">

Nullspace method exploits tools from linear algebra to generate surrogate brain activity with preserved linear features:

(1) preserves a variety of 'features' of empirical brain activity (mean activity, variance of activity, correlations to past brain activity etc )
(2) orders of magnitude faster than previous methods (see compariosn to constrained randomization techniques). 
(3) Scale very well to long brain activity recordings (millions of timepoints)
(4) are user-friendly (github repo coming! )
