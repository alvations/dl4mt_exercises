**An Introduction to Deep Learning with Theano**

Fundamentals for DL4MT  I

Quick review of MLP & Backprop
Deep Belief Nets, Stacked Auto-Encoders
Tricks: drop-out, distributed training, Hessian-free optimization, ReLu, etc. 

Goal: Prep and setup.
Compare logistic regression, MLP, and stacked auto-encoders on same data
Challenges: Implement tricks

**Please work through the notebooks in the following order:**

1- prep_text_classification_corpus.ipynb     
2- prep_pos_corpus.ipynb     
3- baseline_logistic_regression_pos_tagging.ipynb      
4- theano_logistic_regression_pos_tagging.ipynb      
5- theano_autoencoder.ipynb      

As you work through the notebooks, you will notice that some of the cells use the %%writefile magic at the top of the cell to write the content to a file. This is done for classes and functions which will be used in later notebooks. In order for the save paths to work correctly, you need to be running `ipython notebook` inside the directory for that day. 

Every time the cell is run, the file will be overwritten, so if you want to modify the behavior of a class or function, just edit the cell where it is created, and the corresponding file will automatically update. 

***Installation and Setup***

Please also make sure that you are using the bleeding edge version of theano from github. Installation instructions are [here](http://deeplearning.net/software/theano/install_ubuntu.html#bleeding-edge-installs). 

These labs use [Fuel](http://fuel.readthedocs.org/en/latest/setup.html) to build, load, and iterate over datasets, please install that first. 

***Memory and Disk Space Management***
If you are using the Virtual Machine provided for the exercises, you may find the available memory getting low. Once you have worked through a notebook, you can close it to free up the RAM used by that kernel. 


***Resources and Inspirations Used to Create these Tutorials***

http://deeplearning.net/tutorial/dA.html

http://deeplearning.net/tutorial/SdA.html




