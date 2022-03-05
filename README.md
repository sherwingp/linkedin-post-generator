# LinkedIn Viral Post Generator

This was an exercise to create a LinkedIn post generator by training a model on the posts of top LinkedIn influencers.

[![postgenerator-example.jpg](https://i.postimg.cc/J4HLLLyf/postgenerator-example.jpg)](https://postimg.cc/QHDPQvJm)

## What I learned
- Sourcing and preparing data
    - How to tokenize and sequence text
    - How to use Tableau to visualize and filter data 
- Training and evaluating the model
    - How to train a model to recognize the semantics of text over long stretches using recurrent neural networks and LSTMs (Long Short-Term Memory)

## What I would do differently
- The dataset used was not preprocessed enough, due to the variation in post content I should have taken time to label different types of posts (e.g. stories, articles, announcements). This variation led to disjointed outputs, for example, half inspiring story and half rant. 


## Resources used
- This exercise was based on Tensorflow's [Zero to Hero for Natural Language Processing](https://www.youtube.com/watch?v=fNxaJsNG3-s&list=PLQY2H8rRoyvzDbLUZkbudP-MFQZwNmU4S&index=1) series
- Kaggle Dataset: [LinkedIn Influencers' Data](https://www.kaggle.com/shreyasajal/linkedin-influencers-data)
