# 고신고딕 GoshinGothic

**따옴표를 다듬은 한국어 고딕체**

고신고딕은 [프리텐다드(Pretendard)](https://github.com/orioncactus/pretendard)를 기반으로, 신문 편집에 자주 쓰이는 특수기호·한자 자형을 전통적인 출판 관행에 맞게 수정한 오픈소스 폰트입니다. 고려대학교 학보사 [고대신문](https://kunews.ac.kr) 디자인 시스템의 일부로 개발되었습니다.

> 📖 **[소개 페이지 바로가기 →](https://kunews.github.io/GoshinGothic/)**

---

## ✨ 주요 변경 사항

### 1. 둥근 따옴표

프리텐다드의 곧은 따옴표를 **한눈에 구별할 수 있는 둥근 모양**으로 교체했습니다.

<p align="center">
  <img src="docs/img/quotes.png" alt="둥근 따옴표 자형 비교" width="600">
</p>

### 2. 가운데에 붙는 말줄임표

기준선에 위치하던 말줄임표(…)의 위치를 **글자 가운데로 옮겨** 가독성을 높였습니다.

<p align="center">
  <img src="docs/img/ellipsis.png" alt="말줄임표 위치 비교" width="600">
</p>

### 3. 화살괄호형 부등호

수학 기호 형태의 부등호(<>)를 **화살괄호처럼 보이도록 재설계**했습니다. 기사에서 부등호를 화살괄호 대신 사용하는 관행을 반영했습니다.

<p align="center">
  <img src="docs/img/greater-less than-sign.png" alt="부등호 자형 비교" width="600">
</p>

### 4. 한자 글리프 추가

[Noto Sans Korean](https://fonts.google.com/noto/specimen/Noto+Sans+KR)에서 한자 글리프를 가져와 보완했습니다.

---

## 🔤 웨이트

| 웨이트 | font-weight |
| --- | --- |
| Regular | 400 |
| SemiBold | 600 |
| Bold | 700 |
| ExtraBold | 800 |

---

## 📥 다운로드

최신 파일은 GitHub Releases 페이지에서 받으세요.

---

## 📦 파일 구성

```
├── src/              # FontForge 소스 파일 (.sfd)
├── release/          # 배포용 ZIP 및 글꼴 형식에 따른 배포 파일
├── docs/             # 소개 페이지 (GitHub Pages)
├── FONTLOG.txt       # 변경 이력
└── LICENSE           # SIL Open Font License 1.1
```

---

## 🌐 웹폰트로 사용하기

### CSS `@font-face`

```css
@font-face {
  font-family: 'GoshinGothic';
  font-weight: 400;
  font-style: normal;
  src: url('GoshinGothic-Regular.woff2') format('woff2'),
       url('GoshinGothic-Regular.woff')  format('woff');
}

@font-face {
  font-family: 'GoshinGothic';
  font-weight: 600;
  font-style: normal;
  src: url('GoshinGothic-SemiBold.woff2') format('woff2'),
       url('GoshinGothic-SemiBold.woff')  format('woff');
}

@font-face {
  font-family: 'GoshinGothic';
  font-weight: 700;
  font-style: normal;
  src: url('GoshinGothic-Bold.woff2') format('woff2'),
       url('GoshinGothic-Bold.woff')  format('woff');
}

@font-face {
  font-family: 'GoshinGothic';
  font-weight: 800;
  font-style: normal;
  src: url('GoshinGothic-ExtraBold.woff2') format('woff2'),
       url('GoshinGothic-ExtraBold.woff')  format('woff');
}
```

### 적용 예시

```css
body {
  font-family: 'GoshinGothic', 'Pretendard', -apple-system, BlinkMacSystemFont, sans-serif;
}
```

---

## 🔧 빌드

소스 파일(`src/*.sfd`)은 [FontForge](https://fontforge.org/)에서 열 수 있습니다. 글리프를 수정한 뒤 OTF/TTF로 내보내면 됩니다.

---

## 📋 크레딧

| 역할 | 프로젝트 |
| --- | --- |
| **수정 및 배포** | [고대신문사](https://kunews.ac.kr) |
| **원본 폰트** | [Pretendard](https://cactus.tistory.com/306) |
| **한자 글리프** | [Noto Sans Korean](https://fonts.google.com/noto/specimen/Noto+Sans+KR) |

---

## 📄 라이선스

고신고딕은 **SIL 오픈 폰트 라이선스 1.1(OFL-1.1)** 하에 배포됩니다.

자세한 내용은 [LICENSE](LICENSE) 파일 또는 [https://openfontlicense.org](https://openfontlicense.org)를 참고하세요.