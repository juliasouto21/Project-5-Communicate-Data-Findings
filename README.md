# Project-5-Communicate-Data-Findings

## Database
The analysis is based on a dataset with almost 113.937 loans, with 81 features each. The dataset consists of a big number of attributes that can determine loans’ deals and its relationship with borrowers’ APR, such as borrower's Prosper rating, loan terms, loan original amount, borrower's monthly income, borrower's employment status, debt to income ratio, current loan status, etc.
  - [Dataset can be found here](https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1608459230129000&usg=AOvVaw0bZ0zkXjGKNiemURQMBD7d) 
  - [Features dictionary can be found here](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0)

## Key Insights for Presentation
To enhance the key findings, I decided to consider only the features that could affect the most the borrower APR variable in the Presentation being those Loan Original Amount and Prosper Rating. 

I focused mainly on explaining the relationship between APR and Loan Amount and APR and borrowers’ ratings. Having said that, it was also important to understand the effect of rating on the relationship between APR and loan amount as well as on the relationship of Monthly Income and APR.
Further, I plot a graphic to better visualize an analysis of how borrower’s APR play across Rating and Term.

### Key Findings (highlights summarized below):

  - Borrower APR is negatively correlated with Loan Amount - At different size of the loan amount, the APR has a large range, but the range of APR decrease with the increase of loan amount.
  - Borrower APR decreases when Proper’s ratings become better
  - The strongest effect between numerical and categorical variables is between Loan Amount and Monthly Income. The correlation coefficient is 0.41, therefore, there is a positive relation between the borrowers' monthly income and the amount is lent to them, as expected.
  - Concerning Proper’s ratings vs. Loan’s amounts & Prosper APR: the relationship between borrower APR and loan amount turns from negative to slightly positive when the Prosper ratings are equal to AA or A. This might be because people with A or AA ratings tend to borrow higher amounts, increasing APR could prevent them to borrow even more. While decreasing APR could encourage lower rating borrowers to borrow more. 
  - The borrower APR decreases with the increase of borrow term for people with HR-C ratings. However, for borrowers with B-AA ratings, the APR increases with the increase of borrow term.
  - As expected, borrowers with better ratings have larger monthly income and loans’ amount.
  - Although we see a negative relationship between APR and Monthly Income, it doesn't seem true for Ratings equal to A, HR and D. It couldn't find a clear explanation for that.
  - The 36 months loans is the most common type of loan among all employment status categories
  - There is a positive relationship between loan amount and loan term
  - Employed and full-time workers borrowers seem to receive more loans
  - On better Prosper ratings, the loan amount on all three terms increases, the size of the increase / loan amplitude between terms also becomes larger.
  
  ## Feedback:
  I got some feedback from my co-worker that is as a Data Analyst like me to check if she understood my main points on this presentation. I also leverage on past projects in the internet in order to help me to decide what I shoul include in the slide deck presentation, then, I decided to include just the variables that impact the most the Borrower's APR and the variables that had a surprinsing outcome in their relationshop with Loan Amount or Borrower's APR.
  
  ## List of Resources:
  https://www.quora.com/How-do-I-create-a-hyperlink-in-the-README-file-in-my-GitHub-account-which-would-redirect-to-a-new-page-containing-the-project-explanation
  Github website
  https://matplotlib.org/api/_as_gen/matplotlib.pyplot.hist.html
  https://medium.com/python-pandemonium/data-visualization-in-python-histogram-in-matplotlib-dce38f49f89c
  https://www.listendata.com/2019/07/how-to-filter-pandas-dataframe.html
  Udacity's mentor help
  Udacity's chat room
  
