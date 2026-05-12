# 🗳️ 전자투표 시스템

Firebase Realtime Database 연동 · 실시간 다중 사용자 투표 시스템

**🔗 라이브 주소:** `https://<내-깃허브-아이디>.github.io/<저장소-이름>/`

---

## 📁 파일 구성

| 파일 | 설명 |
|------|------|
| `index.html` | 투표 시스템 본체 (단일 실행 파일) |
| `voting-guide.html` | 사용 설명서 |

---

## 🚀 사용 방법

1. 위 **라이브 주소** 접속
2. Firebase Database URL 입력:
   ```
   https://voting-9aa78-default-rtdb.asia-southeast1.firebasedatabase.app
   ```
3. 관리자 비밀번호 입력 후 **연결하기**
4. 🔒 버튼 → 관리자 탭에서 후보자 등록 → 투표 시작

---

## ⚙️ 기능

- 🗳 **투표하기** — 유권자 ID 입력 → 후보자 선택 → 1인 1표 (중복 방지)
- 📊 **실시간 결과** — 3초마다 자동 갱신, 득표 막대 그래프
- ⚙️ **관리자** — 후보자 추가/삭제, 투표 시작/종료, 초기화, 투표자 명단

---

## 🔥 Firebase 정보

- **프로젝트:** voting-9aa78
- **DB URL:** https://voting-9aa78-default-rtdb.asia-southeast1.firebasedatabase.app
- **규칙:** read/write: true (테스트용)
