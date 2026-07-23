## 김민우 | 게임 QA Automation & Process Improvement

## Contents
   
1. [이슈 트래킹, 코드리뷰 자동화 V2](https://github.com/alsdn14/Issuetracker-V2)  
   - 이전에는 단순 Google 스프레드시트–GitLab API 연동으로 이슈 관리 자동화 [이전 버전 링크](https://github.com/alsdn14/Issuetracker) 
   - V2 부터 Google 스프레드 시트 - Gitlab API 연동후 GitLab Merge Request(MR)의 소스 코드 변경점, 이슈 코멘트 내용 등을 AI API로 분석
   - 분석한 내용을 다시 Google 스프레드 시트로 양식에 맞게 이동시켜 팀원들이 보고 Test Case 작성에 참고할 수 있게 했습니다.
  
2. [QA 통합 대시보드 — AI 체크리스트 자동 생성 · 데이터 검색 · 이슈 분석](https://github.com/alsdn14/QA_Dashboard)  
   - GitLab 이슈 기반 QA 체크리스트 자동 생성, 데이터 검증, 테이블 검색 기능을 통합한 웹 대시보드    
   - 로컬 AI 모델(Ollama)을 연동해 자연어로 이슈 조회 및 데이터 분석 가능  

3. [PC 게임 테스트 명령어 매크로 툴]()    
   - PC 게임 테스트용 콘솔 명령어 및 환경 세팅을 원클릭으로 실행하는 GUI 매크로 툴  

4. [밸런스 테스트 자동화](https://github.com/alsdn14/Autobalance)    
   - OCR 기반 경험치·드랍률 측정, 치트 명령 자동 실행 GUI 툴  
  
5. [로그인 테스트 자동화](https://github.com/alsdn14/Login_test)    
   - Selenium 기반 웹 로그인 자동화 및 예외 처리 로직 구현 ( 개인 프로젝트 )  

## 소개
게임 QA 분야에서 **사원 → 리드 → 파트장**으로 성장하며,   
라이브 서비스 품질 확보를 위한 다양한 테스트 프로세스를 수립하고 자동화 환경을 구축해왔습니다.    
이 저장소에 제가 진행한 QA 관련 자동화 사례와 개인 프로젝트를 정리했습니다.   


## 주요 성과
### 자동화 도입
- Google 스프레드시트–GitLab 연동으로 테스트 관리 및 이슈 추적 자동화
- 로컬 LLM(Ollama)으로 GitLab MR 변경 내역을 분석·리스크 항목 자동 추출
- Python 기반 테스트 매크로 툴을 개발·배포하여 QA 인력의 테스트 수행 능력 고도화

### 프로세스 개선
- SQL 기반 쿼리 테스트 시나리오로 데이터 검증 범위 확대
- Unity 환경 로컬 테스트로 개발 초기 주요 이슈 사전 검출
- 불필요한 테스트 절차 제거 및 리스크 기반 테스트 전략 수립으로 프로세스 전반의 효율성 향상

### 운영 및 협업
- 기획·개발·QA 간 협업 체계 개선으로 커뮤니케이션 병목 해소
- 모바일 및 PC 버전 런칭 전 전수 테스트 및 점검 리스트 관리
- 라이브 서비스 중 발생한 주요 버그 실시간 감지 및 긴급 대응
- Jenkins 파이프라인을 활용한 테스트 빌드 제작·배포 및 라이브 서버 안정성 관리

### 교육
- 신규 QA 인력 교육 문서 제작 및 주도
- 데이터 기반 QA 업무 교육 기획 및 실무 중심 진행


## Contact
📱 010-9821-1005  
📧 qkfka0413@naver.com  
🌐 [GitHub](https://github.com/alsdn14)
