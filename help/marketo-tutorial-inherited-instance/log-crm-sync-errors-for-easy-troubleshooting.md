---
title: 간편한 문제 해결을 위한 CRM 동기화 오류 기록
description: CRM 동기화 오류 로그를 사용하여 CRM 동기화 문제를 조사하고 원활하게 실행하는 방법에 대해 알아봅니다.
feature-set: Marketo Engage
feature: Administration
role: Admin
level: Intermediate, Experienced
doc-type: Tutorial
last-substantial-update: 2023-10-16T00:00:00Z
jira: KT-13875
thumbnail: KT-13875.jpeg
hide: false
exl-id: 6a38f5dd-5d25-43d8-a1d3-e75ab396e555
source-git-commit: 058d26bd99ab060df3633fb32f1232f534881ca4
workflow-type: tm+mt
source-wordcount: '423'
ht-degree: 0%

---

# 간편한 문제 해결을 위한 CRM 동기화 오류 기록

로서의 [!DNL Marketo Engage] 관리자, 인스턴스가 CRM과 동기화 상태인지 확인하는 것은 [일상](https://nation.marketo.com/t5/champion-program-blogs/my-marketo-morning-routine-tips-for-driving-marketing-operation/ba-p/247508){target="_blank"}. While the [Notifications section](https://experienceleague.adobe.com/docs/marketo/using/product-docs/core-marketo-concepts/miscellaneous/notification-types.html){target="_blank"} (위치 오른쪽 상단에서 찾기 [!DNL Marketo Engage] 인터페이스)는 자주 발생하는 동기화 문제를 찾아 조사하는 곳입니다. 인스턴스 상태를 체계적으로 관리하는 데 도움이 되는 pro 팁이 있습니다. [!DNL Adobe] Marketo Champion(2019-2022), Amy Goldfine은 관리자가 보다 쉽게 문제를 해결할 수 있도록 CRM 동기화 오류 로그를 유지할 것을 권장합니다.

![동기화 오류 탭의 스크린샷](/help/marketo-tutorial-inherited-instance/_assets/Marketo_Engage_Admin_Salesforce_Sync_Errors_Tab.png)

## CRM 동기화 오류를 기록하는 이유는 무엇입니까?

CRM 동기화 오류를 기록하여 [!DNL Marketo Engage] 관리자는 CRM 관리자와 함께 문제 및 트렌드를 검토하여 근본 원인을 해결할 수 있습니다. 인스턴스에 대한 CRM 동기화 문제를 문서화하려면 아래 단계를 따르십시오.

## CRM 동기화 오류 로그를 유지하는 방법

시작하기 전에 [CRM 동기화 오류 로그 템플릿](/help/marketo-tutorial-inherited-instance/_assets/downloads/Adobe-Marketo-Engage_CRM-Sync-Error-Log-Template.xlsx).

**1단계:** 로 이동 *[!UICONTROL 관리자] 섹션* 위치: [!DNL Marketo Engage]. 아래 *[!UICONTROL 통합]*, 클릭 *[!DNL Salesforce]*, *[!DNL Microsoft Dynamics]*, 또는 *[!DNL Veeva]*, 다음에 따라 [!DNL CRM] 을 사용하고 *[!UICONTROL 동기화 오류]* 탭.

**2단계:** 다음을 선택할 수 있습니다. [오류 레코드를 다음으로 내보내기 [!DNL CSV] 파일 스루 [!UICONTROL 필터] 패널](https://experienceleague.adobe.com/docs/marketo/using/product-docs/crm-sync/salesforce-sync/salesforce-sync-errors.html#filter-sync-errors){target="_blank"}. 몇 시간만 있으면 다음에서 바로 복사하여 붙여넣습니다. *[!UICONTROL 동기화 오류]* 탭으로 가는 것이 좋을 것 같습니다

**3단계:** 오류가 발생한 날짜를 확인합니다.

**4단계:** 해당 오류의 영향을 받는 개인 레코드 수를 입력합니다. (경우에 따라 CRM에서 한 사람에 대해서만 오류가 발생합니다. 때로는 한 번에 동일한 오류를 가진 사람이 많을 것입니다.)

**5단계:** 오류의 영향을 받는 한 사람의 이메일 주소를 메모하십시오. 이렇게 하면 CRM 관리자와 오류를 쉽게 참조하고 논의할 수 있습니다.

**6단계:** [!DNL]에 있는 개인 레코드에 링크 붙여넣기 [!DNL Marketo Engage]] 및 [!UICONTROL CRM 리드/연락처] 그 사람의 기록.

**7단계:** 마지막 열에 오류의 실제 텍스트를 붙여넣습니다.

## 다음은 무엇입니까?

**오류 코드 식별:** 오류 코드를 이해하려면 개발자 설명서에서 설명을 조회합니다 [응답 수준 오류 코드 테이블](https://developers.marketo.com/rest-api/error-codes/#response_level_error_codes){target="_blank"} 일반적인 다음 단계를 찾아 오류를 해결하십시오.

## 작성자

**에이미 골드파인**\
[!DNL Adobe] Marketo 챔피언(2019-2022)
*설립자, MarketingOpsAdvice.com*

![에이미 골드파인](/help/marketo-tutorial-inherited-instance/_assets/authors/Customer_Author_Amy_Goldfine.png){width="25%"}

**에이미 추**
*채택 및 유지 마케팅 관리자[!DNL Adobe]*

![에이미 추](/help/marketo-tutorial-inherited-instance/_assets/authors/Adobe_Author_Amy_Chiu.png){width="25%"}
