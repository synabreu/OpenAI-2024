# OpenAI-2024
OpenAI 2024 Developers Contents

##### 2024년 개발자를 위한 오픈AI 컨텐츠 정리 #####

### Youtube : 12 Days of OpenAI ####

##### [1-800-CHAT-GPT—12 Days of OpenAI: Day 10](https://www.youtube.com/watch?v=LWa6OHeNK3s) #####

  * OpenAI의 ChatGPT를 미국에서는 1-800-242-8478 전화 번호로, 전 세계적으로는 WhatsApp을 통해 더욱 접근 가능하도록 함.
  * 아이폰이나 플립폰, 그리고 옛날 회전석 전화 등 다양한 폰을 이용해 ChatGPT와 음성 및 문자 메시지로 소통할 수 있도록 함.
  * WhatsApp을 통해 채팅하면서 실시간으로 요리 레시피를 수정하는 등의 상호작용을 강조하고, 사용자 편의성을 높힘.
  * ChatGPT 연락처에 번호를 저장할 것을 권장함.
  * 사용 사례: 전화 통화를 통해 정보 검색, 외국어 학습, 챗봇 이용 등을 할 수 있고, WhatsApp을 통해 레시피 검색, 실시간 정보 업데이트, 창의적인 대화 등을 할 수 있음.
    
##### [Dev Day Holiday Edition—12 Days of OpenAI: Day 9](https://www.youtube.com/watch?v=14leJ1fg4Pw) #####

<p style="color: yellow; font-size: 10px">1. 새로운 o1 정식 출시</p>
     <p style="font-size: 8px">* o1 모델의 API 정식 출시. 이 모델은 에이전트 애플리케이션을 지원하며, 고객 지원, 재무 분석 등 다양한 분야에서 활용될 수 있음. 특히, 코딩 모델에서 뛰어나며, 이전 버전인 o1 Preview에 비해 60% 적은 thinking tokens을 사용해 더 빠르고 저렴함.</p>
     <p style="font-size: 8px">* 함수 호출(Function Calling): o1 함수 호출 API 제공. o1 모델이 백엔드 API와 상호 작용할 수 있으며, 개발자들은 모델이 외부 데이터를 활용하거나 특정 작업을 수행할 수 있음. 특히, o1 모델은 함수 호출에서 GPT-4o보다 성능이 훨씬 뛰어남.</p>
     <p style="font-size: 8px">* 구조적 출력 (Structured Outputs): 모델의 출력을 JSON 스키마에 맞춰 구조화하는 기능이 추가했음. 개발자들은 모델로부터 원하는 형식의 데이터를 쉽게 추출할 수 있으며, 특히, 풍부한 기능을 가진 클라이언트 응용 프로그램을 개발하는 데 유용함. o1 모델은 구조적 출력에서도 GPT-4o보다 성능이 뛰어남.</p>
      <p style="font-size: 8px">* 새 개발자 메시지 도입: 시스템 메시지의 새로운 형태인 개발자 메시지가 도입으로 개발자 메시지를 통해 모델이 어떤 지시를 어떤 순서로 따라야 하는지 제어할 수 있으며, 모델의 동작을 개발자가 완전히 제어할 수 있음.</p>
     * 추론 노력(Reasoning Effort): 모델이 문제 해결에 얼마나 시간을 할애할지 제어하는 새로운 파라미터 도입. 이를 통해 쉬운 문제에는 시간과 비용을 절약하고, 어려운 문제에는 더 많은 컴퓨팅 자원을 사용할 수 있도록 함.
     * 비전 입력(Vision Inputs): 이미지 입력을 처리하는 기능이 추가되어, 제조 또는 과학 분야에서 활용할 수 있게 되었음.
     
<p><span style="color: yellow; font-size: 10">2. Real-time API</span></p>
     * WebRTC 지원: 실시간 API에 WebRTC를 지원하여 서버 간 음성 전송 및 응답이 가능해졌음. WebRTC는 인터넷 환경에서 안정적인 통신을 제공하며, 음성 회의나 저지연 비디오 스트리밍과 같은 애플리케이션에서 유용함. 기존에 복잡했던 웹소켓 통합이 12줄의 코드로 간단해졌습음. 
     * 마이크로 컨트롤러 지원: 작은 마이크로 컨트롤러를 이용하여 음성 기반 응용 프로그램을 개발할 수 있게 되었음. 
     * 비용 절감: GPT-40 오디오 토큰 가격이 60% 저렴해졌으며, GPT-4 Mini 오디오 토큰은 10배 더 저렴해졌음. 
     * Python SDK: 리얼타임 API를 더 쉽게 통합할 수 있도록 Python SDK를 지원함.
     * 함수 호출 및 가드 레일: 함수 호출과 가드 레일을 더 쉽게 사용할 수 있도록 API가 변경되었움. 
<span style="color: yellow; font-size: 10">3. 미세 조정(Fine-tuning)</span>
     * 선호도 미세 조정(Preference Fine-tuning): 사용자의 선호도에 맞게 모델을 조정하는 새로운 메서드가 API에 추가되었음. 직접 선호도 최적화 (Direct Preference Optimization) 방법을 사용하여, 사용자가 선호하는 응답과 그렇지 않은 응답을 쌍으로 제공하여 모델을 학습시킬 수 있음. 이를 통해 모델의 응답 형식, 스타일, 추상적인 품질 (예: 유용성, 창의성) 등을 개선할 수 있음.
     * 사용 사례: 고객 지원, 카피라이팅, 창의적 글쓰기, 콘텐츠 검토 등에 유용함.
     * 가격: 선호도 미세 조정은 지도 학습 미세 조정과 동일한 가격으로 제공됨. 
<span style="color: yellow; font-size: 10">4. 그외 업데이트</span>   
     * 새로운 SDK: Go 및 Java SDK에 대한 공식 지원 시작함. 
     * API 키 발급 간소화: API 키를 더 쉽게 발급받을 수 있도록 로그인 및 가입 절차가 개선되었음. 
     * AMA (Ask Me Anything): 발표자들과 API 담당자들이 개발자 포럼에서 AMA를 진행함. 

     
##### [Search—12 Days of OpenAI: Day 8](https://www.youtube.com/watch?v=OzgNJJ2ErEE) #####
##### [Projects—12 Days of OpenAI: Day 7](https://www.youtube.com/watch?v=OzgNJJ2ErEE) #####
##### [Santa Mode & Video in Advanced Voice—12 Days of OpenAI: Day 6](https://www.youtube.com/watch?v=NIQDnWlwYyQ) #####
##### [ChatGPT x Apple Intelligence—12 Days of OpenAI: Day 5](https://www.youtube.com/watch?v=mBhkD0iFf4w) #####
##### []() #####
##### []() #####
##### []() #####
##### []() #####
##### []() #####
##### []() #####
##### []() #####
##### []() #####
##### []() #####
##### []() #####
##### []() #####
##### []() #####
##### []() #####


### OpenAI Developer Conference 2024 ####


### Blog ###

