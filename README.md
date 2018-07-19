# Udacity Machine Learning Engineer Nanodegree Capstone

Capstone project for udacity machine learning nanodegree

Invasive Species Monitoring:
Identify images of invasive hydrangea
(Kaggle Contest)

## requirements
<ul>
    <li>Numpy</li>
    <li>Pandas</li>
    <li>Tensorflow</li>
    <li>Keras</li>
    <li>Matplotlib</li>
    <li>tqdm</li>
    <li>pillow</li>
    <li>opencv-python</li>
</ul>


## Dataset

The data can be obtained from the given link below.
https://www.kaggle.com/c/invasive-species-monitoring/data

## Arranging the data
The data needs be extracted and placed in folders like this:
test.7z into input/test
train.7z into input/train
the csv files would go into input/

The top level directory would have notebooks, and the data in input/ directory.

so after doing this input folder would have
test/
train/
sample_submission.csv
train_labels.csv

After this run the notebook "Download_dataset_and_arrange". Execute the cells in first section and then execute all the cells from section "Preparing the training dataset" till end.

## Running the remaining files

Now run the notebooks in the following order:
1. Exploration
2. basic_cnn
3. improved_cnn