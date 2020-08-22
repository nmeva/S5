# EVA_S5  
### Naveen Kumar M     
#####################################################    
Experiment: 1    
#####################################################    
Target:    
->Get the set-up right  
->Set Transforms  
->Set Data Loader  
->Set Basic Working Code  
->Set Basic Training & Test Loop
    
Results:  
->Parameters: 6.3M  
->Best Training Accuracy: 100%  
->Best Test Accuracy: 99.2%  
  
Analysis:  
->Extremely Heavy Model  
->Model is over-fitting  
->Model can be further improved by reducing the number of parameters.  

File Link: https://github.com/nmeva/S5/blob/master/EVA4_Session_F1.ipynb

###############################################    
Experiment: 2    
###############################################    
Target:
->Reduce the total number of parameters 
->Add batch normalization to the model.
    
Results:  
Parameters: 13K  
Best Training Accuracy: 99.95%  
Best Test Accuracy: 99.34%  
  
Analysis:  
Model is light weight as params are reduced  
Model is Over-fitting after batch normalization  
Model can be further improved.  

File Link: https://github.com/nmeva/S5/blob/master/EVA4_Session_F2.ipynb  

###############################################    
Experiment: 3    
###############################################    
Target:  
As the parameters are reduced add dropout and GAP to the model.
    
Results:  
Parameters: 9K  
Best Training Accuracy: 99.31%  
Best Test Accuracy: 99.48% (seen consistently in last few epochs)    
Analysis:  
Model is light weight.  
This is a fit model.  
Model can be further improved.  

File Link: https://github.com/nmeva/S5/blob/master/EVA4_Session_F3.ipynb  

##################################################    
Experiment: 4    
##################################################    
Target:  
As the parameters are reduced batch normalization, dropout, GAP are aaded to the model along with slight rotation transform.  
Its time use the learning rate and improve the accuracy. 
   
Results:  
Parameters: >10K (9990)  
Best Training Accuracy: 99.43%  
Best Test Accuracy: 99.51% (>99.4 seen consistently 5/15) 
   
Analysis:  
Model is light weight   
This is a fit model.  
Model can be further improved.  

File Link: https://github.com/nmeva/S5/blob/master/EVA4_Session_F4.ipynb  

