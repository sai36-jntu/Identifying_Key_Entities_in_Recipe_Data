# Identifying_Key_Entities_in_Recipe_Data
# Business Objective
The goal is to make online cooking and meal-planning apps easier to use by creating a special NER (Named Entity Recognition) model. This model will automatically find and label important parts of recipes, like ingredients, amounts, and recipe names. That means people won’t have to tag these things by hand anymore, which takes a lot of time and effort. With this automation, users will be able to search, sort, and filter recipes more easily based on what they have, how many people they’re cooking for, or their diet. This will help food and recipe platforms run more smoothly, grow easily, and offer a better experience to users.
# Methodology
The method used here is to train a model that can recognize important words in recipe text using a technique called Conditional Random Fields (CRF). This model can identify and label things like ingredients, amounts, and measurement units. With this, we can turn messy recipe text into organized data, which can then be used to build smart features in cooking apps, diet trackers, or online grocery platforms.
# Assumptions
The pos token given in the dataset are corresponding to the input recipe tokens and are valid.
# Steps Followed
The following steps are followed to train the NER model using the CRF to extract key entities from recipe data.
  1. Import Libraries
  2. Data Ingetion and preparation
  3. Split into train and validation data 70-30%
  4. EDA on training set
  5. EDA on Validation data
  6. Feature extraction
  7. Model building
  8. Prediction and model evaluation
  9. Error analysis on validation data
  10. Conclusion
