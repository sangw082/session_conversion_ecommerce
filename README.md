# 세션 기반 구매 행동 분석 및 전환율 향상 전략

전자상거래 플랫폼에서는 고객의 구매 여정이 일반적으로 `상품 조회(View)`에서 시작해 `장바구니(Cart)`를 거쳐 `구매(Purchase)`로 이어집니다. 그러나 실제 구매까지 이어지는 고객은 전체의 4~7% 수준에 불과하며, 중간 전환 단계에서의 이탈이 매우 빈번하게 발생합니다.

본 프로젝트는 고객이 어느 지점에서 이탈하는지, 어떤 행동이 전환과 연결되는지를 데이터 기반으로 진단하고 개선 방향을 제시하는 데 목적이 있습니다.

> **데이터 출처**: [eCommerce Behavior Data - Kaggle](https://www.kaggle.com/datasets/mkechinov/ecommerce-behavior-data-from-multi-category-store)

---

## 🔍 분석 흐름 요약

### 1. Funnel 전환율 분석
- View → Cart → Purchase 단계별 전환율 계산
- 주요 요인별 비교:
  - **카테고리(Category)**  
  - **시간대(Time of Day)**  
  - **가격대(Price Range)**  
  - **요일(Day of Week)**

### 2. 세션 기반 행동 비교 분석
- 구매 성공 vs 실패 세션 특성 비교
- 주요 비교 지표:
  - 세션 길이(Session Length)
  - 클릭 행동 수(Click Count)
  - 평균 상품 가격대(Avg. Product Price)
  - 기타 사용자 행동 패턴

### 3. 전환 예측 모델링
- **로지스틱 회귀(Logistic Regression)** 기반의 구매 전환 예측
- 주요 행동 변수의 영향력 정량화
- 전환 가능성에 따른 고객 세그먼트 분류

---

## 🧰 사용 기술 및 도구

- Python (pandas, numpy, scikit-learn, matplotlib, seaborn)
- Jupyter Notebook
- Git / GitHub

---


