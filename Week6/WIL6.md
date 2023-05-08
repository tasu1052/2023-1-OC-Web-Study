지난 주 복습
CSS:Cascading Style Sheet
ul:unordered list
ol:ordered list
tr:table row
td:table data

cascading
상속 우선 순위
document object model?
스타일 시트 안에 브라우저 기본 스타일 사용자 스타일
사용자 스타일 안에 인라인 내부스타일 시트, 외부 스타일 시트있음
우선순위 순서
1.사용자 스타일(컴퓨터 사용자)
2.제작자 스타일(개발자)
3.브라우저 기본 스타일
IF 서열이 같다면?
->세부 우선순위 순서
1.!important
2.인라인 스타일 <-중요->줄 안에 썼다고 해서 인라인 스타일
3.id 스타일(하나만 사용가능)
4.클래스 스타일(중복 사용 가능)
5.타입 스타일
selector를 통해 지정가능

id 셀렉터(선택자)
클래스 셀렉터
타입 셀렉터
전체 셀렉터
!important는 property에만 붙임<-다른 서열을 싹 다 무시함.

이번 주 주제
Box model과 FLEX Box

박스의 테두리->Border

박스의 종류
1.블록 레벨요소
2.인라인 레벨요소
블록 레벨 요소->한 줄을 차지하는 박스
<div>, <p>, <h5>등등
인라인 레벨 요소->자신만을 감싸는 박스
<strong>,<span> 등
box model
margin 안에
border 안에
padding 안에
content

padding->content와 border 사이의 간격
margin->테두리와 다른 요소 사이의 여백(간격)

border 종류 여러개 있지만 None, Solid 두 개를 가장 자주 쓴다.

FLEX Box Layout
Flexible Box Layout
아이템이 배열될 방향인 주축을 정할 수 있다.
주축과 수직한 축을 Cross Axis라고 부른다.
main axis:column
cross axis:row

justify-content:main axis
align-item:cross axis

더 알아보면 좋을 것들
1.css grid layouts
2.can I use?


1단계 답:justify-content: flex-end;
2단계 답:justify-content: center;
3단계 답:justify-content:space-around;
4단계 답:justify-content:space-between;
5단계 답:align-items:flex-end;
6단계 답:justify-content: center; align-items: center;
7단계 답:justify-content: space-around; align-items: flex-end;
8단계 답:flex-direction: row-reverse;
9단계 답:flex-direction: column;
10단계 답:flex-direction: row-reverse; justify-content: flex-end;
11단계 답:flex-direction: column; justify-content: flex-end;
12단계 답:flex-direction: column-reverse; justify-content: space-between;
13단계 답:flex-direction: row-reverse; justify-content: center; align-items: flex-end;
18단계 답:flex-wrap: wrap;
19단계 답:flex-direction: column; flex-wrap: wrap;
20단계 답:flex-flow: column wrap;