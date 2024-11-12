# eda-repo-1
EDA 프로젝트 1조 저장소. 마블 스튜디오의 대한민국 영화 산업 영향 분석 
![마블로고](https://github.com/user-attachments/assets/7c1898dc-8605-48fe-a95e-c8a7dd8b5519)
# eda-repo-1
EDA 프로젝트 1조 저장소. 마블 스튜디오의 대한민국 영화 산업 영향 분석 

## 프로젝트 소개

## 팀 소개

|이름|업무|
|---|:---|
|**함동균**|- 데이터베이스 구성 <br>- 월별 국내영화 박스오피스 데이터 분석 및 시각화<br>- 마블영화와 국내 영화 상관관계 분석 및 시각화<br>-국내 상영관 증가 추이 분석 및 시각화<br>- Jira, Confluence 관리 및 일정 조율|
|유재현|- 마블영화 데이터와 국내 영화 개봉일 데이터 분석 및 시각화<br>- 국내 상영관 추이 분석 및 시각화|
|문세희|- 마블영화 데이터와 국내 영화 개봉일 데이터 분석 및 시각화<br>- 월별 국내영화 박스오피스 데이터 분석 및 시각화|
|조지은|- 국내 박스오피스 데이터 수집 및 분석|

## 활용 기술
|구분|상세|
|---|---|
|개발환경|<img src="https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white"/>|
|IDE|<img src="https://img.shields.io/badge/VSCode-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white"/> <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white"/>|
|언어|<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>|
|웹 크롤링|<img src="https://img.shields.io/badge/Selenium-43B02A?style=for-the-badge&logo=selenium&logoColor=white"/> <img src="https://img.shields.io/badge/BeatifulSoup-000000?style=for-the-badge&logo=visualstudiocode&logoColor=white"/>|
|시각화|<img src="https://img.shields.io/badge/PANDAS-150458?style=for-the-badge&logo=pandas&logoColor=white"/> <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white"/> <img src="https://img.shields.io/badge/MATPLOTLIB-000000?style=for-the-badge&logo=visualstudiocode&logoColor=white"/>|
|DB|<img src="https://img.shields.io/badge/AMAZON RDS-000000?style=for-the-badge&logo=visualstudiocode&logoColor=white"/> <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>|
|협업 툴|<img src="https://img.shields.io/badge/SLACK-4A154B?style=for-the-badge&logo=slack&logoColor=white"/> <img src="https://img.shields.io/badge/Confluence-172B4D?style=for-the-badge&logo=confluence&logoColor=white"/> <img src="https://img.shields.io/badge/JIRA-0052CC?style=for-the-badge&logo=jira&logoColor=white"/>|

## 데이터 분석 - 국내 마블의 영향
![아이언맨그래프](https://github.com/user-attachments/assets/95df4c6b-a191-4bd2-8a8d-65d492fb6d2a)
아이언맨이 개봉 전후에 한국 영화들은 개봉을 피하는 모습을 확인할 수 있다.
전후로 1개,2개의 한국영화만이 개봉을 한 상황을 알 수 있다.

![개봉영화수그래프](https://github.com/user-attachments/assets/7ba74788-d4ce-4f46-9eac-be6c55280b39)
마블영화가 개봉을 한 날짜를 기준으로 3개의 구간을 그래프로 나눈 뒤, 
각 마블영화가 개봉했을 때 한국영화가 개봉한 수를 누적추이 그래프를 통해 확인해보았다.
전체적인 맥락으로 보았을 때, 주황색으로 표시된 영역의 그래프가 차지하는 영역이 작을 것으로 생각했지만
각 영역의 크기가 비슷한 것으로 보아 한국영화가 모든 마블영화에 대해 개봉을 피하지 않았음을 확인할 수 있다.

![2008년그래프](https://github.com/user-attachments/assets/ffe74162-b5d4-49d5-bc0c-cbccc9334df4)
마블영화중에서는 관객수가 500만이상이거나 1000만 이상인 영화들이 있었다.
그 영화들은 그래프에 진하게 표시하거나 1000만관객일 경우 빨간색으로 표시하였다. 
그 영화들에 집중해서 한국영화의 관란객 추이를 살펴보았다.
2008년의 경우에는 한국영화를 보는 관람객의 수가 줄어드는 경향이 있었다.

![2019년그래프](https://github.com/user-attachments/assets/91f63450-e4b9-4205-86c5-7aaedb371d68)
하지만 1000만관객을 기록한 어벤져스 인피니티워의 경우에 있어서는 더 큰 영향으로 한국영화의 관람객 수가 줄어야 했다.
그래프에서는 한국영화를 보는 관람객의 수가 오히려 증가한 것을 볼 때, 마블은 한국영화에 큰 영향을 미치지 않았다.

![파이그래프](https://github.com/user-attachments/assets/83f14aa7-5a03-46e0-a97e-ff6506ab6a9f)
500만관객이상, 1000만 관객 이상의 영화를 기록한 역대 영화들의 파이그래프를 그려보았다.
역대 한국에서 개봉한 영화들을 살펴보았을 때, 우리나라의 영화가 차지하는 영역은 60%를 기록했다.
마블영화가 국내영화산업에 있어서 큰 영향을 미치지 않았고, 우리나라가 차지하는 비율이 적지 않았다.

## 데이터 분석 - 한국 영화 산업
