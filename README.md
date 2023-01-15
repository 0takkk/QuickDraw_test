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
pip install opencv-python==4.5.5.4
pip install keras
pip install pandas
pip install sklearn
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

