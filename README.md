# 📊 Semi Data Analysis Project

## 📌 프로젝트 개요

이 프로젝트는 Python과 Jupyter Notebook을 활용하여 **기초적인 데이터 분석 흐름**을 직접 구성해본 미니 프로젝트입니다.  
데이터 불러오기부터 전처리, 시각화까지의 기본 사이클을 경험하고, 분석 로직을 Python 코드로 구현하는 데 집중했습니다.

---

## 🛠 사용 기술 및 환경

<p>
  <img src="https://img.shields.io/badge/Python-3.12-blue?logo=python"/>
  <img src="https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/Matplotlib-3776AB?style=flat-square&logo=python&logoColor=white"/>
</p>

- Language: Python 3.12
- IDE: Jupyter Notebook (VSCode)
- 주요 라이브러리: `pandas`, `matplotlib`, `numpy`

---

## 🔍 분석 흐름

1. **데이터 불러오기 및 구조 확인**  
   CSV 또는 Excel 파일을 불러와 컬럼, 결측치, 기본 통계량 등을 파악하였습니다.

2. **결측치 처리 및 정제 작업**  
   `dropna()`, `fillna()` 등을 사용해 데이터 누락 문제를 해결하고 타입 변환을 수행했습니다.

3. **EDA (탐색적 데이터 분석)**  
   - 분포, 이상치 확인
   - 히스토그램, 박스플롯, 꺾은선 그래프 등을 활용한 시각화
   - 변수 간 상관관계 분석 (`corr()` 등)

4. **시각화 결과 도출 및 해석**  
   간단한 시각 자료를 통해 데이터의 특성과 패턴을 시각적으로 이해했습니다.

---

## 📘 배운 점

- pandas와 matplotlib을 통해 데이터 분석의 기본 흐름을 직접 구현하며 익혔습니다.
- 단순히 데이터를 불러오는 것이 아니라, **문제 정의 → 전처리 → 시각화 → 해석**이라는 구조적 사고의 중요성을 배웠습니다.
- 분석을 위한 Python 사용 경험이 부족했지만, 작은 작업부터 차근차근 수행하며 **기초 개념을 실전에 적용**하는 힘을 길렀습니다.
- EDA를 통해 데이터를 직접 다뤄보며 **데이터를 읽는 눈을 키우는 계기**가 되었습니다.

---

## 🔧 개선 여지

- 다양한 시각화 라이브러리 연습 (예: `seaborn`, `plotly`)
- 함수 분리 및 모듈화
- 분석 결과 기반으로 간단한 리포트 자동 생성 연습
- 이상치 처리 및 범주형 인코딩 방식 개선