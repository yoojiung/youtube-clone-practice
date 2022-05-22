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