---
layout: reading-group
name: Approximation Algorithms
sem: 2019-2
location: Soda 373 (there will be some exceptions, check the calendar below) 
time: Every Friday at 6:00pm 
logistics: Please join our [mailing list](https://groups.google.com/a/lists.berkeley.edu/forum/#!forum/ugapprox-sp19) to stay up to date with our meetings and events.
files: >-
    [scribe note template](/src/approx-sp19/approx-scribe.sty)
weeks:
  - date: 2/2/2019
    topic: >-
        Preliminary logistics meeting — Soda 320 @ 5:30pm

        *   Discuss plans for weekly meetings and semester long goals.

  - date: 2/8/2019
    topic: >-
        Introduction to Approximation Algorithms w/ Set Cover presented by Zod — Soda 373 @ 6:00pm

        *   _Read WS § 1_ A motivation for building approximation algorithms and a tour of design patterns using set cover as an example.
    resources: >-
        [Scribe notes](/src/approx-sp19/scribe-notes-1.pdf) 

  - date: 2/15/2019
    topic: >-
        A greedy 2-approximation for \(k\)-center presented by Ida — Soda 373 @ 6:00pm

        *   _Read WS introduction before § 2.1, § 2.2_ Differentiating between greedy and local search algorithms, a 2-approximation for \(k\)-center, and a proof that this is the optimal approximation ratio unless P=NP.
    resources: >-
        [Scribe notes](/src/approx-sp19/scribe-notes-2.pdf) 

  - date: 2/22/2019
    topic: >-
        Traveling salesman and Christofides presented by Connor and Nathaniel — Soda 373 @ 6:00pm

        *   _Read WS § 2.4_ introducing traveling salesman and Christofides algorithm.
    resources: >-
        Scribe notes in progress... 

  - date: 3/1/2019
    topic: >-
        Maximizing sub-modular functions presented by Antares — Soda 373 @ 6:00pm

        *   _Read WS § 2.5_ about maximizing float in a bank account.
    resources: >-
        [Scribe notes part 1](/src/approx-sp19/scribe-notes-4-1.pdf)  
        [Scribe notes part 2](/src/approx-sp19/scribe-notes-4-2.pdf) 

  - date: 3/8/2019
    topic: >-
        No meeting.
        *   Good luck on midterms!

  - date: 3/15/2019
    topic: >-
        Dynamic programming and knapsack presented by Leon and Lily — Soda 373 @ 6:00pm

        *   _Read WS § 3.1_ on applying dynamic programming to construct a FPTAS for dynamic programming.
    resources: >-
        [Scribe notes (draft)](/src/approx-sp19/scribe-notes-5.pdf) 

  - date: 3/22/2019
    topic: >-
        Rounding linear programs (1) presented by Wilson — Soda 373 @ 6:00pm

        *   _Read WS § 4.5, § 5.8_ on applying LP rounding to uncapacitated facility location.
    resources: >-
        [Scribe notes (draft)](/src/approx-sp19/scribe-notes-6.pdf) 

  - date: 4/5/2019
    topic: >-
        Rounding linear programs (2) presented by Ayush and Leon — **Soda 320** @ 6:00pm

        *   _Read WS § 5.1, § 5.3 - 5.5_ on various LP rounding techniques applied to approximating MAX-SAT.
    resources: >-
        [Scribe notes (draft)](/src/approx-sp19/scribe-notes-7.pdf) 

  - date: 4/12/2019
    topic: >-
        No meeting.
        *   Good luck on midterms again!

  - date: 4/19/2019
    topic: >-
        Primal-dual rounding presented by Robert and Sirej — Soda 373 @ 6:00pm

        *   _Read WS § 7.3, § 7.4_ on primal dual rounding applied to shortest path and generalized steiner tree.
    resources: >-
        Scribe notes in progress... 

  - date: 4/26/2019
    topic: >-
        Randomized SDP rounding (1) presented by Zod — Soda 373 @ 6:00pm

        *   _Read WS § 6.2_ on Goemans and Williamson's algorithm for MAXCUT.
    resources: >-
        [Scribe notes (draft)](/src/approx-sp19/scribe-notes-9.pdf) 

  - date: 5/3/2019
    topic: >-
        Randomized SDP rounding (2) presented by Lily — Soda 373 @ 6:00pm

        *   _Read WS § 6.5_ on Karger, Motwani and Sudan's algorithm for 3-Color.
    resources: >-
        [Scribe notes (draft)](/src/approx-sp19/scribe-notes-10.pdf) 

  - date: 5/9/2019
    topic: >-
        Approx Fest! presented by Antares and Wilson — **Cory 212 @ 7:00pm**

        *   Discuss ball-growing (region growing in WS) and metric LP relaxations along with inapproximability using reductions from unique games.
        *   _Read WS § 8.3_ on Garg, Vazirani, and Yannakakis's algorithm for multicut.
        *   _Read WS § 16.5_ for reductions using the Unique Games Conjecture.
    resources: >-
        [Ball-growing notes](/src/approx-sp19/scribe-notes-11.pdf)  
        [Inapproximability notes (draft)](/src/approx-sp19/scribe-notes-12.pdf)
---

### About this Group

Does P = NP? Maybe [not](https://www.cs.umd.edu/~gasarch/papers/poll.pdf), but that should not stop our study of intractable problems. There are several approaches towards dealing with NP-hard discrete optimization problems. One method is to relax optimality requirements, and instead try to find an efficient solution that is “good enough.” The study of approximation algorithms encompasses both designing and analyzing algorithms to quantify what “good enough” means.

This semester, we study various patterns in designing approximation algorithms by surveying a broad sample of intractable problems. We will encounter problems such as Set Cover and Traveling Salesman and more while discussing design patterns such as approximating via local search and primal-dual rounding of linear programs. As a culmination of our studies, we will discuss what it means to be “inapproximable” and how, in certain cases, it is inefficient to derive a reasonable approximation.

### Topics Outline

We will be reading through Williamson and Schmoy's _Design of Approximation Algorithms_. A copy of this book can be found online [here](http://www.designofapproxalgs.com/). Refer to this [document](https://docs.google.com/document/d/e/2PACX-1vSz6xi2GUsALh5PXM1co_aeIWirTOmImGuv47y9PLcY7_-X-Dlqc4po6jl3sA5gmw7CTPwswIeWUtnw/pub) for a more detailed list of topics.

*   Introduction to various approximation algorithm design patterns
*   Greedy and local search algorithms
    *   Approximating \(k\)-center
    *   Christofides algorithm for Traveling Salesman
    *   Maximizing sub-modular functions
*   Dynamic programming and the Knapsack problem
*   Rounding linear programs
    *   Uncapacitated facility location
    *   MAX-SAT
*   Primal-dual algorithms
    *   Dijkstra's algorithm as a linear program
    *   Generalized Steiner Tree
*   Rounding semidefinite programs
    *   Approximating MAXCUT
    *   Coloring 3-Colorable Graphs
*   Graph cuts: multicut and region growing
*   Hardness of approximation and the PCP Theorem
