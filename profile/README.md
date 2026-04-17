# <img width="35" height="35" alt="될것같은데_Sentinel_Logo" src="https://github.com/user-attachments/assets/1acdd9a9-5e0f-4cfe-8c40-c01df769e29e" /> Sentinel Solution  

## Introduction  
**Team Name:** 될것같은데  
**Project Title:** LLM / MCP 환경에서 기업 내 중요정보 유출 차단 솔루션 개발  
**Solution Name:** Sentinel     
**Host Organization:** Best of the Best 14th at KITRI   

## Team Composition   
**Main Mentor:** 박문범  
**Assistant Mentor:** 박경재  
**Project Leader:** 정재현  
**Project Manager:** 김민서  
**Project Member:** 박하은 / `Endpoint Agent Development`      
**Project Member:** 이강호 / `AI Engineering, Server Development`  
**Project Member:** 이시온 / `Endpoint Agent Development`  
**Project Member:** 최원혁 / `AI Engineering`  

## Solution Skills  
### Supported Important Informations     
**기본 신원 정보**
- 성명
- 전화번호
- 이메일 등 총 5개의 정보

**공적 식별번호**
- 개인통관고유번호
- 주민등록번호
- 여권번호 등 총 8개의 정보

**인증 정보**
- JWT
- API 키
- Github Personal Access Token 등 총 4개의 정보

**금융 정보**
- 카드 번호
- 카드 유효 기산
- 계좌번호 등 총 6개 정보

**가상화폐 정보**
- 니모닉 구문
- 가상자산 개인키
- HD 지갑 확장키 등 총 4개의 정보

**네트워크 정보 + IMEI**
- IPv4
- IPv6
- MAC 주소 등 총 4개의 정보

총 31개의 정보   

<br>

### Supported AI Services  
**설치형 Agent(LLM/MCP 환경)**
- ChatGPT(Desktop)
- Gemini
- Claude
- DeepSeek
- VScode Copilot
- Groq

**크롬 확장 프로그램(LLM 환경)**
- ChatGPT
- Claude
- Gemini 등 총 13개의 대화형 AI 서비스

<br>

### Supported File Extensions  
**프롬프트**   
- 기본 Text 입력형 프롬프트

**문서**
- TXT
- PPT
- CSV
- Docx
- PDF 등 파일 구조 기반 문서 및 PDF 지원

**이미지**
- PNG
- JPG 등 이미지 파일 지원

<br>

### Required Environment 
**설치형 Agent**
- **운영체제:** Windows 운영체제
- **라이브러리:** Python 3.13 버전 이상
- **설치 방식:** exe 파일 실행

**크롬 확장 프로그램**
- **사전 설치:** 프로그램 Chrome 브라우저
- **설치 방식:** 배포된 크롬 확장 프로그램 설치

**솔루션 서버(내/외부망)**
- **운영체제:** Ubuntu 24.04 LTS 권장
- **CPU / RAM:** 4 vCPU 이상 / RAM 24GB 이상
- **GPU:** GPU 최소 1장 이상(추론 / 분석용), 최소 GeForce RTX 3060 12GB 이상(CUDA 지원 필요)
- **저장 공간:** 20GB 이상
- **네트워크:** 내부망(설정 IP, 내부 DNS/라우팅), 외부망(공인 IP 또는 도메인, 443(HTTPS) 오픈)
- **설치 방식:** 쉘스크립트(SentinelServer_AI/blob/main/setup/scripts/deploy.sh) 실행

<br>

### Supported OS  
- Windows

<br>

### Adoption Model for Sentinel Solution    
- On-Premise 등 외부 연결과 차단된 내/외부망 기업 서버
