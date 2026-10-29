# 📸 WordSnap (워드스냅) - 나만의 스마트 영어 단어장

> **사진 한 장으로 완성하는 나만의 영어 연습장**  
> 단어장 사진을 찍으면 AI가 단어와 뜻, 품사를 자동으로 추출하고, 캘린더 복습과 플래시카드 암기 테스트까지 제공하는 웹 애플리케이션입니다.

👉 **웹사이트 바로가기**: [https://diddbcks0728-ship-it.github.io/wordsnap/](https://diddbcks0728-ship-it.github.io/wordsnap/)

---

## ✨ 주요 기능

1. **📷 AI 이미지 단어 자동 추출**
   - 단어장이나 책, 사전 페이지 사진을 올리면 AI가 표제어 영어 단어, 대표 한국어 뜻, 품사를 자동으로 인식하여 목록을 생성합니다.
   - 고해상도(2048px) 처리로 작은 글씨도 빠짐없이 인식합니다.

2. **📅 날짜별 복습 캘린더**
   - 일자별로 학습한 단어 개수를 한눈에 확인하고, 날짜별 복습 또는 선택 날짜까지의 누적 복습 테스트를 실행할 수 있습니다.

3. **🃏 스마트 플래시카드 학습**
   - '외웠어요' / '다시 보기' 인터랙션을 통해 모르는 단어만 반복해서 복습하는 효율적인 암기 시스템을 제공합니다.

4. **☁️ 실시간 클라우드 자동 동기화**
   - 로컬 브라우저 저장소뿐만 아니라 Supabase 클라우드에 자동 동기화되어 모바일과 PC 등 여러 기기에서 학습 내용을 그대로 이어갈 수 있습니다.

5. **📱 PWA (Progressive Web App) 완벽 지원**
   - 모바일(iOS Safari / Android Chrome) 및 데스크톱에서 **"홈 화면에 추가"** 또는 **"앱 설치"**를 눌러 브라우저 주소창 없는 독립된 네이티브 앱처럼 사용할 수 있습니다.
   - 오프라인 캐싱 지원으로 인터넷 연결이 불안정해도 학습 기능을 이용할 수 있습니다.

---

## 🛠 기술 스택

* **Frontend**: HTML5, CSS3, Modern JavaScript (Vanilla JS, No Framework)
* **AI Engine**: Google Gemini 3.5 Flash Lite (`gemini-3.5-flash-lite`)
* **Cloud Database & Auth**: [Supabase](https://supabase.com/) (PostgreSQL & Anonymous Auth)
* **Hosting**: GitHub Pages

---

## 🚀 빠른 시작 (Local)

별도의 빌드나 의존성 설치 없이 브라우저에서 바로 실행할 수 있습니다.

```bash
git clone https://github.com/diddbcks0728-ship-it/wordsnap.git
cd wordsnap
open index.html
```
