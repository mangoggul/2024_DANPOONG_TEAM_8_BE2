# 사용자 맞춤형 미션 생성 및 챗봇, 사용자 분석 API

이 프로젝트는 GPT API와 LangChain의 RAG (Retrieval-Augmented Generation) 기능을 활용하여 사용자 맞춤형 서비스를 제공합니다. 핵심 기능은 다음과 같습니다:

1. **사용자 맞춤형 미션 생성 API**:
    
    개인의 관심사와 목표를 기반으로 미션을 생성하여 동기 부여와 목표 달성을 지원합니다.
    
2. **사용자 맞춤형 챗봇 API**:
    
    대화형 AI를 제공합니다. 이 AI는 사용자가 선택한 캐릭터에 따라 다른 말투를 제공합니다.
    
3. **사용자 분석 API**:
    
    사용자의 설문 데이터와 선호도를 분석하여 정교한 맞춤형 분석을 제공합니다.
    

---

## 주요 기능

### 1. 사용자 맞춤형 미션 생성 API

- **설명**: 제공되는 질문에 사용자가 입력한 결과에 기반하여 미션을 생성하는 기능입니다.
- **기술 스택**:
    - GPT API를 사용한 자연어 생성
    - LangChain RAG을 활용한 맥락 기반 미션 제안

### 2. 사용자 맞춤형 챗봇 API

- **설명**: 사용자가 선택한 캐릭터에 따라 다른 말투의 친구형 챗봇 기능입니다.
- **기술 스택**:
    - Gpt API
    - 프롬프트 튜닝

### 3. 사용자 분석 API

- **설명**: 사용자 데이터를 분석하여 사용자가 부족한 청년자립 영역을 알려주는 기능입니다.
- **기술 스택**:
    - 사용자 데이터 저장 및 분석 (MariaDB)
    - LangChain을 통한 사용자 데이터 처리
