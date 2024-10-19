# 4주차 과제

<br>

[Apple](https://wnsrl7250.github.io/homework/apple/apple.html)

## Issue

**스타일링**

- `CSS Grid`를 사용하여 **반응형 레이아웃**을 구현한다.

  - `display: grid`를 사용하여 Grid 레이아웃을 구현했다.
  - `card-small-grid`에 `@media (min-width: 1024px)`로 1024px 이상일 때 `grid-template-columns: repeat(2, 1fr)`를 주어 아래 네개의 상품을 반응형 레이아웃으로 구현했다.
  - 미디어쿼리를 사용하여 1024px 이상일 때 `padding`, `font-size`, 이미지가 바뀌도록 구현했다.

- 디바이스의 `픽셀 밀도`에 따라 1배율 또는 2배율 이미지가 배경으로 반영되도록 한다.

  - `background-image: image-set(url(./../products/ipad_air.jpeg) 1x,url(./../products/ipad_air_2x.jpeg) 2x` 로 디바이스의 픽셀 밀도에 따라 1배율 또는 2배율 이미지가 적절하게 반영되도록 했다.

- 같은 `card`이지만 글자 색과 버튼의 색이 다른걸 반영하기 위해 `:nth-child(odd/even)`을 사용하여 홀수번째 상품과 짝수번째 상품의 다른 스타일을 구현했다.

- Large Screen에서 `--extra-large-spacing`를 적용했을 때 상품 이미지와 버튼이 겹쳐서 상단 여백은 미디어 쿼리를 적용하지 않았습니다.

## 결과

<p align=center>
  <img src="./../assets/apple/apple-screen.gif" width="500">
</p>

## 아쉬운점

화면을 구현하고 나서 css코드를 봤을때 뭔가 반복되는 내용이 많다고 느꼈다. 여전히 내 코드에 대한 자신이 없다. 어떻게 하면 더 효율적인 코드를 작성할수 있을지 고민이 된다.
