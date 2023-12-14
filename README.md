# Final_Project_IronHack
<!-- @format -->

![logo_ironhack_blue 7](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)

## Markets, trade, and finance

* A journey through the Caos

## Motivation

+ I always loved to unveil mysteries and well whats better to unveil that a mistery about money , AM I RIGHT people?
+ I like puzzles and think about the data and his relationship with the model or with the results.

## What the project even about
+ The project is a predictive model that has a binary target outcome,it either gives a 1 == the price closed higher than it opened or it either gets a 0 == the price closed lower than it opened on daily dataframe

I then compared the results of the model with some famous very simple strategies, like buy and hold, DCA and flipping a coin .

The strategy have a very high return 3500% on 4years which is a lot ,so more time is needed to go through it to see if it got over fitted or if the trades are legal, that meaning the model is not cheating.

## Some metrics 
### Original data + sentiment but cols filtered by importance
+ Precision: 0.69
+ Recall: 0.73
+ F1 Score: 0.71
+ AUC-ROC: 0.68
+ True Negatives (Actual Red Days Correctly Predicted): 74
+ False Positives (Green Days Incorrectly Predicted as Red): 49
+ True Positives (Actual Green Days Correctly Predicted): 111
+ False Negatives (Red Days Incorrectly Predicted as Green): 42
+ overall score 69.3

## My approach
+ I first got the data from binance api ,ohlc and then i downloaded sentiment data (link inside the code) , i also tried doing some techincal indicators , then i testes the gradient boosting classifier with all the diferent data to see how it behave after applying more data or less.

+ I got the importance of the features to filter them and have less noise, made exploratory data(like SHAP value explanation) to better understand the why of each result.

+ This was pretty much like a loop ,getting new features, eda, cleaning testing and putting away this result, at the end i compared all my results and chosed a data, then i tested that data with 10 different models and neuronal networks also.
Chosed one ,and then hyperparamether tuned it to get the best results using grid search.


## Credits

+ Credits are for the amazing teachers that i have and that have teached us how to do all this in only 8 weeks.
+ Also big applause to my cohort ,all them deserve that for theyre resilence!

#### Anything else that seems useful

+ There are 3 jupyter notebooks ,one of them being the main one and the other 2 to create features and test neuronal networks


### presentation link

[PowerPoint Presentation](https://www.canva.com/design/DAF24Q12U08/ZgGqhZbqBY3RSg_1Ei0Ewg/edit?utm_content=DAF24Q12U08&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

