---
title: Analysis Workspace 내에서 운영 대시보드 만들기
description: 에서 대시보드가 어떻게 운영되는지 살펴봅니다. [!DNL Adobe Analytics] 작업 영역은 커뮤니케이션 및 효율성을 혁신합니다.
solution: Analytics
feature-set: Analytics
feature: Curate and Share
topic: Administration
role: User
level: Experienced
doc-type: Article
last-substantial-update: 2023-08-18T00:00:00Z
jira: KT-13829
thumbnail: KT-13829.jpeg
exl-id: 8df9e88f-e564-4a8e-b624-026c873d3f19
source-git-commit: 058d26bd99ab060df3633fb32f1232f534881ca4
workflow-type: tm+mt
source-wordcount: '1130'
ht-degree: 88%

---

# Analysis Workspace 내에서 운영 대시보드 만들기

_[!DNL Adobe Analytics] Workspace의 운영 대시보드가 커뮤니케이션 및 효율성을 혁신하는 방법에 대해 알아봅니다. FAQ, 뉴스 및 공지 사항, 버그 및 기능 대시보드를 만들어 정보를 간소화하고, 사용자 경험을 개선하고, 고객 참여를 높이는 방법을 살펴봅니다._


많은 관리자와 마찬가지로 다음에 대한 내부 정보 허브(Confluence 또는 유사)를 실행합니다. [!DNL Adobe Analytics]. 시간이 지남에 따라 동일한 질문을 반복적으로 답하는데 너무 지친 나머지 핑(Ping)과 불편함 없이 사용자와 관계를 원활하게 할 수 있는 방법이 필요합니다. 다소 정적인 정보를 위한 저장소가 필요합니다.

“내 VPN이 꺼져 있음” 또는 “지금은 읽을 수 없음” 등과 같은 이유로 사용자는 Confluence 사이트에 대한 내 참조를 종종 무시했습니다. 기본적으로 “나중에 해당 문서를 읽겠음”은 이 문서를 절대 읽지 않고 다음 주에 동일한 질문에 다시 답변하겠음을 의미합니다.

***실현 히트:**작업 영역의 다기능성은 획기적인 기능일 수 있습니다. 사용자는 작업 영역 내에서 빠르고 직접적인 답변을 선호하므로 답변을 작업 영역에 유지하면서 추가 단계를 피합니다.*

전사적으로 공유할 운영 대시보드를 계속 만들었습니다. 지금까지는 사용자에게 중앙 집중식으로 정보를 제공하고 사용자 어려움을 줄이는 데 노력했습니다. 시간 경과에 따라 효율성을 높이는 간편한 진화 프로세스였습니다.

사람들은 나 없이도 좋은 정보를 많이 얻을 수 있었고, 사이트의 영역을 이해하고, 얼마나 멋있는지 볼 수 있었습니다 [!DNL Adobe Analytics] 은(는) 이며, (은??는) 질문을 줄이고 시간을 절약할 수 있습니다.

**사이트의 모든 속성이나 주요 영역에 대한 대시보드를 만드는 것이 좋습니다.** 속성/사이트/앱/흐름에 대한 개요를 제공하고 기본 정보와 빠른 인사이트를 얻어야 합니다. 모든 사용자가 소유하지 않고도 속성을 이해할 수 있도록 이를 전사적으로 공유해야 합니다. 이러한 대시보드는 개인적으로 받은 질문 중 80%에 답변하여 소중한 시간을 절감할 수 있습니다.

이 답변 중 어느 것도 Confluence 사이트를 유지하는 데 방해가 되지 않으며, 이 사이트를 소유하는 것이 매우 유용합니다. 각 운영 대시보드의 맨 위에서도 참조합니다. 하지만 저와 사용자는 모두 단축키를 선호합니다.

목표 달성에 도움을 준 GenDigital을 위해 본인이 만든 세 가지 운영 대시보드에 대해 안내해 드리겠습니다.

1. FAQ
1. 뉴스 및 공지 사항
1. 버그, 기능 및 주요 릴리스 로그


## 1 - FAQ 대시보드

무한 반복되는 답변에 지치셨나요? 중지! FAQ 대시보드를 만들어 시간을 절약합니다. 질문하기 전에 사용자는 대시보드를 참조하거나 응답에서 빠르게 연결할 수 있습니다.

질문이 콘텐츠와 같이 제목 및 답변/설명으로 사용되면 [텍스트 시각화](https://experienceleague.adobe.com/docs/analytics/analyze/analysis-workspace/visualizations/text.html)를 만들어 모두를 축소하여 질문만 표시합니다. 관련성(예: 페이지 또는 제품)별로 그룹화하거나 패널을 사용합니다. 단순하게 유지하면서 맨 위 일반적인 쿼리의 우선 순위를 지정합니다.

긴 이메일을 작성하거나 이전 설명을 다시 검색하는 대신 FAQ 대시보드를 업데이트합니다. 지금 시작하고 시간이 지남에 따라 확장합니다. 하이퍼링크를 사용하여 보고서 내 다른 대시보드나 관련 FAQ를 참조합니다. 필요한 경우 복잡한 컨텍스트를 다른 대시보드에서 FAQ에 연결하여 제공합니다.

Gen Digital의 경우 FAQ는 사용자 지정에 중점을 둡니다. [!DNL Adobe Analytics] 기본이 아닌 를 사용합니다. 마우스 오른쪽 버튼으로 클릭하고, “시각화 링크 가져오기”를 선택하고, vanity URL을 공유하여 특정 FAQ 링크를 이메일로 보냅니다. 이는 사용자의 정확한 콘텐츠를 강조 표시합니다. 데이터 일러스트레이션에 자유 형식 테이블을 사용하여 “설명 편집”으로 더 많은 설명을 추가합니다.

FAQ가 포괄적으로 여겨지면 회사와 공유하여 광범위한 액세스와 학습 기회를 얻을 수 있습니다. 필요에 따라 작업을 지속적으로 개선합니다.

FAQ 대시보드 형태에 대한 일부 스크린샷은 다음과 같습니다.

![스크린샷 1](assets/screenshot-1_v2.png)

![낮은 트래픽 FAQ1](assets/low-traffic-faq.png)

![비디오 추적 FAQ](assets/track-video-faq.png)

![다운로드 추적 FAQ](assets/track-downloads-faq.png)

## 2 - 뉴스 및 공지 사항 대시보드

다른 유용한 운영 대시보드는 뉴스 및 공지 사항 대시보드입니다. 사용자에게 정보를 제공하기 위해 이 작업을 시작했지만 대신 핑(Ping)이 울리고 사용자가 불편해하는 것 같습니다. 이 업데이트는 모두 사용자에게 필요한가요? 어떤 사용자에게 필요한가요? 고급 사용자에게만 필요한가요? 아무도 읽지 않는 주간 뉴스레터를 전송해야 하나요? 대신 사용자는 작업 영역에서 직접 업데이트하여 로그인되는 즉시 업데이트를 확인할 수 있지만, 아무도 읽으려 하지 않는 다른 회사 이메일을 전송할 필요가 없습니다.

이러한 대시보드는 전사적으로 표시되므로 업데이트되면 즉시 맨 위에 표시됩니다. 뉴스 및 공지 사항 대시보드에 포함되는 정보 유형은 다음과 같습니다.

- 회사측 기능 릴리스 및 업데이트(주로 코드 릴리스)
- 의 중요한 새로운 기능 [!DNL Adobe]
- 오피스 아워 일정
- 확인할 모든 개요 대시보드 목록 및 추천 보고서

새로운 기능, 추적 및 필수 대시보드를 다룹니다. 텍스트 보고서의 하이퍼링크(또는 마우스 오른쪽 버튼 클릭 및 편집 설명을 통해 다른 보고서 상단)를 사용하면 의 다른 대시보드에 연결할 수 있습니다. [!DNL Adobe Analytics] 또는 [!DNL Adobe]의 기능 릴리스 페이지입니다.

내 뉴스 및 공지 사항 대시보드 형태는 다음과 같습니다.

![스크린샷 2](assets/screenshot-2.png)

## 3 - 버그, 기능 및 주요 릴리스 로그

이 운영 대시보드의 목표는 중앙 위치에 모든 버그와 오류를 배치하는 것입니다. 기존에는 Excel로 관리했는데 공유하기가 번거롭고 힘듭니다. 작업 영역에 직접 입력하지 않는 이유는 무엇일까요?

눈에 잘 띄지 않기를 원한다면 뉴스 및 공지 사항 대시보드에 통합할 수도 있습니다. 단, 버그 보고가 회사에 상당히 중요할 경우 별도의 대시보드가 도움이 될 수 있습니다.

텍스트 시각화를 사용하고, 글머리 기호로 최대한 단순하게 유지합니다. 글머리 기호 앞에는 버그 날짜 및 속성이 붙습니다(예: “3jan23-17jan23 - Norton.com”, “Prior to 14sep22 - Chat”). 그런 다음 세부 정보를 추가하고 짧고 간결하게 유지합니다. 문제가 있는 팀을 표시하지 않고, 사용자가 신경 쓰지 않는 기술 세부 정보를 너무 많이 추가하지 않습니다.

최신 버그는 맨 위에 있지만, 이전 버그는 연간 텍스트 보고서(예: “2022 - 알려진 버그, 오류 및 변경 사항”)에 있어 모두 축소됩니다.

특별하지 않습니다. 작업이 정말 간편합니다. 하드 드라이브에 보관하고 Confluence에서 계속 업데이트하는 Excel 파일보다 휠씬 더 낫습니다.

또한 여기에서 다른 운영 대시보드와 유사한 개요 대시보드와 추천 보고서를 참조합니다. FAQ 링크와 뉴스 및 공지 사항 대시보드는 상단 방향으로 배치됩니다.

로그 형태의 예는 다음과 같습니다.

![스크린샷 3](assets/screenshot-3.png)

에서 운영 대시보드 만들기 [!DNL Adobe Analytics] Workspace는 나에게 있어 판도를 바꾸는 역할을 해 왔다. 여러 관리자와 마찬가지로 내부 허브를 관리하고 답변 및 효과적인 사용자 커뮤니케이션을 복제하는 데 노력했습니다. 동적 저장소의 필요성이 늘면서 작업 영역의 다기능성이 고객 참여를 혁신할 수 있다는 것을 깨닫게 되었습니다. 에서 작동 중인 대시보드의 기능을 수용하시기 바랍니다. [!DNL Adobe Analytics] 작업 영역. 사용자 경험을 개선하고 시간을 절약하며 보다 체계화된 환경을 누릴 수 있습니다. 이제 여정이 시작됩니다. 그리고 이러한 대시보드는 효율성과 사용자 친화성의 핵심입니다.

## 작성자

이 문서의 작성자:

![Christel Guidon](assets/Christel-Headshot-150.png)

**크리스텔 기돈**, 디지털 [!DNL Analytics] Gen의 플랫폼 관리자

[!DNL Adobe Analytics] 챔피언