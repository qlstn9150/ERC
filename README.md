제 2회 휴인논 참여
===
Cite: [AIFactory](https://aifactory.space/competition/detail/2234)  
Data download: [KEMDy20](https://nanum.etri.re.kr/share/kjnoh/KEMDy20?lang=ko_KR)

1.Data Preprocessing
---
```
1.data_class.ipynb
```
- 대화별 Emotion,Arousal,Valence에 대한 데이터 생성
```
data_eda.ipynb
```
- IBI, TEMP, EDA 생체 데이터만 사용
- 5개의 클래스 외 나머지 클래스 삭제
- 전처리된 데이터 total.csv 생성

2.Class Visualizing
---
```
2.class_visualizing.ipynb
```
- 생체 데이터별 2차원 축소
- 축소된 데이터를 성별/감정을 클래스로 지정하여 시각화

3.Classification 
---
```
3.classification.ipynb
```
- autoML 활용
