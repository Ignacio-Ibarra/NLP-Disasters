###  **Using a random forest model we get a score of approximately 0.663 ~ 0.668**

{'bootstrap': True, 'ccp_alpha': 0.0, 'class_weight': None, 'criterion': 'gini', 'max_depth': None, 'max_features': 'auto', 'max_leaf_nodes': None, 'max_samples': None, 'min_impurity_decrease': 0.0, 'min_impurity_split': None, 'min_samples_leaf': 2, 'min_samples_split': 15, 'min_weight_fraction_leaf': 0.0, 'n_estimators': 75, 'n_jobs': None, 'oob_score': False, 'random_state': 42, 'verbose': 0, 'warm_start': False}

### **Feature Importances** 

The most important are `avg_word_len` (the avg number of characters per word of each tweet text) and `characters_count_clean_sw` (the number of character after cleaning of each tweet text).  
