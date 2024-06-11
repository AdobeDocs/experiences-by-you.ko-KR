---
title: 설명서를 사용하여 인스턴스 거버넌스 안내서 개발
description: 에 대한 설명서 및 변경 로그를 만들고 유지 관리하는 강력한 절차를 설정하는 방법에 대해 알아봅니다. [!DNL Marketo Engage] 인스턴스. 이렇게 하면 팀의 지식 공유에 드는 시간이 절약될 뿐만 아니라 인스턴스의 상태와 효율성도 향상됩니다.
feature-set: Marketo Engage
feature: Administration
role: Admin
level: Intermediate, Experienced
doc-type: Tutorial
last-substantial-update: 2023-10-16T00:00:00Z
jira: KT-14103
thumbnail: KT-14103.jpeg
hide: false
exl-id: e127b84d-ef92-4527-a0e6-a36af35b7ee0
source-git-commit: b2e05ff39e065691dda530ed17762a55cf2e6778
workflow-type: tm+mt
source-wordcount: '895'
ht-degree: 0%

---

# 설명서를 사용하여 인스턴스 거버넌스 안내서 개발

레거시로 이동할 때 [!DNL Marketo Engage] 예를 들어, 최신 기능 및 기술 설명서가 부족하다는 문제가 종종 수반됩니다. 관리자로서 적절한 인스턴스 거버넌스를 보장하기 위한 지침을 수립하는 것은 간과할 수 없는 핵심 책임입니다. 이는 다음과 같은 중요한 전략 중 하나입니다. [기존 환경에서 작업할 때 효율성 향상 [!DNL Marketo Engage] 인스턴스](https://nation.marketo.com/t5/champion-program-blogs/3-tips-to-increase-your-efficiency-in-an-inherited-instance/ba-p/247582).

[!DNL]에서 가져온 이 단계별 자습서 [!DNL Adobe] Marketo Champion] (2018), Nick Hajdin이 인스턴스 설정을 간략히 설명하고, 기본 운영 프로그램을 문서화하고, [!DNL changelog] 엄격한 거버넌스 정책을 시행하기 위해.

## 상속된 인스턴스에 대한 인스턴스 거버넌스 안내서 및 설명서를 개발하는 이유는 무엇입니까?

자세한 설명서 및 [!DNL changelog] 효율적인 관리 및 지식 전달에 필수적입니다. [!DNL Marketo Engage] 인스턴스. 인스턴스 설정 중에 변경한 사항과 결정을 추적하면 다음과 같은 이점이 있습니다.

1. 확장 가능한 방식으로 내부 사용자를 보다 쉽게 교육합니다.
2. 에서 보다 효율적으로 구축 [!DNL Marketo Engage] 장기적으로.
3. 이메일을 파헤치는 데 드는 시간을 줄이기 위해 인스턴스의 건강과 위생을 유지하십시오. [감사 추적](https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/audit-trail/audit-trail-overview.html), 및 [활동 로그](https://experienceleague.adobe.com/docs/marketo/using/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/locate-the-activity-log-for-a-person.html) 컨텍스트를 가져옵니다.
4. 전송 시간 절약 [!DNL Marketo Engage] 새로운 사용자에게 지식 제공 [!DNL Marketo Engage] 팀에게 이직이 발생하는 경우 관리자

## [!DNL Marketo Engage] 거버넌스 안내서 101

거버넌스 가이드는 인스턴스 설정 및 시스템 디자인 요구 사항에 대한 진실의 소스 역할을 합니다. 이 문서에 포함하기 권장되는 주요 정보는 다음과 같습니다.

* 프로그램/폴더 구조
* 사용자 및 역할 권한
* 커뮤니케이션 제한
* 거버넌스 표준
* 플랫폼에 대한 액세스 권한을 부여하기 전에 내부 사용자 교육

## 에 대한 거버넌스 안내서 개발 및 유지 관리 방법 [!DNL Marketo Engage] 인스턴스

### 1단계: 거버넌스 안내서 및 설명서의 현재 상태 식별

* **상속된 인스턴스에 대한 설명서를 찾을 수 없습니다.** 최근에 새 역할을 시작했는데 상속된 인스턴스에 대한 설명서를 찾을 수 없는 경우 **2단계로 이동** 제공되는 다운로드 가능한 템플릿을 사용해 보십시오.
* **다음 파일에 대한 설명서가 있습니다.** 축하합니다, 좋은 징조입니다! 마지막 변경 사항이 언제 수행되는지 보려면 관련 사항을 검토해야 합니다. 팀 구성원이 적극적으로 유지 관리하고 있지 않은 경우 새로 고치고 내부 사용자에게 최신 상태를 유지하는 방법을 교육하는 것이 좋습니다.

### 2단계: 다음에 포함될 요소 식별 [!DNL Marketo Engage] 설명서 및 [!DNL Changelogs]

형식은 클라우드 기반 플랫폼부터 공유 문서까지 다양합니다. 조직의 요구 사항에 맞는 형식을 디자인할 수 있습니다. [다음은 간단한 설명서 및 변경 로그 Excel 템플릿입니다](/help/marketo-tutorial-inherited-instance/_assets/downloads/Adobe_Marketo_Engage_Inherited_Instance_Documentation-Changlog.xlsx) 시작할 수 있는 중요한 요소를 설명합니다. 여기에는 다음이 포함됩니다.

* 설명서
   * 프로그램 템플릿 이름
   * 채널
   * 만든 날짜
   * 제작자
   * 프로그램 목적
   * 상태
   * 프로그램 템플릿 링크
   * 참고 사항
* 변경 로그
   * 프로그램 템플릿 이름
   * 변경 날짜
   * 업데이트한 사람
   * 업데이트 목적
   * 변경 전 경험(링크/스크린샷 포함)
   * 변경 후 경험(링크/스크린샷 포함)
   * 프로그램 URL

### 3단계: 주요 운영 프로그램의 현재 상태 파악 및 문서화

먼저 구독 수준에 영향을 미치는 주요 운영 프로그램을 식별합니다. 데이터 관리 등을 예로 들 수 있습니다 [!DNL Campaign]s, Lead Lifecycle, Lead Scoring, [!DNL CRM] 동기화 및 전달성.

식별된 각 운영 프로그램에 대해 현재 상태를 문서화합니다. 여기에는 프로그램의 목적, 설정, 관련 스마트 캠페인 및 다른 도구와의 통합(해당되는 경우)에 대한 세부 정보가 포함됩니다.

### 4단계: 시행 [!DNL Changelog] 유지 관리

다음 단계는 사용자를 위한 엄격한 거버넌스 정책을 수립하는 것입니다. [!DNL Marketo Engage] &quot;&quot;을(를) 지정하는 인스턴스[!DNL Changelog] 유지 관리.&quot; 이 정책은 인스턴스 전체의 운영 프로그램에 대한 모든 업데이트를 철저히 문서화합니다.

팀원에게 이러한 문서의 중요성과 문서에 액세스하고 올바르게 업데이트하는 방법을 교육합니다. 변경 로그 유지 관리에 대한 책임을 할당하는 것이 도움이 될 수 있으므로 소수의 지정된 마케팅 운영 팀원 또는 관리자가 지속적으로 변경 사항을 기록하고 사인오프를 제공합니다.

### 5단계: 설명서 중앙 집중화

와(과) 관련된 모든 문서를 저장하기 위한 중앙 위치 또는 저장소 설정 [!DNL Marketo Engage] 인스턴스. 공유 드라이브, 전용 폴더 또는 클라우드 기반 시스템일 수 있습니다.

### 6단계: 정기적으로 검토 및 업데이트

설명서의 정기 검토를 예약하여 정확하고 최신 상태로 유지하십시오. 바쁜 시간에는 쉽게 간과될 수 있습니다. 미리 알림 메시지를 달력에 설정하여 팀이 운영 프로그램의 모든 변경 또는 최적화를 반영하도록 정기적으로 업데이트합니다.

## 다음은 무엇입니까?

다운로드 시작 [단순 템플릿](/help/marketo-tutorial-inherited-instance/_assets/downloads/Adobe_Marketo_Engage_Inherited_Instance_Documentation-Changlog.xlsx).

위의 단계에 따라 거버넌스 안내서 및 설명서를 개발하십시오. 프로세스를 진행하면서 다음 경험 규칙을 염두에 두십시오.

**기존 설명서를 업데이트합니다.**
설명서를 최신 상태로 유지하는 것이 중요합니다. 지난 3년 동안 수정되지 않은 경우 인스턴스를 감사할 때 설명서를 수정하는 데 시간을 투자하십시오.

**공유 및 교육:**
설명서 공유 및 [!DNL changelog] 관련 팀원과 함께 이러한 기록을 업데이트하는 방법에 대해 교육합니다.

**정기 검토:** 새로운 변경, 최적화 또는 조정이 발생할 때 이를 포함하도록 1년 내내 검토하고 유지할 시간을 미리 예약합니다.

포괄적인 최신 설명서 유지 관리 [!DNL Marketo Engage] 인스턴스는 장기적으로 시간과 노력을 절약하고 효과적인 인스턴스 관리를 용이하게 합니다.

### 작성자

**닉 하즈딘**
[!DNL [!DNL Adobe] Marketo 챔피언] (2018)
*[!DNL Digital Technology Senior Manager at Accenture]*

![닉 하즈딘](/help/marketo-tutorial-inherited-instance/_assets/authors/Customer_Author_Nicholas_Hajdin.png){width="30%"}

**에이미 추**
*채택 및 유지 마케팅 관리자,[!DNL Adobe]*

![에이미 추](/help/marketo-tutorial-inherited-instance/_assets/authors/Adobe_Author_Amy_Chiu.png){width=30%}
