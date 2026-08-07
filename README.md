# UihwanLee.github.io

| 경로 | 내용 |
|---|---|
| `/` | 클라이언트 개발 포트폴리오 (2026) — `index.html` 단일 파일 |
| `/2022/` | 이전 React 포트폴리오 (2022) |

## 구조 메모

`2022/index.html` 은 CRA 빌드물이라 에셋을 절대경로(`/static/...`)로 참조한다.
그래서 `static/`, `favicon.ico`, `manifest.json`, `logo*.png`, `asset-manifest.json` 은
**루트에 그대로 둬야 한다**. 옮기면 2022 페이지가 빈 화면이 된다.
