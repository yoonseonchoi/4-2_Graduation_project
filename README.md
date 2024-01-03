# 4-2_Graduation_project
## Stock Price Prediction Using AI Models
시계열 데이터로 Time Series Forecasting을 실험하고 각 모델들의 예측 성능 비교를 위한 프로젝트이다.<br>
S&P500 주가 데이터로 실험을 진행하였으며 DLinear, Pyraformer, PatchTST, ESTIMATE 4가지 모델을 사용하였다.<br>
lookback window와 lookahead window를 각각 달리 하여 각 모델별로 short-term time series prediction과 long-term time series prediction을 수행하였다.<br>
MAE, MSE, RMSE, RankIC, RankIR 총 5가지 평가지표를 통해 예측 성능을 비교하였다.

## Related Work
### DLinear
![image](https://github.com/yoonseonchoi/4-2_Graduation_project/assets/102509278/ec241634-6cba-4d34-9ac0-ff8d530b99fa)<br>
[1] Ailing Zeng, Muxi Chen, Lei Zhang, Qiang Xu. Are transformers effective for time series forecasting? arXiv preprint arXiv:2205.13504, 2022.
### Pyraformer
![image](https://github.com/yoonseonchoi/4-2_Graduation_project/assets/102509278/78460ec2-1a75-4e67-b7a8-056eadc333ec)
![image](https://github.com/yoonseonchoi/4-2_Graduation_project/assets/102509278/d19ceb61-4a0b-4c70-8817-0680a22be224)<br>
[2] Shizhan Liu, Hang Yu, Cong Liao, Jianguo Li, Weiyao Lin, Alex X Liu, and Schahram Dustdar. Pyraformer: Low-complexity pyramidal attention for long-range time series modeling and forecasting. In International Conference on Learning Representations, 2022.
### PatchTST
![image](https://github.com/yoonseonchoi/4-2_Graduation_project/assets/102509278/34cbfe06-6ea1-4cca-a99c-2a429b3bfcc3)<br>
[3] Yuqi Nie, Nam H. Nguyen, Phanwadee Sinthong, Jayant Kalagnanam. A time series is worth 64 words: long-term forecasting with transformers. In International Conference on Learning Representations, 2023.
### ESTIMATE
![image](https://github.com/yoonseonchoi/4-2_Graduation_project/assets/102509278/95dc9043-f0cf-4b37-8821-85423be9f678)<br>
[4] Thanh Trung Huynh, Minh Hieu Nguyen, Thanh Tam Nguyen, Phi Le Nguyen, Matthias Weidlich, Quoc Viet Hung Nguyen, Karl Aberer. Efficient integration of multi-order dynamics and internal dynamics in stock movement prediction. arXiv preprint arXiv:2211.07400, 2022.

## Results
![image](https://github.com/yoonseonchoi/4-2_Graduation_project/assets/102509278/188dfbc0-adef-454e-a03a-8c5a6f2ce820)
![image](https://github.com/yoonseonchoi/4-2_Graduation_project/assets/102509278/3e6960a9-2f4a-4fba-8d96-20f8e775d823)
