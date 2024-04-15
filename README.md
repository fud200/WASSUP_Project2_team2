# WASSUP_Project2_team2

<img src = 'imgs/logo.png' width="400" height="200"/>

## EST soft WASSUP AI 개발과정 2기 시계열 프로젝트
**(Team 7) 에너자2조**
**팀원 및 담당 업무**
  + 김형범(조장/PM)
  + 유준엽(PL)
  + 허영민(서기/PMO)
  + **모든 인원이 모든 과정에 참여합니다. 담당 업무는 명목상 정했습니다. 모든 인원이 프로젝트를 이끌어 나가는 중 입니다.**
---
## Our Subject
**아마존 리뷰 요약**
## Download our data
**데이터의 용량이 커 데이터를 다운 받을 수 있는 링크를 첨부합니다.**

https://drive.google.com/drive/folders/1mF-oyHSlxdMnmKC5_tLIcfmc9yI8l3Jx?usp=sharing

## Files
  + **Reviews.csv** : (다운로드 링크에서 다운 가능) EDA, Preprocessing 에 사용되는 원본 리뷰 데이터입니다.
  + **review_data.csv** : (다운로드 링크에서 다운 가능) Preprocessing.ipynb를 통해 Reviews.csv를 전처리한 데이터입니다.
  + **res_df_attention.csv** : modeling.ipynb를 통해 생성된 리뷰 요약 결과입니다.
  + **EDA.ipynb** : Reviews.csv 파일을 데이터로 사용해 시각화하는 파일입니다.
  + **Preprocessing.ipynb** : Reviews.csv 파일을 전처리하여 모델 학습에 사용할 review_data.csv 파일을 생성합니다.
  + **modeling.ipynb** : 모델을 정의하고 review_data.csv파일을 데이터로 학습해 결과파일 res_df_attention.csv를 생성합니다.
  + **attention.py** : modeling.ipynb에서 모델링 부분에 사용할 Attention layer를 정의한 파일입니다.
