## 📌 사용기술

- HTML
- CSS

## 📌 데모 링크

https://jocular-gelato-04ea3b.netlify.app/

## 📌 강의내용 정리

### Position속성에 값들🎈 

- **static** : 웹사이트의 기본 속성값 , top right bottom left 등 위치 속성은 무시됨.

- **relative**: HTML태그가 있는 위치에서 left right top bottom값을 통해 움직임 (요소가 위치한 기준에서 옮김)

- **absolute**: 부모영역에서  left right top bottom 을 이용해 주어진 위치로 움직임(부모 절대값 기준으로 옮김)

  <p style="color:red">
  * 단! 여기서 부모란?: 부모 태그가 relative, absolute, fixed 속성 중 하나여야 함. 만약 부모태그가 해당 속성을 가지고있지 않다면 body태그 기준으로 움직임 왜냐하면 body태그는 relative를 기본 속성으로 가지고 있기 때문이다 
  </p>

- **fixed** : absolute와 비슷하지만 스크롤로 내려도 그 위치에 고정, 무조건 브라우저 창 기준임

- **Sticky** : relative와 비슷하지만 스크롤로 내리면 fixed처럼 그 위치에 고정 

### flexbox 의 특징!🎊

- **display**: flex는 모든 요소를 가로로 둔다 

- **display**: flex는 부모한테 적용을 하고 자손을 건트롤 한다.

- **justify-content** :가로로 요소들을 움직인다 (flex-start, center, flex-end, space-between, space-around 등의 값이 있음)

- **align-items**: 세로로 요소들을 움직인다  

- **flex-direction**:column 가로로 정렬된 요소를 세로로 바꾸고 justify-content는 세로로 align-items는 가로방향으로 바뀐다 

👉🏻[flexbox연습하는 웹사이트🐸](https://flexboxfroggy.com/#ko)