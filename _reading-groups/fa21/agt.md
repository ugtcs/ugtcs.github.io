---
layout: reading-group
name: Algorithmic Game Theory
sem: 2021-4
location: Cory 400
time: 20:00 - 21:00
logistics: >-
    Please fill out our interest form 
    [here](https://tinyurl.com/ugtcsinterestform) if you would like to join this reading group
files: >- 
    [scribe note template](/src/maxflow-sp20/maxflow-scribe.sty)
weeks:

  - date: Week 1 (9/20)
    topic: >-
        Introduction to (Algorithmic) Game Theory. Why does Algorithmic Game Theory Matter?

        *   [Week 1](http://timroughgarden.org/f13/l/l1.pdf) of Roughgarden’s AGT.
    resources: >-
        [notes](/src/agt_fa19/AGTWeek1.pdf) 

  - date: Week 2 (9/27)
    topic: >-
        Introduction to Auctions. What properties make a good auction? Vickrey, Sponsored Search, and Myerson’s Lemma.

        *   [Week 2](http://timroughgarden.org/f13/l/l2.pdf) of Roughgarden’s AGT.
  
        *   [Week 3](http://timroughgarden.org/f13/l/l3.pdf) of Roughgarden’s AGT.
    resources: >-
        [notes](/src/agt_fa19/scribe2.pdf) 

  - date: Week 3 (10/4)
    topic: >-
        Finish Myerson's lemma, knapsack auctions, and the revelation principle.
  
        *   [Week 3](http://timroughgarden.org/f13/l/l3.pdf) of Roughgarden’s AGT.
        
        *   [Week 5](http://timroughgarden.org/f13/l/l5.pdf) of Roughgarden’s AGT.
    resources: >-
        [notes](/src/agt_fa19/Week_3__Knapsack_Auctions_and_Welfare_Maximization__agt_f19_.pdf) 

  - date: Week 4 (10/11)
    topic: >-
        The challenge of Revenue Maximization: Briefly discuss the difference between revenue maximization and welfare maximization, then talk about the revelation principle. 
        Finally, find a formula relating revenue to welfare.

        *   [Week 4](http://timroughgarden.org/f13/l/l4.pdf) of Roughgarden’s AGT.

    resources: >- 
        [notes](/src/agt_fa19/Week_4_Prophet_Inequality.pdf) 

  - date: Week 5 (10/18)
    topic: >-
        Prophet Inequality. How close can we get in sequential auctions to oracle optimality? Discuss interesting single-item auctions with Prophet Inequality, and introduce Bulow-Klemperer. Multi-parameter Mechanism Design, and VCG Mechanism. Can we find desirable auctions when demand is multi-parametered? Using VCG, we look at Combinatorial Auctions. Find interesting problems from psets online to discuss.
        *   [Week 6](http://timroughgarden.org/f13/l/l6.pdf) of Roughgarden’s AGT.

        *   [Week 7](http://timroughgarden.org/f13/l/l7.pdf) of Roughgarden’s AGT.
        
        *   [Week 8](http://timroughgarden.org/f13/l/l8.pdf) of Roughgarden’s AGT.

  - date: Week 6 (10/25)
    topic: >-
        Mechanism Design in non-monetary settings: school choice, kidney exchange, stable matching, etc. Briefly, we discuss the Clinching Auction.

        *   [Week 9](http://timroughgarden.org/f13/l/l9.pdf) of Roughgarden’s AGT.
        
        *   [Week 10](http://timroughgarden.org/f13/l/l10.pdf) of Roughgarden’s AGT.

  - date: Week 7 (11/1)
    topic: >-
        Price of Anarchy. How much can games/outcomes suffer if everyone decides to act selfishly instead of working together? We revisit Braess’ Paradox, and find tighter bounds on the Price of Anarchy. We introduce the Atomic Selfish Routing game.

        *   [Week 11](http://timroughgarden.org/f13/l/l11.pdf) of Roughgarden’s AGT.
        
        *   [Week 12](http://timroughgarden.org/f13/l/l12.pdf) of Roughgarden’s AGT.

  - date: Week 8 (11/8)
    topic: >-
        Equilibrium Hierarchy. What types of equilibria exist in games, and how can we think about them? Find interesting problems from psets online to discuss.

        *   [Week 13](http://timroughgarden.org/f13/l/l13.pdf) of Roughgarden’s AGT.

  - date: Week 9 (11/15)
    topic: >-
        Price of Anarchy 2: Electric Boogaloo. Analysis of the price of different forms of equilibria.

        *   [Week 14](http://timroughgarden.org/f13/l/l14.pdf) of Roughgarden’s AGT.
        
        *   [Week 15](http://timroughgarden.org/f13/l/l15.pdf) of Roughgarden’s AGT.

  - date: Week 10 (11/22)
    topic: >-
        Convergence to Equilibrium: Should we expect players to converge towards an equilibrium? How quickly? Under what circumstances? Lecture 17 is on the Experts algorithm, but we won’t discuss it much because it’s covered in CS 170.

        *   [Week 16](http://timroughgarden.org/f13/l/l16.pdf) of Roughgarden’s AGT.
        
        *   [Week 17](http://timroughgarden.org/f13/l/l17.pdf) of Roughgarden’s AGT.

  - date: Week 11 (11/29)
    topic: >-
        Convergence to more specific types of equilibrium, including Correlated Equilibrium and Mixed Nash Equilibrium. We’ll look at Minimax, Max Cut, and Congestion problems.

        *   [Week 18](http://timroughgarden.org/f13/l/l18.pdf) of Roughgarden’s AGT.
        
        *   [Week 19](http://timroughgarden.org/f13/l/l19.pdf) of Roughgarden’s AGT.

  - date: Week 12 (12/6)
    topic: >-
        Intractability of Equilibrium: which games are inherently intractable in terms of finding equilibria? Wrapup, with look at take-home final.

        *   [Week 20](http://timroughgarden.org/f13/l/l20.pdf) of Roughgarden’s AGT.
        
        *   [Final](http://timroughgarden.org/f13/ps/ps5.pdf) of Roughgarden’s AGT.
---

From an article by Professor Tim Roughgarden:

The widespread adoption of the Internet and the emergence of the Web changed society’s relationship with computers. 
The primary role of a computer evolved from a stand-alone, well-understood machine for executing software to a conduit for global communication, content-dissemination, and commerce. 
The algorithms and complexity theory community has responded to these changes by formulating novel problems, goals, and design and analysis techniques relevant for modern appli- cations. 
Game theory, which has studied deeply the interaction between competing or cooperating individuals, plays a central role in these new developments. 
Research on the interface of theoretical computer science and game theory, an area now known as algorithmic game theory (AGT), has exploded phenomenally over the past ten years.

The primary research themes in AGT differ from those in classical microeconomics and game theory in important, albeit predictable, respects. 
Firstly in application areas: Internet-like networks and non-traditional auctions motivate much of the work in AGT. 
Secondly in its quantitative engi- neering approach: AGT research typically models applications via concrete optimization problems and seeks optimal solutions, impossibility results, upper and lower bounds on feasible approxi- mation guarantees, and so on. 
Finally, AGT usually adopts reasonable (e.g., polynomial-time) computational complexity as a binding constraint on the feasible behavior of system designers and participants. 
These themes, which have played only a peripheral role in traditional game theory, give AGT its distinct character and relevance.
