# Megabyte School HTML/CSS 연습

## 2022.04.18 정을수 강사님 HTML/CSS 강의
### 학습내용
1. 상황에 맞는 HTML 태그 사용
1. HTML 우선 순위 연습
```
<body>
  <div>
    <h1>네이버 캐스트</h1>
    <h2>오픈 캐스트</h2>
    <p>이것은 오픈 캐스트의 내용입니다.</p>
    <h3>게임 캐스트</h3>
    <p>이것은 오픈캐스트의 내용입니다.</p>
    <h3>자동차 캐스트</h3>
    <p>이것은 자동차캐스트의 내용입니다.</p>
    <h3>인테리어 캐스트</h3>
    <p>이것은 자동차캐스트의 내용입니다.</p>
  </div>
</body>

// 1. 네이버캐스트
//       1. 오픈 캐스트
//             1. 게임 캐스트
//             2. 자동차 캐스트
//             3. 인테리어 캐스트
```
---
## 2022.04.19 Javascript 특강
### 학습내용
1. 자바스크립트로 모달창 만들기
1. if문으로 인풋창 만들기
- trim과 일치연산자로 if문 구성하기
```
// trim 방식
if (!value.trim()) {
  alert("false!");
} else {
  alert("true!");
}

// 일치연산자 방식
if (value == 0) {
  alert("false!");
} else {
  if (value === " ") {
    alert("false!");
  } else {
    alert("true!");
  }
}
```