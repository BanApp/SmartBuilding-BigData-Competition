# 2023년 스마트빌딩 빅데이터 분석 경진대회(최우수상):1st_place_medal:
## IoT를 통해서 수집된 실내 데이터를 바탕으로 실내 재실인원 예측 모델 제작(CatBoost)

## 최종결과: 최우수상(상장 + 아이패드 우승 상품):fire:

![a](https://github.com/BanApp/SmartBuilding-BigData-Competition/assets/93313445/13eb6d3e-4786-44a6-834d-df9f663a434b)

***
## 파일설명

1. bin_classfier.pkl - 0과 0이 아닌 데이터들을 구분하기 위한 이진 분류 모델(피클 파일)

2. multi_classfier.pkl - 1,2,3,4,5,6 데이터들을 구분하기 위한 다중 분류 모델(피클 파일)

3. 모델_학습.ipynb - 코랩 환경에서 구동 가능한 이진분류 모델, 다중 분류 모델 학습 코드, GPU 사용, catboost 설치 필요, 데이터셋 경로 설정 필요.

4. 모텔_테스트.ipynb - 코랩 환경에서 구동 가능한 경로를 통해서 피클 모델 및 데이터 호출 후 평가 할 수 있는 코드, catboost 설치 필요, 데이터셋 경로 및 모델 경로 설정 필요.

5. 아이디어 요약본 - EDA, 데이터 전처리 및 모델제작에 대한 아이디어 요약.

6. 아이디어 설명 - 아이디어에 대한 자세한 설명과 세부사항 및 결과 수록.
   
***


# 👨‍ 제작자

<br/>

<table>
  <tr>
    <td height="140px" align="center"> <a href="https://github.com/BanApp"><img src="https://avatars.githubusercontent.com/u/93313445?s=460&v=4" width="140px" /><br/></a></td>

  </tr>
  <tr>
      <td align="center">👦🏻 정민준 (EDA, 모델 제작, 발표)</td>
  </tr>
  <tr>
      <td align="center">단국대학교<br/>컴퓨터공학과<br/></td>
  </tr>
</table>
<br/><br/>


# 🎥 프로젝트 소개

## Iot 센서 데이터를 통해 수집된 데이터를 바탕으로 실내 재실인원 예측

플랫폼: 'Goolge Colab'<br>
GPU: Tesla T4<br>
GPU API: cuda<br>
모델 : CatBoost

<br/><br/>

# 📘 기능 설명

## 1) 모델_학습.ipynb 를 통해서 학습 데이터(csv)를 호출하고 데이터를 전처리후 모델을 학습한다.
## 2) 모델_테스트.ipynb 를 통해서 평가 데이터(csv)를 호출하고 데이터를 전처리후 모델을 사용한다.

