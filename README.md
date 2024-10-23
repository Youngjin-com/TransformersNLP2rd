# 트랜스포머로 시작하는 자연어 처리

<img src="https://www.youngjin.com/images/book_cover/9788931475869.png" height="350px" style="border: 2px solid grey;">

[트랜스포머로 시작하는 자연어 처리(영진닷컴)](https://blog.naver.com/ydot/223440955819)

『트랜스포머로 시작하는 자연어 처리』는  자연어 처리(Natural Language Processing, NLP)와 트랜스포머(transformer) 모델의 혁신적 발전을 심도 있게 탐구한다. 자연어 이해(Natural Language Understanding, NLU)를 위한 언어 모델링, 챗봇, 텍스트 요약, 음성 인식, 기계 번역 등의 응용 분야에서 트랜스포머 모델의 역할은 중요하다. 특히, BERT와 GPT-3와 같은 모델들이 RNN과 CNN을 대체하며 더 높은 성능을 보이는 과정을 상세히 설명한다.

트랜스포머의 셀프-어텐션 메커니즘과 병렬 처리 능력은 대규모 데이터 학습을 가능하게 하며, 이는 NLP 작업의 판도를 바꾸고 있다. 이 책은 파이썬, 파이토치, 텐서플로우 등의 도구를 사용하여 언어 이해의 핵심 요소를 다루고, 다양한 트랜스포머 모델의 아키텍처를 분석한다. 또한 GPT-4와 같은 대규모 모델의 학습과 응용을 통해 AI의 최신 동향을 파악할 수 있다.

**저자** Denis Rothman  
**역자** 윤기, 박지성, 임창대, 하헌규  
**발행일** 2024년 07월 02일  
**크기** 188*257mm  
**쪽수** 648쪽  
**가격** 42,000원  
**ISBN** 9788931475869

<br>

## 💡시작하기

이 노트북들은 [Google Colab](https://colab.research.google.com/)과 같은 클라우드 플랫폼이나 로컬 컴퓨터에서 실행할 수 있습니다. 일부 챕터는 합리적인 시간 내에 실행하기 위해 GPU가 필요하므로, CUDA가 미리 설치된 클라우드 플랫폼을 사용하는 것을 권장합니다.

<br>

## 💡OpenAI API 시작하기
2023년 12월 6일. OpenAI는 현재 플랫폼을 업데이트 중입니다. 이 저장소의 노트북에서 문제가 발생할 경우 다음 팁을 참고하여 해결할 수 있습니다:
- 2024년 1월 4일부로 'davinci'에 대한 [OpenAI 지원 종료](https://platform.openai.com/docs/deprecations)가 적용됩니다. 권장되는 대체 모델은 'davinci-002'입니다.
- Google Colab: OpenAI 설치를 위해 Cohere(언어 기능)와 tiktoken(BPE 토크나이저)를 설치해야 합니다. (!pip install tiktoken 및 !pip install --upgrade cohere)
- API 호출이 "openai.Completion.create"에서 "client.chat.completions.create"로 변경되었습니다. 여기서 client는 [YOUR OPENAI CLIENT]로 지정됩니다. 
- API 호출에서 engine=[모델 이름]이 model=[모델 이름]으로 변경되었습니다.
- 응답 객체가 진화하고 있습니다. 권장사항: 먼저 "response"를 출력한 다음, 객체를 분석하여 필요한 부분을 접근하십시오.
- 문제가 계속될 경우, 이전 OpenAI 버전을 고정하여 설치할 수 있습니다: !pip install openai==0.28

이 업데이트 팁의 예시는 다음 노트북에서 찾을 수 있으며, 필요에 따라 다른 노트북에도 적용할 수 있습니다:
-[Getting_Started_GPT_3.ipynb](https://github.com/Denis2054/Transformers-for-NLP-2nd-Edition/blob/main/Chapter07/Getting_Started_GPT_3.ipynb), [Summarizing_with_ChatGPT.ipynb](https://github.com/Denis2054/Transformers-for-NLP-2nd-Edition/blob/main/Chapter09/Summarizing_with_ChatGPT.ipynb), 그리고 [Semantic_Role_Labeling_with_ChatGPT.ipynb](https://github.com/Denis2054/Transformers-for-NLP-2nd-Edition/blob/main/Chapter10/Semantic_Role_Labeling_with_ChatGPT.ipynb)

<br>

## 💡실습용 예제 파일 & 소스 코드
도서 실습에 필요한 예제 파일과 소스 코드는 챕터별로 구성하였으며, 깃허브 저장소뿐만 아니라 [영진닷컴 홈페이지](https://www.youngjin.com/reader/pds/pds.asp)에서도 다운로드받을 수 있습니다.  
코드 작성 시에는 코드를 직접 입력하거나, 책에서 제공하는 소스 코드 파일을 사용하세요.

<br>

## 💡문의 및 정오표
- [문의](mailto:Support@youngjin.com)
- [정오표](https://www.youngjin.com/Artyboard/mboard.asp?strBoardID=errata)
