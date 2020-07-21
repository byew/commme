# commme  
# model
The four models are in /pytorch_transformers/modeling_bert.py  
1:Class BertForSequenceClassification_gru  
2:Class BertForSequenceClassification_grulstm  
3:Class BertForSequenceClassification_last3  
4:Class BertForSequenceClassification_last3_p  


# run steps  
data   
1:cd data  
2:run process001_42k.py  

run model  
3:cd model  
4:run 001,002,003,004.sh  
5:get result1-4  



6.cd combine  
7:copy result1-4 to  ./data  
8:cd src and python vote001.py  
