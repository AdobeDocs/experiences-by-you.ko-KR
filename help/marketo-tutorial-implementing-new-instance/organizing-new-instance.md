---
title: 새 인스턴스 구성 및 이름 지정 규칙 설정
description: Marketo Engage 인스턴스 내에 좋은 조직을 설정하여 조직 내의 향후 마케터가 프로그램을 쉽게 탐색하고, 자산을 수정하고, 보고서를 가져올 수 있는 방법을 알아봅니다.
role: Admin
level: Beginner
doc-type: Article
solution: Marketo Engage
duration: 0
last-substantial-update: 2024-05-03T00:00:00Z
jira: KT-14813
thumbnail: KT-14813.jpeg
exl-id: 19b3de9e-53f3-4308-b46e-7b8f756c30a0
source-git-commit: 1205848b1985a99b91f9d4d25e1a79f0df379589
workflow-type: tm+mt
source-wordcount: '1166'
ht-degree: 2%

---

# 새 인스턴스 구성 및 이름 지정 규칙 설정

새 Marketo Engage 인스턴스를 구현하는 관리자는 조직 내에서 향후 마케터가 인스턴스를 쉽게 탐색할 수 있는 기반을 다지고 있습니다. 트리 폴더 구조 및 이름 지정 규칙에 익숙해지면 인스턴스가 깔끔하게 유지되고 장기적인 성공을 위해 설정됩니다. 이 튜토리얼은 Adobe 및 Marketo Engage 챔피언(2019-2020), Natalie Kremer가 [폴더를 일관성 있게 구성하고 에셋의 이름을 지정](https://nation.marketo.com/t5/champion-program-blogs/keep-marketo-engage-organized-with-folders-and-naming/ba-p/245630){target="_blank"}하는 데 도움이 되는 예제를 포함합니다.

## 폴더를 구조화하고 이름 지정 규칙을 적용하는 것이 필요한 이유는 무엇입니까?

인스턴스에서 정돈되어 있으면 사용자와 동료가 캠페인, 프로그램 및 에셋을 쉽게 추적하고 프로그램 성과를 보고할 수 있습니다. 인스턴스에서 탐색 트리를 구성하고 규모에 맞게 빌드하려면 [폴더](https://experienceleague.adobe.com/ko/docs/marketo/using/product-docs/core-marketo-concepts/miscellaneous/understanding-folders){target="_blank"}, [표준 명명 규칙](https://experienceleague.adobe.com/ko/docs/marketo/using/product-docs/core-marketo-concepts/programs/working-with-programs/best-practice-how-to-organize-your-programs#naming-schemes){target="_blank"} 및 [복제](https://experienceleague.adobe.com/ko/docs/marketo/using/product-docs/core-marketo-concepts/programs/working-with-programs/best-practice-how-to-organize-your-programs#cloning){target="_blank"}와 같은 기능을 사용하는 것이 좋습니다.

## Marketo Engage 인스턴스 구성 방법

>[!VIDEO](https://video.tv.adobe.com/v/3422766/?quality=12&learn=on&captions=kor)

### 1단계 - 프로그램을 순서대로 배치하기 위한 폴더 구조 설정

인스턴스를 구성하는 첫 번째 단계는 [폴더 구조를 설정](https://experienceleague.adobe.com/docs/marketo/using/product-docs/core-marketo-concepts/miscellaneous/create-new-campaign-folder.html?lang=ko)하는 것입니다. 이 단계를 통해 프로그램 및 자산을 쉽고 질서 있게 찾을 수 있습니다.

다음은 트리에서 폴더를 구조화할 때의 몇 가지 빠른 팁입니다.

* 검색 기능을 위해 플랫 폴더 구조를 유지합니다.
* 조직의 팀 구조(예: 지역 또는 팀) 또는 이니셔티브(예: 뉴스레터)를 반영하도록 폴더를 구성합니다.
* 검색 기능을 활성화하고 적절한 아카이빙 시점(예: 2024)을 알리는 시간 기반 레이블을 포함하십시오.
   * 관리자는 적어도 1년에 한 번 폴더를 보관하는 것이 좋습니다. 연간 폴더 이름을 사용하면 라이브 스마트 캠페인을 쉽게 비활성화하고 연말에 전체 폴더를 보관할 수 있습니다.

다음은 이러한 팁을 실제로 적용하는 폴더 예입니다.

**트리의 폴더 이름**

>[!BEGINTABS]

>[!TAB 마케팅 활동]

![폴더 마케팅 활동](/help/marketo-tutorial-implementing-new-instance/assets/folders-marketing-activities.png)

>[!TAB 디자인 스튜디오]

![폴더 디자인 스튜디오](/help/marketo-tutorial-implementing-new-instance/assets/folders-design-studio.png)

>[!TAB 데이터베이스]

![폴더 데이터베이스](/help/marketo-tutorial-implementing-new-instance/assets/folders-database.png)

>[!ENDTABS]

### 2단계 - 프로그램 내 폴더 만들기

이제 프로그램 수준에서 폴더 구조를 적용해 보겠습니다. 가장 좋은 방법은 로컬 자산을 하위 폴더에 저장하는 것입니다. 프로그램을 깔끔하게 유지하고 내부 사용자가 프로그램을 효율적으로 수정하거나 보고할 수 있습니다. 일반적인 하위 폴더에는 이메일, 랜딩 페이지, 스마트 캠페인, 목록, 보고서 등이 포함됩니다.

**프로그램 내 폴더 이름**
* 캠페인 - *상호 작용 및 상태 추적을 관리하는 모든 캠페인용 폴더*
* 로컬 Assets - *이 프로그램과 관련된 모든 자산의 폴더입니다.*
   * 이메일
   * 랜딩 페이지
   * 스마트 캠페인
   * 목록 - *프로그램별 목록이 있는 경우에만 필요합니다.*
   * Forms - *프로그램별 Forms이 있는 경우에만 필요합니다. 대부분의 Forms은 글로벌 Assets입니다.*
   * 보고서 - *프로그램별 보고서가 있는 경우에만 필요합니다.*

### 3단계 - 프로그램 및 에셋에 대한 이름 지정 규칙 만들기

트리에 폴더 구조가 있으면 프로그램 및 에셋의 이름을 일관되게 지정할 수 있습니다. 이는 이름 지정 규칙을 표준화하는 것이 내부적으로 이름 지정 프로세스를 확장하는 데 도움이 되는 경우입니다. 다음은 검색 가능성을 보장하기 위해 명명 규칙을 설정하는 데 사용할 수 있는 몇 가지 구성 요소입니다.

* 프로그램 유형 약어 - 이메일, 콘텐츠, 육성, 웨비나 등
* 카테고리 - 프로그램 유형 - 독립 실행형 이메일, 뉴스레터 등
* 날짜 - 프로그램 시작 날짜
* 간단한 설명 - 프로그램에 대한 간단한 설명

이제 수식에 값을 입력하고 다양한 프로그램 유형에 대한 프로그램 이름을 생성해 보겠습니다.

#### 프로그램 명명 공식

| **프로그램 형식의 약어** | **YYYY** | **\-** | **MM** | **\-** | **DD(선택 사항)** | **범주** | **\-** | **프로그램에 대한 간단한 설명** |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| EM - 이메일 전송(이메일 프로그램) | YYYY | \- | MM | \- | DD(선택 사항) | 카테고리 | \- | 프로그램에 대한 간략한 설명 |
| NL - 뉴스레터 | YYYY | \- | MM | \- | DD(선택 사항) | 카테고리 | \- | 프로그램에 대한 간략한 설명 |
| 영어 - 참여 프로그램 | YYYY | \- | MM | \- | DD(선택 사항) | 카테고리 | \- | 프로그램에 대한 간략한 설명 |
| WBN - 웨비나 | YYYY | \- | MM | \- | DD(선택 사항) | 카테고리 | \- | 프로그램에 대한 간략한 설명 |
| IW - 대화형 웨비나 | YYYY | \- | MM | \- | DD(선택 사항) | 카테고리 | \- | 프로그램에 대한 간략한 설명 |
| TS - 박람회 | YYYY | \- | MM | \- | DD(선택 사항) | 카테고리 | \- | 프로그램에 대한 간략한 설명 |
| LE - 라이브 이벤트 (Roadshow) | YYYY | \- | MM | \- | DD(선택 사항) | 카테고리 | \- | 프로그램에 대한 간략한 설명 |
| UG - 사용자 그룹 | YYYY | \- | MM | \- | DD(선택 사항) | 카테고리 | \- | 프로그램에 대한 간략한 설명 |
| WC - 웹 사이트 컨텐츠 | YYYY | \- | MM | \- | DD(선택 사항) | 카테고리 | \- | 프로그램에 대한 간략한 설명 |
| CS - 컨텐츠 신디케이션 | YYYY | \- | MM | \- | DD(선택 사항) | 카테고리 | \- | 프로그램에 대한 간략한 설명 |
| LI - 목록 가져오기 | YYYY | \- | MM | \- | DD(선택 사항) | 카테고리 | \- | 프로그램에 대한 간략한 설명 |
| OA - 온라인 Advertising | YYYY | \- | MM | \- | DD(선택 사항) | 카테고리 | \- | 프로그램에 대한 간략한 설명 |
| PPC - 클릭당 과금 | YYYY | \- | MM | \- | DD(선택 사항) | 카테고리 | \- | 프로그램에 대한 간략한 설명 |

| **예** |
| --- |
| ES 2023-10 Gated Content - XYX 백서 |
| WC-2023-10- 월별 웨비나 - ABC 사례 연구 |

#### 자산 이름 지정 공식

에셋 이름을 지정하기 위해 한 수준 아래로 내려가면 프로그램 이름을 반복하지 않고 나중에 클론 작업을 사용할 때 짧은 및 일반 식별자를 사용하는 것이 좋습니다. 다음은 염두에 두어야 할 몇 가지 빠른 팁입니다.

* 프로그램 프로세스의 시퀀스에 따라 자산 번호를 매깁니다.
* 이름 지정 구성 요소를 &quot;.&quot; 대신 구분하려면 &quot;-&quot;(하이픈)을 사용합니다.(점) 또는 &quot;\_&quot;(밑줄)
   * 왜요? Marketo Engage은 점을 사용하여 프로그램 이름과 캠페인 이름을 구분합니다. 자산이 하이퍼링크될 때 &quot;\_&quot;를 사용하면 자산을 볼 수 없습니다.
* 에셋 이름에 표준 약어를 사용하여 참조를 단축하고 쉽게 인식할 수 있습니다.

이러한 점을 고려하여 다음 에셋에 이러한 팁을 적용하고 이름을 생성하는 공식을 생성하겠습니다.

##### 프로그램 프로세스의 시퀀스에 따라 에셋의 이름을 지정합니다.

| **프로그램 프로세스의 시퀀스** | **\-** | **설명** |
| --- | --- | --- |
| 01 | \- | 설명 |
| 02 | \- | 설명 |
| 03 | \- | 설명 |

| **예: 스마트 목록** |
| --- |
| 01-이메일 보내기 |
| 02-열림 |
| 03-클릭됨 |
| 04-작성된 양식 |
| 05-영향(프로그램 성공) |
| 06-구독 취소됨 |

##### 에셋 유형의 약어로 에셋의 이름을 지정합니다

| **에셋 유형의 약어** | **자산 유형** | **\-** | **목표 설명** |
| --- | --- | --- | --- |
| LP - 랜딩 페이지 | LP | \- | 목표 설명 |
| 이메일 - 이메일(아웃바운드) | EMAIL | \- | 목표 설명 |
| 경고 - 이메일 경고 | 경고 | \- | 목표 설명 |
| WF - 웹 양식 | WF | \- | 목표 설명 |
| EXCL - 제외 목록 | EXCL | \- | 목표 설명 |
| SLST - 스마트 목록 | SLST | \- | 목표 설명 |
| LST - 정적 목록 | LST | \- | 목표 설명 |

| **예** |
| --- |
| LP-등록 |
| LP-감사 |
| 이메일 아웃바운드 |
| 이메일 뉴스레터 |
| EMAIL-Invitation |
| 이메일 미리 알림 |
| 경쟁 제품 제외 |

##### 다운로드 가능한 파일(.pdf)에 에셋 유형의 약어로 이름을 지정합니다

| **자산 유형** | **콘텐츠 설명** | **\-** | **에셋 유형의 약어** | **.** | **PDF** |
| --- | --- | --- | --- | --- | --- |
| WP - 백서 | 컨텐츠 설명 | \- | WP | . | pdf |
| CS - 사례 연구 | 컨텐츠 설명 | \- | CS | . | pdf |
| DS - Data Sheet | 컨텐츠 설명 | \- | DS | . | pdf |

| **예: 다운로드 가능한 PDF 파일** |
| --- |
| XYZ-Gadget-DS.pdf |
| Acme-Company-CS.pdf |
| How-XYZ-Gadgets-make-life-easier-WP.pdf |

>[!CAUTION]
>
>위의 예에서 파일 이름을 지정할 때 공백을 사용하지 말고 밑줄 &quot;\_&quot;를 사용하지 마십시오

## 다음은 무엇입니까?

* [조직 및 이름 지정 규칙 Marketo Engage](./assets/adobe-marketo-engage-organization-and-naming-conventions.xlsx){target="_blank"} 워크시트를 다운로드하여 폴더 구조 및 이름 지정 규칙 만들기를 지원합니다.
* 표준 명명 규칙에서 필요한 구성 요소를 결정하면 Google Sheet 또는 Microsoft Excel로 공식을 작성하는 것이 좋습니다. 나중에 사용하려면 스프레드시트에 값을 입력하여 프로그램 이름을 생성하면 됩니다.
* 전반적인 폴더 구조를 파악한 후에는 팀에서 가장 자주 사용하는 사용 사례와 가장 일반적인 요청을 바탕으로 필요한 템플릿을 고려해야 합니다. 그런 다음 첫 번째 프로그램 템플릿 작성을 시작합니다. [Adobe Marketo Engage 프로그램 템플릿](https://business.adobe.com/blog/how-to/get-started-with-marketo-engage-program-templates){target="_blank"}을(를) 시작하려면 계속 읽으십시오.

### 작성자

{{natalie-kremer}}

{{amy-chiu}}
