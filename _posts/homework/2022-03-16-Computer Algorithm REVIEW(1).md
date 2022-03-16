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

![](https://postfiles.pstatic.net/MjAyMTA0MjBfMTk1/MDAxNjE4OTIyMzk0MTgy.j2_O_rezeM6d-n2smkdQN1QZSEiTUaGzza8GJJ5c34gg.bOmTpWBXxOiz6YtkkNTelZQ_kXTEeRyM5-bpsZaGTdog.PNG.010203sj/10.PNG?type=w773)

***Ω(오메가)(점근적 하한)***

알고리즘이 이것보다 나쁘거나 같음

n이 높을수록 성능이 좋음

즉 Ω(n)보다 Ω(n^2)이 성능이 좋고 그보다 Ω(n^3)이 성능이 좋다

***Θ(세타)***

O와 Ω의 접점이 Θ 라고 볼 수 있다

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

간단히 git 과 터미널을 이용해 업데이트 할 수 있다.

```
git add . //변경된 파일 추가
git commit -m "update" //변경된 파일 확정
git push //변경된 파일을 원격 서버에 업데이트
```

