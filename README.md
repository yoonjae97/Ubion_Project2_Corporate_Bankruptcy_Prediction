# Ubion_Project2
<br/>
## 유비온디지털센터에서 진행한 최종 프로젝트
<br/>
## 프로젝트 세부 내역
### https://alabaster-sturgeon-3c8.notion.site/f85f51d49a3d4dc7b02e538c75b63798
<br/>
## 요약
### 이 프로젝트는 코스닥에서 제조업 기업들을 대상하며 텍스트 데이터를 사용함으로써 모델에 적시성을 반영하고
### 부도 예측 과정에서 재무비율만을 사용할 때보다 뉴스 기사와 같은 텍스트 데이터를 활용할 때 예측력이 
### 향상되는지, 텍스트 데이터를 어떤 방식으로 가공할 때 더 높은 성능을 보이는지 확인해보는 연구이다.
### 분석 결과로는 재무비율만을 사용할 때보다 텍스트 데이터를 같이 사용할 때 높은 성능을 보임으로써
### 텍스트 데이터의 유의성을 확인할 수 있었다.
<br/>
## 자동화 파일 사용
### 자동화에 있는 파이썬 파일은 부도 예측 프로세스를 하나로 압축한 것이며 
### 해당 폴더의 최종.csv파일을 데이터베이스에 입력 후 py파일을 실행하고 원하는 기업을
### 입력하면 해당 기업이 데이터베이스에 존재할 경우 DB에서 재무비율을 가져오고
### 현재 시점 - 3개월을 기준으로 1년간의 뉴스를 수집해서 전처리 후 
### 부도 기사 비율로 만들어 기업의 1년내 부도를 예측한다.
<br/>
### 파이썬 3.8.0 버전에서 작동시킬 수 있다.
<br/>
## 주제 : 텍스트마이닝을 활용한 기업부도예측 모형 연구
<br/>
### 진행기간 : 2022.06.07 ~ 2022.07.08
