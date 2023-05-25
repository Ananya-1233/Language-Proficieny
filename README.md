# Language-Proficieny
A natural language model that assesses the proficieny of English essays and rates them on six different aspects.

Using MultiOutputRegressor of sklearn library to fit a natural language processing model capable of predicting the following details about an input essay:

cohesion , syntax , vocabulary , phraseology , grammar , conventions.

# Dataset

1. The dataset is collected from an open-source data science website www.kaggle.com
2. The dataset consists of seven columns.
3. The first one is text and the rest are the output ratings for said text.
4. The task is to predict these six evaluations by analyzing the text section using NLP.

# Method

In an NLP project, the first and foremost task is to remove stopwords and simplify the text.
Next follows the generation of a tokenizer which assigns a token value to each word in the text corpus.
These tokens serve as the input for the NLP model.
Then, split the dataset into training and testing partitions and develop a MultiOutputRegressor model that provides multiple output for a single input.
