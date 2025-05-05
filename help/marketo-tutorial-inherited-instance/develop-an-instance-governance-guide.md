---
title: 설명서를 사용하여 인스턴스 거버넌스 안내서 개발
description: ' [!DNL Marketo Engage] 인스턴스의 설명서 및 변경 로그를 만들고 유지 관리하는 강력한 절차를 설정하는 방법에 대해 알아봅니다.'
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
source-git-commit: 1205848b1985a99b91f9d4d25e1a79f0df379589
workflow-type: tm+mt
source-wordcount: '874'
ht-degree: 0%

---

# 설명서를 사용하여 인스턴스 거버넌스 안내서 개발

기존 [!DNL Marketo Engage] 인스턴스를 시작할 때 최신 기능 및 기술 설명서가 부족하다는 문제가 종종 발생합니다. 관리자로서 적절한 인스턴스 거버넌스를 보장하기 위한 지침을 수립하는 것은 간과할 수 없는 핵심 책임입니다. [설정된 [!DNL Marketo Engage] 인스턴스](https://nation.marketo.com/t5/champion-program-blogs/3-tips-to-increase-your-efficiency-in-an-inherited-instance/ba-p/247582)에서 작업할 때 효율성을 높이는 중요한 전략 중 하나입니다.

[!DNL [!DNL Adobe] Marketo Champion] (2018)에서 가져온 이 단계별 자습서는 Nick Hajdin이 인스턴스 설정을 간략히 설명하고, 기본 운영 프로그램을 문서화하고, [!DNL changelog]을(를) 유지 관리하여 엄격한 거버넌스 정책을 적용하는 프로세스를 안내합니다.

## 상속된 인스턴스에 대한 인스턴스 거버넌스 안내서 개발

자세한 설명서와 [!UICONTROL Changelog]는 [!DNL Marketo Engage] 인스턴스 내에서 효율적인 관리와 지식 전달에 필수적입니다. 인스턴스 설정 중에 변경한 사항과 결정을 추적하면 다음과 같은 이점이 있습니다.

1. 확장 가능한 방식으로 내부 사용자를 보다 쉽게 교육합니다.
2. 장기적으로 [!DNL Marketo Engage]에서 보다 효율적으로 빌드합니다.
3. 이메일, [감사 추적](https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/audit-trail/audit-trail-overview.html) 및 [활동 로그](https://experienceleague.adobe.com/docs/marketo/using/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/locate-the-activity-log-for-a-person.html)를 검색하는 데 걸리는 시간을 줄이기 위해 인스턴스의 상태 및 위생 상태를 유지하세요.
4. 팀에 이직이 있는 경우 새 [!DNL Marketo Engage] 관리자에게 [!DNL Marketo Engage] 지식을 전송하는 데 시간을 절약하십시오.

## [!DNL Marketo Engage] 거버넌스 안내서 101

거버넌스 가이드는 인스턴스 설정 및 시스템 디자인 요구 사항에 대한 진실의 소스 역할을 합니다. 이 문서에 포함하기 권장되는 주요 정보는 다음과 같습니다.

* 프로그램/폴더 구조
* 사용자 및 역할 권한
* 커뮤니케이션 제한
* 거버넌스 표준
* 플랫폼에 대한 액세스 권한을 부여하기 전에 내부 사용자 교육

## [!DNL Marketo Engage] 인스턴스에 대한 거버넌스 안내서를 개발 및 유지 관리하는 방법

### 1단계: 거버넌스 안내서 및 설명서의 현재 상태 식별

* **상속된 인스턴스에 대한 설명서를 찾을 수 없습니다.** 최근에 새 역할을 시작했지만 상속된 인스턴스에 대한 설명서를 찾을 수 없는 경우 **2** 단계로 이동하여 제공된 다운로드 가능한 템플릿을 시작하십시오.
* **다음 파일에 대한 설명서를 가지고 있습니다.** 축하합니다. 좋은 징조입니다! 마지막 변경 사항이 언제 수행되는지 보려면 관련 사항을 검토해야 합니다. 팀 구성원이 적극적으로 유지 관리하고 있지 않은 경우 새로 고치고 내부 사용자에게 최신 상태를 유지하는 방법을 교육하는 것이 좋습니다.

### 2단계: [!DNL Marketo Engage] 설명서 및 [!DNL Changelogs]에 포함할 요소 식별

형식은 클라우드 기반 플랫폼부터 공유 문서까지 다양합니다. 조직의 요구 사항에 맞는 형식을 디자인할 수 있습니다. [시작할 수 있는 중요한 요소를 다루는 간단한 설명서 및 변경 로그 Excel 서식 파일입니다](/help/marketo-tutorial-inherited-instance/_assets/downloads/Adobe_Marketo_Engage_Inherited_Instance_Documentation-Changlog.xlsx). 여기에는 다음이 포함됩니다.

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

먼저 구독 수준에 영향을 미치는 주요 운영 프로그램을 식별합니다. 예를 들면 데이터 관리 [!DNL Campaign], 리드 라이프사이클, 리드 점수, [!DNL CRM] 동기화 및 게재 가능성이 있습니다.

식별된 각 운영 프로그램에 대해 현재 상태를 문서화합니다. 여기에는 프로그램의 목적, 설정, 관련 스마트 캠페인 및 다른 도구와의 통합(해당되는 경우)에 대한 세부 정보가 포함됩니다.

### 4단계: [!UICONTROL 변경 로그] 유지 관리 적용

다음 단계는 &quot;[!UICONTROL Changelog] 유지 관리&quot;를 요구하는 [!DNL Marketo Engage] 인스턴스에 대해 엄격한 거버넌스 정책을 설정하는 것입니다. 이 정책은 인스턴스 전체의 운영 프로그램에 대한 모든 업데이트를 철저히 문서화합니다.

팀원에게 이러한 문서의 중요성과 문서에 액세스하고 올바르게 업데이트하는 방법을 교육합니다. 변경 로그 유지 관리에 대한 책임을 할당하는 것이 도움이 될 수 있으므로 소수의 지정된 마케팅 운영 팀원 또는 관리자가 변경 사항을 지속적으로 기록하고 승인을 제공합니다.

### 5단계: 설명서 중앙 집중화

[!DNL Marketo Engage] 인스턴스와 관련된 모든 문서를 저장할 중앙 위치 또는 저장소를 설정합니다. 공유 드라이브, 전용 폴더 또는 클라우드 기반 시스템일 수 있습니다.

### 6단계: 검토 및 업데이트

설명서의 정기 검토를 예약하여 정확하고 최신 상태로 유지하십시오. 바쁜 시간에는 쉽게 간과될 수 있습니다. 미리 알림 메시지를 달력에 설정하여 팀이 운영 프로그램의 모든 변경 또는 최적화를 반영하도록 정기적으로 업데이트합니다.

## 다음은 무엇입니까?

이 [단순 템플릿](/help/marketo-tutorial-inherited-instance/_assets/downloads/Adobe_Marketo_Engage_Inherited_Instance_Documentation-Changlog.xlsx)을(를) 다운로드하여 시작하십시오.

위의 단계에 따라 거버넌스 안내서 및 설명서를 개발하십시오. 프로세스를 진행하면서 다음 경험 규칙을 염두에 두십시오.

**기존 설명서 업데이트:**
설명서를 최신 상태로 유지하는 것이 중요합니다. 지난 3년 동안 수정되지 않은 경우 인스턴스를 감사할 때 설명서를 수정하는 데 시간을 투자하십시오.

**공유 및 교육:**
관련 팀원과 설명서 및 [!DNL changelog]을(를) 공유하고 이러한 레코드를 업데이트하는 방법을 교육합니다.

**정기적 검토:** 새로운 변경, 최적화 또는 조정 내용을 포함하도록 1년 내내 검토하고 유지 관리할 시간을 미리 예약합니다.

[!DNL Marketo Engage] 인스턴스에 대한 포괄적이고 최신 설명서를 유지하면 장기적으로 시간과 노력을 절약하고 효과적인 인스턴스 관리를 용이하게 할 수 있습니다.

### 작성자

**Nick Hajdin**
[!DNL [!DNL Adobe] Marketo Champion] (2018)
*[!DNL Digital Technology Senior Manager at Accenture]*

![Nick Hajdin](/help/marketo-tutorial-inherited-instance/_assets/authors/Customer_Author_Nicholas_Hajdin.png){width="30%"}

**에이미 추**
*채택 및 유지 마케팅 관리자,[!DNL Adobe]*

![에이미 주](/help/marketo-tutorial-inherited-instance/_assets/authors/Adobe_Author_Amy_Chiu.png){width=30%}
