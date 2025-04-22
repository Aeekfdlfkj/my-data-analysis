타이타닉 생존자 예측 분석 🚢

이 프로젝트는 Titanic 데이터를 기반으로 승객들의 생존 여부를 예측하는 분석입니다.  
기초적인 데이터 전처리 및 탐색적 데이터 분석(EDA), 간단한 머신러닝 모델링까지 다루며, 데이터 분석 기본기를 익히기 위한 목적입니다.

---

📌 프로젝트 목표
- Titanic 탑승자 데이터를 바탕으로 생존에 영향을 미친 요인들을 분석
- 데이터 전처리 및 시각화, 머신러닝 기초 모델 실습

---

🔍 주요 작업 내용
- 결측치 확인 및 처리 (`Age`, `Cabin`, `Embarked` 등)
- 범주형 변수 인코딩 (`Sex`, `Embarked`)
- 가족 관련 변수(`SibSp`, `Parch`)를 활용해 `FamilySize` 파생 변수 생성
- `Survived`와의 관계 시각화 (성별, 나이, 객실 등급 등)
- 간단한 모델링 (예: 의사결정트리, 로지스틱 회귀)

---

💡 사용 기술
- Python (pandas, matplotlib, seaborn, scikit-learn)
- Jupyter Notebook

---

 📁 파일 설명
- `titanic.ipynb` : 전체 분석 및 모델링 과정을 담은 주피터 노트북

---

 📂 데이터셋
- Kaggle 링크: [Titanic - Machine Learning from Disaster](https://www.kaggle.com/c/titanic)
- 본 레포지토리에는 데이터 파일이 포함되어 있지 않습니다. 직접 다운로드 후 사용해주세요.
