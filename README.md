# Critical_Heat_Flux_LocationPrediction

The prediction of critical heat flux (CHF) location is
a challenging issue in power generation industries. Several factors
viz. geometric parameters and operating conditions influence the
occurrence of CHF, and many mechanisms have been proposed to
better explain the physics behind the occurrence of CHF. As CHF
is a complex phenomenon, its dependency on these factors exhibit
non-linear relationship. Further, it is challenging to account for
all the factors simultaneously in a single model. Moreover, the
benchmark experimental data has to be available to validate the
constructed model with all the factors. Due to these reasons, the
influence of some of the factors remain unresolved. Considering
the above issues, the present study employs different machine
learning models to predict CHF location and identify the accurate
model based on the comparisons against the chosen benchmark
experimental data. 

Becker et al. [1] data bank was selected for
machine learning model training as well as the testing due to
the wide range of operating conditions covered. Hyperparameter
tuning is applied to optimize the performance of the models.
Among all the implemented models, the artificial neural network
(ANN) model is found to perform well with the training and the
test datasets. The MAPE of the training and testing data points
are 4.01% and 6.04%, respectively. The accuracy score of the
ANN model is approximately 96% for the training and 94% for
the testing datasets. The proposed model is helpful for design
engineers and analysts in power plants for design optimization
and to reduce the computational time.
