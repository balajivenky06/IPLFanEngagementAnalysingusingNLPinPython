# IPL Fan Engagement Analysis using NLP in Python

This project aims to understand IPL Cricet fan engagement

Here Fans Twitter message is scrapped using Twitter API on daily basis based on different Hashtag mentions
Similarly Fans Posts/Comments in IPL teams official facebook pages were also scrapped using REST API.
Informations like user who posted, Data, Geographic Location, Tweets/Posts etc.. were scrapped and saved in JSOL format.

All the output files are combined and used NLP for Fan base segmentation.

NLP Methods

1) Bag of Words
2) Stop word Removal
3) TF-IDF normalization
4) Model Building using K-Means Clustering
5) Final output prediction
