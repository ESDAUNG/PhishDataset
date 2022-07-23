# PhishDataset
Segmentation-based Phishing URL Detection
This is the dataset distributed in my paper "Segmentation-based Phishing URL Detection".
The paper is published in WI-IAT '21: IEEE/WIC/ACM International Conference on Web Intelligence and Intelligent Agent Technology. Paper is available @.https://doi.org/10.1145/3486622.3493983

Phishing Dataset : We collected phishing URLs from PhishTank , the most popular site distributing phishing websites, from May 2021 to June 2021. 

Legitimate Dataset : Legitimate URLs were prepared by the following steps: 
1) legitimate domains were chosen randomly from a set of domains included in the IP2Location  dataset consistently from January 2021 to March 2021, 
2) Each chosen domain was accessed by Apache Nutch crawler to gather the web pages located in the same domain at most 100 pages, and
3) A legitimate URL was randomly chosen from the gathered URLs in each domain.
Note that URLs in IP2Location consist of both legitimate and phishing URLs; however, we assume that most URLs are legitimate. 

A balanced dataset with 10,000 legitimate and 10,000 phishing URLs and an imbalanced dataset with 50,000 legitimate and 5,000 phishing URLs were prepared.

Label 0 represents Legitimate URL

Label 1 represents Phishing URL
