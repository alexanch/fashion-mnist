# fashion-mnist
Multi-class image classifier on the fashion MNIST dataset utilizing fastai library.


#### fastai can be used to solve different types of problems: collab. filtering, vision, text, tabular. More info: [[docs.fast.ai]]( https://docs.fast.ai/applications.html#data)

#### In each case (except for collab filtering), the module is organized this way:
- **transform:**
  This sub-module deals with the pre-processing (data augmentation for images, cleaning for tabular data, tokenizing and numericalizing for text).

-  **data:**
   This sub-module defines the dataset class(es) to deal with this kind of data.

-  **models:**
   This sub-module defines the specific models used for this kind of data.

-  **learner:**
   When it exists, this sub-module contains functions that will directly bind this data with a suitable model and add the necessary callbacks.
   
**Feel free to experiment here:** [kaggle.com](https://www.kaggle.com/alexanch/image-classification-w-fastai-fashion-mnist)   
   
   
Source: [[docs.fast.ai]](https://docs.fast.ai/applications.html#data) <br />
Original dataset: [[Fashion MNIST]](https://github.com/zalandoresearch/fashion-mnist)
