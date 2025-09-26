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
