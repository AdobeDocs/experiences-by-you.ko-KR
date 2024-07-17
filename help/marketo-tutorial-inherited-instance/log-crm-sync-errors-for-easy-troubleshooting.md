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
source-git-commit: b2e05ff39e065691dda530ed17762a55cf2e6778
workflow-type: tm+mt
source-wordcount: '408'
ht-degree: 0%

---

# 간편한 문제 해결을 위한 CRM 동기화 오류 기록

[!DNL Marketo Engage] 관리자는 인스턴스가 CRM과 동기화 상태인지 확인하는 것이 [일별 루틴](https://nation.marketo.com/t5/champion-program-blogs/my-marketo-morning-routine-tips-for-driving-marketing-operation/ba-p/247508){target="_blank"}의 핵심 부분이어야 합니다. [알림 섹션](https://experienceleague.adobe.com/docs/marketo/using/product-docs/core-marketo-concepts/miscellaneous/notification-types.html){target="_blank"}([!DNL Marketo Engage] 인터페이스의 오른쪽 상단 모서리에서 찾기)에서 자주 발생하는 동기화 문제를 찾아 조사하기 시작하지만 인스턴스 상태를 체계적으로 관리하는 데 도움이 되는 Pro 팁이 있습니다. [!DNL Adobe] Marketo 챔피언(2019-2022), Amy Goldfine은 관리자가 보다 쉽게 문제를 해결할 수 있도록 CRM 동기화 오류 로그를 유지할 것을 권장합니다.

![동기화 오류 탭의 스크린샷](/help/marketo-tutorial-inherited-instance/_assets/Marketo_Engage_Admin_Salesforce_Sync_Errors_Tab.png)

## CRM 동기화 오류를 기록하는 이유는 무엇입니까?

[!DNL Marketo Engage] 관리자는 CRM 동기화 오류를 기록하여 CRM 관리자와 함께 문제 및 추세를 검토하여 근본 원인을 해결할 수 있습니다. 인스턴스에 대한 CRM 동기화 문제를 문서화하려면 아래 단계를 따르십시오.

## CRM 동기화 오류 로그를 유지하는 방법

시작하기 전에 [CRM 동기화 오류 로그 서식 파일](/help/marketo-tutorial-inherited-instance/_assets/downloads/Adobe-Marketo-Engage_CRM-Sync-Error-Log-Template.xlsx)을 다운로드하십시오.

**1단계:** [!DNL Marketo Engage]의 *[!UICONTROL 관리자] 섹션*(으)로 이동 *[!UICONTROL 통합]*&#x200B;에서 사용하는 [!DNL CRM]에 따라 *[!DNL Salesforce]*, *[!DNL Microsoft Dynamics]* 또는 *[!DNL Veeva]*&#x200B;을(를) 클릭한 다음 *[!UICONTROL 동기화 오류]* 탭을 클릭합니다.

**2단계:** [!UICONTROL 필터] 패널을 통해 [오류 레코드를  [!DNL CSV] 파일로 내보내기](https://experienceleague.adobe.com/docs/marketo/using/product-docs/crm-sync/salesforce-sync/salesforce-sync-errors.html#filter-sync-errors){target="_blank"}하도록 선택할 수 있습니다. 몇 시간만 있으면 *[!UICONTROL 동기화 오류]* 탭에서 직접 복사하여 붙여 넣는 것이 좋습니다.

**3단계:** 오류가 발생한 날짜를 확인합니다.

**4단계:** 해당 오류의 영향을 받는 개인 레코드 수를 입력합니다. (경우에 따라 CRM에서 한 사람에 대해서만 오류가 발생합니다. 때로는 한 번에 동일한 오류를 가진 사람이 많을 것입니다.)

**5단계:** 오류의 영향을 받는 한 사람의 전자 메일 주소를 확인하세요. 이렇게 하면 CRM 관리자와 오류를 쉽게 참조하고 논의할 수 있습니다.

**6단계:** [!DNL Marketo Engage] 및 해당 사용자의 [!UICONTROL CRM 리드/연락처] 레코드에 있는 개인 레코드에 링크를 붙여 넣습니다.

**7단계:** 마지막 열에 오류의 실제 텍스트를 붙여 넣습니다.

## 다음은 무엇입니까?

**오류 코드 식별:** 오류 코드를 이해하려면 개발자 설명서 [응답 수준 오류 코드 테이블](https://developers.marketo.com/rest-api/error-codes/#response_level_error_codes){target="_blank"}에서 설명을 조회하고 오류를 해결하기 위한 일반적인 다음 단계를 찾으십시오.

## 작성자

**에이미 골드파인**\
[!DNL Adobe] Marketo 챔피언(2019-2022)
*설립자, MarketingOpsAdvice.com*

![에이미 골드파인](/help/marketo-tutorial-inherited-instance/_assets/authors/Customer_Author_Amy_Goldfine.png){width="25%"}

**에이미 추**
[!DNL Adobe]*의*&#x200B;채택 및 유지 마케팅 관리자

![에이미 추](/help/marketo-tutorial-inherited-instance/_assets/authors/Adobe_Author_Amy_Chiu.png){width="25%"}
