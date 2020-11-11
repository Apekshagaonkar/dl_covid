# dl_covid
DL for COVID detection.

# Covid_CXNET

- Paper : https://arxiv.org/abs/2006.13807
- Github : https://github.com/armiro/COVID-CXNet
- Dataset : covid-cxr-dataset

# Workflow :
### 0.Dataset_preperation.ipynb: (Changes needs to be done)
  - Output files :
    - 1. **cxr_samples.npy** : Images of covid and non covid.
    - 2. **cxr_label.npy**   : Respective Labels of covid and noncovid images.
    
### 1.Image_segmenatation.ipynb:
  - Input:
    - 1. **cxr_samples.npy** : Images of covid and non covid.
    - 2. **cxr_label.npy**   : Respective Labels of covid and noncovid images.
  - Output files :
    - 1. **cxr_segmented.npy** : Images of covid and non covid segemented.
    - 2. **cxr_ylabel.npy**   : Respective Labels of covid and noncovid segemented images.
    
### 2.Training_model.ipynb: (In progress)
  - Input  :
    - 1. **cxr_segmented.npy** : Images of covid and non covid segemented.
    - 2. **cxr_ylabel.npy**   : Respective Labels of covid and noncovid segemented images.
  - Output :
      
### 3.Testing_model.ipynb : (yet to be started) 
  - Input : 
    - 1. Model
    - 2. Testing images
    
### Model_flow.ipynb: Reference notebook
      

