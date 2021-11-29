# machinelearning-basic
---
* [Basic](https://github.com/jinokiim/machinelearning-basic/tree/main/basics)
---
## Useage
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white)
---
## Contents
* [basics](#basics)
* [exercise](#exercise)

---
## Setup
* [Basic Setting](#basic-setting)
* [Install Scikit-learn for Machine Learning](#install-scikit-learn-for-machine-learning)



---

## Basic Setting
1. 아나콘다 다운로드
    1) 크롬 브라우저 실행  
    2) https://www.anaconda.com/download/ 링크로 이동 설치파일 다운로드  
    3) 설치 파일 실행


2. 아나콘다 가상환경 만들기

    - 아나콘다 버전확인
      ```console
      $ conda --version
      ```

    - 아나콘다 정보보기
      ```console
      $ conda update conda
      ```

    - 아나콘다 업데이트
      ```console
      $ conda update conda
      ```

    - 아나콘다 가상환경 생성
      ```console
      $ conda create -n ml python=3.8
      ```
      
    - ml 가상환경 접속
      ```console
      $ conda activate 'name'
      ```

    - 패키지 설치
      ```console
      $ conda install scikit-learn matplotlib seaborn pandas notebook
      ```

    - 주피터 노트북 탭 자동완성 삭제
      ```console
      $ conda remove -n ml jedi
      ```
    - 주피터 노트북 확장프로그램 설치
      ```console
      $ pip install jupyter_contrib_nbextensions
      $ jupyter contrib nbextension install
      ```

    - 주피터 노트북 실행
      ```console
      $ jupyter notebook
      ```
![캡처](https://user-images.githubusercontent.com/88222461/140847938-6df42bf3-e182-4f64-ba22-83a79bfd8aa1.PNG)
---

## Install Scikit-learn for Machine Learning

```console
$ conda install scikit-learn
```
---

### graphviz 설치 (오픈소스 다이어그램 생성기)
[graphviz 홈페이지](https://graphviz.org/download/) 에서 다운로드.  

### Download for Windows  
#### Stable Windows install packages:  
*graphviz-2.49.3* 설치

##### 명령프롬프트(cmd) 관리자 권한으로 실행


##### 가상환경 접속
```
conda activate ml
```

##### graphviz 설치
```
pip install graphviz
```
```
dot -c
```
입력
### XGBoost(Extra Gradient Boost) 설치
- https://xgboost.readthedocs.io/ 
- Gradient Boost 알고리즘을 기반으로 개선해서 분산환경에서도 실행할 수 있도록 구현 나온 모델.
- Gradient Boost의 단점인 느린수행시간을 해결하고 과적합을 제어할 수 있는 규제들을 제공하여 성능을 높임.
- 회귀와 분류 모두 지원한다.
- 캐글 경진대회에서 상위에 입상한 데이터 과학자들이 사용한 것을 알려저 유명해짐.
- 두가지 개발 방법
    - [Scikit-learn 래퍼 XGBoost 모듈 사용](https://xgboost.readthedocs.io/en/latest/python/python_api.html#module-xgboost.sklearn)
    - [파이썬 래퍼 XGBoost 모듈 사용](https://xgboost.readthedocs.io/en/latest/python/python_api.html#module-xgboost.training)
##### XGBoost 설치
``
$ conda install -y -c anaconda py-xgboost
``
