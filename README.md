<p align="center">
  <img src="assets/icon.png" width="120" alt="담담 AI Logo" />
</p>

<h1 align="center">담담 AI 🦫</h1>

<p align="center">
  <strong>1인 AI 콘텐츠 기업 · 나만의 에이전트 팀 · 제2의 두뇌</strong><br/>
  VS Code / Cursor 확장 프로그램으로, 담담의 AI 에이전트 팀이 24시간 콘텐츠를 함께 만듭니다.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/version-1.0.0-blue" alt="version" />
  <img src="https://img.shields.io/badge/license-MIT-green" alt="license" />
  <img src="https://img.shields.io/badge/brand-담담-purple" alt="brand" />
  <img src="https://img.shields.io/badge/engine-Ollama%20%7C%20LM%20Studio-orange" alt="engine" />
  <img src="https://img.shields.io/badge/mascot-🦫%20카피바라-brown" alt="mascot" />
</p>

---

## 🦫 담담(Damdam)이란?

**담담**은 1인 AI 콘텐츠 크리에이터 기업입니다. 회사 마스코트는 **귀여운 카피바라** 🦫.  
차분하지만 단단하게, 담담하게 콘텐츠를 만들어 나갑니다.

> **담담 AI**는 블로그, 뉴스레터, 인스타그램, 디자인, 리서치를 담당하는 AI 에이전트 팀이  
> 내 지식과 결정 로그를 컨텍스트로 삼아 24시간 자율적으로 일하는 워크스페이스입니다.

---

## 🤖 담담 에이전트 팀

| 에이전트 | 역할 | 전문 분야 |
|:--|:--|:--|
| **CEO 담담 🦫** | 공동 CEO | 전체 의사결정, 작업 분배, 콘텐츠 전략 방향 |
| **Instagram 📷** | Head of Instagram | 릴스/피드 기획, 캡션, 해시태그, 팔로워 인게이지먼트 |
| **인스타관리 📊** | Instagram 관리 AI | DM 응답 초안, 팔로워 분석, 댓글 관리, 성장 전략 |
| **Designer 🎨** | 담당 디자이너 | 브랜드 아이덴티티, 썸네일, 비주얼 시스템 |
| **블로그 📝** | 블로그 포스팅 전문가 | SEO 최적화, 키워드 리서치, 시리즈 기획 |
| **뉴스레터 📧** | 뉴스레터 전문가 | 구독자 확보, 이메일 시퀀스, 오픈율 최적화 |
| **영숙 비서 📱** | Personal Assistant | 일정·할 일 관리, 데일리 브리핑, 텔레그램 보고 |
| **Writer ✍️** | 콘텐츠 라이터 | 카피라이팅, 스크립트, 후크, 담담 브랜드 보이스 |
| **Researcher 🔍** | 트렌드 리서처 | 트렌드 분석, 경쟁사 벤치마킹, 데이터 요약 |

---

## ⚡ 주요 기능

### 1. 🧠 자율 에이전트 팀 (24시간 미션 수행)
CEO 담담이 팀 전체를 오케스트레이션합니다. 내가 자리를 비워도 에이전트들이 알아서 다음 스텝을 실행합니다.

### 2. 📂 자율 지식 구조화
원시 데이터(Raw Data)를 에이전트가 스스로 판단해 Markdown 파일로 분할·조립·저장합니다.

### 3. ☁️ 클라우드 자동 동기화
파일 생성 즉시 GitHub 저장소에 자동으로 `git add`, `commit`, `push`합니다.

### 4. 🔗 로컬 모델 자동 감지
Ollama 또는 LM Studio에 설치된 모델을 자동 감지하여 드롭다운에 연결합니다.

---

## ⚒️ 에이전트 권한

| Action | Description |
|:--|:--|
| **📄 Create Files** | 새로운 파일과 폴더를 생성합니다 |
| **✏️ Edit Files** | 기존 파일 내의 콘텐츠를 수정합니다 |
| **🗑️ Delete Files** | 불필요한 파일을 즉각 제거합니다 |
| **📖 Read Files** | 담담의 프로젝트 파일을 읽어 맥락을 파악합니다 |
| **📂 Browse Directories** | 디렉토리 구조를 분석합니다 |
| **🖥️ Run Commands** | `npm run build`, `git push` 등 터미널 명령을 수행합니다 |

---

## 📥 설치 방법

### 개발자 빌드 (Build from Source)
```bash
git clone https://github.com/cheongik/connect-ai_COPY.git
cd connect-ai_COPY
npm install
npm run compile
npx vsce package
```

---

## ⚙️ 엔진 설정

### ✅ LM Studio (Apple Silicon, Windows) — 권장
1. [lmstudio.ai](https://lmstudio.ai/) 에서 설치
2. Gemma 3, Llama 3 또는 Qwen Coder 등 원하는 모델 로드
3. **Developer 탭** 진입 후 **Start Server** 클릭
4. 담담 AI 설정에서 엔진을 "LM Studio"로 선택

### ✅ Ollama (Mac, Linux)
```bash
brew install ollama
ollama pull gemma3
```

---

## 🔒 보안 (완벽한 프라이버시)

- **Zero Cloud API:** 담담의 콘텐츠는 외부 클라우드로 나가지 않습니다.
- **Zero Telemetry:** 모든 연산은 100% 로컬 환경에서 이루어집니다.

---

<p align="center">
  <strong>🦫 담담(Damdam) — 차분하지만 단단하게</strong><br/>
  1인 AI 콘텐츠 기업의 심장, 담담 AI
</p>
