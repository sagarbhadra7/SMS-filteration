# SMS-filteration
This project has crated for the SMS spam and ham classification
Below are the document specification.
we will try to build a simple classifier using machine learning which will help in identifying whether a given SMS is a spam or not. Parallely, we will also be understanding a few basic components of Natural Language Processing (NLP) for the readers who are new to natural language processing.

Below are the stats of the all the model.

model	                best_score	    best_params
svm	                  0.980080	      {'C': 5, 'kernel': 'linear'}
random_forest	        0.971673	      {'n_estimators': 2200, 'n_jobs': -1}
KNeighborsClassifier	0.966922	      {'n_neighbors': 3}
Bagging	              0.966007	      {'bootstrap': False, 'max_samples': 1200, 'n_estimators': 2100, 'n_jobs': -1}
Adaboost              0.983734	      {'algorithm': 'SAMME.R', 'learning_rate': 0.2, 'n_estimators': 2000}
SVC_poly	            0.979349	      {'C': 1, 'coef0': 15, 'degree': 4, 'kernel': 'poly'}
