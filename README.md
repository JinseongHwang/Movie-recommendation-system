# Movie-recommendation-system

<br>

**[블로그](https://blog.naver.com/PostList.nhn?blogId=eddy5360&from=postList&categoryNo=42)에서 이 프로그램을 만들기 위한 개념들을 공부하며 정리하고 있습니다.**

<br>

## 프로그램 소개

```
사용자가 영화를 보고난 후 평가한 점수를 기반으로, 취향을 분석하는 모델을 만들어서 영화를 추천하는 프로그램입니다.
```

<br>

## 프로그램 도식화

![개요-도식화](https://user-images.githubusercontent.com/52629158/107345977-811c7100-6b07-11eb-8fc3-11b6984b8e4c.jpg)

**Step 1**

- Collaborative Filtering 방식으로 가장 기본적인 취향 모델 알고리즘을 작성한다.

**Step 2**

- 작성한 모델을 Application Server에 올려서 잘 작동하는지 확인한다.

**Step 3**

- 기존의 모델을 Machine Learning을 활용한 Matrix Factorization(MF) 방식을 사용한 모델로 변경한다.

**Step 4**

- Batch와 DB를 연동해서 작동 테스트를 진행한다.

<br>

## 테스트 데이터 출처

[movielens](https://grouplens.org/datasets/movielens/)에서 영화 평가 데이터(.csv)를 가져온다.