## anaconda 설치
anaconda 설치

## 가상환경 생성하기
```
conda create -n 가상환경이름 pyhon=버전  // 설치
conda env list  // 가상환경 목록
(conda) activate 가상환경이름  // 실행
(conda) deactive 가상환경이름  // 종료 

conda create -n tftest python=3.6
conda activate tftest
```

## 패키지 설치
```
pip install tensorflow
pip install matplotlib
pip install opencv-python==4.5.5.64
pip install keras
pip install pandas
pip install sklearn
pip install scikit-learn
pip install scipy
```

## 주피터 노트북에 가상환경 등록
```
pip install jupyter notebook
python -m ipykernel install --user --name 가상환경이름 --display-name "표시할 커널이름"  // 커널 연결
python -m ipykernel install --user --name tftest --display-name "tftest"

jupyter notebook  // 주피터 노트북 실행
```
<img width="1212" alt="image" src="https://user-images.githubusercontent.com/89503136/212532283-56ed5339-18ca-4e3d-8378-d75a992d6812.png">

## 데이터셋 가져오기
1. clone 받은 파일 안에 data 폴더 만들기
2. [데이터셋](https://console.cloud.google.com/storage/browser/quickdraw_dataset/full/numpy_bitmap;tab=objects?prefix=&forceOnObjectsSortingFiltering=false)에서 .npy 파일을 저장해서 /data 폴더 안에 넣기

## 실행
1. readDateset.py 실행 (원하는 오브젝트에 대한 npy 파일을 읽음)
2. trainModel.py 실행 (학습 및 모델 아키텍처와 모델 가중치를 h5 파일 형식으로 저장)
3. imagePredicy.py 실행
