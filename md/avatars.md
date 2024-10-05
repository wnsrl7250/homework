# 2주차 과제

- 아바타 이미지는 배경 방식이 아닌 콘텐츠 이미지(<img> 요소)로 마크업한다.
- 아바타 이미지의 크기 - 64px X 64px
- `margin: 10px`로 아바타 이미지 간의 간격 - 20px
- user의 online/offline을 표시하기 위해 `background-color: #dbdbdb` / `background-color: #4cfe88`로 설정
- span에 `position: absolute`를 적용하고 부모요소에 `position: relative`를 적용하여 user의 상태 표시 정보를 배치

## float을 사용하여 다음의 레이아웃을 구현해 본다.

- `overflow: hidden`을 적용해서 부모 요소를 넘어가는 자식 요소 부분을 안보이게 처리
- `float: left`를 사용하여 이미지를 왼쪽으로 정렬
- `class="line"`에 `clear : left`로 플로트된 요소들을 정리하여 다음 요소가 새로운 줄에서 시작하도록 함

<hr>

## flex를 지원하는 환경에서는 다음과 같이 배치되도록 레이아웃을 구현해 본다.

- `display: flex`를 사용하여 플렉스 레이아웃을 적용
- `justify-content: start`로 자식 요소들을 시작 지점(왼쪽)에서부터 정렬
