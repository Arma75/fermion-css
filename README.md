# fermion-css
"눈에 잘 보이는 디자인"을 지향하는 no class css 라이브러리입니다.

## File structure diagram
```
/fermion-css                    <-- 프로젝트 루트 디렉토리
├── css                         <-- CSS 파일 디렉토리
│   ├── fermion.css             <-- 사용자가 링크할 최종 라이브러리 파일
│   └── src                     <-- 라이브러리 스타일을 구성하는 private 소스 파일
│       ├── _layout.css         <-- 문서 구조 및 레이아웃 관련 스타일
│       └── _reset.css          <-- 모든 태그의 기본 스타일 초기화
│
├── examples                    <-- 라이브러리 예제 페이지 디렉토리
│
└── README.md                   <-- 프로젝트 설명 및 사용 안내
```

### _reset
```css
@import url('https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100..900;1,100..900&display=swap');

* {
    font-family: "Roboto", sans-serif;
    font-size: 16px;
    font-weight: normal;
    line-height: 1.5;

    box-sizing: border-box;
    padding: 0;
    margin: 0;
    text-decoration: none;

    appearance: none;
    outline: none;
    box-shadow: none;
}
```

!issue
fermion CSS를 적용하면서 디자인을 체크할만한 페이지와 컴포넌트들이 필요하다.
