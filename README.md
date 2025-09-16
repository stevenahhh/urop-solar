# Physics-Informed Random Forest SSA-CNN-LSTM 프로젝트

## MUST KNOW: WSL ONLY PROJECT

## 환경 설정

1. Miniconda/Anaconda 설치  
2. 필요 시 CUDA, cuDNN 설치 


## 가상환경 및 패키지

```bash
conda create -n tf-gpu python=3.10
conda activate tf-gpu
pip install tensorflow==2.19.0 jupyterlab
```



## 실행 방법

1. Jupyter Lab 실행

```bash
conda activate tf-gpu
jupyter lab
```

2. `pi-lstm.ipynb` 열기
3. 마지막 셀만 확인
4. 데이터: `full-data.csv`



## 파일 위치

Windows에서 파일 복사 경로:
`네트워크 → Linux → Ubuntu → home → <윈도우계정명> → urop-solar`

```bash
cd ~/urop-solar
```

## VSCode

* VSCode Remote - WSL 접속 가능
* 단, Jupyter Lab은 필수 실행
