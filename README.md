# 함박눈체

[배포처 바로가기](https://blog.naver.com/snowfrost001/221708816790)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `SF Hambak Snow`입니다.

### HTML

```html
<link
  rel="stylesheet"
  href="https://cdn.jsdelivr.net/gh/fonts-archive/SFHambakSnow/SFHambakSnow.css"
  type="text/css"
/>
```

### CSS `@Import`

```css
@import url("https://cdn.jsdelivr.net/gh/fonts-archive/SFHambakSnow/SFHambakSnow.css");
```

### CSS `@font-face`

```css
@font-face {
  font-family: "SF Hambak Snow";
  font-weight: normal;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/fonts-archive/SFHambakSnow/SFHambakSnow.woff2")
      format("woff2"), url("https://cdn.jsdelivr.net/gh/fonts-archive/SFHambakSnow/SFHambakSnow.woff")
      format("woff"),
    url("https://cdn.jsdelivr.net/gh/fonts-archive/SFHambakSnow/SFHambakSnow.ttf")
      format("truetype");
}
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.

```css
font-family: "SF Hambak Snow", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto,
  Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
-라이센스-

개인용, 상업용 모두 사용 가능

2차 수정 및 배포 가능

영리 목적의 판매를 금합니다

자세한 내용은 https://blog.naver.com/snowfrost001/222287054506 참고
```
