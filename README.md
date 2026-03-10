# PyTorch Training Pipeline using Dataset and DataLoader

This is a small practice notebook where I tried to understand how a 
basic PyTorch training pipeline works using Dataset and DataLoader.

In this notebook I used the Breast Cancer dataset. First I loaded the 
dataset using pandas and did some basic preprocessing like dropping 
unnecessary columns, encoding labels and scaling the features.

After that I split the dataset into train and test data.

Then I created a custom PyTorch Dataset class and used DataLoader to 
load the data in batches. This helps when training deep learning models.

Finally I used the DataLoader inside a simple training loop to see how 
data moves through the training pipeline.

## What I practiced in this notebook

- Loading dataset using pandas  
- Data preprocessing  
- Train test split  
- Feature scaling  
- Creating a custom PyTorch Dataset  
- Using DataLoader for batching  
- Understanding a basic training pipeline in PyTorch  
