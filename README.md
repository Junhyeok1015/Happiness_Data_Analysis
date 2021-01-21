# Happiness_Data_Analysis
🧐 어느 나라가 가장 행복할지 분석해봅시다 🧐

## Dataset
World Happiness Report Dataset(2019) : https://www.kaggle.com/unsdsn/world-happiness

변수 설명
- Overall rank : 전반적인 행복지수 순위
- Country or region : 국가
- Score : 행복지수
- GDP per capita : 1인당 국내총생산
- Social Support : 주변인들의 지원정도
- Healthy life expectancy : 건강 기대 수명
- Freedom to make life choice : 하고싶은 것을 할 수 있는 자유
- Generosity : 기부 문화
- Perceptions of corruption : 부패 인식 정도

### 행복지수 분포
![Happiness_Distribution](https://user-images.githubusercontent.com/18099627/105358634-c43aa100-5c39-11eb-8a6b-b06ddf46a2d8.png)

- 행복지수의 중앙값은 5.38
- 우리나라 행복지수 : 5.9
- 행복한편이네요 :)

### 지도로 본 행복지수
![Happniess Map](https://user-images.githubusercontent.com/18099627/105359114-6b1f3d00-5c3a-11eb-8a6e-f4076ceccc1e.png)

- 색이 밝을수록 행복지수가 낮음을 의미합니다.
- 대부분의 아메리카 지역의 국가들이 행복지수가 높고 아프리카에 위치한 국가들이 행복지수가 낮음을 확인할 수 있습니다
- 한국은 54위로 나름(?) 상위권입니다.

### 행복지수와 변수간의 상관관계
![image](https://user-images.githubusercontent.com/18099627/105359370-b89baa00-5c3a-11eb-959c-30139986c97a.png)

- 두번째행의 Score(행복지수) 와 다른 변수들간의 상관관계를 확인해보자면 GDP가 높으면 높을수록, 주변사람의 도움이 많으면 많을수록, 기대 수명이 높을수록 행복지수가 높음을 확인할 수 있습니다. 어찌보면 당연한 말이네요
- 반면에 기부문화나 부패 인식 정도가 행복지수에 큰 영향을 주고 있는것 같진 않아보입니다.

### 행복지수는 예측이 가능할까?
![image](https://user-images.githubusercontent.com/18099627/105359655-0adccb00-5c3b-11eb-916c-46a22d7f02d9.png)

- 순위와 국가를 제외한 변수들로 간단한 선형회귀 알고리즘을 이용하여 행복지수를 예측해보았습니다.

## 추가적인 분석은 코드를 확인해주시면 감사하겠습니다.
