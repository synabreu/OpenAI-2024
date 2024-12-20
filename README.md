# OpenAI-2024
개발자를 위한 OpenAI 2024 발표 자료, 최신 내용 업데이트 및 튜토리얼, 오픈 소스까지 정리

##### 2024년 개발자를 위한 오픈AI 컨텐츠 정리 #####

### Youtube : 12 Days of OpenAI ####

##### [Work with Apps—12 Days of OpenAI: Day 11](https://www.youtube.com/watch?v=g_qxoznfa7E) #####

    * OpenAI의 ChatGPT 데스크톱 앱 업데이트 : ChatGPT 데스크톱 앱의 강력해진 기능과 사용 편의성을 강조하고, 향후 2025년까지 더욱 발전된 'agentic'한 ChatGPT 예고
    * Mac과 Windows용 ChatGPT 데스크톱 앱의 기능 향상
    * 앱과의 직접적인 연동을 통해 사용자의 컴퓨터 화면 정보를 활용하여 코드 작성, 문서 작성 보조, 자동화 작업 등을 지원하는 기능이 추가
    * 실제 데스크톱 앱을 사용하여 Xcode, Warp 터미널, Notion 등의 앱과 ChatGPT를 연동하는 데모를 보여줌
    * 새로운 모델(01, 01 Pro)을 통한 향상된 코드 생성 및 데이터 분석 기능, 음성 입력을 지원하는 'Advanced Voice Mode'의 활용 예시 제시

##### [1-800-CHAT-GPT—12 Days of OpenAI: Day 10](https://www.youtube.com/watch?v=LWa6OHeNK3s) #####

    * OpenAI의 ChatGPT를 미국에서는 1-800-242-8478 전화 번호로, 전 세계적으로는 WhatsApp을 통해 더욱 접근 가능하도록 함.
    * 아이폰이나 플립폰, 그리고 옛날 회전석 전화 등 다양한 폰을 이용해 ChatGPT와 음성 및 문자 메시지로 소통할 수 있도록 함.
    * WhatsApp을 통해 채팅하면서 실시간으로 요리 레시피를 수정하는 등의 상호작용을 강조하고, 사용자 편의성을 높힘.
    * ChatGPT 연락처에 번호를 저장할 것을 권장함.
    * 사용 사례: 전화 통화를 통해 정보 검색, 외국어 학습, 챗봇 이용 등을 할 수 있고, WhatsApp을 통해 레시피 검색, 실시간 정보 업데이트, 창의적인 대화 등을 할 수 있음.
    
##### [Dev Day Holiday Edition—12 Days of OpenAI: Day 9](https://www.youtube.com/watch?v=14leJ1fg4Pw) #####

    1. 새로운 o1 정식 출시
     * o1 모델의 API 정식 출시. 이 모델은 에이전트 애플리케이션을 지원하며, 고객 지원, 재무 분석 등 다양한 분야에서 활용될 수 있음. 특히, 코딩 모델에서 뛰어나며, 이전 버전인 o1 Preview에 비해 60% 적은 thinking tokens을 사용해 더 빠르고 저렴함.
     * 함수 호출(Function Calling): o1 함수 호출 API 제공. o1 모델이 백엔드 API와 상호 작용할 수 있으며, 개발자들은 모델이 외부 데이터를 활용하거나 특정 작업을 수행할 수 있음. 특히, o1 모델은 함수 호출에서 GPT-4o보다 성능이 훨씬 뛰어남.
     * 구조적 출력 (Structured Outputs): 모델의 출력을 JSON 스키마에 맞춰 구조화하는 기능이 추가했음. 개발자들은 모델로부터 원하는 형식의 데이터를 쉽게 추출할 수 있으며, 특히, 풍부한 기능을 가진 클라이언트 응용 프로그램을 개발하는 데 유용함. o1 모델은 구조적 출력에서도 GPT-4o보다 성능이 뛰어남.
     * 새 개발자 메시지 도입: 시스템 메시지의 새로운 형태인 개발자 메시지가 도입으로 개발자 메시지를 통해 모델이 어떤 지시를 어떤 순서로 따라야 하는지 제어할 수 있으며, 모델의 동작을 개발자가 완전히 제어할 수 있음.
     * 추론 노력(Reasoning Effort): 모델이 문제 해결에 얼마나 시간을 할애할지 제어하는 새로운 파라미터 도입. 이를 통해 쉬운 문제에는 시간과 비용을 절약하고, 어려운 문제에는 더 많은 컴퓨팅 자원을 사용할 수 있도록 함.
     * 비전 입력(Vision Inputs): 이미지 입력을 처리하는 기능이 추가되어, 제조 또는 과학 분야에서 활용할 수 있게 되었음.
     
    2. Real-time API
     * WebRTC 지원: 실시간 API에 WebRTC를 지원하여 서버 간 음성 전송 및 응답이 가능해졌음. WebRTC는 인터넷 환경에서 안정적인 통신을 제공하며, 음성 회의나 저지연 비디오 스트리밍과 같은 애플리케이션에서 유용함. 기존에 복잡했던 웹소켓 통합이 12줄의 코드로 간단해졌습음. 
     * 마이크로 컨트롤러 지원: 작은 마이크로 컨트롤러를 이용하여 음성 기반 응용 프로그램을 개발할 수 있게 되었음. 
     * 비용 절감: GPT-40 오디오 토큰 가격이 60% 저렴해졌으며, GPT-4 Mini 오디오 토큰은 10배 더 저렴해졌음. 
     * Python SDK: 리얼타임 API를 더 쉽게 통합할 수 있도록 Python SDK를 지원함.
     * 함수 호출 및 가드 레일: 함수 호출과 가드 레일을 더 쉽게 사용할 수 있도록 API가 변경되었움. 
     
    3. 미세 조정(Fine-tuning)
     * 선호도 미세 조정(Preference Fine-tuning): 사용자의 선호도에 맞게 모델을 조정하는 새로운 메서드가 API에 추가되었음. 직접 선호도 최적화 (Direct Preference Optimization) 방법을 사용하여, 사용자가 선호하는 응답과 그렇지 않은 응답을 쌍으로 제공하여 모델을 학습시킬 수 있음. 이를 통해 모델의 응답 형식, 스타일, 추상적인 품질 (예: 유용성, 창의성) 등을 개선할 수 있음.
     * 사용 사례: 고객 지원, 카피라이팅, 창의적 글쓰기, 콘텐츠 검토 등에 유용함.
     * 가격: 선호도 미세 조정은 지도 학습 미세 조정과 동일한 가격으로 제공됨. 
     
    4. 그외 업데이트   
     * 새로운 SDK: Go 및 Java SDK에 대한 공식 지원 시작함. 
     * API 키 발급 간소화: API 키를 더 쉽게 발급받을 수 있도록 로그인 및 가입 절차가 개선되었음. 
     * AMA (Ask Me Anything): 발표자들과 API 담당자들이 개발자 포럼에서 AMA를 진행함. 
     
##### [Search—12 Days of OpenAI: Day 8](https://www.youtube.com/watch?v=OzgNJJ2ErEE) #####

     * OpenAI의 ChatGPT 검색 기능 업데이트 
     * 기존 유료 사용자들에게 제공되던 검색 기능의 속도 및 모바일 사용성 개선과 새로운 지도 경험 추가
     * 음성 모드와 연동하여 음성으로 검색이 가능하게 업데이트
     * 모든 로그인한 무료 사용자들에게 전 세계적으로 ChatGPT 검색 기능을 제공한다


##### [Projects—12 Days of OpenAI: Day 7](https://www.youtube.com/watch?v=OzgNJJ2ErEE) #####

     * "챗GPT 프로젝트" 기능 출시 : 챗GPT 내에서 대화를 프로젝트별로 구성하고 관리할 수 있는 새로운 기능
     * 파일 업로드, 사용자 지정 지시사항 설정, 캔버스 기능 활용 등의 기능을 통해 사용자들이 챗GPT를 더 효율적이고 효과적으로 사용 예시 제공: 비밀 산타 선물 교환 준비, 집 수리 관리, 개인 웹사이트 제작
     * 프로젝트 기능이 단순한 대화 정리 도구를 넘어 복잡한 작업을 체계적으로 관리하는 데 유용함을 강조
     * 서브스크립션 플러스, 프로, 팀 사용자부터 순차적으로 출시될 예정

##### [Santa Mode & Video in Advanced Voice—12 Days of OpenAI: Day 6](https://www.youtube.com/watch?v=NIQDnWlwYyQ) #####

     * 12월 12일 발생한 서비스 중단에 대한 사과
     * 고급 음성 모드(Advanced Voice Mode)에 비디오 및 화면 공유 기능 추가
     * 실시간으로 비디오와 화면을 공유하며 ChatGPT와 더욱 풍부하고 자연스러운 대화를 나눔
     * 크리스마스를 맞이하여 ChatGPT에서 산타와 대화할 수 있는 기능 추가 
     
##### [ChatGPT x Apple Intelligence—12 Days of OpenAI: Day 5](https://www.youtube.com/watch?v=mBhkD0iFf4w) #####

     * iPhone, iPad, Mac고 같은 애플 기기와 ChatGPT의 통합 발표 : 전반적으로 ChatGPT의 접근성을 높이고, 사용 편의성을 개선하는 데 초점
     * Siri, Apple의 작성 도구, 그리고 iPhone 16의 카메라 기능과의 연동을 통해 ChatGPT를 손쉽게 사용할 수 있도록 했음
     * 사용자는 계정 없이도 사용 가능하며, Siri를 통해 음성 명령으로 ChatGPT를 호출
     * Siri를 통해 음성 명령으로 ChatGPT를 호출하거나, 문서 작성 및 편집 과정에 ChatGPT를 활용하거나, 사진을 분석하여 ChatGPT로 정보를 얻을 수 있음

##### [Canvas—12 Days of OpenAI: Day 4](https://www.youtube.com/watch?v=qZ0ImE41pVs) #####

     * 새로운 캔버스 기능 업데이트: 캔버스를 통해 ChatGPT와의 대화를 단순한 채팅을 넘어, 글쓰기나 코딩 작업을 위한 협업 도구로 확장시킴.
     * 모든 사용자에게 Canvas를 제공하고 기본 모델에 통합
     * Canvas 내에서 Python 코드 실행 및 결과 확인
     * 개인 맞춤형 GPT(Custom GPT)에도 Canvas 기능을 적용하여 사용자 지정 모델의 기능 향상
     * 보다 효율적이고 직관적인 방식으로 ChatGPT를 활용하여 창작 및 프로그래밍 작업을 수행할 수 있도록 하는 업데이트

##### [Sora–12 Days of OpenAI: Day 3](https://www.youtube.com/watch?v=2jKVx2vyZOY) #####

     * OpenAI가 새롭게 출시한 비디오 생성 AI 모델인 Sora 출시 : Sora가 창의적인 비디오 제작을 위한 강력하고 직관적인 도구로 강조함
     * Sora의 핵심 기능으로는 텍스트나 이미지를 기반으로 비디오를 생성하고, 기존 비디오를 편집/변형하는 기능(Remix, Recut, Blend, Loop) 소개
     * 개발 배경으로는 크리에이터를 위한 도구 제공, 텍스트 중심의 AI 한계 극복, 그리고 AGI 로드맵 달성을 위한 중요한 단계라는 점이 강조함
     * 사용 편의성과 사용 가능 국가 및 요금제에 대한 정보와 함께, 향후 개선 및 안전성에 대한 언급함

##### [Reinforcement Fine-Tuning—12 Days of OpenAI: Day 2](https://www.youtube.com/watch?v=yCIYS9fx56U) #####

     * OpenAI가 개발한 새로운 모델 개선 프로그램인 강화 학습 미세 조정(Reinforcement Fine-Tuning, RFT) 소개
     * 기존의 지도 학습 미세 조정과 달리, RFT는 모델이 문제에 대해 스스로 생각하고 답변을 평가받은 후, 올바른 추론 과정을 강화하는 방식으로 학습함
     * 소량의 데이터만으로도 특정 분야에서 전문가 수준의 성능을 달성할 수 있다고 희귀 유전 질환 진단을 예시로 설명함
     * 발표의 목적은 RFT의 잠재력을 보여주고, 연구자 및 기업들을 대상으로 한 알파 프로그램 참여를 유도
     * [OpenAI's Reinforcement Fine-Tuning Research Program](https://openai.com/form/rft-research-program/)

##### [OpenAI o1 and o1 pro mode in ChatGPT — 12 Days of OpenAI: Day 1](https://www.youtube.com/watch?v=iBfQTnA2n2s) #####

     * OpenAI가 12일 동안 매주 새로운 기능을 공개하는 이벤트의 첫날 발표 내용
     * GPT-4보다 훨씬 향상된 성능을 가진 새로운 언어 모델 "o1"의 정식 출시 : 속도와 지능, 다중 모드 입력 기능 개선
     * 챗GPT Pro의 출시(월 200달러)를 발표하며, 무제한 모델 접근 및 고급 기능(o1 Pro 모드 포함)을 제공하여 고급 사용자의 요구 충족
     * OpenAI의 기술적 발전과 사용자 경험 개선에 대한 노력을 보여주는 동시에, 향후 11일간의 추가 발표에 대한 기대감을 높이는 것

### OpenAI Developer Conference 2024 ####


### Blog ###

