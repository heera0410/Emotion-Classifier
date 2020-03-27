## Observations
- From the experimental results, some observations about the proposed approach are shown as follows.
- The dataset which we used has 4,16,810 records.
- The data size affects the classification performance.
- When the training data is more, the model will always perform better(AWD-LSTM). The number of records in training data are 333448.
- The standard measure Accuracy is used to evaluate the performance of the model. And the metric confusion matrix is plotted to view the performance.
- Word Embedding is achieved using fastai TextClasDataBunch and TextLMDataBunch classes, so that the emotions of the text can be effectively classified.
- The proposed approach AWD-Lstm shows state of the art performance with 93.99% accuracy.This shows the feasibility of an LSTM-based approach to text emotion classification. 
- ASGD weight dropped LSTM returns the average of the weights of the current and previous iteration which is required to identify the importance of each word in a sentence to classify the text under its class(emotions).


## Future Work 1
  Our future work includes contributing to the literature on understanding communications on the topic of suicide in social media by 
- creating a new human-annotated dataset to help identify features of suicidal ideation, 
- creating a set of benchmark experimental results for machine learning approaches to the classification of suicidal ideation, and 
- developing a machine classifier capable of distinguishing between worrying language such as suicidal ideation, and flippant references to suicide, awareness raising about suicide and reports of suicide. This is especially relevant to quantify actual volumes of worrying language on social media for the purposes of understanding risk to human safety.

## Future Work 2
  - Our future work also includes to help university administrators and teachers address problematic areas in teaching and learning. 
  - We propose to create a system that analyzes student comments from both course surveys and online sources to identify sentiment polarity, the emotions expressed, and satisfaction versus dissatisfaction.
  
## Future Work 3
  - Our future work includes to create system with the ability to detect emotion in text which can increase human-computer interaction. If the computer could tell a person's mood or emotional state, it would be able to switch to an accommodting form of interaction.

  
