# "Capturing GreenTech related commercial activities of listed companies"
Authors: Kevin Riehl, Aavula Sai Kiran, Miryala Narender
Published in Journal: "Global Business Review" (2022)

## Abstract
The purpose of this work is to investigate whether news flows can be used to effectively capture financial success of green commercial activities conducted by listed companies.  The authors employ a large, cross-sectoral, global dataset, consisting of 97,954 articles from ten online magazines, mentioning over 344 different firms that are part of more than 286 listed companies, covering the years 2004 to 2017 and over 32 countries. The notifications focus on GreenTech related activities performed by companies. The authors conduct event studies to calculate abnormal returns and text analytics to gather (hyper-) textual features. Finally, the authors analyse the relationship between returns and features using OLS regression models. Results indicate that textual features extracted from web notifications significantly provide new market information. Thus, news flow is found to serve as a reliable measure to reflect the financial success of green activities for future research on listed companies. Features such as multimedia elements turn out to not provide new market information, while readability and sentiment measures do. 
The authors extend the growing literature on GreenTech by proposing the novel combination of textual and event study analysis in order to enable research on green commercial activities conducted by listed companies. 

## Data, Software and Analysis Workflow
In the folder "data" of this repository you can find:
- **main_regression_tbl.csv** - The table used for regression analysis
- **TextualAnalysis.zip** - A folder with necessary dictionaries, and a folder with results of textual analysis of hypertexts and titles, readability and word counts
- **Software.zip** - A folder with useful software such as sentiment analysis, Harvard general Inquirer, and necessary dictionaries for textual analysis
- **DataModelA.zip** - First part of data, including tables with all articles, firms, stock companies, countries, industries, regions, and relationship data. Moreover, this includes financial ratios of the investigated stock companies such as beta, market capitalization, price-book-ratio, and many more
- **DataModelB.zip** - Second part of data, including stock price data and index price data for event study analysis

<img src="https://github.com/DerKevinRiehl/greentech_globalbusinessreview/blob/main/github_imgs/titleimage.PNG" width="500">

## Citations
Please cite our paper if you find our work, data, analysis and code useful:

Riehl, Kevin and Kiran, Aavula Sai and Narender, Miryala. Capturing GreenTech related commercial activities of listed companies. (submitted to Global Business Review)

```
@article{riehl2022capturinggreentechrelated,
  title={Capturing GreenTech related commercial activities of listed companies},
  author={Riehl, Kevin and Kiran, Aavula Sai and Narender, Miryala},
  journal={Global Business Review},
  year={2022}
}
```
