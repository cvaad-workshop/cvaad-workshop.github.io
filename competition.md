---
title: Floor plan generation
feature_text: 
feature_image: "../assets/images/cover-image3.png"
---

The floor plan generation task takes as input the boundary of a building, the structural elements necessary for the building's structural integrity, and a set of user constraints formalized in a graph structure, with the goal to automatically generate the full floor plan. 
While previous research on floor plan generation has mainly focused on the scale of individual apartments, our challenge sets the stage for floor plan generation at a larger scale: the scale of the apartment complex. 
With the help of [Archylise](https://www.archilyse.com/), we developed [Modified Swiss Dwellings: a ML-ready Dataset for Floor Plan Generation at Scale](https://data.4tu.nl/datasets/e1d89cb5-6872-48fc-be63-aadd687ee6f9) which was used for the challenge.

![image](https://github.com/cvaad-workshop/cvaad-workshop.github.io/assets/40263235/6b9d3d60-9589-4434-8b74-55752f67acec)

- The **dataset** can be downloaded [here](https://data.4tu.nl/datasets/e1d89cb5-6872-48fc-be63-aadd687ee6f9).
- The **guidelines** of the challenge can be found [here](https://github.com/cvaad-workshop/iccv23-challenge).

The submitted models were evaluated on [Codalab](https://codalab.lisn.upsaclay.fr/competitions/14431). 
~~We will update you on when the server is ready (we expect the server to run at the start of July).~~

## Reward
We have a reward of 1000eu for the best competitor.

## Best competitors
We happily announce the **two best contenders**:

> **Emanuel Kuhn (Delft University of Technology)**. Emanuel developed a model for floor plan generation based on [HouseDiffusion](https://arxiv.org/abs/2211.13287), a state-of-the-art diffusion model tailored towards floor plan generation of single-family houses. He added several modules to adapt it to our task and checked the generalizability of the diffusion method towards our dataset. Technical report [here](https://arxiv.org/abs/2312.03938).

> **Yuntae Jeon (Sungkyunkwan University)**. Yuntae developed a model for floor plan generation that combines a U-Net with a graph convolution network in latent-space. Technical report [here](https://arxiv.org/abs/2309.13881).

While Emanuel scored best on the user tests, Yuntae scored best on the quantitative metrics. Hence, we decided to split the price in two.

## Important dates
- ~~Challenges open: June 22nd, 2023~~
- ~~Challenges close: September 25th, 2023~~
- ~~Technical reports due: September 25th, 2023~~
- ~~Winners announced: Live session at ICCV~~

## Rules
- For submissions on CodaLab to qualify to the challenge we require the contenders to submit a short technical report about their final submission. See details below under “Report”. Submissions without a report associated do not qualify to the competition.
- Top contenders in the challenge are required to make their work reproducible. This means that contenders should be able to share their code (or show to others how it can be used) and that the results are equivalent to the scores in the leaderboard. The organizers might (randomly) contact top contenders to check these criteria. (It is not required, although highly encouraged, to provide a GitHub repository, or similar, about the submission.)
- Organizers retain the right to disqualify any submissions that violate these rules.
- Be aware that you _are_ allowed to use any other data for training or any pre-trained model.

## Report
- For submissions on CodaLab to qualify to the challenge we require the authors submit a short technical report about their final submission.
- We suggest that the technical report consists of three sections: introduction, method, and results/discussion.
- The report should not be longer than 3 pages and shouldn't extend 2000 words.
- Authors are to submit their report to [ArXiv](https://arxiv.org/) and submit the link to c.c.j.vanengelenburg AT tudelft DOT nl. Those unable to submit to Arxiv can email their report directly to c.c.j.vanengelenburg AT tudelft DOT nl.
- After the conference we will publish the links to the technical reports on the workshop website.
