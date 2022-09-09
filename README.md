# 셀레니움을 이용한 게더타운 바닥 깔기 자동화

## 개요
* 본 프로젝트는 KT AIVLE SCHOOL에서 진행한 메타버스 스터디룸 제작 이벤트입니다.
* 셀레니움을 이용해 게더타운 로그인과, 미리 지정해둔 이미지를 그대로 게더타운 바닥에 깔아주는 작업을 자동화시킵니다.

## 자동화 영상
https://user-images.githubusercontent.com/89781598/189283665-24a8493d-e092-43fd-8f33-dd7e32aa4722.mp4


## 프로젝트 설명
<h3 align="center">🪄 프로젝트에 대한 설명은 아래의 네이버 블로그를 참고해주세요! 🪄</h3>

- [1편] 프로젝트 소개 : https://blog.naver.com/j227ung/222868866219
- [2편] EDA : https://blog.naver.com/j227ung/222868890634
- [3편] Config to Select, 통계 기법을 제어하다. : https://blog.naver.com/j227ung/222868893036
- [4편] 베이지안 옵티마이제이션(Bayesian Optimization) : https://blog.naver.com/j227ung/222869791893
- [5편] SUBMIT : https://blog.naver.com/j227ung/222870620816


## 패키지 사용

<p align="center">
  <img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white"/></a>&nbsp
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=NumPy&logoColor=white"/></a>&nbsp
  <img src="https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=SciPy&logoColor=white"/></a>&nbsp
  <img src="https://img.shields.io/badge/scikit-learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white"/></a>&nbsp
  <br>
    <img src="https://img.shields.io/badge/-statsmodel-green"/></a>&nbsp
    <img src="https://img.shields.io/badge/-itertools-black"/></a>&nbsp
    <img src="https://img.shields.io/badge/-catboost-yellow"/></a>&nbsp
    <img src="https://img.shields.io/badge/-byes_opt-blueviolet"/></a>&nbsp
    
</p>

## 파일 구조
```
📦KT.BAD_WEB
 ┣ 📂CSV
 ┃ ┣ 📜cat_esb_best2.csv
 ┃ ┣ 📜CONFIG_RESULT.csv
 ┃ ┗ 📜logistic_result.csv
 ┣ 📂PT
 ┃ ┣ 📜부산경남_안중찬.pdf
 ┃ ┗ 📜부산경남_안중찬.pptx
 ┣ 📜01.EDA.ipynb
 ┣ 📜02.CONFIG.ipynb
 ┣ 📜03.Bayesian-Optimization.ipynb
 ┗ 📜04.SUBMIT.ipynb
```

## 파일 설명
- EDA.ipynb
    - EDA에 관련된 코드들이 담겨져있습니다.
- CONFIG.ipynb
    - CONFIG To Select에 대한 코드가 담겨져있습니다.(자세한 내용은 위의 불로그 참조)
- Bayesian-Optimization.ipynb
    - Bayesian-Optimization으로 하이퍼 파라미터 튜닝을 한 코드들이 담겨져 있습니다.
- SUBMIT.ipynb
    - 최종 제출된 모델의 코드가 담겨져 있습니다.
- 부산경남_안중찬.pdf,pptx
    - 모델에 대한 설명이 담겨져 있습니다. AIVLE SCHOOL에서 프레젠테이션을 진행하였습니다.
- cat_esb_best2.csv
    - 성능이 가장 좋은 모델이 예측한 값입니다.
- CONFIG_RESULT.csv
    - Config to Select의 결과입니다.
- logistic_result.csv
    - logistic 검정의 결과입니다.

## 문의사항
* email : ajc227ung@gmail.com

