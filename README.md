# Call Log Prediction
## Best Model 
__________
### 1-Randome forest 
- Base model average CV score __0.646__
- Random search best model score __0.716__
`{'n_estimators': 2400,
 'min_samples_split': 5,
 'min_samples_leaf': 4,
 'max_features': 'auto',
 'max_depth': 10,
 'bootstrap': True}`
 - applying pca minimum 0.95 to the best modle score __0.928__
 
### 2- Multilayer perceptron MLP score __0.929__
 - Model parameters _27*729*27*10*2_ 
 - Model hyper-parameters 
 `MLPClassifier(random_state=1, max_iter=1000, alpha=1e-5,
                    hidden_layer_sizes=(729,27,10),activation="tanh",
                    verbose=True,shuffle=True,early_stopping=True,,validation_fraction=.2)`
                    
____________________
## Feature importance
![alt text](https://github.com/AJamal27891/1YBCwVpt3HNYOiYL/blob/main/Shapeimportance.PNG?raw=true)
