# BERT-fine-tuning-for-sentence-classification

This tutorial project describes the practical application of transfer learning in NLP to create high performance models with minimal effort on a range of NLP tasks. We use BERT with the huggingface PyTorch library to quickly and efficiently fine-tune a model to get near state of the art performance in sentence classification.

<hr>

Datasource: http://snap.stanford.edu/data/amazon/productGraph/categoryFiles/

I use the android app review dataset of size 91 MB (reviews_Apps_for_Android_5.json.gz). I am analysing the sentiments from the review text column. As a result, if the ratings are above 3 then the review text reflects positive review, while if they are 3 or below, the review text reflects negative review.

<hr>

Reference: https://colab.research.google.com/drive/1Y4o3jh3ZH70tl6mCd76vz_IxX23biCPP#scrollTo=BJR6t_gCQe_x
