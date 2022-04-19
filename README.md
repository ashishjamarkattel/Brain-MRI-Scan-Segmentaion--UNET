
# MRI SCAN SEGMENTATION

## ABOUT

Dataset contains the image of brain along with mask of particular image where we have to build a system that
could segment the image where the tumor is located.

#### SOURCE - Kaggle Mri Scan 

## APPROCH

#### PROBLEM STATEMENT

Since, brain tumor is the one of the diseases that could be fatal when found in the last stage.
but when it could be detected in the starting stage it could save life.
So, by any means is their any way we could save person using Machine Learning.
Also it could help the health professional by saving their time when checked  manually due to this reason 
it would be helpful if any automation can be made with more precison that could detect the brain tumor when 
provided the MRI SCAN . Our model should be able to distinguish the MRI image whether it contains
tumor or not.

## PERFORMANCE METRIX

If the proble was of classification, F1 score would be the best fit for the model. But in case of segmentation, here we 
would use DICE LOSS as the evaluation metrix that determines how close the model is with actual mask. 

MODEL
Since this is the task of segmentaion we can use UNET.
but here for learning i will be using 2 model 

    1. UNET
    


## CONSTRAIN

    1. Low Latency Delay - Can take time but not days.
    2. Loss Must be Minimum.

## Status

The model is completed using UNET where used a model from SEGMENTATION-MODEL Library.
and caNET is yet to implement.
where,

    Dice loss -  0.1820
    IOU SCORE - 0.7678


