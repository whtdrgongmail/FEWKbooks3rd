# FEWKbooks

**FEWK; Far East White Kingdom** — Universe Setting Project since 2021.10.31 by Universe Designer **WhtDrgon** (Kim Dongeun).

This repository hosts the online reader sample for the **3rd edition** of FEWK — both the Core Rulebook (106 chapters, 15 parts) and the World Book (170 chapters, 12 parts). The site is a single-page vanilla HTML/CSS/JS application, designed to be served statically (GitHub Pages).

---

## 읽어보기 / Read Online

- Live site: `https://whtdrgon.github.io/FEWKbooks/` *(pending deploy)*

## 구조 / Structure

```
FEWKbooks/
├── index.html            # SPA entry (light/dark toggle, search, mailto feedback)
├── content/
│   ├── home.md           # FEWK 소개 · 마스터 연혁
│   ├── roadmap.md        # 출판 이후 로드맵
│   ├── license.md        # FWOL v1.0 전문
│   ├── corerulebook/     # Core Rulebook 3rd (122 files)
│   └── worldbook/        # World Book 3rd (228 files)
├── assets/               # CSS · JS · images
├── scripts/convert.py    # 편집본 → 독자용 샘플 변환기
├── LICENSE               # MIT (code)
└── README.md
```

## 라이선스 / License — 2층 구조

이 리포는 **이중 라이선스**를 적용합니다:

| 대상 | 라이선스 | 파일 |
|---|---|---|
| **코드** (index.html, CSS/JS, scripts/convert.py) | [MIT License](LICENSE) | `LICENSE` |
| **FEWK 세계관 콘텐츠** (`content/` 아래 모든 원고) | FWOL v1.0 | [content/license.md](content/license.md) |

- **IP 소유**: 김동은 Kim Dongeun (활동명 하얀용 / WhtDrgon) 개인
- **생산 기술**: MEJE Works Corp. 소유의 "세계관 관리 프로세스" 기술 활용

2 차 창작·팬 창작은 FWOL v1.0 의 범위 안에서 허용됩니다. 상세는 `content/license.md` 참조.

## 피드백 / Feedback

오탈자·규칙 모순·번역 제안 등은 사이트의 우측 하단 "편집자에게 한마디" 버튼에서 메일로 전송하거나, 직접 **whtdrgon@gmail.com** 로 보내주세요.

## 로컬 실행 / Run Locally

```bash
cd FEWKbooks
python3 -m http.server 8080
# 브라우저에서 http://localhost:8080/ 열기
```

## 링크 / Links

- Twitter/X: [@게임기획자하얀용](https://twitter.com/게임기획자하얀용)
- 2022 NFT 콜라보 보도: [머니투데이 기사](https://www.mt.co.kr/stock/2022/07/27/2022072715530622171)
- 2024.6 KEITI편 시범 펀딩: [tumblbug.com/fewkop](https://tumblbug.com/fewkop)

---

© 2021–2026 Kim Dongeun (WhtDrgon). Worldbuilding process technology © MEJE Works Corp.
