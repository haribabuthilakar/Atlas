# ATLAS - Constrained Beam Search Based Sequence model for product category classification

This project aims to predict the taxonomy of an image through Attention Sequence model. 

## Architecture Blueprint
![alt text](https://github.com/vumaasha/Atlas/blob/master/img/blueprint.png "Architecture")

## How do I use this Project?
![alt text](https://github.com/vumaasha/Atlas/blob/master/img/Path.png "Path")

There are 2 ways you can use this Project:

1. Path 1
    1. [Use ATLAS Dataset](https://github.com/vumaasha/Atlas/blob/master/dataset/README.md)
    
    No. of images: 200,000
    
    No. of apparel categories: 50
    
    No. of e-commerce sources used to scrape images: 13
    
    Images include apparel for: Men & Women
    
    You can download and use our dataset either to train on this Attention model or for other Computer Vision Applications.
    
    2. [Run the pre-trained model](https://github.com/vumaasha/Atlas/blob/master/models/apparel_classification/README.md)

    Run the model to predict the taxonomy of the given apparel along with the output image of the Attention technique.

*** 

2. Path 2
    1. [Build your own Custom Dataset](https://github.com/vumaasha/Atlas/blob/master/dataset/README.md)
    
        * If you would like to predict the taxonomy of images outside of the 50 categories we have collected, you can use our existing crawlers to modify and include specific categories.
        
        * Alternatively, you can use your own image corpus from other sources and run the model.     
           
    2. Run model to generate new Taxonomy
    
       * [Clean the dataset](https://github.com/vumaasha/Atlas/blob/master/models/normal_vs_zoomed/README.md)
       
       The image dataset needs to be cleaned in order to remove any zoomed images. 
       
       * [Run Model](https://github.com/vumaasha/Atlas/blob/master/models/apparel_classification/README.md)
      
      
     
