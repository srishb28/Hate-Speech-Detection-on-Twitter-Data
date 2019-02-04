# Hate-Speech-Detection-on-Twitter-Data
Several experiments were performed to detect hate speech by first categorizing which words fall under the category of hate/offensive words and then use deep learning  and other machine learning techniques to learn abstract feature representations from input data and see how well the model performs on Twitter dataset.
Publicly available English Twitter dataset of 11K annotated tweets was used (https://github.com/ZeerakW/hatespeech). This dataset consists of the following columns:-
•Tweet ID
•Class Labels (Racism/Sexism/None)
With the help of Twitter API,the individual tweets and the details of user based on the Tweet ID were obtained. Apart from detecting
hate speech comments based on just the tweets,we thought of extracting additional features concerning the users' tendency to utter hate
speech, as expressed by their previous history. We took inspiration from the work of Pitsilis (Pitsilis, Georgios K., Heri Ramampiaro,
and Helge Langseth. "Detecting Offensive Language in Tweets Using Deep Learning." arXiv preprint arXiv:1801.04433 (2018).), which takes into account user’s behaviour while detecting hate speech in a post.
