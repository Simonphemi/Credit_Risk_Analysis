# Credit_Risk_Analysis
Through this project, we use Python to build and evaluate several machine learning models to predict credit risk. We applied ML methods as follows:

Oversampling using the RandomOverSampler and SMOTE algorithms.
Undersampling using the ClusterCentroids algorithm.
A combination approach of over-undersampling using the SMOTEENN algorithm.
The BalancedRandomForestClassifier algorith.
The EasyEnsembleClassifier algorith.

## Results
<img width="801" alt="1" src="https://user-images.githubusercontent.com/79813670/123577238-70605500-d7a1-11eb-82af-a2ed75512b97.PNG">
<img width="792" alt="2" src="https://user-images.githubusercontent.com/79813670/123577249-77876300-d7a1-11eb-953f-891fee9e385b.PNG">
<img width="752" alt="3" src="https://user-images.githubusercontent.com/79813670/123577279-853ce880-d7a1-11eb-9439-667fe4414863.PNG">
<img width="729" alt="4" src="https://user-images.githubusercontent.com/79813670/123577290-8c63f680-d7a1-11eb-9d4a-80cb38e100f9.PNG">
<img width="804" alt="b1" src="https://user-images.githubusercontent.com/79813670/123577302-971e8b80-d7a1-11eb-8eef-6958264b4b26.PNG">
<img width="806" alt="b2" src="https://user-images.githubusercontent.com/79813670/123577320-9dad0300-d7a1-11eb-978e-d7e86dfacd18.PNG">
<img width="615" alt="b3" src="https://user-images.githubusercontent.com/79813670/123577366-b0bfd300-d7a1-11eb-8879-da267b5f3e94.PNG">
<img width="442" alt="b5" src="https://user-images.githubusercontent.com/79813670/123577410-c3d2a300-d7a1-11eb-95cb-ffad37562a36.PNG">
<img width="735" alt="b6" src="https://user-images.githubusercontent.com/79813670/123577419-c92fed80-d7a1-11eb-9ca8-89203f3ddbdb.PNG">
combination sampling 2.PNG<img width="801" alt="1" src="https://user-images.githubusercontent.com/79813670/123577137-44dd6a80-d7a1-11eb-90df-f3bc71055b49.PNG">

# Conclusion
We can deduce from the above analysis that a lot of customers are being turned down for being tagged as high risk though they are not, this suggestss ultimately the bank is missing out on potential good reliable clients which will help them make profit by paying off loans in good time. I would not recommend to use any of the above 6 models.These methods used  are better at predicting high risk loans with accuracy in the high 80s to low 90s.Whereas with a low numbers for both models, we see a lot of high number of false positives.
