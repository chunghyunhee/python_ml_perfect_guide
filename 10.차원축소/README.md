## 목표
- 이론이해가 안가면 충분히 찾아보기
- 코드 공부는 1시간 내로 끝내기(시간재기)

## 내용
- 특성추출은 단순히 기존 피처를 저차원의 피처로 압축하는 것이 아니라 더 잘 설명할 수 있는 다른 공간으로 매핑하여 추출하는 것을 의미한다. 
- 차원을 축소하는 idea는 투영과 매니폴드 학습법이 있다. 
- 그 종류인 알고리즘에 대해 배운다. 

## 1. PCA
- excelsior님의 blog : https://excelsior-cjh.tistory.com/167?category=918734

## 2. LDA
- 지도학습의 분류에서 사용
- PCA + 개별 클래스 기준 유지

## 3. SVD
- 고윳값 분해 :https://datascienceschool.net/view-notebook/7fd58178d9e64be682058db7e024d8b5/
- 특잇값 분해 : https://darkpgmr.tistory.com/106
- 차원축소 훑어보기 : https://www.slideshare.net/madvirus/pca-svd

## 4. NFM

## 정리.
- 많은 차원을 가지는 이미지나 텍스트의 경우, PCA나 SVD를 사용
- 원본행렬에서 잠재된 요소를 찾는 토픽모델링, 추천시스템의 경우는 SVD, NMF를 사용한다. 


## 질문.
- 잠재적인 요소가 어떤 건지는 알지 못하나?
- SVD, NMF에서 잠재적인 변수를 사용하는 방법?