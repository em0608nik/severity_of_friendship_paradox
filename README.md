# Severity of Friendship Paradox in Networks

This repository contains resources and a Jupyter Notebook for analyzing and designing metrics for quantifying the friendship paradox in networks. The repository includes dataset files, scripts, and instructions for running the analysis on Google Colab or your local machine.

---

## **How to Open the Notebook**

### **Using Google Colab**

1. **Open the Notebook in Colab**:

   * Navigate to the notebook on GitHub.
   * Click on the notebook file (`Assignment_1.ipynb`).
   * Click the **"Open in Colab"** button that appears at the top of the page once loading has finished or manually open the notebook in Google Colab by appending the following link:

     ```
     https://colab.research.google.com/github/em0608nik/severity_of_friendship_paradox/blob/main/Assignment_1.ipynb
     ```

2. **Run the Setup Code Block**:

   * To access the dataset files used in the Notebook, you would need to clone them along with the repository to the local Colab runtime. For that, run the code block with the following contents, found in the notebook (or copy and run it manually by yourself):

     ```python
     import os

     if 'google.colab' in str(get_ipython()):
         if not os.path.exists('severity_of_friendship_paradox'):
             !git clone https://github.com/em0608nik/severity_of_friendship_paradox.git
         %cd severity_of_friendship_paradox
     ```

3. **Run the Notebook**:

   * Once the repository is cloned, proceed to run the remaining cells in the notebook as needed.

---

### **Using Your Local Machine**

1. **Clone the Repository**:

   * Open a terminal and run:

     ```bash
     git clone https://github.com/em0608nik/severity_of_friendship_paradox.git
     cd behaviour_analysis
     ```

2. **Run the Notebook**:

   * Open the notebook locally using Jupyter Notebook or Jupyter Lab:

     ```bash
     jupyter notebook Assignment_1.ipynb
     ```

---
## Databases

We chose the following 8 networks to test our $M_2$:

* **`Auburn71`**
  
https://networkrepository.com/socfb-Auburn71.php

* **`Baylor93`**

https://networkrepository.com/socfb-Baylor93.php 

Auburn71 and Baylor93 are social friendship networks extracted from Facebook consisting of people (nodes) with edges representing friendship ties within Auburn Univeristy of Alabama and Baylor Univeristy of Texas, respectively.

* **`Mouse Brain Axons`**

https://networkrepository.com/bn-mouse-kasthuri-graph-v4.php

Mouse Brain Axons is a brain network representing a mouse's brain, where edges represent fiber tracts (axons in the brain) that connect one vertex to another.

* **`Gene Funcs`**

https://networkrepository.com/bio-WormNet-v3.php 

Gene Funcs is a biological network, representing gene functional associations with the gene as the nodes and the associations as the edges, with the intention of research into predicting RNAi phenotypes. 

* **`Yeast protein`**
  
https://networkrepository.com/bio-yeast.php
  
Network 7 is a biological network, representing the protein connection in yeast.

* **`Hamsterster`**

https://networkrepository.com/soc-hamsterster.php
  
Hamsterster is of the friendships and family links between users of the website http://www.hamsterster.com. 
* **`BA-2`**

  https://networkrepository.com/BA-2-24-60-L2.php 
  
**`Eopinions`**

https://networkrepository.com/soc-epinions.php
  
Eopinions 10 is a social network, capturing trust between users.
