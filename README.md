# 두넌체

[배포처 바로가기](https://thxbroo.tistory.com/m/8)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `Donoun`입니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/Donoun/Donoun.css" type="text/css"/>
```

### CSS `@Import`

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/Donoun/Donoun.css');
```

### CSS `@font-face`

```css
@font-face {
    font-family: 'Donoun';
    font-weight: normal;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/Donoun/Donoun.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/Donoun/Donoun.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/Donoun/Donoun.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/Donoun/Donoun.ttf') format('truetype');
}
```

&nbsp;

## 다이나믹 서브셋

웹폰트의 최적화를 위해 모던 브라우저에서는 글리프를 여러개로 나누어 필요한 부분만 동적으로 파싱하는 다이나믹 서브셋을 제공합니다. 폰트의 용량이 부담된다면 아래 코드를 사용하는 걸 추천합니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/Donoun/subsets/Donoun-dynamic-subset.css" type="text/css"/>
```

### CSS

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/Donoun/subsets/Donoun-dynamic-subset.css');
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.



```css
font-family: "Donoun", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
1. '두넌체'는 무료 폰트입니다. 판매하는 것 외엔 모두 가능합니다. 
개인 및 기업 사용자를 포함한 모든 사용자에게 상업적인 용도로 무료 제공되며, 자유롭게 사용하실 수 있습니다. 
(영상매체, 인쇄매체, 웹, 모바일 등 다양한 매체에 자유롭게 사용이 가능합니다.) 
2. 단 사용자가 폰트를 수정하거나/변형하여 재배포/판매할 수 없습니다. 
3. '두넌체'를 사용한 인쇄물, 광고물(온라인 포함)의 이미지가 있다면 저는 좋아서 자랑할겁니다.
```
