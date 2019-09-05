# CLERAF
## Cross-Lingual Evidence Ranking for Automated Fact-checking

Dataset introduced with the paper Deep Multi-Task Learning for Multi-Lingual Claim Detection and Verification.

Cross-Lingual dataset that can be used to analyze the stance between article and claims, useful for automated fact checking.

The dataset consists of 15512 text-pairs, for a total of 6 columns: Claim, Article, Label, Language, URL, Publisher.
To ensure consistency with data that is already available for this task each pair is labeled with one of the following six: Lie, False, Mostly False, Barely True, Half True, True.

The label distribution is the following:
- Lie 1369
- False 8130
- Mostly False 1609
- Barely True 1119
- Half True 1232
- True 2053

A Python Notebook with the steps to reproduce the dataset starting from json files obtained by Google FactCheckTool is provided.

![Infographics](https://lucafavano.com/images/portfolio/cleraf.png)

TODO: Publish paper and dataset soon :)
