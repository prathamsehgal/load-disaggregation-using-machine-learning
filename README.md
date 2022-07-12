## load-disaggregation-using-machine-learning
![App Screenshot](https://th.bing.com/th/id/OIP.Zl_hi962EkdFKpdzEnOLiAHaJC?pid=ImgDet&rs=1)



 # About
1. This is a Course Project done in under the Guidance of Prof. Zakir Rather Hussain in the Energy Systems Course (EN-304) IIT BOMBAY.
Course Intstructor:-Zakir Hussain Rather(Professor at IIT Bombay)
Project Mentor:-Dhiraj Khadka(PHD Student at IIT Bombay)
2. Developed and implemented a Machine Learning Model as a member of three-person team. 


# Observations
1. Based on parameter tunning step we can see that

2. 5 most important features are - 'RH_out', 'RH_8', 'RH_1', 'T3', 'RH_3'
3. 5 least important features are - 'T7','Tdewpoint','Windspeed','T1','T5'
4. As can be observed with R2 Score , compared to Tuned model 0.63 the R2 score has come down to 0.47 which is decrease of 16% .
5. The reduction in R2 score is high and we should not use reduced feature set for this data set.

# PROJECT SUMMARY
1. Studied in detail the load disaggregation and its importance 
2. Survey the existing techniques for load disaggregation in the literature 
3. Implemented ML/deep learning model for load disaggregation of various household appliances and compared results with other machine learning techniques
4. Achieved test R2score of 0.63  with ExtraTrees Regressor Machine Learning Algorithm.

# Conclusion
1. The best Algorithm to use for this dataset Extra Trees Regressor

2. The untuned model was able to explain 57% of variance on test set .

3. The tuned model was able to explain 63% of varaince on tese set which is improvement of 10%

4. The final model had 22 features

5. Feature reduction was not able to add to better R2 score.The main reason could be availability of lesser data for the prediction after feature reduction.
