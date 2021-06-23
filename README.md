# Credit Risk
<img alt="insecure" src="https://github.com/V-Abhishek/credit-risk/blob/main/images/Loan.png" />

### PROJECT DESCRIPTION
Credit Card and home ownership loans are some examples of credit provided by the banks or other financial institutions to individuals. The likelihood that a borrower would not repay their loan to the lender is known as **Credit Risk**.<br /> The event of borrower not being able to pay their debt is called **Default**. In case of default the lender will suffer a substantial loss. To protect themselves against borrower debts, lenders access credit risk associated with each borrower.
<br />In this project, we have calculated the estimated **Expected Loss/Expected Credit Loss** that Lending Club institution would incur based on the consumer loans lent out by them. <br /> The following formula is applied to calculate the Expected Loss.<br />
<p align="center">
<strong>EL = PD x LGD x EAD</strong><br />
<strong>EL - Expected Loss</strong><br />
<strong>PD - Probability of Default</strong><br />
<strong>LGD - Loss Given Default</strong><br />
<strong>EAD - Exposure at Default</strong>
</p> 

##### TERMINOLOGIES

**Expected Loss - The amount a lender loses incase a borrower defaults.**<br />

**Probability of Default - The borrower inability to repay their debt in full amount on time.**<br />

**Loss Given Default - The proportion of the total exposure that cannot be recovered by the lender once a default has occurred.**<br />

**Exposure at Default - The total value that a lender is exposed to when a borrower defaults.**<br />

<p> We have built PD, LGD and EAD models and combined them to calculate the Expected Loss of the entire portfolio (Lenders Club).</p>
---

### Project Structure

1. Data folder contains the dataset used for the project
	1. loan_data_2007_2014.csv - Consumer Loans lent by Lenders Club from 2007 to 2014
	2. original.xlsx - Defines each column in the dataset (loan_data_2007_2014.csv)
2. Programs folder contains Jupyter Notebooks explaining each process of building the models in detail
	1. Data Preparation.ipynb - Details the process of data cleansing and extracting the data for building models	
	2. Probability of Default Model.ipynb - Details the process of building Probability of Default(PD) model and validating its accuracy using **Gini and Kolmogorov coefficents**
	3. Expected Loss.ipynb - Details the process of building Loss Given Default(LGD) and Exposure at Default(EAD) models. Finally, illustrates process of combining all three models to calculate Expected Loss
3. Models folder contains PD, LGD Stage-I and LGD Stage-II models exported and saved with .sav extension
4. Preprocessed Data folder contains data exported into .csv files after data cleansing 	

---

### LANGUAGE AND TOOLS

- Python
- Jupyter Notebook

### INSTALL AND RUN

- Install Jupyter Notebook
- Import the notebook(.ipynb) files into Jupyter# credit-risk