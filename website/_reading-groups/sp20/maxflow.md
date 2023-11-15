---
name: Convex Optimization and Maximum Flows
sem: 2020-2
layout: reading-group
location: See update
time: Round table discussions each Monday at 6:30 pm, and presentations each Friday at 6:00 pm
logistics: >-
    Please join our emailing list [here](https://groups.google.com/d/forum/ugtcs-maxflow-sp20) to stay up to date with current events.
    Fill out this [Google Form](https://forms.gle/D4PKQVwo7RPJc23p8") for course units.
files: >-
    [scribe note template](/src/maxflow-sp20/maxflow-scribe.sty)
weeks:
  - date: 2/3/2020
    topic: >-
      Reading group General meeting and preliminary logistics — Soda 380 @ 7:00pm

      - Discuss semester long goals, plans for weekly meetings, and unit requirements.
  - date: 2/7/2020
    topic: >-
      [CKMST11] Part 1 presented by Antares &mdash; Soda 373 @ 6:00pm

      - Read § 3 of _[Electrical flows, laplacian systems, and faster approximation of maximum flow in undirected graphs](https://arxiv.org/abs/1010.2921)_

      - Round table discussion in _Soda 373 @ Wednesday 2/5 7:00pm_ will cover experts, electrical flows, and a sketch of the $$\tilde{\mathcal{O}}(\frac{m^{3/2}}{\epsilon^{5/2}})$$ time algorithm.

    resources:
      Scribe notes coming soon
  - date: 2/14/2020
    topic: >-
      [CKMST11] Part 2 presented by Albert and Natalie &mdash; Soda 373 @ 6:00pm

      - Read § 4 of _[Electrical flows, laplacian systems, and faster approximation of maximum flow in undirected graphs](https://arxiv.org/abs/1010.2921)_

      - Round table discussion in _Cory 212 @ Monday 2/10 6:30pm_ will sketch the $$\widetilde{\mathcal{O}}(\frac{m^{4/3}}{\epsilon^3})$$ time algorithm.
    resources:
      Scribe notes coming soon
  - date: 2/21/2020
    topic: >-
      Maxflow noting and coding workday  &mdash; Soda 373 @ 6:00pm

      - No round table discussion this week; we'll be coding and writing scribe notes for CKMST on Friday.
  - date: 2/28/2020
    topic: >-
      [KOSZ13] Part 1 presented by Josh and Naveen &mdash; Soda 373 @ 6:00pm

      - Read § 2-4 and 6 of _[A simple, combinatorial, algorithm for solving SDD systems in nearly-linear time](https://arxiv.org/abs/1301.6628)_

      - Round table discussion in _Cory 212 @ Monday 2/24 6:30pm_ will sketch the $$\widetilde{\mathcal{O}}(m \log^2 n \log \log n \log (\frac{n}{\epsilon}))$$ time algorithm for solving SDD linear systems.
    resources:
      Scribe notes coming soon
  - date: 3/6/2020
    topic: >-
      [KOSZ13] Part 2 presented by Robert &mdash; Soda 373 @ 6:00pm

      - Read § 6, 9, 10 of _[A simple, combinatorial, algorithm for solving SDD systems in nearly-linear time](https://arxiv.org/abs/1301.6628)_

      - Round table discussion in _Cory 212 @ Monday 3/2 6:30pm_ will sketch the geometric intuition for the KOSZ algorithm.
    resources:
      Scribe notes coming soon
  - date: 3/13/2020
    topic: >-
      Campus Recommendation to Move to Online Meetings due to COVID-19 &mdash; no meeting

      - Please stay safe and wash your hands!
  - date: 3/19/2020
    topic: >-
      [Sherman13] presented by Prof. Rao &mdash; Zoom @ 4:00pm <span style="color:red">**Thursday 3/19**</span>

      - Read _[Nearly Maximum Flows in Nearly Linear Time](https://arxiv.org/abs/1304.2077)_

      - Link to the webcast will be available before the meeting.

---

<span style="color:red">**Update on 3/13/2020 - due to recent developments regarding the transmission of COVID-19, we will be moving our meetings to an online video conferencing service. More details regarding how you can connect will be available soon. Please stay safe and wash your hands!**</span>

In the past decade, major advancements in the design and analysis of algorithms have risen from a confluence of techniques developed in continuous and discrete optimization.
One example in which this blend of approaches has been particularly effective is towards algorithms for solving maximum flow problems on graphs.
This semester, we will read recent papers related to maxflow and learn about techniques developed in optimization related to analyzing Laplacian linear system solvers, interior point methods, and preconditioner construction.

### Paper List

A selection of papers that we may read

- [_Electrical flows, laplacian systems, and faster approximation of maximum flow in undirected graphs_](https://arxiv.org/abs/1010.2921)
  - Paul Christiano, Jonathan A. Kelner, Aleksander M&#261;dry, Daniel A. Spielman, and Shang-Hua Teng
- [_A simple combinatorial algorithm for solving SDD systems in nearly-linear time_](https://arxiv.org/abs/1301.6628)
  - Jonathan A. Kelner, Aaron Sidford, Lorenzo Orecchia, and Zeyuan Allen Zhu
- [_Navigating central path with electrical flows: from flows to matchings, and back_](https://arxiv.org/abs/1307.2205)
  - Aleksander M&#261;dry
- [_Path finding methods for linear programming: Solving linear programs in $$\mathcal{O}(\sqrt{\text{rank}})$$ iterations and faster algorithms for maximum flows_](https://arxiv.org/abs/1312.6677)
  - Yin Tat Lee and Aaron Sidford
- [_An almost-linear-time algorithm for approximate max flow in undirected graphs, and its multicommodity generalizations_](https://arxiv.org/abs/1304.2338)
  - Jonathan A. Kelner, Yin Tat Lee, Lorenzo Orecchia, and Aaron Sidford
- [_Computing maximum flows with augmenting electrical flows_](https://people.csail.mit.edu/madry/docs/aug_flow.pdf)
  - Aleksander M&#261;dry
- [_Generalized preconditioning and network flow problems_](https://arxiv.org/abs/1606.07425)
  - Jonah Sherman
- [_Flows in almost linear time via adaptive preconditioning_](https://arxiv.org/abs/1906.10340)
  - Rasmus Kyng, Richard Peng, Sushant Sachdeva, Di Wang
- [_Faster energy maximization for faster maximum flows_](https://arxiv.org/abs/1910.14276)
  - Yang P. Liu and Aaron Sidford

### Additional Resources

- A number of talks regarding the above papers have been recorded and posted to YouTube
  - Aleksander Mądry's [talk](https://www.youtube.com/watch?v=sgCq7g67920) on approximating maxflow using electrical flows
  - Aleksander Mądry's [introduction](https://www.youtube.com/watch?v=OJPj2-lkqMo) to interior point methods
  - Aleksander Mądry's [talk](https://www.youtube.com/watch?v=ZIxp0rPEQ_c) on solving maxflow using interior point methods
  - Aaron Sidford's [talk](https://www.youtube.com/watch?v=4ZyqCOrszLc) on solving linear programs in $$\mathcal{O}(\sqrt{\text{rank}}) $$ iterations
- [Bootcamp](https://simons.berkeley.edu/workshops/spectral2014-boot-camp) from the Simon's Institute's Fall 2014 program on Algorithmic Spectral Graph Theory
- [Bootcamp](https://simons.berkeley.edu/workshops/optimization2017-boot-camp) from the Simons Institute's Fall 2017 program on Bridging Continuous and Discrete Optimization
