#### nav_bar note  
#### 마크업은 제대로된 시멘틱으로 구성하는 것부터 시작한다!!**
1. 그냥 div를 하지 말고 의미가 있는 시멘틱 마크업을 사용한다.   
  `nav, header,,,`

2. fontawesome을 사용한다. 
  `ex) accusoft`

3. 메뉴는 의미가 있는 list로 바꾸기  
   
4. 아이콘도 목록이 있는 항목이기 때문에 `ul` 사용

5. 스타일링을 할때는 가장 상위항목부터 시작해서 하위항목으로 꾸미기.    
  
6. 실제로 스타일 적용이 되는 엘리먼트에 스타일을 적용함 li.. a 이렇게 ..   
   
7. css 변수 지정
  - 너무 극단적인 하얀색과 검은색은 사용자에게 좋지 않기 때문에 어느정도 톤 다운 된 것을 사용한다. 

-----
  
#### 유튜브 클론 note  
1. 초반에 시작할 때.. 박싱은 너무 어렵지 않고 단순하게. 

2. 전반적으로 쓰이는 컬러 등 미리 변수로 지정하여 사용. 

3. css 전처리기 !! 
   
```
 sass & less => 
 postCSS => 리액트에서는 모듈화 해서 사용한다 
 => 순수 css를 하고 갈아타는게 좋다. 
```
  
   
4. 적용하고자 하는 범위를 최대한 작게 해서 지정한다. 

```
(1)아래처럼 지정하면 모든 ul 태그에 지정되기 때문에 
ul {
  list-style: none;
}

(2) 아래처럼 작은 단위로 지정하여 표현하기
.info .metadata .hashtags {
  display: flex;
  font-size: var(--font-small);
  color: var(--blue-color)
}
```
  
5. 말줄임을 아래처럼 적용하라고 도큐먼트를 참고할 수 있다. 

https://developer.mozilla.org/ko/docs/Web/CSS/-webkit-line-clamp

   
6. 화면을 크게 나누는 경우의 계획을 세우기@

화면 전환점에 flex direction을 적용하여 바꾼다.
  

7. 업데이트 하기. 
  
