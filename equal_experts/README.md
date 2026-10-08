 ## :warning: Please read these instructions carefully and entirely first
* Clone this repository to your local machine.
* Use your IDE of choice to complete the assignment.
* When you have completed the assignment, you need to  push your code to this repository and [mark the assignment as completed by clicking here](https://app.snapcode.review/submission_links/ea5b1939-eecf-4040-911e-97d9a2755577).
* Once you mark it as completed, your access to this repository will be revoked. Please make sure that you have completed the assignment and pushed all code from your local machine to this repository before you click the link.

## Problem Statement
Thank you for taking the time to participate in this challenge. You should expect to spend up to 3 hours preparing your chosen exercise. 

Please read all the instructions below carefully and don’t hesitate to contact us if you have any queries.

Things we value:
- **Code organisation** –  The code must speak for itself. 
- **Simplicity** – We value simplicity, solutions should reflect the difficulty of the assigned task, and should NOT be overly complex.
- **Reasoning** – You should be able to explain your methodology choices.
- **Repeatability** – We value reliable, scripted solutions which can be replicated.
- **Self-explanatory code** – For instance, variables and methods should have good clean names. The code should be simple and straightforward to understand. 
- **Data Visualisation** – We value clean, simple and easy to understand visualisations.
  
## Anonymous submission
We practice a blind review process for exercise submissions, so please don’t include your name (or the name of your company) anywhere in your submitted source code, documentation, or comments. This makes our interview process as fair and systematic as possible.

The person who reviews your submission won’t have access to your CV or know anything about you, including your name. Your identification in the email communications with our recruitment won’t be shared with the reviewer.

## Data Exploration
You are free to use any tool of your choice, although we recommend Python  

NOTE: If you don't use a notebook, please add contextual information within the script and provide extra documentation with visualisations if needed. 

## Instructions
Download this dataset:
https://www.kaggle.com/btolar1/weka-german-credit

The dataset contains 1000 entries with 20 categorial/symbolic attributes. In this dataset, each entry represents a person who takes a credit by a bank. Each person is classified as good or bad (CLASS attribute) credit risk according to the set of attributes.

Using whichever methods and libraries you prefer, create a notebook with the following:

- Data preparation and Data exploration
- Identify the three most significant data features which drive the credit risk
- Modeling the credit risk
- Model validation and evaluation using the methods that you find correct for the problem

## How to run the notebook
Tested with Python 3.14.

1. Create and activate a virtual environment, then install the dependencies:
   ```bash
   python -m venv .venv
   .venv\Scripts\activate        # Windows
   source .venv/bin/activate     # macOS / Linux
   pip install -r requirements.txt
   ```
2. Open the notebook:
   ```bash
   jupyter notebook solution.ipynb
   ```
3. Run all cells (Kernel → Restart & Run All).

The dataset is downloaded automatically from Kaggle with `kagglehub`, and no Kaggle login is needed. If the download fails, the notebook uses the copy in `data/credit-g.csv`, so it also runs offline.

All random steps use a fixed seed (`RANDOM_STATE = 42`), so the results can be reproduced.


    
