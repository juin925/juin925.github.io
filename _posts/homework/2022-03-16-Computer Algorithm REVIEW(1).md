---
layout: post
date: 2022-03-16 18:19:01 +0900
title: "Computer Algorithm REVIEW(1)"
---

>>알고리즘을 점근적으로 분석하는 방법

***O(Big-Oh)(점근적 상한)***

알고리즘이 이것보다 좋거나 같음

n이 작을수록 성능이 좋음

즉 O(n^3) 보다 O(n^2)이 성능이 좋고 그보다 O(n)이 성능이 좋다

![](https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2FmzozV%2FbtqCDkBbnhF%2F6sx2a6ct1pBVdzQ7Esurj1%2Fimg.png)

**그림출처 https://atoz-develop.tistory.com/entry/%EC%95%8C%EA%B3%A0%EB%A6%AC%EC%A6%98-%EC%95%8C%EA%B3%A0%EB%A6%AC%EC%A6%98%EC%9D%98-%EC%84%A4%EA%B3%84%EC%99%80-%EB%B6%84%EC%84%9D-%EC%8B%9C%EA%B0%84-%EB%B3%B5%EC%9E%A1%EB%8F%84%EC%99%80-%EC%A0%90%EA%B7%BC%EC%84%B1%EB%8A%A5**

***Ω(오메가)(점근적 하한)***

알고리즘이 이것보다 나쁘거나 같음

n이 높을수록 성능이 좋음

즉 Ω(n)보다 Ω(n^2)이 성능이 좋고 그보다 Ω(n^3)이 성능이 좋다

![](https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2FcTD1Sn%2FbtqCz558nqN%2FXDURNI4wwIuq4Q0doH5kGK%2Fimg.png)

***Θ(세타)***

O와 Ω의 접점이 Θ 라고 볼 수 있다

![](https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2F0LfpM%2FbtqCBx8I85m%2FvwP3zSVUMB3k4Qqx3o95C1%2Fimg.png)

***그럼 어디까지 쓸만한 알고리즘일까?***

O(n^2) 보다 성능이 좋은 애들까지는 그래도 괜찮다고 볼 수 있다


>>우리의 생각과 개발을 공유하고싶을땐 git

**https://git-scm.com (git download 하는 곳)**

내가 컴퓨터 알고리즘 수업에서 지킬을 이용해 블로그를 만들었는데 많은사람이 봤으면 좋겠다. 그럴때 사용할 수 있는게 **git 과 github**이다.

나는 git 을 다운받고 hyper 라는 터미널을 이용해 my-awesome-site 에 접속하여 github와 연동시켜주었다. github와 연동시키는 방법은

```
git remote add origin "요구하는 주소"
git branch -M main
git push -u origin main
```

위를 터미널에 순서대로 작성하면 된다.

그럼 이제 다른 사람들이 내 블로그에 접속이 가능한데 내 블로그는 https://juin925.github.io/ 로 접속하면 된다.

***블로그 업데이트 내용을 업데이트 하고싶을때***

블로그 내용을 더 작성을 했는데 이걸 어떻게 다른 사람도 볼 수 있는 내 블로그에 업데이트를 할까 ?

간단히 **git 과 터미널**을 이용해 업데이트 할 수 있다.

```
git add . //변경된 파일 추가
git commit -m "update" //변경된 파일 확정
git push //변경된 파일을 원격 서버에 업데이트
```

이외에도 git 용어 정리

* `git init [directory]` : 초기화

* `git clone [repository]` : "복제" 원격 저장소에 있는 것을 가져온다 : 협업할때 필요

* `git pull` : github 다운로드 - 원격저장소에 있는 것을 로컬저장소로 내려받음

* `git status` : 변경된 파일이 있는지 검사함

* `git log` : 현재 브랜치의 커밋 이력을 보여줌

* `git branch` : 현재 위치한 브랜치 확인

* `git checkout "a"` : a 브랜치로 이동

* `git reset` : 시점 되돌리기

이것으로 2주차 컴퓨터 알고리즘 리뷰를 마친다

**p.s 제 블로그를 봐주시는 분들에게 아직 부족한 글쓰기 실력이지만 노력하겠습니다!**