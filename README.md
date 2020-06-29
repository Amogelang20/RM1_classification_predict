# RM1_Classification_Predict - Climate Change Belief Analysis  

This notebook illustrates the process taken to find a model that can predict user sentiment with relative accuracy. Machine learning models are used to predict an individual's belief in climate change based on historical tweet data and the F1 score is the measure used to evaluate the accuracy of these models.  

## What you will need   

+ Latest version of python.
+ Access to jupyer/google colab.
+ Basic understanding of classification and machine learning models.   

## Prerequisites  

### Installing the required pip packages:  

- Comet_ml:  
```bash
 pip install comet_ml==3.1.9
 ```   
 
 - Wordcloud:
 ```bash
 pip install wordcloud==1.7.0
 ```   
 
 - Emoji:  
 ```bash
 pip install emoji==0.5.4
 ```   
 
 - Pyspellchecker:  
```bash
 pip install pyspellchecker==0.5.4
 ```   
 
 - Ftfy:
 ```bash
 pip install ftfy==5.7
 ```   
 
 ### Libraries utilised in building the model:  
 
import numpy, pandas, time, wordcloud, matplotlib.pyplot, seaborn, 
       PIL, re, nltk, sklearn, emoji, ftfy, spellchecker, itertools, pickle  
       
## Datasets used  

### train.csv - is the dataset that is used to train our model.  
 
 ***
**Variable definitions:**  

- **tweetid** - Unique Twitter ID .
- **message** - Tweet body.       
- **sentiment** - Sentiment of tweet.  


**Each tweet is then labeled as one of the following classes:**  
 
    
| **Class** | **Tag** | **Description** |
|:---------:|:----------------:|:----------------|
|   **2**   | **News** |The tweet links to factual news about climate change |
|   **1**   | **Pro** |The tweet supports the belief of man-made climate change |
|   **0**   | **Neutral** |The tweet neither supports nor refutes the belief of man-made climate change |
|  **-1**   | **Anti** |The tweet does not believe in man-made climate change | 
***

### test.csv - is the dataset on which we applied our model to.  

During testing we do not have access to the **tweetid** variable, but the testing dataset remains the same as the training dataset otherwise
  ***  
  
 ## Details

Once libraries and datasets are imported, the learning process begins:  
+ Data description    
+ Preprocessing    
+ Exploratory data analysis
+ Splitting the data
+ Feature extraction
+ Model training
+ Evaluate model accuracy
+ Saving important data
+ Produce output
+ Conclusion

## Contributions
Pull requests can be made. If changes to be made on the repository are major changes, one can contact the owners for permission to go ahead.

## License
This project is licensed under the MIT License.
  
## Authors
Amogelang Mpyatona  
Lebogang Mogano 
Nkululeko Myeni 
Tshegofatjo Makhafola 
Xenaschke Croucamp  

## Acknowledgements
Ridha Moosa for his assistance.
 
 
 
 
 
 
 
 
 
 
