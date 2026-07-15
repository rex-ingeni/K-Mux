<p align="center">
  <img src="icon.png" width="120" alt="K-Mux" />
</p>

<h1 align="center">K-Mux</h1>

<p align="center">
  <b>Claude Code · Codex CLI를 위한 macOS 데스크톱 앱</b><br/>
  <sub>CLI의 구조화 프로토콜을 앱 스타일 채팅으로 — 스트리밍 · 마크다운 · 툴 카드 · 컨텍스트 게이지</sub>
</p>

<p align="center">
  <img alt="platform" src="https://img.shields.io/badge/platform-macOS%20(Apple%20Silicon)-black" />
  <a href="https://github.com/rex-ingeni/K-Mux/releases/latest"><img alt="release" src="https://img.shields.io/github/v/release/rex-ingeni/K-Mux" /></a>
  <img alt="license" src="https://img.shields.io/badge/license-MIT-blue" />
</p>

---

## K-Mux란

K-Mux는 **Claude Code**와 **Codex** CLI를 감싸는 macOS 앱입니다. 두 CLI가 내보내는
구조화된 스트림 프로토콜을 파싱해, 터미널 로그가 아니라 **앱 스타일 채팅 UI**로 보여줍니다.
하나의 세션을 **터미널(TUI) 탭**과 **GUI 탭**으로 자유롭게 오갈 수 있습니다.

## 주요 기능

- 💬 **실시간 스트리밍 채팅** — 응답이 토큰 단위로 흐릅니다.
- 📝 **마크다운 · 링크 미리보기 · 코드 하이라이트** — 인라인 SVG 다이어그램도 바로 렌더링.
- 🧰 **툴 카드** — 셸 실행 · 파일 편집 · MCP 툴 호출을 접이식 카드로 정리.
- 📁 **작업 폴더 패널** — 생성·수정된 파일을 한눈에.
- 📊 **컨텍스트 게이지** — 남은 컨텍스트를 정확히 표시.
- 🔀 **터미널 ↔ GUI 전환** — 세션마다 실 PTY와 GUI를 오갑니다.
- 🔒 **승인 카드** — 샌드박스 밖 작업은 허용/거부를 물어봅니다.
- 🌗 **메뉴바 트레이** — 라이트/다크에 자동 적응하는 아이콘.
- ⬆️ **자동 업데이트** — 버튼 한 번으로 최신 버전 적용.

## 다운로드 & 설치

1. [**최신 릴리스**](https://github.com/rex-ingeni/K-Mux/releases/latest)에서
   `K-Mux-<버전>-arm64.dmg`를 받습니다. *(Apple Silicon / macOS)*
2. DMG를 열고 **`K-Mux.app`을 `Applications` 폴더로 드래그**한 뒤 실행합니다.

> 처음 실행 시 "확인되지 않은 개발자" 경고가 뜨면 **우클릭 → 열기**로 한 번만 허용하면 됩니다.<br/>
> *(함께 제공되는 `.app.zip`은 앱의 **자동 업데이트**가 사용하는 파일입니다 — 직접 받을 필요 없습니다.)*

## 자동 업데이트

새 버전이 올라오면 앱이 자동으로 감지합니다.

- 좌측 패널 하단의 **업데이트 확인** 버튼에 `● 업데이트 v0.1.x` 배지가 뜨거나,
  메뉴바 트레이 메뉴에 **업데이트 하기**가 나타납니다.
- 누르면 **다운로드 → 무결성 검증 → `.app` 교체 → 재실행**까지 전부 자동으로 진행됩니다.
  직접 압축을 풀거나 재설치할 필요가 없습니다.

## 요구 사항

- macOS (Apple Silicon)
- [Claude Code](https://claude.com/claude-code) 그리고/또는 Codex CLI 설치

---

<sub>이 저장소는 배포 · 소개 전용입니다 — <code>version.json</code> 매니페스트와 릴리스 바이너리만 두고 소스코드는 포함하지 않습니다.</sub>
