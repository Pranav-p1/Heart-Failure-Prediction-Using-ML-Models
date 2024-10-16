# Heart-Failure-Prediction-Using-ML-Models

Predicting heart failure risk at the time of hospital admission: A Machine Learning Approach

Cardiovascular diseases are a major cause of morbidity and mortality globally. Patients admitted to
emergency departments or cardiac care units with cardiovascular conditions require prompt and
accurate clinical interventions. However, the sheer volume and complexity of data collected at
admission pose challenges for healthcare providers in predicting patient outcomes effectively.

Healthcare stakeholders, including doctors, physicians, clinicians, pathology laboratories, and
hospitals, are under pressure to deliver efficient, data-driven care. The manual analysis of
extensive demographic, clinical, and biochemical data can be time-consuming and prone to errors,
leading to delayed or suboptimal decision-making.

This project addresses the need for a machine learning (ML) model that predicts key in-hospital
outcomes, specifically heart failure. By leveraging ML techniques, the proposed decision support
system can process large volumes of data, evaluate multiple variables simultaneously, and adjust
dynamically to varying patient conditions. The model’s interpretability is ensured through
permutation feature importance and aligning predictions with clinical knowledge.

The system aims to enhance hospital decision-making by providing timely, actionable insights. It
will help prioritize high-risk patients, optimize resource use, and enable more accurate clinical
decisions, ultimately improving patient outcomes and resource allocation in cardiovascular
treatment units.

Summary of the project outcomes:

The project successfully developed and evaluated multiple machine learning models for predicting
heart failure and other in-hospital outcomes using a comprehensive dataset. The key models
assessed were Logistic Regression, XGBoost, and an Artificial Neural Network (ANN). Each model
was evaluated based on accuracy, precision, recall, F1-score, and AUC.
• Logistic Regression: Provided a good baseline model with an AUC of 0.79. However, it
faced challenges with class imbalance, particularly in detecting heart failure cases.
• XGBoost: Demonstrated high accuracy and robust performance after hyperparameter
tuning. Despite improvements, the model struggled with class imbalance, particularly in
recall for heart failure cases.
• ANN: Showed strong performance with high AUC scores and improved recall for heart
failure cases after feature selection. The model's complexity required significant
computational resources.
The models provided valuable insights into the predictors of heart failure and highlighted areas for
further refinement, particularly in handling class imbalance and improving recall for the minority
class.

Kaggle Dataset: https://www.kaggle.com/datasets/ashishsahani/hospital-admissions-data

Link to the original article: https://doi.org/10.3390/diagnostics12020241

If you use this dataset in academic research all publications arising out of it must cite the following paper:
Bollepalli, S.C.; Sahani, A.K.; Aslam, N.; Mohan, B.; Kulkarni, K.; Goyal, A.; Singh, B.; Singh, G.; Mittal, A.; Tandon, R.; Chhabra, S.T.; Wander, G.S.; Armoundas, A.A. An Optimized Machine Learning Model Accurately Predicts In-Hospital Outcomes at Admission to a Cardiac Unit. Diagnostics 2022, 12, 241. https://doi.org/10.3390/diagnostics12020241

The Jupyter notebook file (Capstone_project.ipynb) is directly visible once you click it.

To download and view the html code, click on the Capstone_project.html file and then, on the next page, download the raw (.html) file (option to download on right hand side). Save it on your computer and open it in your web browser (prefer Google Chrome). You will then be able to see the full code as well as the figures and tables.

You can also read the report for more details.

Thank you and feel free to contact me in case of anything!!!
