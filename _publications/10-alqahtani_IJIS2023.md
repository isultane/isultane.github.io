---
collection: publications
permalink: /publications/10-alqahtani_IJIS2023

title: "Security bug reports classification using fasttext"
authors: "Sultan S Alqahtani"
venue_key: "10-alqahtani_IJIS2023"
track: TBC

pages: "1-14"
date: 2023-12-21
doiurl: 

paperurl: https://link.springer.com/article/10.1007/s10207-023-00793-w
notes:
---

**Abstract:** Software developers and maintainers must address security bug reports (SBRs) before they are publicly disclosed, and their system is left vulnerable to attack. Bug tracking systems may contain securities-related reports which are unlabeled as SBRs, which makes it hard for developers to identify them. Therefore, finding unlabeled SBRs is an essential to help security expert developers identify these security issues fast and accurately. The goal of this paper is to aid software developers to better classify bug reports that identify security vulnerabilities as security bug reports through fasttext classifier. Previous work has applied text analytics and machine learning learners to classify which bug reports are security related. We improve on that work, as shown by our analysis of five open-source projects. We first collected a dataset of 45,940 bug reports from five software repositories (e.g., the work of Peters et al. and Shu et al.). Second, we conducted an experiment throughout the classification of SBRs using machine learning technique; particularly, we built fasttext classifiers. Finally, we investigated the accuracy of our built fasttext classifiers in identifying SBRs. Our experiment results show that our fasttext classifier can achieve an average F1 score of 0.81 when used to identify SBRs. Furthermore, we examined the generalizability of identifying SBRs by applying cross-project validation, and our results showed that the fasttext classifier is able to achieve an average F1 score values of 0.65. Finally, we made our data and results available at Alqahtani (fasttext implementation, 2023. https://github.com/isultane/fasttext_classifications) to help the replication of our work.