# Feedback-Prize-Effectiveness-Kaggle-Competition
https://www.kaggle.com/competitions/feedback-prize-effectiveness
This notebook includes my approach on Feedback Prize Effectiveness competition on Kaggle. 
* I used Universal-Sentence-Encoder as pretrained model in my notebook. 
* Three(3) inputs used for this analysis
  * **Token:** Created by tokenization of `discourse_effectiveness` column
  * **Type:** Encode `discourse_type` column
  * **line_num:** Since data created by number of sentences belongs to unique essays and these sentences are ordered I want to try whether inculding rank of sentence within unique essay can improve the results.
  
According to these knowledge architecture of ANN looked like this:
![image](https://user-images.githubusercontent.com/66626016/176889800-5ed9a4c4-ae65-48ee-a463-259cb2677b94.png)
