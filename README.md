# Amazon Price Prediction with Images

Original Dataset : https://www.kaggle.com/datasets/lokeshparab/amazon-products-dataset

## Project workflow
1. Read in csv file
2. Filter unavailable url
3. Create dataloader
4. Augment Images
5. Define Model
6. Train Model
7. Evaluate Model
8. Saliency Map
9. Class Activation Map

Each ipynb file (AC, SC, WM, Combine) runs a model with the same architecture on different datasets and gives output on the jupyter notebook on data retrieval, original images, augmented images, model training, results, saliency maps, and class activation maps. The relative paths are set so the notebook read data from the data folder, outputs images to the image folder and outputs model parameters, model results, image information to the output folder where each category is given a folder with its category name.

## data folder
Store original dataset downloaded form kaggle where csv files have url link for image with prices / categories etc.

## images folder
Output images such as price histograms, loss per epoch etc.

## output folder
Output trained model parameters / downloaded information on images and stored by each category.

