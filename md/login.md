# 3주차 과제

<br>

[LogIn](https://wnsrl7250.github.io/homework/login/login.html)

## Issue

**`마크업`**

- 아이디와 비밀번호는 필수 입력 서식임을 알 수 있도록 구현할 것

  - `required`속성을 사용해서 해당 필드가 필수 입력임을 나타냈다.

- 로그인 상태 유지와 IP 보안 ON/OFF UI는 마우스 이외에 `키보드로도 조작 가능`하도록 구현할 것

  - `tabindex`를 사용해서 포커스를 받을 수 있도록 했다.

**`스타일링`**

- 미디어 쿼리를 사용하여 반응형으로 구현할 것(768px 미만 모바일 / 768px 이상 데스크탑)
- 모바일 퍼스트로 스타일링 할 것
  (공통 스타일과 모바일 스타일을 먼저 구현한 후 데스크탑 스타일을 재정의)

  - `@media (min-width: 768px)`로 화면 너비가 768px 이상일 때 적용되는 스타일을 정의 했다.

- 모바일 환경에서 IP 보안 ON/OFF 스위치 UI는 사용자에게 제공되지 않도록 구현할 것

  - `display : none`으로 모바일 환경에서 보이지 않도록 처리했다.
  - 미디어 쿼리를 사용하여 화면 너비가 768px 이상일 때 `display:block`으로 보이도록 했다.

- 로그인 상태유지 체크박스 배경 이미지 및 크기와 여백은 다음과 같이 지정할 것

  `선택안함` : `unchecked.svg` (제공한 `<svg>` 코드를 활용하여 이미지로 저장하여 사용)

  `선택함` : `checked.svg` (제공한 `<svg>` 코드를 활용하여 이미지로 저장하여 사용)

  - 기본 체크박스 UI를 `display : none`으로 숨겼다.
  - `checkbox-label`에 `cursor : pointer`로 사용자가 클릭할 수 있는 요소임을 나타냈다.
  - `checkbox-img`에 `background-image: url("./../../assets/login/unchecked.svg");`로 기본(체크되지 않은) 상태의 이미지를 설정했다.
  - `.checkbox:checked + .checkbox-label .checkbox-img { background-image: url("./../../assets/login/checked.svg"); }`로 체크박스가 체크된 상태의 이미지를 설정했다.

## 아쉬운점

html을 배운대로 해보려니 생각보다 많이 어려웠다. 마크업을 어떻게 구성할지 css를 어떻게 적용시켜야 할지도 막막했다. 기억이 잘 나지 않아서 실습했던 내용들을 뒤져가며 해결하기 위해 노력했다. 아직도 이게 잘 작성된 마크업인지 css인지 모르겠다. 복습을 제대로 해야겠다....<br>
`feedback-message`를 `input`을 눌렀을 때 아래에 나오게 하고 싶었는데 css로는 어떻게 해야할지 모르겠다....<br>
