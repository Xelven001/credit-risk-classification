

## Overview of the Analysis


## Purpose: 
    The purpose of this analysis is to determine weather an individual would be a credit risk or not in terms of approval for a loan. 

## Features (Data to train model): 

    *Loan Size 
    *Interest Rate
    *Borrower Income
    *Debt to Income
    *Number of Accounts 
    *Derogatory Marks 
    *Total Debt

## Goal/Target Value: 
    This model aims to determine Loan Status as a 0 or 1 translatting to Approval or Denied respectively. 

## Logistic Regression Model Results:

        Accuracy: 99% - Outstanding accuracy gives confidence in model overall 

        Negative Category Results: 
            Precision = 1.00 (Perfect precision means no false positives were detected. Supports a strong model as the higher the value, the better. )
            Recall = 0.95 (Very high number suggests a good model as the higher the value, the lower the false negative values will be)

        Positive Category Results: 
            Precision = 0.85 (The  Precision here suggests a decent model as this can tranlate to a 15% False Positive rate.)
            Recall = 0.91 (Recall is high resulting in a 8% False Negative rate( out of ). )

     


## Summary

    With an accuracy of 99%, this model has a strong foundation for great performance. Paring this accuracy with Precision results, specifically our Negative Category results,
    the model true potential. The biggest concern in this model lies with the Precision score for our Postive Category results. However, due to the extremely high accuracy, I would reccommend the use of this model. 
