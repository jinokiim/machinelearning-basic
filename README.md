# machinelearning-basic

---

## Contents
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
      $ conda create -n ml python=3.8
      ```

    - 패키지 설치
      ```console
      $ conda install scikit-learn matploylib seaborn pandas notebook
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

## 

