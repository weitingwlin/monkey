# Monkey classification: 

## Using trainsfer learning from  the _inception3_ model  

I use the [**10 Monkey Secied** dataset from kaggle](https://www.kaggle.com/slothkong/10-monkey-species)

This notebook **monkey_aws.ipynb** includes code for data preparation and training (fine-tuning) the _inception3_ model (using an AWS EC2-xlarge instance). 
The code for data augmentation is stored in another notebook (**data_sugmentation.ipynb**).

With augmentation, the model can correctly classify between the ten monkey species with accuracy of ~96%.

Demonstration of the how the result can be found in notebook **monkey_app.ipynb**.

## Examples:

(see notebook **monkey_app.ipynb** for the code to generate these examples.)

### 1. Example from the validation set

Input image:
![image](data/examples/n416.jpg)
Predicted species:
![image](data/atlas/n4058.jpg)

### 2. Upload your own image (in _.jpg_, _.jpeg_ or _.png_)

Input image:
![image](data/examples/baby3.jpg)
Predicted species:
![image](data/atlas/n2157.jpg)

