# kaggle-Toxic-Comment-Classification-Challenge

Discussing things you care about can be difficult. The threat of abuse and harassment online means that many people stop expressing themselves and give up on seeking different opinions. Platforms struggle to effectively facilitate conversations, leading many communities to limit or completely shut down user comments.

The Conversation AI team, a research initiative founded by Jigsaw and Google (both a part of Alphabet) are working on tools to help improve online conversation. One area of focus is the study of negative online behaviors, like toxic comments (i.e. comments that are rude, disrespectful or otherwise likely to make someone leave a discussion). So far they’ve built a range of publicly available models served through the Perspective API, including toxicity. But the current models still make errors, and they don’t allow users to select which types of toxicity they’re interested in finding (e.g. some platforms may be fine with profanity, but not with other types of toxic content).

In this competition, you’re challenged to build a multi-headed model that’s capable of detecting different types of of toxicity like threats, obscenity, insults, and identity-based hate better than Perspective’s current models. You’ll be using a dataset of comments from Wikipedia’s talk page edits. Improvements to the current model will hopefully help online discussion become more productive and respectful.

Disclaimer: the dataset for this competition contains text that may be considered profane, vulgar, or offensive.

From https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge

How to use
=================================================================
1. Install python packages.
  ```  
  pip install -r requirements.txt
  ```
  
2. Download data
  ```
  kaggle competitions download -c jigsaw-toxic-comment-classification-challenge -p ./data
  ```
3. Download GloVe
  - you can download blow link, and then you have to move glove.6B.50d.txt to data dictory
  - https://nlp.stanford.edu/projects/glove/
  
4. Execute jupyter
  ```
  jupyter notebook
  ```

5. Run code 
  - you can open Toxic_classification.ipynb and Run

Accuracy
=================================================================
![accuracy.png](./image/accuracy.png)


Reference
=================================================================
- https://www.ijcai.org/Proceedings/16/Papers/408.pdf
