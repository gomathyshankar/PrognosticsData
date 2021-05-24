# Remaining useful life (RUL) - Prognostics Health Management data
Remaining useful life (RUL) is the amount of time(in hours or cycle) a machine is likely to operate before it requires repair or replacement. Predicting the RUL has the following advantages:

Avoid unplanned downtime.
Optimize operating efficiency
Scheduled maintenance
This interesting usecase is about identifying the Remaining Useful Lifetime (RUL) of Aircraft Engines. The task is to estimate remaining life of an unspecified system using historical data only, irrespective of the underlying physical process.

Data sets consists of multiple multivariate time series. Each data set is further divided into training and test subsets. Each time series is from a different engine – i.e., the data can be considered to be from a fleet of engines of the same type. Each engine starts with different degrees of initial wear and manufacturing variation which is unknown to the user. The data is contaminated with sensor noise.

The engine is operating normally at the start of each time series, and develops a fault at some point during the series. In the training set, the fault grows in magnitude until system failure. In the test set, the time series ends some time prior to system failure. The objective of the competition is to predict the number of remaining operational cycles before failure in the test set, i.e., the number of operational cycles after the last cycle that the engine will continue to operate. Also provided a vector of true Remaining Useful Life (RUL) values for the test data.

Reference: A. Saxena, K. Goebel, D. Simon, and N. Eklund, “Damage Propagation Modeling for Aircraft Engine Run-to-Failure Simulation”, in the Proceedings of the Ist International Conference on Prognostics and Health Management (PHM08), Denver CO, Oct 2008.

Dataset can be downloaded from: https://ti.arc.nasa.gov/tech/dash/groups/pcoe/prognostic-data-repository/#turbofan


Please download the notebook from code folder and use Google colab/jupyter for execution. 
