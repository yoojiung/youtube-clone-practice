# youtube clone

## wireframe
web사이트를 만들기 전에 전반적인 디자인구조를 잡는 일

***

## HTML 빠르게 마크업하기
```
header+section.player+section.info+section.upnext
```
강사님은 위 같은 코드로 빠르게 \<body> 를 채웠다  

***

## color picker
color picker를 이용하면 웹사이트에 사용된 색상을 확인할 수 있다 

***

## root
```
:root {
  /* color */
  --white-color:#fff
  --black-color:
  --blue-color:
  /* size */
  --side-padding:12px;
  --avator-size:36px;
  /* font size */
  --font-large : 18px;
  --font-medium : 14px;
  --font-small : 12px;
  --font-micro : 10px;
}
```
root값 사용
```
padding: var(--side-padding);
```
root를 이용해서 일정한 디자인을 유지할 수 있다

***

## *
```
* {
  padding : 0;
  margin: 0;
  box-sizing: border-box;
}
```
전역속성 선택자를 사용해서 값을 지정해주었다

***

## button 처리
```
button,
button:focus {
  border: none;
  cursor: pointer;
  outline: none;
}
```
기본으로 속성되어있는 값을 빼주어야 디자인적으로 좋음

***

## css line clamp
```
.metadata .titleAndbutton span {
  font-size: var(--font-large);
  width: 300px;
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-line-clamp: 3;
  overflow: hidden;
}
```
구글에서 css line clamp mdn을 이용해서 반응형을 위해 라인을 넘치는 것을 방지

***

## img 크기조절
width , height 를 이용해서 정리

***


