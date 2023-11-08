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
- `download_tokenizer_model.ipynb`: use this one to save pretrained on my pc
- `prepare_data.ipynb`: use this one to preprocess data and export to a new data
- `utils.py`: helper function
- `train.py`: training
- `./bert/`: where I saved both tokenizer and model
- `dataset/`: data here
## todo
- add scheduler to optimizer
- train with bigger batch_size, full dataset
- inference