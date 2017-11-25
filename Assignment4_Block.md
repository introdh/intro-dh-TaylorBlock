This data set as a whole draws from an entire network of 20,288 U.S. Supreme Court cases, and the cases that they cited from 1754 to 2002. The purpose of this larger data set is to analyze the relationship between cases and the precedent cited within those trials. Precedent is important to look at as it indicates which cases were the most influential, as well as how other cases used the precedent for their own trial. (Fowler et al., pg. 1)
  
The study Network Analysis and the Law: Measuring the Legal Importance of Precedents at the U.S. Supreme Court stated, “Precedent plays a central role in the judiciary by providing information to judges and other decision makers about the relevance or weight of particular facts for a legal issue and by defining legal consequences or tests that pertain to those facts (Schauer 1987; Aldisert 1990, 606; Richards and Kritzer 2002).” (Fowler et al., pg. 2) This shows that the cases used as precedent most often carry the most weight for future trials. 

From this larger set, I chose to focus on sex discrimination within employment, and sex discrimination separate from employment. Within the network I created using these two topics, there are two important components: the nodes, and edges. In this case, the nodes represent the individual cases, and the edges represent which cases have been used as a precedent. Therefore, the relationship between the cases is directly shown by these edges. 

The first question that crossed my mind as I created this network was, “Which case is the most important?” To answer this question I used the centrality measurement. Degree centrality represents how many times a case has been cited; thus, a higher degree indicates more times the case has been cited. The article, The Authority of Supreme Court Precedent, states, “At the most basic level one might use the number of inward citations, or degree centrality, to measure the importance of a given decision (Proctor and Loomis, 1951; Freeman, 1979).” (Fowler et al., pg. 20) Therefore, the higher the centrality, the more important the case in terms of precedent. 

![Image of Centrality](https://github.com/introdh/intro-dh-TaylorBlock/blob/master/Centrality.png) 

Using the centrality network I created, there are two cases that received the highest Eigen value. These cases are, Craig vs. Boren and Frontiero vs. Richardson. The 1976 case, Craig vs. Boren, was the first case in which a majority of the Supreme Court determined that sex classifications by age were subject to judicial review under the Fourteenth Amendment’s Equal Protection Clause. Oklahoma had passed a law that stated males had to be 21 years of age to purchase low alcohol beer, but allowed females to purchase the same beer at 18 years of age. The court found this law to be unconstitutional, and Craig won the case. This case was important because, “The Court established a new standard for review in gender discrimination cases.” (Oyez) 

I found this to be very interesting for a number of reasons. First, I assumed that in one of the most central cases, the plaintiff would be female not male. When choosing this data, I held the assumption that it would be mostly females suing. Additionally, I wonder if the fact it was a male plaintiff effected the outcome of the cases that used Craig vs. Boren as precedent. 

In the second case, Frontiero vs. Richardson, Sharron Frontiero, lieutenant in the United States Air Force, argued that her husband should be allowed to be financially dependent on her, just as military wives could be dependent on their husbands. Frontiero’s request was denied by the courts. This case was also interesting, as it was not exactly what I expected. 

It is important to note that neither of these cases were considered sex discrimination within employment. This raises questions regarding the prevalence and importance of cases involving discrimination at the work place. Knowing our history, there were certainly many cases of discrimination at the work place, were people afraid to bring these cases to trial? Maybe there were a fair amount, but none of them were significant enough to gain any centrality. 

![Image of Year](https://github.com/introdh/intro-dh-TaylorBlock/blob/master/Year.png) 

The year network also led me to a number of questions. Being familiar with the history of the women’s suffrage movement, women did not receive any technical legal rights until 1920. After women received the vote in 1920, second and third wave feminism addressed sexism in the workplace, equal pay and reproductive rights. However, women were not very prevalent in the court system until around 1970 due to social stigma that portrayed women as submissive, and not as capable of going to trial. That being said, we see majority of the nodes occurring between 1970-1980. These cases addressed third wave feminism issues which were primarily centered-around reproductive rights. I found it interesting that there were only three cases marked in the late 1990s, as feminism was still in full swing. Knowing the kinds of issues we deal with in todays society, I think it would be useful to compare this data with data from the past 10 years. This would allow us to analyze how the cases have changed to address different kinds of issues over a larger time period. 

A limitation to our set of data is the lack of inward and outward citations. The article, Network Analysis and the Law: Measuring the Legal Importance of Precedents at the U.S. Supreme Court, stated, “The combination of nodes and links (both outward and inward) create a precedent network of any number of cases—for example, within an issue area or among all existing cases.” On the networks we created, we cannot see whether or not a node is citing another node, or if it is being cited. It would have been another point of analysis if we could have used inward and outward centrality. 

A general constraint of building networks is the overall lack of context. Without a thorough explanation, it is hard to tell exactly what these networks are representing. Scott Weingart said, “The structure and nature of a network might change depending on the perspective of a particular node, and I know of no model that captures this complexity.” (Weignart) Many of these issues that networks cover are very complex. Even within my network, I found it important to touch a bit on the history of women’s rights. However, one could argue my network cannot be complete without a full history.


## Works Cited
"Craig v. Boren." Oyez, 23 Nov. 2017, www.oyez.org/cases/1976/75-628.

Fowler, James H., and Sangick Jeon. “The Authority of Supreme Court Precedent.” Social Networks, vol. 30, no. 1, 2008, pp. 16–30.

Fowler, James H., et al. “Network Analysis and the Law: Measuring the Legal Importance of Precedents at the U.S. Supreme Court.” Political Analysis, vol. 15, no. 03, 2007, pp. 324–346.

"Frontiero v. Richardson." Oyez, 23 Nov. 2017, www.oyez.org/cases/1972/71-1694.

Weingart, Scott. “Demystifying Networks, Part I & II.” Journal of Digital Humanities. Vol 1 No. 1. Winter 2011.







