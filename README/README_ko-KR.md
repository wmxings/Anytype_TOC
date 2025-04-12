[中文](../README.md) | [English](README_en-US.md) | [日本語](README_ja-JP.md) | [한국어](README_ko-KR.md) | [Deutsch](README_de-DE.md) | [Русский](README_ru-RU.md) | [Français](README_fr-FR.md) | [繁體中文](README_zh-TW.md)

# Anytype 플로팅 목차

## 프로젝트 배경
2022년부터 Anytype 커뮤니티 사용자들은 플로팅 목차 기능 추가를 요청해 왔습니다. 안타깝게도 2025년 4월 현재까지 이 기능은 공식 개발 로드맵에 포함되지 않았습니다. 흥미롭게도, Anytype의 주요 경쟁사인 Notion도 이 기능 구현에 대해 적극적이지 않습니다.

## 솔루션
이 프로젝트는 커스텀 CSS를 사용하여 Anytype에 심플하고 우아한 플로팅 목차를 구현합니다. 이 솔루션은 커뮤니티 사용자 [@sandroid](https://community.anytype.io/t/custom-table-of-contents-custom-css/27360/8)의 접근 방식과 일치합니다.

설계 과정에서 sspai.com의 플로팅 목차 스타일을 참고했습니다. Anytype이 JS를 지원하지 않고 커스텀 CSS만 지원하는 제한에도 불구하고, 최종 결과물은 매우 훌륭합니다.

## 데모
![플로팅 목차 데모](../image/IMG_20250411_234639.gif)

## 기능
- 심플하고 우아한 플로팅 목차 레이아웃
- 페이지 스크롤에 따라 이동하는 목차로 편리한 내비게이션
- 목차 항목 호버 효과

## 사용 방법
1. Anytype을 열고 `파일 -> 열기 -> 커스텀 CSS`로 이동
2. `custom.css` 또는 `custom.min.css`의 내용을 `커스텀 CSS` 파일에 복사
3. Anytype을 재시작하여 변경사항 적용

## 참고사항
- 커스텀 스타일링이 필요한 경우 `custom.css`의 매개변수를 수정할 수 있습니다 