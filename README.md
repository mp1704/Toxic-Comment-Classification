# Toxic-Comment-Classification
**NOTE:** Since I run this code on my local PC, i need to reduce `batch_size` and `max_sequence_length`
## downloading dataset
```
mkdir dataset
kaggle competitions download -c jigsaw-toxic-comment-classification-challenge
unzip -q jigsaw-toxic-comment-classification-challenge.zip
unzip -q train.csv.zip
```
## folder structure


## todo
- add scheduler to optimizer
- train with bigger batch_size, full dataset
- inference