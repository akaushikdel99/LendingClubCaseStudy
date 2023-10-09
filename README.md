# Lending Club Case Study
> This assignment provides insight into solving real business problems using Exploratory Data Analysis (EDA). It includes a case study that not only applies EDA techniques but also introduces the basics of risk analytics in the banking and financial sector. The goal is to understand how data can be utilized to reduce the risk of monetary loss in lending operations.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- The case study is about a consumer finance company that wants to use data analytics to manage the risk of lending loans to urban customers. The company has a data set of past loan applicants and their default status, which can be used to explore the factors that influence the likelihood of default. The case study also explains the different scenarios and outcomes of loan acceptance and rejection, and how they affect the company’s profitability and reputation. The objective of the case study is to apply exploratory data analysis techniques to find patterns and insights that can help the company make better lending decisions.
- Following are the objectives of this case study
    - To use exploratory data analysis (EDA) to identify the risky loan applicants who are likely to default on their loans and cause credit loss to the company.
    - To understand the driving factors behind loan default, i.e. the variables that are strongly correlated with default.
    - To use this knowledge for the company’s portfolio and risk assessment and improve its lending decisions.
- The dataset used for this excercise is a loans dataset for period 2007 to 2011

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
 - There is a higher chance of default for loan amount(loan_amnt) greater than 15000
 - Higher the term the more chances of failure
 - Lower the grade the higher the default rate
 - Lower the income(annual_inc) the higher the default rate
 - More the int_rate the higher chances of default
 - NE state(addr_state) seems to be leading in defaults by 60% default rate. In terms of volume CA leads the pack
 - More than 6 enquires(inq_last_6mths) are likely to cause default
 - Bankruptcies (pub_rec_bankruptcies) has impact on default rate

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- pandas
- matplotlib
- seaborn

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Contact
Created by [@akaushikdel99] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->