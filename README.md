# Data Science Intern Take Home

The following is a take-home coding and modeling exercise.  NOTE: ANY CODE TAKEN 
FROM A NON-API SOURCE MUST BE CITED! Any submission that does not cite a source, 
whether it's Kaggle, Stack Overflow, or other data science sites, WILL BE IMMEDIATELY 
REJECTED with no exceptions. We recommend citing sources including scikit-learn.org, 
pandas.pydata.org, and other API sources just to avoid confusion. Also cite any git 
repos, including your own, that you have used. 

You will have 3 hours to complete the exercise.

### Problem Statement

An executive has asked you to explore some new data we have received on a subset
of our customers and report back with some findings about the information
contained in the data. Your objective is to leverage the dataset to learn more
about our customers. To do this please explore the data and build a model to
predict the account status of each customer. You are free to use any technique
or method you would like to explore the data and generate insights. 

We ask that you generate a report to summarize your findings. The report should
present evidence for your findings and take-aways that you generate. The report
can be a code notebook like R Markdown or a Jupyter Notebook, a Word document,
or a Powerpoint Presentation (Google Doc equivalents are fine). In addition we
ask that you share all code and analysis that you used to explore the data and
generate the report. We should be able to recreate any findings you present from
the code that you share with us. If you do use a notebook to build your report
please send an additional html copy of the notebook. 

### Data

 You will find 2 files attached in this take home: 
- `account_info.csv`: This dataset is at an account-transaction type level, so
each account will have multiple rows. The data contains the total balance,
number of debit, and number of credit transactions in 9 different checking
categoires. In addition there is an "Overall" category that contains the
account's total balance, number of debit, and number of credit transactions for
all categories, including the previous 9 categories. "Debit" transactions are
withdrawals from the account and "credit" transactions are deposits. Some
accounts had no transactions in a given category so those have 0 balance,
debits, and credits for those categories. 
- `account_labels.csv`: contains the account_id and label which specifies if 
the account is in default; 1 being default, 0 being not default. 

### Deliverables

- Explanation of the code, experiments, and thought process behind approaches you decided 
to take
- Code/scripts/notebooks that you used to run the experiments
- The presentation document you would present to summarize your work

Some guidance on what a great submission looks like:
- All deliverables as specified in this README;
- Clean, well-structured, and commented code;
- Data processing as necessary;
- Clear explanations of your thought process behind the approaches you decided to take.


Upon completion, please e-mail your response to datascienceus@kabbage.com
