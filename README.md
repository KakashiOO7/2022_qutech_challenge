# QuTech Challenges @ MIT iQuHACK 2022

<p align="left">
  <a href="https://qutech.nl" target="_blank"><img src="https://user-images.githubusercontent.com/10100490/151484481-7cedb7da-603e-43cc-890c-979fb66aeb60.png" width="25%" style="padding-right: 0%"/></a>
  <a href="https://iquhack.mit.edu/" target="_blank"><img src="https://user-images.githubusercontent.com/10100490/151647370-d161d5b5-119c-4db9-898e-cfb1745a8310.png" width="10%" style="padding-left: 0%"/> </a>
</p>


## How its working

1.Alice have two options for encoding 1 and two options for encoding 0. she can use 0°(↕) or 45°(/) polarised photon(angle with respect to vertical) for 1 and for 0 she can use 90°(↔) or -45°(\) polarised photon.

2.After encoding she will send his photons to bob. Bob has 2 types of decoding polariser + type and x type. 0°(↕) and 90°(↔) polarised photons can pass + type polariser with probability 1 but 45°(/) and -45°(\) polarised photons can pass with probability1/2 as we have seen above. Similarly 45°(/) and -45°(\) polarised photons can pass x type polariser with probability 1 but  0°(↕) and 90°(↔) polarised photons can pass with probability1/2 only.
3.Now bob will randomly choose + and x type polariser for measuring state of each photon.

4.After measurement bob will send his sequence of + and x type plates that he chooses randomly through an unsecure line. Where eve can also listen this conversation.

5.Now Alice will tell bob about which choice was correct and which bit bob received corrupt.

6. finally Alice and bob both knew about which bit was corrupted so both will put 0 on corrupted bit and now both will agree upon a key.
This fig. Given below also Demonstrate the communication procedure.

![image](https://drive.google.com/file/d/1x4CEiE826FzVEi70cXOjT2_aJnxGnbz_/view?usp=sharing)

 
## start app 
```sh
python3 Main_prog.py
```

## how to give input

## Description 

For the 2022 edition of the iQuHack (interdisciplinary Quantum HACKathon), [QuTech](https://qutech.nl) has partnered with the team at MIT to propose 2 challenges, hosted in our own multi-hardware Quantum Technology platform, [Quantum Inspire](https://www.quantum-inspire.com). These aim to draw participants to the challenges at the heart of our mission: to develop scalable prototypes of a quantum computer and an inherently safe quantum internet, based on the fundamental laws of quantum mechanics.

To qualify for the QuTech Division Challenge, participants should submit a project that addresses either the proposed Quantum Error Correction (QEC) challenge or the Quantum Key Distribution (QKD) challenge. Detailed descriptions of these two challenges and their goals are available in the documents linked below (hosted in this repository):

- [Quantum Error Correction Challenge](https://github.com/iQuHACK/2022_qutech_challenge/blob/main/QuantumErrorCorrectionChallenge.pdf)
- [Quantum Key Distribution Challenge](https://github.com/iQuHACK/2022_qutech_challenge/blob/main/QuantumKeyDistrubutionChallenge.pdf)


## Scoring and Submission

**Rubric:** https://docs.google.com/document/u/1/d/e/2PACX-1vR5PVoInN_Fi42lIOchhblgGBPblgNyouj1XHukonZ4sdqY-p5ulS9TxdzvddEcDNFc5k_6teFyKzXv/pub

**Submission:** Please visit https://iquhack.mit.edu/ for details on how to submit your project.
