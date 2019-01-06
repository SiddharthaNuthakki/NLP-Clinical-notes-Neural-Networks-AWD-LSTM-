# Master-s_Capstone-project
A natural language processing model which can map clinical notes to medical codes and predict the final diagnosis from 
unstructured entries of history of present illness, symptoms at the time of admission etc is developed. Previous studies have demonstrated 
that deep learning models perform better at this task than conventional machine learning models. We employed the state-of-the-art 
deep learning method ASG Weight-Dropped Long Short-Term Memory (AWD-LSTM) on the largest emergency department clinical notes dataset 
MIMIC III with 1.2M notes for top-50. End-to-end machine learning methods were employed in our evaluations in contrary to manually 
defined rules. We used maximum vocabulary of 60,000 words and with a minimum frequency of 3. Our models predicted the top-10 and 
top-50 ICD-9 codes of diagnosis with 80.3% and 70.7% accuracy respectively. The second model could predict top-10 and top-50 ICD-9 
codes of procedures with 80.5% and 63.9% accuracy respectively. Prediction of final diagnosis from either history of present illness 
or symptoms can let physicians identify promising treatment, which can potentially transform the conventional care of diagnosis 
followed by treatment. With the scores from the present models, the next step is to deploy on a small-scale real-world scenario and 
compare with human coders as gold standard. We believe further research of this approach can create highly accurate predictions which 
can ease workflow in clinical setting. 
