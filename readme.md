
## Prosper Loan Data Exploration
![Prosper logo](https://theme.zdassets.com/theme_assets/620392/15bce55ae4d83412bf085346000935c073426921.png)


### Dataset Overview
There are 113937 rows and 81 columns, most variables data types are in objects, int, float,and bool.
from 81 columns, i choosed only 26 columns only,removed duplicated entry from the datasets that makes sure data clean,so of tidy issues are not solved because of data size.

### Investigation Overview
While Investigation of dataset, more focused on CreditGrade , Term , LoanStatus, BorrowerAPR and etc, this investigation more helpful for first time applying loans on prosper and how is loan proposal is selected, so this things decipted in form of charts like hist, scatter, bar charts so on.

### Summary Of Findings
Exploring the PROSPER loan dataset was really interesting. I discovered many insights about the peer-to-peer lending which I wasn’t aware of. In fact this type of lending in Europe is not at all common. The main difficulties that I encountered during this project were related to the variable selection that I did. I wanted to explore the categorical variables of this dataset mainly because I haven’t been exposed to this type of data analysis in the past and learning to do so would be useful.he most common pattern throught out this dataset exploration is that PROSPER had a difficult time during the first years of it’s operation and a part of it can be attributed to the financial crisis that unfolded after 2008. Nevertheless, it seems that their credit rating system wasn’t at all optimal because more than 1/3 of their loans defaulted during 2005-2008. So it is not strange that the SEC imposed a cease and desist order on PROSPER from the end of November 2008 till July 2009. Moving after the SEC order PROSPER managed to fix its credit rating system and the default rates were normalised to fairly acceptable rates.

To this end adding a model that forecasts which loans will default on the PROSPER platform is certainly feasible. We could use the variables that were explored in this project and seemed to be related with the default ratio. This is something that I will definetely try to do in the future.

### Key Insights For Presentation
for the presentation, I focus on prospering loan status, means how many of them completed and still paying loans, for that loan status variable helped me a lot and used seaborn countplot function to answer this question, results are so colorful and I enjoyed,I wanted to explore the categorical variables of this dataset mainly because I haven’t been exposed to this type of data analysis in the past and learning to do so would be useful.he most common pattern throught out this dataset exploration is that PROSPER had a difficult time during the first years of it’s operation and a part of it can be attributed to the financial crisis that unfolded after 2008. Nevertheless, it seems that their credit rating system wasn’t at all optimal because more than 1/3 of their loans defaulted during 2005-2008. So it is not strange that the SEC imposed a cease and desist order on PROSPER from the end of November 2008 till July 2009. Moving after the SEC order PROSPER managed to fix its credit rating system and the default rates were normalised to fairly acceptable rates.


