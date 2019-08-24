# APPENDIX
This GitHub repository serves as the online appendix for the paper: AUTOMATIZÁLT KERESKEDÉSI STRATÉGIA A VÁLLALATI FELVÁSÁRLÁSOK PIACÁN SUPPORT VECTOR MACHINE SEGÍTSÉGÉVEL, written by 
Marcell Kujbus on the 31st of July, 2019. The english name of the paper is: Automatized trading strategy on the merger and acquisition market via Support Vector Machine. <br>
The repository contains the document, and the referred plots. 
***
**Abstract**
There are existing anomalies in financial markets, which do not seem to disappear not even after their observation. One stylized fact in the Merger and Acquisition market is the following: 
if a company gets acquired, then its shares price increase sharply weeks before the point when the deal is announced up until some months after the acquisition. Hence, an efficient 
statistical model could generate significant excess return, that is not captured by the capital asset pricing model. Based on previous works, I gather financial variables to proxy 
the incentives, that lead to an acquisition. The Bloomberg provides data for my study. However, the data has to be cleared, so I apply the most modern tool for 
dealing with missing values, and to filter the outliers. 1-Norm soft margin Support Vector Machine is used afterwards to model this phenomenon. 
I find the optimal hyperparameters, that maximize the in-sample area under the Receiver Operating Charachteristic curve via cross-validation on a grid search. 
Out-sample results prove that the acquired companies are distinguished from the ones that are not along the reported variables. 
Kelly's formula gives us a dynamic money management tool to build a trading strategy using the outcome of the SVM. The strategy yields a significant alpha value. 
***
If you have any comments, do not hesitate to contact me via email: marcellkujbus@gmail.com
**author: Marcell Kujbus**