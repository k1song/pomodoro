# 🍅 Pomo — 감성 포모도로 타이머

아름다운 디자인의 웹 포모도로 타이머. 접속 즉시 1클릭으로 집중을 시작하세요.

🌐 **Live Demo**: [pomodoro-k1song.pages.dev](https://pomodoro-k1song.pages.dev)

---

## Features

### ⏱ 타이머
- 집중 / 휴식 모드 탭 전환
- 타이머 링 안에서 직접 시간 편집 (▲▼ 버튼 + 직접 입력)
- MIN에 60 이상 입력 시 자동으로 HR/MIN 변환
- 시작 전 5초 카운트다운
- 일시정지 / 종료 제어

### ⏰ 세션 종료 후
- 타이머 종료 후 초과 시간 자동 카운트 (+00:01, +00:02...)
- 초과 수행 시간도 오늘의 집중 시간에 포함
- **계속하기**: 알람 종료 후 초과 시간 유지하며 집중 지속
- **종료**: 다음 세션으로 전환

### ✅ 할 일 (Tasks)
- 입력란에 task 입력 후 Add 또는 Enter로 추가 (최대 10개)
- 항목 클릭으로 선택 → 집중 세션 완료 시 자동 완료 처리
- ✎ 수정 버튼으로 내용 편집, ✓ 또는 Enter로 저장
- ⠿ 핸들 드래그로 순서 변경
- × 클릭 시 삭제 확인 후 제거
- 새로고침 후에도 데이터 유지

### 🔔 알람
- **알람 알림**: 세션 종료 시 브라우저 팝업 알림 on/off
- **알람 소리**: 세션 종료 시 1분간 알람음 on/off
- **소리 종류 5가지**: Gentle Bell · Tibetan Bell · Harp Arpeggio · Guitar Harmonic · Aurora

### 🎨 뷰어 & 사운드
- **테마 8가지**: Lofi · Sunset · Forest · Galaxy · Yellow · Vivid · Rainbow · Dawn
- **글씨 크기**: 1~5단계 조절
- **배경 사운드**: 빗소리 · 카페 · 모닥불 · 파도 · 바람 (타이머와 독립적으로 항상 재생)
- **음소거**: 🔊 버튼 또는 M 키로 배경음 즉시 음소거/해제
- **전체화면** / **숫자 가리기** (타이머 실행 중 자동 숨김)

### 📊 통계
- 오늘의 완료 세션 수 🍅
- 오늘의 총 집중 시간 ⏱ (초과 시간 포함)
- 자정마다 자동 초기화

### 🌐 기타
- 3개 국어 지원 (한국어 · English · 中文)
- 반응형 디자인 (모바일 지원)
- 💾 모든 설정 자동 저장 (localStorage)

---

## Keyboard Shortcuts

| 키 | 기능 |
|---|---|
| `Space` | 시작 / 일시정지 |
| `F` | 전체화면 전환 / 해제 |
| `H` | 숫자 가리기 on/off |
| `M` | 배경음 음소거 / 해제 |

---

## Getting Started

`index.html` 파일 하나로 동작합니다. 별도 설치가 필요 없습니다.

```bash
# 로컬에서 열기
open index.html

# 또는 간단한 서버로 실행
npx serve .
```

## Deploy

Vercel, Netlify, GitHub Pages, Cloudflare Pages 등에 바로 배포 가능합니다.

## Tech Stack

- Vanilla HTML / CSS / JS (프레임워크 없음)
- Web Audio API (알람 사운드 5종 + 배경 사운드 5종)
- Web Notifications API
- Google Fonts (Outfit, Noto Sans KR/SC)

## License

MIT
