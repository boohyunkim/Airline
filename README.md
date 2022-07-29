# Airline

```
2022년도 코멘토 직무부트캠프 프로그램에서 진행했었던 프로젝트입니다.
캐글의 Airline Passenger Satisfaction 데이터셋을 활용한 분석입니다.
항공사 승객 데이터를 보고 고객 만족도 요인분석 및 예측 알고리즘을 구현하는 것이 목적입니다.

타겟변수는 satisfaction이며, 평가지표는 Accuarcy, AUC 등 다양하게 활용했습니다.
코딩은 Jupyter Notebook, 발표자료는 ppt를 사용하였습니다.


해당 주소: https://www.kaggle.com/datasets/teejmahal20/airline-passenger-satisfaction
```



## Airline 폴더


> Airline.csv  
```
캐글에서 제공한 항공사 고객 데이터셋 원자료 파일입니다.
```
##

> Airline_Experiment(EDA).ipynb
```
항공사 고객 데이터를 전처리한 Jupyter Notebook 파일입니다.  
```
##


> Airline_Experiment_DataModeling(Categorical).ipynb
```
전처리한 항공사 고객 데이터를 모델링한 Jupyter Notebook 파일입니다. 
(해당 데이터셋의 리커트 5점 척도는 원-핫 인코딩으로 처리)
```
##

> Airline_Experiment_DataModeling(Numerical, Pycaret).ipynb
```
전처리한 항공사 고객 데이터를 모델링한 Jupyter Notebook 파일입니다. pycaret을 사용하였습니다.
(해당 데이터셋의 리커트 5점 척도는 연속형으로 처리)
```
##

> Airline_Experiment_DataModeling(Numerical, Sklearn, Optuna).ipynb
```
전처리한 항공사 고객 데이터를 모델링한 Jupyter Notebook 파일입니다. sklearn과 optuna를 사용하였습니다.
(해당 데이터셋의 리커트 5점 척도는 연속형으로 처리)
```
##

> Airline_revised.csv
```
항공사 고객 데이터를 임시로 전처리한 데이터셋 csv 파일입니다. 
```
##

> Airline_revised_Numerical.csv
```
항공사 고객 데이터를 전처리한 데이터셋 csv 파일입니다. 
(해당 데이터셋의 리커트 5점 척도는 연속형으로 처리)
```
##

> Description.xlsx
```
해당 데이터셋의 변수를 설명한 코드북 파일입니다. 
```
##
 

> optuna_contour.jpg, optuna_coordinate.jpg, optuna_optimization_history_plot.jpg, optuna_parameter_importance.jpg
```
optuna 라이브러리를 사용하여 하이퍼파라미터를 튜닝한 결과의 이미지입니다.
각 파라미터들의 상관관계, 하이퍼파라미터 중요도를 보여줍니다.
```
##


> problem.txt
```
리커트 5점제 척도를 어떻게 전처리할지에 대해서 아이디어를 기록해놓은 메모입니다.
```






## Airline.PDF 폴더
```
코멘토 직무부트캠프 기간동안 발표했던 ppt를 모아두었습니다.
EDA, 모델링 과정에서의 진행과정과 아이디어를 기록해두었습니다. 
```




참고. 프로그램 내의 실행결과와 pdf로 정리한 결과값이 약간씩 오차가 있습니다.
코드 내에서 EDA는 Arrival Delay in Minutes 변수의 결측값이 있는 칼럼 330개를 제거하고 분석한 결과이고,
pdf 내에서의 EDA는 결측값 제거 없이 그대로 분석한 결과입니다.

또한, 코드 내에서 모델링 결과는 seed 값을 '123'으로 고정한 결과값이며,
pdf 내에서의 모델링 결과는 seed 값을 따로 지정하지 않은 결과값입니다.
