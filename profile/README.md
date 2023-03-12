![image](https://user-images.githubusercontent.com/57169754/223782788-3bed867f-cae2-4555-b816-218b4ed29540.png)
# 🤔어떤 프로그램인가요?

샌드위치 주문을 위한 디지털휴먼 키오스크 프로그램입니다.
* 사용자의 음성을 입력 데이터로 받아 커스텀 샌드위치를 주문을 처리합니다. 
* 그 과정에서 사용자에게 실제 점원과 대화하는 느낌을 줄 수 있도록
  >
  > 실사 같은 외양을 갖춘 디지털휴먼이 점원 역할을 합니다.<br>
  > 디지털휴먼 점원이 실감나는 언어적/비언어적 표현을 합니다.(목소리, 제스쳐, 눈 깜빡임, 미소 등)<br>
  > 회원 등록된 사용자에게는 관심 메뉴 등록/주문 서비스를 제공합니다.
  >
* 사용자의 선택을 돕기 위해 선택옵션을 단순 Text가 아니라 해당 아이템의 3D object로 제공합니다.

<br>

## ❓제작 동기
COVID-19 사태 이후 대부분의 식당, 카페 등에서 간단한 계산업무는 키오스크 기계로 대체되고 있습니다. 일상생활에서 키오스크를 접할 일은 늘어나고 있지만, [디지털 소외계층](https://www.youthassembly.kr/news/582948)이 적응하기에 이러한 현상은 무리가 있습니다.<br>
디지털 소외계층이 말하는 `키오스크 주문이 어려운 이유`를 조사하였습니다. 간략히 정리하면 아래와 같았습니다.
  1. 키오스크 사용방법을 모르거나, 사용방법이 복잡하고 어렵다. 
  2. 주문을 돕는 카운터 직원이 없어 메뉴에 대한 이해/메뉴 선택이 어렵다.
  3. 신식기계를 조작하는 것 자체가 꺼려진다.

💡위 문제들을 해결하기 위해 음성인식 주문이 가능한 디지털휴먼 키오스크 프로그램 아이디어를 구상하게 되었습니다.

<br>

## 🗺️ 전체 시스템 구성도
![image](https://user-images.githubusercontent.com/57169754/221845562-15f9cacc-9da8-4c33-9f09-baf08c7a5b33.png)

<br>

## 🎞️ 시연영상(클릭 시 유투브 이동)
[![link to Youtube](https://user-images.githubusercontent.com/60374155/224118471-24f4a5d8-c170-47b3-a6e9-019b5aae953b.png)](https://youtu.be/IG65KLyU3Nw)
<br>

## 🔧 사용도구
### 개발 도구
| 사용 목적 | 도구 이름 |
|:---------|:---------|
|샌드위치 주문을 위한 메타휴먼 키오스크 프로그램| UnrealEngine4 |
| 디지털 휴먼  |Epic games Metahuman Creator Maya, NvidiaOmniverse(Audio2Face) |

### 사용 라이브러리 및 재료
| 목록 | 내용 |
|:---------|:---------|
|Dialogue Builder [UnrealEngine Market Place] | 대화 노드에 맞춰 오디오재생 및 애니메이션 플레이를 가능하게 하는 플러그인 |
|Google Speech Kit [UnrealEngine Market Place] | Google Cloud에서 제공하는 STT/TTS API를 UE내 Blueprint에서 쉽게 활용할 수 있도록 하는 플러그인 |
|MCO Mocap Basics [UnrealEngine Market Place] | Body Animation 무료 소스 모음 |
|VaRest [UnrealEngine Market Place] | 웹서버 통신을 위한 http method를 사용할 수 있도록 하는 플러그인 |
|fastfood resturant map [UnrealEngine Market Place] | 샌드위치 음식점 배경 맵 |
|GPT3 [OpenAI] | Open AI에서 제공하는 GPT3 API를 UE내 사용할 수 있도록 하는 플러그인 |
<br>

## 📜 참고자료
| 종류 | 참고문헌 |
|:---------|:---------|
| 웹사이트 | [GPT3 플러그인 다운로드/환경설정 및 UE 적용 방법](https://www.youtube.com/watch?v=i-Aw32rgM-w) |
| 웹사이트 | [UE dialogue builder 튜토리얼](https://www.youtube.com/watch?v=4w8NpR1wgOU) |
| 웹사이트 | [UE Varest와 mysql 연동 방법, PHP예시](https://unrealengine.tistory.com/159) |
| 웹사이트 | [Audio2Face, Maya를 통해 face Animation 제작방법](https://www.youtube.com/watch?v=AjpuBW2RXHI) |
| 웹사이트 | [Maya 내 face Animation 상세 수정 방법](https://www.youtube.com/watch?v=E8DwHkkjgOA) |
| 웹사이트 | [UE 3인칭 마네킹 캐릭터에 MetaHuman Animation retartgetting 방법](https://docs.metahuman.unrealengine.com/ko/retargeting-animations-to-a-metahuman-in-unreal-engine-4/ ) |
| 웹사이트 | [UE Control Rig을 이용하여 Animation 생성 및 수정 방법](https://www.youtube.com/watch?v=2k2gNc_7CT0) |
| 웹사이트 | [UE4 blueprint 기초 사용법, 전반적인 도구 설명](https://www.youtube.com/playlist?list=PLi6SIeAlP8AVvHzAVv5ZGApb4dVva40dy) |
| 웹사이트 | [GPT3와 Google Speech Kit 적용 프로젝트 예시, 블루프린트 설계도 제공](https://www.youtube.com/watch?v=wtv_043sIrg) |
| 웹사이트 | [UE4 사용법 유료 강의](https://www.inflearn.com/course/%EC%96%B8%EB%A6%AC%EC%96%BC-%EC%97%94%EC%A7%844-%EC%9E%85%EB%AC%B8/dashboard) |
| 서적 | 이득우의 언리얼 C++ 게임 개발의 정석 |
| 서적 | (C++로 시작하는) 언리얼 4 게임 프로그래밍 |
<br>

## 💪 역할

| 안소라 | 이민하 | 임혜진 | 정다은 |
|:---------|:---------|:---------|:---------|
| * 프로그램 배경 구매 및 테스트<br>* 음식,재료 mesh 구매 및 테스트<br>* 디지털휴먼 의상 asset 제작<br>* 일부 Face Animation 세부 수정| * 프로그램 전체 시스템 설계 및 총괄<br>* DB설계 및 Web server 구축<br>* GPT3, STT 설계 및 데이터 처리<br>* GPT3 AI Script ver.2 작성 및 디버깅<br>* 시스템 UI설계 | * STT, GPT3 BaseLine 설계 및 테스트<br>* Face/Body Animation 제작/수정<br>* UI Animation Sequence 제작<br>* 시스템 내 Animation 적용 | * [MHC](https://www.unrealengine.com/ko/metahuman)툴을 통한 디지털휴먼 생성<br>* GPT3 AI Script ver.1 작성<br>* 음식,재료 mesh 구매 및 테스트 | 
| [anthfk](https://github.com/anthfk) | [mina-401](https://github.com/orgs/dahasoim/people/mina-401) | [imagine99](https://github.com/imagine99) | [dan1792](https://github.com/dan1792) |

<br>

## ✔️ 레포지토리
* Public
  - [MySQL-Apache-UnrealEngine, 시스템DB](https://github.com/dahasoim/MySQL-Apache-UnrealEngine) - 이민하
  - [MetahumanAnim, 디지털휴먼 애니메이션](https://github.com/dahasoim/metahuman_Anim) - 안소라, 임혜진
  - [GPT3-STT-UE4, 음성인식 및 데이터가공](https://github.com/dahasoim/GPT3-STT-UE4) - 이민하, 임혜진, 정다은
  - [GPT3-STT-UE4 Demo](https://github.com/dahasoim/GPT3-STT-UE4_Demo) - 임혜진
* Private
  - [Clothes, 앞치마/모자 assetes](https://github.com/dahasoim/clothes) - 안소라
  - [Food3D, 음식/식재료 assetes](https://github.com/dahasoim/food_3D) - 안소라, 임혜진, 정다은
  - [BackGround, 프로그램 배경](https://github.com/dahasoim/Background) - 안소라
