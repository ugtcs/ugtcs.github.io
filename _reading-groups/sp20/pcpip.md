---
layout: reading-group
name: Probabilistically Checkable Proofs & Interactive Proofs
sem: 2020-2
files: | 
    [scribe note repository](https://github.com/ugtcs/sp20-pcpip)
location: Soda 405
time: Thursdays 2:00-3:30pm
logistics: |
    Please join the #sp20-pcpip channel on Slack for logistics and announcements!
weeks:
  - date: Week 1 (2/10-2/14)
    topic: |
        Interactive Proofs (IPs), MA/AM, Graph Non-Isomorphism (GNI)

        presented by Max &mdash; Thursday 2:00-3:30pm in Soda 405
    resources: |
        - [PCPIP sp2019 lecture 1](https://www.youtube.com/watch?v=-WCvJurvmlM&list=PLkFD6_40KJIyWWtxCPBHwGsrutjvwM5_U&index=2&t=0s)
        - [PCPIP sp2019 lecture 4](https://www.youtube.com/watch?v=Q1K3eOEgxao&list=PLkFD6_40KJIyWWtxCPBHwGsrutjvwM5_U&index=4)
  - date: Week 2 (2/17-2/21)
    topic: |
        Zero-Knowledge Proofs
  - date: Week 3 (2/24-2/28)
    topic: |
        Some Nice Containments: $$\mathsf{coNP} \subseteq \mathsf{IP}, \mathsf{IP} = \mathsf{PSPACE}$$
  - date: Week 4 (3/2-3/6)
    topic: |
        __Breather week__. 
        Nothing is scheduled this week, in case we need time to catch up/finish previous topics.
  - date: Week 5 (3/9-3/13)
    topic: |
        Set Lower Bounds, GNI, public coins
  - date: Week 6 (3/16-3/20)
    topic: |
        Special Topic. QIP?
        
  - date: Week 7 (3/23-3/27)
    topic: |
        __Enjoy spring break!__
  - date: Week 8 (3/30-4/3)
    topic: |
        PCP theorem part 1 - exp size, LPCP, BLR
  - date: Week 9 (4/6-4/10)
    topic: |
        PCP theorem part 2 - assignment testers
  - date: Week 10 (4/13-4/17)
    topic: |
        __Breather week__. 
        Nothing is scheduled this week, in case we need time to catch up/finish previous topics.
        
  - date: Week 11 (4/20-4/24)
    topic: |
        Hardness of approximation
        
  - date: Week 12 (4/27-5/1)
    topic: |
        Special Topic. IOPs, SNARKs?
  - date: Week 13 (5/4-4/8)
    topic: |
        __RRR week__. Likely nothing planned, good luck with finals!
---

Over the past 3 decades, one of the biggest advancements in theoretical computer science has come from how we look at the complexity of a problem: instead of considering the fastest algorithms that find a correct solution, what is the complexity of a procedure that verifies correctness and authenticity of a solution? Does it require multiple rounds of conversation? If so, what are the fewest number of rounds that are necessary? Does this answer change when you incorporate randomness: that is, potentially accept incorrect solutions albeit with small probability? Can this notion be carried out reading extremely minimal sections of the proof? Is it possible to convince someone you have the correct solution without giving away what that solution is? All of these intuitive and interesting questions are explored with rigor in the PCP/IP reading group. We will learn the basics of interactive, zero-knowledge, and probabilistically checkable proofs, as well as their various applications.

### Additional Resources

- Our reading group will mostly be a subset of Prof. Alessandro Chiesa's fantastic Spring 2019 [PCPIP course](http://people.eecs.berkeley.edu/~alexch/classes/CS294-S2019.html)
  - Full video recordings for the course are available [here](https://www.youtube.com/playlist?list=PLkFD6_40KJIyWWtxCPBHwGsrutjvwM5_U)
- Prof. Luca Trevisan has a course on PCPs and hardness of approximation [here](https://people.eecs.berkeley.edu/~luca/pcp/)