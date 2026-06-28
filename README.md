# 글자 수 세기 (Character Counter)

텍스트를 붙여넣으면 글자 수를 즉시 카운트하는 무료 온라인 도구.
공백 포함/제외 글자 수, 단어·문장·줄 수, UTF-8 바이트 수까지 실시간으로.

🔗 **바로 쓰기**: https://hanariago.github.io/tool-char-counter/

> 한국어 · English · 日本語 · 中文 · Español 지원

## 기능
- 공백 포함 / 공백 제외 글자 수
- 줄 수 · 단어 수 · 문장 수
- UTF-8 바이트 수 (한글 약 3바이트, 영문 1바이트)
- 이모지·특수문자도 코드포인트 단위로 정확히 1자 계산
- 실시간 카운트 (입력 즉시 반영)
- 5개 언어 지원 + 브라우저 언어 자동 감지
- 초기화 버튼

## 사용법
페이지를 열고 텍스트 영역에 글을 붙여넣으면 끝. 입력 즉시 모든 수치가 갱신됩니다.
우측 상단에서 언어를 바꾸거나 `?lang=en` 처럼 URL 파라미터로 언어를 지정할 수 있습니다.

## 기술 스택
- 순수 HTML/CSS/JS (외부 라이브러리 없음, 단일 파일)
- 서버 전송 없음 (모든 계산이 브라우저에서만 동작)
- GitHub Pages 호스팅

## 검색/노출
- SEO 메타 + Open Graph + Twitter Card
- JSON-LD 구조화 데이터 (`WebApplication`)
- `robots.txt`, `sitemap.xml`, AI 검색용 `llms.txt`
- 다국어 `hreflang`

## 라이선스
[MIT License](LICENSE) — 자유롭게 사용·수정·배포 가능. 자세한 내용은 `LICENSE` 파일 참조.

---
Made by [Lena](https://x.com/thezenvoid) · License: MIT
