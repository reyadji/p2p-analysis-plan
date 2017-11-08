# data-512-a3
Final Project Plan

##INTRODUCTION
Peer-to-peer (P2P) is “the practice of lending money to individuals or business through online services that match lenders with borrowers” (Wikipedia). Also known as crowdlending, the lenders are also usually individuals and the loans are unsecured. Lending intermediaries are needed to facilitate P2P lending by assessing risk, packaging similar loans, and manage the marketplace.
One of the earliest and biggest P2P lending company in the US is Lending Club (registered in NYSE as LendingClub Corp). It raised $1 billion in what became the largest technology IPO in 2014. However, Lending Club stumbled economically in 2016 due to various issues, from scandal over its CEO’s stakes in one of the Lending Club investment vehicle to its opaque loan assessment. This less-than-ideal situation led to Lending Club’s stocks cratered from the high of $28 in late 2014 to less than $6 at the time of writing. 
Despite Lending Club’s misstep, the original vision of peer-to-peer-lending, to turn “banking system into frictionless, transparent and highly efficient online marketplace, helping people achieve their financial goals every day”, still has some merit, particularly in efficiently helping customers with appropriate loans. 

##GOAL
I will explore and dissect Lending Club’s customer sample dataset and rejection sample dataset in Q2 2017 to shed a light on peer-to-peer loan assessment efficacy, investor profit, and hidden bias/discrimination. These findings in turn can be made to improve peer-to-peer lending practice, specifically Lending Club, to fulfil the vision mentioned above.

As a personal goal (aside from finishing the Human-Centered Data Science final project) is to self-publish this paper in Medium, LinkedIn blogs, and other online publications.    


##DATASET
The datasets are available on https://www.lendingclub.com/info/download-data.action, which does not require an active Lending Club account. Each dataset is available in certain time period, e.g. 2007-2011, 2012, etc. I plan to use the latest data available, which is second quarter of 2017.

The datasets are:
1.	Loan data (LoanStats_2017Q2.csv): Complete loan data for all approved loans in Q2 2017. It contains 105,451 datapoints, and each datapoint has 142, including current loan status, installment, grade, employment, etc.
2.	Rejected Loan Application (RejectStats_2017Q2.csv): Loan applications data in Q2 2017 that do not meet Lending Club’s requirement. It contains 1,665,309 datapoints, and each datapoint has 9 features 

and one dictionary file:
1.	LCDataDictionary.xlsx, which is a dictionary for all the attributes in the Loan dataset and Rejected dataset.



##RESEARCH QUESTIONS
The datasets provide us with sufficient data to start exploratory analysis around research questions related to socioeconomy, privacy, bias/discrimination, and other human and non-human elements of P2P lending.
Some exploratory analysis

Some possible research questions:
1.	RQ1: 
2.	RQ2: 
3.	RQ3: 

##DELIVERABLES
I anticipate the deliverables for this project will include at least:
•	A Jupyter notebook that contains the entire Python code and its embedded code information as well as artefacts generated by the code, e.g. graphs.
•	A documentation README.md file that contains information pertaining analysis reproducibility, attributions, and data descriptions.
•	A LICENSE file that contains MIT LICENSE for my code.
•	A comprehensive paper either in long-form article or in web publication format that contains an introduction, purpose, research questions, results, discussion, and references sections. Basically, a refined how, why, what, who of the entire project written for public consumption.


##SOFTWARE PRE-REQUISITE
The project requires Python 3 with Pandas and Matplotlib packages as well as Jupyter notebook for publication.
All the code will be publicly available on GitHub.



##OPEN QUESTIONS
There are a couple open questions which should be answered before the project is completed.
1.	What is the license/copyright terms of these data?
Unfortunately, the datasets do not come with clear licensing or copyright terms attached. Instead, the usage terms are probably included in one of these documents: 
•	https://www.lendingclub.com/info/investor-api-agreement.action
•	https://www.lendingclub.com/legal/terms-of-use
The answer to this question is very crucial to the project. The project cannot move forward if the datasets are under more restrictive license.

2.	How does Lending Club sample their customers for this dataset? Is it completely randomized or representatively sampled?
I expect my audience to exhibit some well-deserved skepticism toward financial institutions, and there is a chance that Lending Club cherry-picks datapoints of their customers to skew public image. Having answers for how the datasets are collected will greatly improve the results’ validity.  


## HUMAN-CENTERED ASPECT OF THE PROJECT
In the surface, analyzing Lending Club datasets seems to be purely motivated by economic reason, but underneath it is inherently human-centered. According to the Lending Club mission statement above, Peer-to-peer lending is people investing in other people goals. Each datapoint represent not only an individual, but also a group of individuals with similar traits. While financial institutions lenders tend to reduce their customers into mere numbers to maximize their profits, P2P lending should tell the human story behind the numbers. The project’s findings and hypotheses can lead into better peer-to-peer lending practice for more people.

In addition to that, I need to examine whether Lending Club follows ethical guidelines regarding their customers data, such as maintaining anonymity in the dataset, soliciting informed consent before collecting the data. 

For reproduction and replication purpose, the datasets have to be publicly available and licensed for wide use.


##REFERENCES
•	https://www.lendingclub.com/company/about-us
•	https://en.wikipedia.org/wiki/Lending_Club
•	https://www.nytimes.com/2016/05/15/business/lending-club-a-story-stock-that-skimped-on-the-details.html 


