# swe-sentiment-dataset

A sentiment annotated dataset for sentiment analysis in Swedish. The dataset contains 2 368 texts in Swedish, all containing emojis. 

The data is organized in a `.csv` file as follows:
```
text  |  label  |  all_labels
```

- The sentiments are either positive, neutral or negative, denoted as `pos`, `neu` and `neg`.
- The texts have been labeled by human annotators, where the majority label has been chosen as `label`. 
- `all_labels` contains a list of all labels by the annotators.

## Data source & more information

The data contains Twitter posts and YouTube comments. The paper below describes the creation of the dataset in more detail.

### Citation information

If you use the dataset, please cite the following [paper](https://www.diva-portal.org/smash/record.jsf?pid=diva2%3A1762861&dswid=4666):

> Berggren, Lovisa. "Sentiment Analysis for Swedish: The Impact of Emojis on Sentiment Analysis of Swedish Informal Texts." (2023).

Feel free to use the dataset for further research or hobby projects.
