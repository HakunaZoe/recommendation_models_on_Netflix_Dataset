# recommendation_models_on_Netflix_Dataset
# Compare Models of Recommendation on Netflix Dataset (2022 Fall ADM)


* Team (members): Yijun Zhou (email) yiz209@pitt.edu
* Project presentation: click [here](Data_Mining_Final_Project.pdf) to go to the presentation slides
* Project paper: click [here](data_mining_final_project_yijun.pdf) to go to the final report




## Description
This project aims to build different recommendation models and compare the performance of models on Netflix Dataset. 

## Prerequisites
the python packages used are listed here:   
pandas   
numpy   
matplotlib   
pickle   
time   
torch   
torchmetrixs   
torch.nn   
torch.optim   
torchmetrixs   
gensim   
multiprocessing   

## Authors
name: Yijun Zhou
email: yiz209@Pitt.edu

## Acknowledgments
I am really thankful to Yuru Lin, Xizhi Wu, and Arun Balajiee:)

### Inspiration
 https://github.com/pyy0715/Neural-Collaborative-Filtering


## Project requirement 

In this homework assignment, you will extend your hw01 and hw02. Your goal is to incorporate two different graph-based neural network methods to boost the recommendation performance. You will test your new implementation using the same Netflix Prize data.

1. We have covered several graph-based neural network methods in our class and readings, including shallow and deep approaches, knowledge graph appraoches, etc. Pick **two distinctive methods** that you are interested in, implement and evaluate their performance on the Netflix movie recommendation dataset. In your final report, explain why you select the methods, and provide a rationale for why you think the method may potentially improve your recommender system.
2. Use the best two models from your previous assignments (hw01, hw02) as your baseline.
    * (B1) your best model from hw01-02; describe what the model is
    * (B2) your 2nd best model from hw01-02; describe what the model is
    * (A1) your first graph-based neural network model
    * (A2) your first graph-based neural network model

3. Compare the model performance based on both implicit and explicit feedback. This allows you to understand the strength of your models. For explicit feedback, use MAPE and RMSE as evaluation metrics (as in hw01), and for implicit feedback, use HR and NDCG (as in hw02). In your final report, provide a detailed performance analysis and discuss the strengths and weaknesses of your models.

**Note:**  If you use anyone's shared code or build your model based on any existing repositories, make sure you include all of them in your acknowledgment and references.

4. Your submission will include (1) a reproducible notebook, (2) project presentation slides, and (3) a final paper. See [final project guideline](https://drive.google.com/file/d/1OFsUgGk7FOYi8qJ4fv7_4J5IA-bRMsU_/view?usp=share_link) for more details.
