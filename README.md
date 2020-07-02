# Anushka_Portfolio

# [Project 1: Implementation-of-Viola-Jones](https://github.com/anushkaw055/implementation-of-Viola-Jones)

Implement the Viola-Jones Algorithm for rapid face detection in python from scratch. First developed a feature extraction script, which extracted 2.5 thousand features from a 19 by 19 grayscale image. I applied the feature extraction script to a 2000 image of non-faces and 500 images of faces. I implemented the AdaBoost algorithm through the python multiprocessor module, leading to a decrease in execution time by 20%. I ran 10 rounds of the algorithm to achieve an empirical error of 67% on the testing data set. Feature manipulated the cost function on the algorithm to priories false-positive, which led to a 5.4% false-positive error.
![](/images/positions_by_state.png)

I have followed the algorithm given in the paper and have implemented the technique of non-maximal suppression as well to remove the overlapping windows or square boxes from appearing.


# [Project 2: RL_DDPG_Recommendation](https://github.com/bcsrn/RL_DDPG_Recommendation)
Project for Course : Reinforcement Learning

How to Run code:
Using Google Colab Platform:
Place data in Data Folder in drive folder RL Project.
The path to your data should look like - My Drive/RL Project/Data
The Notebook is in the RL Project Folder. Run the cells in sequence

Using an IDE:
Download the data from the link referred below
Change the paths in the python folder to the path to the data
On windows the path could look like: r'C:\Users\HOME\Documents\RLProject\Data\ml-1m\'
Install the dependencies - pytorch,torch,sklearn,numpy,pandas,scipy,matplotlib,tqdm they are mentioned at the top of the python file 
Run python -W ignore rl_actorcritic_ddpg_movie_recommendation.py

Implementation of Paper: Deep Reinforcement Learning based Recommendation with Explicit User-Item Interactions Modeling. 
Ref: Liu, Feng & Tang, Ruiming & Li, Xutao & Ye, Yunming & Chen, Haokun & Guo, Huifeng. (2018). Deep Reinforcement Learning based Recommendation with Explicit User-Item Interactions Modeling. 

Dataset Link: https://grouplens.org/datasets/movielens/1m/

Dataset Reference: F. Maxwell Harper and Joseph A. Konstan. 2015. The MovieLens Datasets: History
and Context. ACM Transactions on Interactive Intelligent Systems (TiiS) 5, 4,
Article 19 (December 2015), 19 pages. DOI=http://dx.doi.org/10.1145/2827872

