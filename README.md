# AI-CLUB-REPO
This is a solution to the problem of prediction of future demand of power for next hour given the data till the current hour. There are two supporting files giving data for the weather and economic data (selected on basis of usefullness) that are being used for prediction. I have used all the standard methods used for such projects such as eda, feature engineering etc to make the ipynb file.
the mape scores of the models used are -
--1.Random Forest - 2.93%

--2.XGBoost - 2.85%

--3.XGBoost1 - 2.82%

--4.LGBM - 2.69%

--5.CATBoost - 3.30%

--6.Stacking(with linear regression over xgb1 + lgbm + cat) - 2.57% (Final Prediction).

The reader is requested to please see the report of the notebook included at the end of the ipynb file.
