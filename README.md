# Aditya_Sharma_StaquSVHN
Google Street View House Number(SVHN) Dataset, and classifying them through CNN

Classifying 32 x 32 copped images given in format 2
using CNN architecture.

   `data_preprocess.ipynb to preprcess the data`
   
   `svhn_model.ipynb to run the model and report results`
    
**Added confusion metric, miscalssified images and some classfied images**

    
**Findings:**
```
From logs we can make out that dropout rate should be higher to learn
good features as images have lots of others digits image pixels also.

So it get confused more often`
```

**Note:** 
```
Above experiment is performed under 4GB RAM and 1GB GPU Memory
So it was difficult to train it for more steps, and adding more layers in architecture
```
