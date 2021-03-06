## COMP90051 - Statistical Machine Learning

### Project 1:  Link Prediction

The code included within this project correspond to an approach to the "Link Prediction" problem deployed as part of the subject COMP90051: Statistical Machine Learning. 



**Problem Description:** Given a training network - a list of pairwise relationships – representing a partial crawl of the Twitter Social network, how to distinguish between real and fakes edges in a given test set only by using the supplied information.



**Solution:**  By using "igraph" - a python graph library - we construct a sub-graph made of nodes in the network and directed edges between them representing relations between nodes. From this graph and based on topological features alone, we produce a supervised machine learning algorithm that ascribes a probability to any tuple, thereby quantifying its potential as a “missing” link. 


### Requirements

The program was built using python 3.6 in it's 64 bit version. The solution also require a series of libraries which can be installed by using the "requirements.txt" file included within the project and using the following command:

	**pip install -r requirements.txt**



### Running the code

For opening the code, just run the following command:

​	**jupyter notebook SML_Project1.ipynb**

