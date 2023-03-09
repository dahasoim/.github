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

## 🎞️ 실행화면
[![link to Youtube](https://user-images.githubusercontent.com/60374155/224118471-24f4a5d8-c170-47b3-a6e9-019b5aae953b.png)](https://youtu.be/IG65KLyU3Nw)
<br>

## 🔧 사용도구

<br>

## 📜 참고자료

<br>

## 💪 역할

| 안소라 | 이민하 | 임혜진 | 정다은 |
|:---------|:---------|:---------|:---------|
| * 프로그램 배경 구매 및 테스트<br>* 음식,재료 mesh 구매 및 테스트<br>* 디지털휴먼 의상 asset 제작<br>* 일부 Face Animation 세부 수정| * 프로그램 전체 시스템 설계 및 총괄<br>* DB설계 및 Web server 구축<br>* GPT3, STT 설계 및 데이터 처리<br>* GPT3 AI Script ver.2 작성 및 디버깅<br>* 시스템 UI설계 | * STT, GPT3 BaseLine 설계 및 테스트<br>* Face/Body Animation 제작/수정<br>* UI Animation Sequence 제작<br>* 시스템 내 Animation 적용 | * [MHC](https://www.unrealengine.com/ko/metahuman)툴을 통한 디지털휴먼 생성<br>* GPT3 AI Script ver.1 작성<br>* 음식,재료 mesh 구매 및 테스트 | 
| [anthfk](https://github.com/anthfk) | [mina-401](https://github.com/orgs/dahasoim/people/mina-401) | [imagine99](https://github.com/imagine99) | [dan1792](https://github.com/dan1792) |

<br>

## ✔️ 레포지토리 및 참고사항
* Public
  - [MySQL-Apache-UnrealEngine, 시스템DB](https://github.com/dahasoim/MySQL-Apache-UnrealEngine) - 이민하
  - [MetahumanAnim, 디지털휴먼 애니메이션](https://github.com/dahasoim/metahuman_Anim) - 안소라, 임혜진
  - [GPT3-STT-UE4, 음성인식 및 데이터가공](https://github.com/dahasoim/GPT3-STT-UE4) - 이민하, 임혜진, 정다은
  - [GPT3-STT-UE4 Demo, 위 Repository의 BaseLine](https://github.com/dahasoim/GPT3-STT-UE4_Demo) - 임혜진
* Private
  - [Clothes, 앞치마/모자 assetes](https://github.com/dahasoim/clothes) - 안소라
  - [Food3D, 음식/식재료 assetes](https://github.com/dahasoim/food_3D) - 안소라, 임혜진, 정다은
  - [BackGround, 프로그램 배경](https://github.com/dahasoim/Background) - 안소라

* [시연영상]()
* [팀 Notion]()
