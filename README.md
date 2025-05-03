# Customer Segmentation using K-Means, PCA, and FAMD

이 프로젝트는 고객 데이터를 기반으로 **PCA (주성분 분석)**, **FAMD (혼합 데이터 요인 분석)**, **K-Means Clustering**을 활용하여 고객 세분화를 수행한 Python 분석 노트북입니다.

## 📌 프로젝트 개요

- **데이터**: 수치형 및 범주형 데이터 혼합
- **주요 기법**:
  - PCA를 통한 수치형 변수 차원 축소
  - FAMD를 통한 수치형 + 범주형 변수 혼합 차원 축소
  - K-Means로 군집화
- **분석 목적**: 고객 세그먼트 이해 및 데이터 시각화

## 📂 파일 구성

- `customer_segmentation_kmeans-PCA,FAMD.ipynb` : 주석 추가된 분석 노트북
- `README.md` : 프로젝트 설명 문서

## 🏃 실행 방법

1. 필요한 라이브러리 설치:

```bash
pip install pandas matplotlib seaborn scikit-learn prince
