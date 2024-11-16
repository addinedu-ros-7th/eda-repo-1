# eda-repo-1
EDA 프로젝트 1조 저장소. 마블 스튜디오의 대한민국 영화 산업 영향 분석 
![마블로고](https://github.com/user-attachments/assets/7c1898dc-8605-48fe-a95e-c8a7dd8b5519)

## 💡 프로젝트 소개
* 본 프로젝트는 세계적으로 히어로 영화 돌풍을 일으켰던 마블영화의 흥행과 한국 영화 산업간의 상관관계를 분석한다.
<br />

## 🤖 팀 소개

|이름|업무|
|---|:---|
|**함동균**|- 데이터베이스 구성 <br />- 월별 국내영화 박스오피스 데이터 분석 및 시각화<br />- 마블영화와 국내 영화 상관관계 분석 및 시각화<br />-국내 상영관 증가 추이 분석 및 시각화<br />- Jira, Confluence 관리 및 일정 조율|
|조지은|- 마블영화 데이터와 국내 영화 개봉일 데이터 분석 및 시각화<br />- 국내 상영관 추이 분석 및 시각화|
|유재현|- 마블영화 데이터와 국내 영화 개봉일 데이터 분석 및 시각화<br />- 월별 국내영화 박스오피스 데이터 분석 및 시각화|
|문세희|- 국내 박스오피스 데이터 수집 및 분석|
<br />

## 🖥️ 활용 기술
|구분|상세|
|---|---|
|개발환경|<img src="https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white"/>|
|IDE|<img src="https://img.shields.io/badge/VSCode-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white"/> <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white"/>|
|언어|<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>|
|웹 크롤링|<img src="https://img.shields.io/badge/Selenium-43B02A?style=for-the-badge&logo=selenium&logoColor=white"/> <img src="https://img.shields.io/badge/BeatifulSoup-000000?style=for-the-badge&logo=visualstudiocode&logoColor=white"/>|
|시각화|<img src="https://img.shields.io/badge/PANDAS-150458?style=for-the-badge&logo=pandas&logoColor=white"/> <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white"/> <img src="https://img.shields.io/badge/MATPLOTLIB-000000?style=for-the-badge&logo=visualstudiocode&logoColor=white"/>|
|DB|<img src="https://img.shields.io/badge/AMAZON RDS-000000?style=for-the-badge&logo=visualstudiocode&logoColor=white"/> <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>|
|협업 툴|<img src="https://img.shields.io/badge/SLACK-4A154B?style=for-the-badge&logo=slack&logoColor=white"/> <img src="https://img.shields.io/badge/Confluence-172B4D?style=for-the-badge&logo=confluence&logoColor=white"/> <img src="https://img.shields.io/badge/JIRA-0052CC?style=for-the-badge&logo=jira&logoColor=white"/>|
<br />


## 데이터 수집 및 전처리
### 1.영화관입장권통합전산망 (KOBIS)
![영화](https://github.com/user-attachments/assets/360752ed-d172-4323-afb8-53c5d915ec0f)
<br />
국내 영화 박스오피스 데이터
월별 국내 박스오피스 데이터
### 2.케글 (Kaggle)
![image](https://github.com/user-attachments/assets/9ef03df7-951f-4b38-8ea5-ce889dd87215)
<br />
마블 영화 박스오피스 데이터
### 3.서울시 영화상영관 인허가 정보
![image](https://github.com/user-attachments/assets/cb3931fe-afcc-45ea-b450-bf3ab9f4d362)
<br />
<br />
<br />

## 데이터 분석 - 국내 마블의 영향

마블영화가 개봉함에 따라 한국 영화들의 개봉추이와 관람객수에 관점을 두고 분석을 진행하였다.
![아이언맨그래프](https://github.com/user-attachments/assets/95df4c6b-a191-4bd2-8a8d-65d492fb6d2a)
<br />
아이언맨이 개봉 전후에 한국 영화들은 개봉을 피하는 모습을 확인할 수 있다.
전후로 1개,2개의 한국영화만이 개봉을 한 상황을 알 수 있다.

![개봉영화수그래프](https://github.com/user-attachments/assets/7ba74788-d4ce-4f46-9eac-be6c55280b39)
<br />
마블영화가 개봉을 한 날짜를 기준으로 3개의 구간을 그래프로 나눈 뒤,
각 마블영화가 개봉했을 때 한국영화가 개봉한 수를 누적추이 그래프를 통해 확인해보았다.
전체적인 맥락으로 보았을 때, 주황색으로 표시된 영역의 그래프가 차지하는 영역이 작을 것으로 생각했지만
각 영역의 크기가 비슷한 것으로 보아 한국영화가 모든 마블영화에 대해 개봉을 피하지 않았음을 확인할 수 있다.

![2008년그래프](https://github.com/user-attachments/assets/ffe74162-b5d4-49d5-bc0c-cbccc9334df4)
<br />
마블영화중에서는 관객수가 500만이상이거나 1000만 이상인 영화들이 있었다.
그 영화들은 그래프에 진하게 표시하거나 1000만관객일 경우 빨간색으로 표시하였다.
그 영화들에 집중해서 한국영화의 관란객 추이를 살펴보았다.
2008년의 경우에는 한국영화를 보는 관람객의 수가 줄어드는 경향이 있었다.

![2019년그래프](https://github.com/user-attachments/assets/91f63450-e4b9-4205-86c5-7aaedb371d68)
<br />
하지만 1000만관객을 기록한 어벤져스 인피니티워의 경우에 있어서는 더 큰 영향으로 한국영화의 관람객 수가 줄어야 했다.
그래프에서는 한국영화를 보는 관람객의 수가 오히려 증가한 것을 볼 때, 마블은 한국영화에 큰 영향을 미치지 않았다.

![파이그래프](https://github.com/user-attachments/assets/83f14aa7-5a03-46e0-a97e-ff6506ab6a9f)
<br />
500만관객이상, 1000만 관객 이상의 영화를 기록한 역대 영화들의 파이그래프를 그려보았다.
역대 한국에서 개봉한 영화들을 살펴보았을 때, 우리나라의 영화가 차지하는 영역은 60%를 기록했다.
마블영화가 국내영화산업에 있어서 큰 영향을 미치지 않았고, 우리나라가 차지하는 비율이 적지 않았다.
## 데이터 분석 - 한국 영화 산업
앞서 분석한 결과, 마블영화가 국내에 끼친 영향이 적은 것으로 판단하였다.
이를 통해, 한국 영화 산업 자체가 어떻게 성장했는지를 분석을 시작했다.<br />
![매출액그래프](https://github.com/user-attachments/assets/45c14b3c-7ce0-42f3-a972-b7f36b120a67)
<br />
한국영화의 매출은 2014년을 제외하고 꾸준히 성장했음을 매출액 증가율 그래플 통해 알 수 있었다.
또한 연도별 매출액은 1000만 마블영화가 개봉하더라도 꾸준히 증가했음을 알 수 있다.
---<br />
![연간영화관수증감그래프](https://github.com/user-attachments/assets/394e5305-f398-4b3c-8a5a-fc81ff7a5e9a)
<br />
한국 영화산업에 있어서 영화관의 수가 감소하지는 않았을까? 라는 물음으로 국내 영화관의 증감 추이를 지도를 통해 시각화하게 되었다.
그래프를 통해 확인해본 결과, 국내 영화관의 수는 꾸준히 증가했다. 이를 통해 한국 영화 산업은 꾸준히 성장했음을 알 수 있다.
---<br />
![스크린수비율3차](https://github.com/user-attachments/assets/457bf0a4-bfa1-4a80-b404-8f2c23c29653)
<br />
스크린 수 또한 해외영화와 더불어 한국영화도 꾸준히 증가함을 볼 수 있엇다. 2011년에는 스크린 수가 크게 증가함을 확인할 수 있었다.
2011년에는 어떤 일이 있어서 이러한 결과가 있었는지 찾아보게 되었다.
---<br />
![영화산업뉴스](https://github.com/user-attachments/assets/0e1e0020-f5ac-4558-bb0e-47a9068e4cb1)
<br />
국내에서도 영화산업을 꾸준히 증가시키려는 국가적인 계획을 가지고 있었고, 이를 통해 한국영화산업의 성장을 위해 꾸준한 투자가 이루어지고 있었던 것도 확인할 수 있었다.
<br />
<br />
<br />
## 결론
*  마블 영화가 국내 영화산업에 주는 영향이 미미했다.
*  대한민국 영화산업은 마블 영화의 상영기간을 불문하고 꾸준히 성장했다.
*  대한민국 영화산업은 마블 영화의 영향을 받지 않고 스스로 성장했다.
![movie_openrate ](https://github.com/user-attachments/assets/77ddb5ec-7809-44cd-8513-0d5bb01256a7)
