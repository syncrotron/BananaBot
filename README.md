# CMPT 898 Project: Banana Bot

Banana Bot is an attempt at a Efficientnet based banana crop yield prediction system. This project was undertaken as a course project at the University of Saskatchewan. Banana Bot utilizes [Efficientnet](https://arxiv.org/abs/1905.11946) as a backbone to a [Feature Pyramid Network](https://arxiv.org/abs/1612.03144) with a custom direct regression toppers.  Although not currently integrated, the outputs of the Feature Pyramid toppers were to be
combined with a weighted average. This network consumes isolated images of banana bunches collected from by [Krishna Kishor Kammaje](https://www.kaggle.com/krisho007) for their [Banana Count and Weight in a bunch](https://www.kaggle.com/krisho007/banana-count-and-weight-in-a-bunch) Kaggle submission. Finally, this network was based off currently unpublished CVPPP paper. As soon as this paper is published, a link to the paper and credit will be given were appropriate.

As a final note before proceeding to how to run this notebook, this project was unsuccessful at predicting banana count per image. Some work is yet to be done, with this repo serving as an example/starting point for future projects.



## How to Run The Project

### Prerequisites:

* [Python 3.7](https://www.python.org/downloads/release/python-370/) or [higher](https://www.python.org/downloads/)
* A python virtual environment with a Jupyter server and these packages: tensorflow, pandas, numpy and matplotlib.pyplot (I suggest following [this](https://www.youtube.com/watch?v=PnK1jO2kXOQ&list=PLJxCTxje563P3YRH2hHM1tFv8R7p0_2p6&index=4) video on how to get everything set up)
* A decent graphics card (I ran the network on a GTX 1080 and could barely run it before encountering a memory overflow).

Running the project is simple. Download the repo and run the notebooks blocks sequentially. Ensure that the *Estu.csv* and the folder *data* are in the same folder as the executing notebook.
