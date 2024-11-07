# 인공지능을 이용한 분리수거 분류 및 인공지능 모델 비교

## 프로젝트 소개
* 본 프로젝트는 환경 문제가 심각해진 지금, 무분별하게 버려지는 쓰레기 문제를 해결하기 위해 인공지능을 이용한 분리수거 분류 프로그램을 개발하고, 다양한 알고리즘의 성능을 비교하는 것을 목표
* 이를 통해 재활용 비율을 증대시키고, 분리수거의 접근성을 높이는데 기여 및 인공지능에 이해

## 프로젝트 진행 이유
1. **환경 문제 해결**: 재활용 쓰레기 중 일부가 일반 쓰레기로 버려지는 문제를 해결하기 위해 인공지능을 활용하여 정확한 분리수거 분류가 필요
2. **데이터 활용**: 인터넷과 일상생활에서 쉽게 얻을 수 있는 데이터들을 활용하여 프로젝트를 진행
3. **학습 기회**: 이미지 처리 방식에 대한 이해를 높이고, 인공지능 모델이 새로운 데이터의 정확도를 평가하는 방법을 배움

## 사용한 알고리즘
프로젝트에서는 다음의 4가지 알고리즘을 활용하여 쓰레기 분류 모델을 개발 진행
- 로지스틱 회귀
- K-means
- 심층신경망 (DNN)
- 합성곱 신경망 (CNN)

## 결과

### 알고리즘 정확도 비교
* 로지스틱 회귀
- ![image](https://github.com/user-attachments/assets/94a36023-d709-4083-bd66-2de6b56def34){: width = "400"}


* k-means
* DNN
* CNN

* DNN
* CNN
| 알고리즘          | 정확도 (%) |
|------------------|------------|
| 로지스틱 회귀    | 낮은 정확도 |
| K-means          | 낮은 정확도 |
| 심층신경망 (DNN) | 73         |
| 합성곱 신경망 (CNN) | 82         |

### 테스트 결과

| 알고리즘          | 테스트 이미지 수 | 정답 수 | 정확도 (%) |
|------------------|------------------|---------|------------|
| 합성곱 신경망 (CNN) | 10               | 7       | 70         |
| 심층신경망 (DNN)   | 10               | 6       | 60         |

## 결론
본 프로젝트를 통해 분리수거 분류를 위한 인공지능 모델 개발의 필요성과 효과를 확인할 수 있었습니다. 앞으로 이러한 기술을 활용하여 환경 보호에 기여할 수 있는 방안을 모색할 계획입니다.
