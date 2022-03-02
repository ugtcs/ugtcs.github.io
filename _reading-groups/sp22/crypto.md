---
layout: reading-group
name: Special Topics in Cryptography
sem: 2022-2
location: Cory 540AB most days, Cory 531 on March 2 and March 9
time: Wednesdays 18:30 - 20:00
logistics: >-
    Please fill out our interest form 
    [here](https://docs.google.com/forms/d/e/1FAIpQLScT9Z22QgcxRjRhNR6bRUvVbK9QGgRKL0WfLcwEVu4oIXrLNA/viewform) to join this reading group
files: >- 
    [scribe note template](/src/maxflow-sp20/maxflow-scribe.sty), [reading group recordings](https://drive.google.com/drive/u/1/folders/14DkB_s1pBs5ta5ciFTtwFpTQj53Bqr5H)
weeks:

  - date: Week 1 (2/7)
    topic: >-
        Intro to Cryptography

        *   Basic cryptographic primitives and the relation between them
        
        *   (Part 1 aka CS161 Crypto Module Crash Course): Encryption / Authentication : Symmetric / Asymmetric. Commitments. Basic cryptographic primitives and the relation between them
        
        *   (Part 2):  Lecture 1 cont. OWF => PRG => PRF if we have time.
    recources: >-
        *   [CS 161 Textbook](https://textbook.cs161.org/crypto)
  
  - date: Week 2 (2/14)
    topic: >-
        Interactive proofs, Zero knowledge

        *   Updating proofs for the computer age! Plus: how to prove something without giving away any knowledge
    recources: >-
        *   [Lecture 8](https://crypto.stanford.edu/cs355/21sp/lec8.pdf)
  
  - date: Week 3 (2/21)
    topic: >-
        Succinct Non-interactive Arguments (SNARGs) from PCPs, Polynomial commitments

        *   Making zero-knowledge proofs efficient. What is the role of interactivity and randomness in proof?
    resources: >-
        *   [Lecture 11](https://crypto.stanford.edu/cs355/21sp/lec11.pdf)
  
  - date: Week 4 (2/28)
    topic: >-
        BUFFER WEEK (discrete log if time)

        *   Discrete log: a problem whose hardness many cryptographic primitives depend on.
  
  - date: Week 5 (3/7)
    topic: >-
        Oblivious transfer, Two-party computation: Yao's garbled circuits

        *   How to compute functions on two secret inputs without revealing anything but their output. How to request information without revealing what you requested.
    resources: >-
      *   [Lecture 13](https://crypto.stanford.edu/cs355/21sp/lec13.pdf)
  
  - date: Week 6 (3/14)
    topic: >-
        Secret sharing

        *   Splitting up secrets among people so people can only recover them by pooling their information.
    resources: >-
        *   [Lecture 14](https://crypto.stanford.edu/cs355/21sp/lec14.pdf)
  
  - date: Week 7 (3/28)
    topic: >-
        Multi-party Computation

        *   Two-party computation, but with more parties!
    resources: >-
        *   [Lecture 15](https://crypto.stanford.edu/cs355/21sp/lec15.pdf)
  
  - date: Week 8 (4/4)
    topic: >-
        Differential privacy

        *   How to aggregate data without leaking individuals' information.
    resources: >-
        *   [Lecture 16](https://crypto.stanford.edu/cs355/21sp/lec16.pdf)
  
  - date: Week 9 (4/11)
    topic: >-
        BUFFER WEEK
  
  - date: Week 10 (4/18)
    topic: >-
        Private Information Retrieval

        *   How do I create a database such that no one knows what data I have retrieved from the database?
    resources: >-
        *   [Lecture 17](https://crypto.stanford.edu/cs355/21sp/lec17.pdf)
  
  - date: Week 11 (4/25)
    topic: >-
        Fully homomorphic encryption (LWE)

        *   Enc(f(x))=f(Enc(x)) for all x and polynomials f, yuh
    resources: >-
        *   [Lecture 19](https://crypto.stanford.edu/cs355/21sp/lec19.pdf )
---

The reading group will follow an abridged version of Stanford [CS 355](https://crypto.stanford.edu/cs355/21sp/schedule/) Sp21.

Our main references are the readings listed on Stanford CS 355's syllabus. Additional resources that I find helpful/fun (this will be continuously updated):

- Past offerings of Stanford CS 355. Just change the url on their website.
- [Lectures](https://www.youtube.com/channel/UCH_TKbymPv-9NdCIroUSBiA/videos) and [notes](https://www.cs.cmu.edu/~goyal/15356/lecture_notes.pdf) by [Vipul Goyal](https://www.cs.cmu.edu/~goyal/)
- Dan Boneh's [book](http://toc.cryptobook.us/)
- Henry Corrigan-Gibb's [class on Cryptosystems](https://6893.csail.mit.edu/)
- Justin Thaler's [book](https://people.cs.georgetown.edu/jthaler/ProofsArgsAndZK.html) on proof systems

Fun stuff in Stanford CS 355 that are left out (can talk about if we have time)
- OWF => PRG => PRF => PRP => Block Cipher
- Discrete Log
- Elliptic Curves
- Pairing-based Cryptography
- SNARGs from Polynomial commitment + IOP
	- [Thaler's talk](https://georgetown.zoom.us/rec/play/kUuOJF7uHoApp8fSqwheZz1FPzRq0ZKxpIufTO2TyPpjc9ubjTTDzNZS0a88GrVCZgPoTrTd2foiQjs.pvY8SbCTUX-7oqJf?startTime=1639755325000&_x_zm_rtaid=U5qk8mSTScCif0KvSeRE1Q.1643240311771.7ea7ca5bdb01137b07ebfd566bf43230&_x_zm_rhtaid=168).
- More Lattice-based Cryptography

