---
layout: reading-group
name: Beyond Worst Case Analysis
sem: 2018-4
location: Cory 293 (there are some exceptions where we will meet elsewhere such as Soda 373) 
time: Every Monday at 5:30 pm 
logistics: Please join our [mailing list](https://groups.google.com/a/lists.berkeley.edu/forum/#!forum/ugbwca-fa18)  to stay up to date with our events. We will also be holding special events so do check the calendar below. 
files: >-
    [Scribe note template](/src/bwca-fa18/bwca-scribe.sty)
weeks:
  - date: 8/28/2018
    topic: >-
        Preliminary logistics meeting — Soda 373 @ 6:30pm

        *   Discussed plans for weekly meetings
  
        *   Considered a number of semester long projects
 
        *   Discussed topics regarding UGTCS student group
    resources: >-
        [Meeting minutes](https://docs.google.com/a/berkeley.edu/document/d/e/2PACX-1vQZ_1Z8lANtOlPaQU3M6LUmmXz5rP8mYq-I7LETk0UoB0pYO_bd5kCaAKKeY_9u2K_2nYrnjyWjg07D/pub) 

  - date: 9/10/2018
    topic: >-
        Probability and Linear Algebra presented by Antares, Hermish — Cory 293 @ 5:30pm

        *   Suggested readings for Discrete Probability
            *   Review [notes](https://people.eecs.berkeley.edu/~luca/cs276/notesprob.pdf) covering basic discrete probability and using Markov, Chebyshev inequalities to bound the probability of bad events.
            *   More extensive [discussion](http://cs229.stanford.edu/section/cs229-prob.pdf) covering discrete and continuous probability.

        *   Suggested readings for Linear Algebra
            *   [Chapter 1](https://people.eecs.berkeley.edu/~luca/books/expanders-2016.pdf) of Luca's book on expander graphs covering real symmetric matrices and the variational characterization of eigenvalues.
            *   A more extensive [discussion](http://cs229.stanford.edu/section/cs229-linalg.pdf) used in Stanford's CS229
    resources: >-
        [Scribe notes](/src/bwca-fa18/scribe-notes-1.pdf) 

  - date: 9/17/2018
    topic: >-
        Largest Clique in a Random Graph presented by James, William, Zod — Cory 293 @ 5:30pm

        *   These [notes](https://people.eecs.berkeley.edu/~luca/bwca18/lecture01.pdf) on proving that the max clique is 2log(n) w.h.p and a greedy algorithm for finding a log(n) clique.
    resources: >-
        [Scribe notes](/src/bwca-fa18/scribe-notes-2.pdf) 

  - date: 9/24/2018
    topic: >-
        Planted Clique via spectral algorithm presented by William, Zod — **Soda 373** @ 5:30pm

        *   These [notes](https://people.eecs.berkeley.edu/~luca/bwca18/lecture03.pdf) on using spectral methods to find a planted clique of size sqrt(n).
        
        *   The original [paper](http://www.math.tau.ac.il/~nogaa/PDFS/clique3.pdf) on the AKS planted clique algorithm.
        
        *   Try some exercises

        *   Implement the spectral algorithm and test it on [this instance](https://people.eecs.berkeley.edu/~luca/bwca18/)
        
        *   Show how recover a planted dense subgraph of size k > c sqrt(n), where c is a sufficiently large constant. In this model, a set S of k vertices is randomly chosen, then edges within S are chosen each with probability 3/4, and all other edges are chosen with probability ½
    resources: >-
        [Scribe notes](/src/bwca-fa18/scribe-notes-3.pdf)  

        [iPython notebook](https://github.com/ugtcs/notebooks/blob/master/fa18-bwca/lec3-spectral-planted-clique.ipynb) 

  - date: 10/1/2018
    topic: >-
        Semidefinite Programming presented by Vishnu — Cory 293 @ 5:30pm

        *   These [notes](https://people.eecs.berkeley.edu/~luca/bwca17/lectures/lecture04.pdf) from the original BWCA course.
        
        *   These [notes](http://people.csail.mit.edu/moitra/docs/6854lec19.pdf) from Ankur Moitra's 6.854.
    resources: >-
        [Scribe notes](/src/bwca-fa18/scribe-notes-4.pdf) 

  - date: 10/8/2018
    topic: >-
        Planted Clique via Semidefinite Programming presented by Wilson — **Soda 341A** @ 5:30pm

        *   These [notes](http://theory.stanford.edu/~tim/w17/l/l11.pdf) from Tim Roughgarden's CS264 (portion on planted clique).
    resources: >-
        [Scribe notes](/src/bwca-fa18/scribe-notes-5.pdf) 

  - date: 10/15/2018
    topic: >-
        Stochastic Block Model (1) presented by Antares, Nate, Vishnu — Cory 293 @ 5:30pm

        *   These [notes](https://people.eecs.berkeley.edu/~luca/bwca18/lecture04.pdf) on approximately finding partitions using spectral methods.
        
        *   These [notes](http://www.cs.yale.edu/homes/spielman/561/lect21-15.pdf) from Dan Spielman's course on spectral graph theory.
    resources: >-
        [Scribe notes](/src/bwca-fa18/scribe-notes-6.pdf) 

        [iPython notebook](https://github.com/ugtcs/notebooks/blob/master/fa18-bwca/lec6-approx-sbm.ipynb) 
    
  - date: 10/22/2018
    topic: >-
        Stochastic Block Model (2) presented by Antares, Haaris — Cory 293 @ 5:30pm

        *   These lecture notes ([note 1](https://people.eecs.berkeley.edu/~luca/bwca18/lecture05.pdf) and [note 2](https://people.eecs.berkeley.edu/~luca/bwca18/lecture06.pdf)) on exactly recovering communities with an SDP based algorithm.
    resources: >-
        [Scribe notes](/src/bwca-fa18/scribe-notes-7.pdf) 

        [iPython notebook](https://github.com/ugtcs/notebooks/blob/master/fa18-bwca/lec7-exact-sbm.ipynb) 

  - date: 10/29/2018
    topic: >-
        BWCA noting and coding workday — Cory 293 @ 5:30pm

        *   Help build various iPython notebooks showcasing the algorithms we have seen so far this semester.

  - date: 11/5/2018
    topic: >-
        Bilu-Linial Stability and k-Medians presented by Antares, Saam — Cory 293 @ 5:30pm

        *   These lecture [notes](http://theory.stanford.edu/~tim/w17/l/l6.pdf) on perturbation-stable k-Medians clustering.
  
        *   For extra reading, consider checking out these notes on...
            *   [perturbation stability in minimum s-t cut and minimum multiway cut](http://theory.stanford.edu/~tim/w17/l/l7.pdf)
            *   [perturbation stability in maxcut](http://theory.stanford.edu/~tim/w17/l/l8.pdf)
    resources: >-
        Scribe notes coming soon 

  - date: 11/12/2018
    topic: >-
        Administrative holiday — no meeting
    
        *   Have a relaxing day off!

  - date: 11/19/2018
    topic: >-
        School closure due to smoke — no meeting

        *   Stay safe everyone!

  - date: 11/26/2018
    topic: >-
        Balcan-Blum-Gupta Stability and k-Medians presented by James — Cory 293 @ 5:30pm

        *   These lecture [notes](http://theory.stanford.edu/~tim/f14/l/l6.pdf) on approximation-stable k-Medians clustering.
    resources: >-
        [Scribe notes](/src/bwca-fa18/scribe-notes-9.pdf) 

  - date: 12/7/2018
    topic: >-
        Theory Fest! Online Algorithms presented by Antares, Brian, Haaris, Hermish, Wilson — Cory 293 @ 4:00pm

        *   These [notes](https://people.eecs.berkeley.edu/~luca/cs261/lecture17.pdf) on competitive analysis, the secretary problem and caching.
        
        *   These [notes](https://people.eecs.berkeley.edu/~luca/cs261/lecture18.pdf) on experts and multiplicative weight update.
        
        *   For extra reading, checking out
            *   Further [notes](http://theory.stanford.edu/~tim/f14/l/l4.pdf) on caching.
            *   These lectures from [Matt Weinberg](https://www.google.com/url?q=https://simons.berkeley.edu/talks/sequential-decision-making&sa=D&ust=1543893258879000), [Seffi Naor](https://www.google.com/url?q=https://simons.berkeley.edu/talks/competitive-analysis-online-algorithms&sa=D&ust=1543893258879000), [Nicolò Cesa-Bianchi](https://www.google.com/url?q=https://simons.berkeley.edu/talks/online-learning-convex-optimization&sa=D&ust=1543893258879000) and [Tim Roughgarden](https://www.google.com/url?q=https://simons.berkeley.edu/talks/beyond-worst-case-analysis&sa=D&ust=1543893258879000)
        *   Stay afterwards for the BWCA End of Year social!
    resources: >-
        Scribe notes coming soon
---

### Topics Outline

Refer [here](https://docs.google.com/a/berkeley.edu/document/d/e/2PACX-1vTDz9Ua2oGYKQ3y_CROdjyIABdUA64amNbw_F7M7f67VXBcA9uc-eyD7BWLl4lM0Jnbe5JfdxA9cS3T/pub) for a detailed list.

*   Background review in Discrete Probability and Linear Algebra
*   Random instances, planted distributions, and semi-random models
    *   Cliques in a random graph
    *   Planted cliques in random graphs
    *   Finding partitions in the Stochastic Block Model

*   Smoothed analysis of the Simplex algorithm
*   Instance stability
    *   Stability as defined by Bilu and Linial
    *   Stability as defined by Balcan, Blum and Gupta
*   Online algorithms
    *   Secretary problem and paging
    *   Experts and Multiplicative Weights

### Additional Resources

*   Luca Trevisan's [CS294-134](https://people.eecs.berkeley.edu/~luca/bwca17/index.html) Beyond Worst Case Analysis
*   Tim Roughgarden's [CS264](http://theory.stanford.edu/~tim/w17/w17.html) Beyond Worst Case Analysis (Winter 2017)
*   Ankur Moitra's [6.854](http://people.csail.mit.edu/moitra/854.html) (MIT's CS270 equivalent). It even includes a link to lecture videos.
*   [Bootcamp](https://simons.berkeley.edu/workshops/uncertainty2016-boot-camp) from the Simons Institute's Fall 2016 program on Algorithms and Uncertainty

### Loose Ends

Here are various notes on odd topics that were skimmed over during the course of the reading group.

*   Coming soon...
