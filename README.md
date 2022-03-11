# Applied Machine Learning Days EPFL 2022<br />"Visual Disinformation and the Dark Side of Internet Memes"

This repository contains code and data for the workshop "Visual Disinformation and the Dark Side of Internet Memes" at the Applied Machine Learning Days EPFL 2022 ([Workshop Link](https://appliedmldays.org/events/amld-epfl-2022/workshops/visual-disinformation-and-the-dark-side-of-internet-memes)).

## Workshop Part 1

Klick on the following link to open the notebook in Google Colab (recommended):

## Workshop Part 2

Klick on the following link to open the notebook in Google Colab (recommended):

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/i4Ds/AMLD-2022-Visual-Disinformation/blob/main/part2.ipynb)


Alternatively, clone the repository and install dependencies. Git lfs is required to fetch the data [Git lfs](https://git-lfs.github.com/). Warning: In this version you will see the solutions to some exercises (cell-hiding does not work).

```
apt-get update
apt-get install git-lfs
git clone https://github.com/i4Ds/AMLD-2022-Visual-Disinformation.git
cd AMLD-2022-Visual-Disinformation
```

```
pip install -r requirements_part2.txt
```

```
tar -xf ./data/GRU_202012.tar.gz --directory ./data/
```

In the notebook skip the preparatory steps.

## Workshop Organizers

Raphael Meier, Scientific Project Manager, armasuisse S+T

Marco Willi, Research Associate, FHNW

Michael Graber, Professor, FHNW

## Supported By

[Armasuisse S+T](https://www.ar.admin.ch/de/armasuisse-wissenschaft-und-technologie-w-t/home.html)

<p align="left">
  <img src="./logos/ar.png" width="350" alt="armasuisse S+T">
</p>

[FHNW - University of Applied Sciences and Arts Northwestern Switzerland](https://www.fhnw.ch/en) - 
<p align="left">
  <img src="./logos/fhnw.png" width="350" alt="FHNW">
</p>


[Cyber Defence Campus](https://www.ar.admin.ch/en/armasuisse-wissenschaft-und-technologie-w-t/cyber-defence_campus.html)
<p align="left">
  <img src="./logos/cyd.png" width="350" alt="Cyber Defense Campus">
</p>



## References & Acknowledgements

Data for Part 1 are from:


Data for Part 2 are from Twitter Transparency: [Link](https://transparency.twitter.com/en/reports/information-operations.html). Any usage is subject to Twitter's terms and conditions [Link](https://developer.twitter.com/en/developer-terms).


Radford, Alec, Jong Wook Kim, Chris Hallacy, Aditya Ramesh, Gabriel Goh, Sandhini Agarwal, Girish Sastry, et al. “Learning Transferable Visual Models From Natural Language Supervision.” ArXiv:2103.00020 [Cs], February 26, 2021. http://arxiv.org/abs/2103.00020.
