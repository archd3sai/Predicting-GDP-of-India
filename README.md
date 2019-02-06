# Predicting-GDP-of-India
Prediction of GDP based on Different Socio-economic factors

Data Source: World Bank Open Data

Models:
1) Random Forest:                               15.64 % Test MSE
2) Ridge Regression:                            10.51 % Test MSE
3) Principal Component Regression:              09.27 % Test MSE
4) Lasso Regression:                            06.84 % Test MSE
5) MLR with Forward Subset Selection:           05.22 % Test MSE

Implemented Model: MLR with Forward Subset Selection

GDP Growth = – 2.949 + 1.988 *(Population age 40-44, male) 
		                 – 5.305e-01 * (Population age 35-39, female) 
		                 + 2.538 * (Population age 25-29, female) 
		                 – 8.169e-01 * (Population age 15-64, Total)
		                 – 6.625e-02 * (Consumer Price Index) 
		                 – 5.478e-13 * (Discrepancy in Expenditure Estimate of GDP) 
		                 – 9.095e-02 * (Gross National Expenditure) 
		                 + 3.706e-02 * (Military Expenditure) 
		                 – 4.941e-10 * (Arms Import)
