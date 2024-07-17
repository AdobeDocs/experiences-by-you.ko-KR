---
title: 기본 CRM 커넥터의 필드 동기화
description: Marketo Engage에서 사용할 필수 CRM 필드를 전략적으로 선택하여 초기 CRM 통합을 간소화하는 방법을 알아봅니다. 데이터 사전 연습을 수행하여 원활한 CRM 동기화에 필요한 필드를 식별하여 영업 및 마케팅 팀이 계속 일치할 수 있도록 합니다.
role: Admin
level: Beginner
doc-type: Article
solution: Marketo Engage
duration: 0
last-substantial-update: 2024-05-04T00:00:00Z
jira: KT-14811
thumbnail: KT-14811.jpeg
exl-id: 42b7ca3d-e445-4c11-ad3d-d4e70c101c8e
source-git-commit: bed599454a75159492f13aab1f802c09d92bf7ed
workflow-type: tm+mt
source-wordcount: '1569'
ht-degree: 0%

---

# 기본 CRM 커넥터의 필드 동기화

조직 내에서 Salesforce 또는 Microsoft Dynamics를 사용하고 있습니까? 그렇다면 Marketo Engage의 기본 CRM 커넥터(예: Salesforce, Microsoft Dynamics 및 Veeva)를 사용하여 Marketo Engage과 CRM 간에 관련 정보를 원활하게 공유하여 마케팅 및 판매 활동을 조정할 수 있습니다. 초기 CRM 동기화를 구성하기 전에 Marketo Engage 데이터베이스를 깔끔하게 유지하기 위해 두 시스템 간에 동기화할 필드를 식별해야 합니다.

Adobe Professional Services에서 제안한 모범 사례를 사용하여 이 연습을 수행하는 방법에 대해 자세히 알아보십시오. 다음으로 표준 필드 및 사용자 정의 필드를 이해하고 Marketo Engage과 CRM 간의 관계를 문서화합니다.

## CRM을 Marketo Engage과 통합하기 전에 동기화할 필드를 식별하십시오.

CRM을 Marketo Engage과 통합할 때 모든 CRM 필드를 Marketo Engage에 동기화할 필요가 없을 수 있습니다. 필요한 필드에 대해 전략적으로 작업하면 Marketo Engage 인스턴스가 데이터 흐름을 보다 효율적으로 처리하는 데 도움이 될 수 있습니다.

Marketo Engage과 CRM 시스템 간의 초기 동기화는 대부분의 기존 표준 필드(예: 이메일, 이름/성, 회사 등)에 대한 연결을 자동으로 만듭니다. 또한 커넥터는 Marketo Engage에서 CRM의 해당 필드에 자동으로 매핑되는 새 필드를 만들어 잠재 고객, 연락처, 계정 및 기회에 대한 [사용자 지정 필드](https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/administration/field-management/custom-field-type-glossary){target="_blank"}를 동기화합니다.

초기 동기화를 수행하기 전에 CRM에서 동기화할 필드를 식별하고 구성하는 것은 기본 커넥터 설정 프로세스의 중요한 단계입니다. 이를 데이터 사전 연습이라고 하며, 이를 통해 생성되는 중복 필드 수를 최소화하고 후속 재매핑 단계를 최대한 원활하게 수행할 수 있습니다. 이 연습에는 일반적으로 마케팅 및 영업 팀과 CRM 관리자의 입력이 포함되어 관련 필드만 Marketo Engage 인스턴스에 동기화됩니다.

## 데이터 사전을 작성하는 방법

일반적으로 가장 좋은 방법은 마케팅 목적에 필요한 CRM 필드만 동기화하는 것입니다. 이 연습으로 시작하여 Marketo Engage에 매핑해야 하는 CRM의 필드를 구성하고 처음 CRM 동기화를 올바르게 실행하십시오.

>[!NOTE]
>CRM에 초기 동기화를 시작하기 전에 이미 Marketo Engage에 동등한 사용자 지정 필드가 있는 사용자 지정 필드가 있는 경우 CRM 필드의 Marketo Engage에 새 &quot;복제&quot; 필드가 만들어집니다. 초기 동기화가 완료되면 CRM 필드를 원래 Marketo Engage 필드에 다시 매핑하고 중복 필드를 숨길 수 있지만 [Adobe 고객 지원 센터](https://experienceleague.adobe.com/en/docs/customer-one/using/home#create-a-support-ticket-with-admin-console){target="_blank"}에 문의해야 합니다. 자세한 내용은 7단계 를 참조하십시오.

**1단계:** 현재 CRM에서 사용할 수 있는 대략적인 필드 목록을 작성하고 Marketo Engage에 표시할지 여부를 표시합니다.

* 의사 결정 프로세스에 CRM 관리자, 마케팅 및 영업 팀의 피드백을 포함합니다.
* 각 필드에 대한 API 이름 및 필드 유형을 문서화합니다.
* 이러한 필드(예: 읽기 전용 또는 읽기-쓰기)에 대해 Marketo Engage이 가져야 하는 액세스 수준을 결정합니다.


**2단계:** Marketo Engage 인스턴스의 [관리 > 필드 관리 섹션](https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/administration/field-management/view-field-mappings-between-marketo-and-salesforce){target="_blank"}을(를) 검토하여 동기화에 포함할 사용자 지정 필드를 시스템에서 직접 식별하십시오.

* 각 필드에 대한 API 이름 및 필드 유형을 문서화합니다.
* CRM에 이미 동등한 필드가 있는 필드를 나타냅니다.
* CRM에 동등 필드가 아직 없는 필드를 나타냅니다.


**3단계:** 기본 맵 필드를 사용하여 데이터 사전 작성을 시작합니다.

* Marketo Engage은 플랫 데이터베이스를 사용하므로 데이터 사전의 형식을 다음과 같이 지정하는 것이 좋습니다.

   * 첫 번째 열: Marketo Engage 필드 이름
   * 두 번째 열: Marketo Engage API 이름
   * 세 번째 열: [Marketo Engage 필드 형식](https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/administration/field-management/custom-field-type-glossary){target="_blank"}(예: 부울, 통화, 날짜 등)
   * 후속 열에서 CRM 객체 유형(가망 고객, 연락처, 계정, 기회)에 대해 을 반복하고 Marketo Engage에 원하는 액세스 수준(예: 읽기, 쓰기, 편집)에 대한 추가 열을 추가합니다.
  <br>

  다음은 그 모습의 샘플입니다.
  ![데이터 사전 테이블](/help/marketo-tutorial-implementing-new-instance/assets/data_dictionary.png){width="100%" zoomable="yes"}


* 먼저 CRM에 대해 자동으로 매핑될 기본 필드를 추가합니다.

   * [Salesforce](https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/default-salesforce-field-mapping){target="_blank"}
   * [Microsoft Dynamics](https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/crm-sync/microsoft-dynamics/microsoft-dynamics-sync-details/default-dynamics-field-mapping){target="_blank"}
   * [Veeva](https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/crm-sync/veeva-crm-sync/sync-details/default-veeva-field-mapping){target="_blank"}

* Marketo Engage의 각 기본 필드가 동기화할 CRM의 필드와 일치하는지 확인합니다. 예를 들어 Marketo Engage의 &quot;구독 취소됨&quot; 필드는 CRM의 &quot;이메일 옵트아웃&quot; 필드일 수 있습니다.
* 필요한 경우 CRM API 이름, 권한 및 [데이터 형식](https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/administration/field-management/custom-field-type-glossary){target="_blank"}을 조정합니다.

**4단계:** 데이터 사전에 추가 필드 추가

* 각 필드에 대한 표시 이름, 원하는 CRM 권한 및 데이터 유형을 포함합니다.
* CRM에 필드가 있지만 Marketo Engage에 없는 경우 CRM 필드의 동일한 값으로 Marketo Engage 표시 및 API 이름을 채웁니다.
* 필드가 Marketo Engage에 있지만 CRM은 아닌 경우 CRM 표시 이름을 원하는 값으로 채우되, 필드가 생성될 때까지 CRM API 이름을 비워 둡니다.
* 두 시스템에 동일한 필드가 있는 경우 동일한 줄에 해당 필드를 포함하고 데이터 사전 시트의 맨 오른쪽에 있는 &quot;메모&quot; 섹션에서 다시 매핑해야 함을 나타냅니다.

>[!NOTE]
>동기화 필터 필드([Salesforce](https://nation.marketo.com/t5/product-blogs/instructions-for-creating-a-custom-sync-rule/ba-p/242758){target="_blank"})를 만들 계획인 경우 | [Microsoft Dynamics](https://community.dynamics.com/blogs/post/?postid=8a91d93e-2181-45dd-a8fb-1092010bc8f1){target="_blank"})에서 이 단계에 API를 포함시키되 CRM에 필드가 만들어질 때까지 API 이름을 비워 두십시오.

**5단계:** CRM 관리자와 데이터 사전 검토

* CRM에서 Marketo Engage에 이미 있는 필드를 만들고 새 CRM 필드의 표시 및 API 이름으로 데이터 사전을 업데이트합니다.
* CRM의 잠재 고객과 연락처 개체 간에 필드 매핑을 수행합니다([Salesforce](https://nation.marketo.com/t5/product-blogs/instructions-for-creating-a-custom-sync-rule/ba-p/242758){target="_blank"}). | [Microsoft Dynamics](https://community.dynamics.com/blogs/post/?postid=8a91d93e-2181-45dd-a8fb-1092010bc8f1){target="_blank"}). 잠재 고객을 연락처로 전환하면 필드를 Marketo Engage의 단일 필드로 통합할 수 있습니다.
* Marketo 동기화 프로필에 데이터 사전에 명시된 각 필드에 대한 적절한 권한이 있는지 확인합니다.
   * [Salesforce에서 프로필 권한 설정](https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-2-of-3-create-a-salesforce-user-for-marketo-enterprise-unlimited#set-profile-permissions){target="_blank"}
   * [Microsoft Dynamics에서 프로필 권한 설정](https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/crm-sync/microsoft-dynamics/sync-setup/microsoft-dynamics-365-with-s2s-connection/step-2-of-3-set-up#create-application-user-in-microsoft){target="_blank"}
   * [Veeva에서 프로필 권한 설정](https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/crm-sync/microsoft-dynamics/sync-setup/microsoft-dynamics-365-with-s2s-connection/step-2-of-3-set-up#create-application-user-in-microsoft){target="_blank"}

**6단계:** 초기 동기화 수행

* Marketo Engage과 동기화하려는 모든 필드에 데이터 사전에 정의된 대로 CRM에서 적절한 권한이 있는지 확인하십시오.
* ***Marketo Engage과 동기화하지***&#x200B;하려는 모든 필드가 [Marketo 동기화 프로필에서 숨겨져 있는지 확인](https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/hide-a-salesforce-field-from-the-marketo-sync){target="_blank"}합니다. 실수로 동기화된 필드를 제거하는 것보다 새 필드를 동기화에 더 늦게 추가하는 것이 훨씬 더 쉽습니다.
* CRM을 동기화 필터 필드와 연결하시겠습니까? Salesforce에 동기화하는 경우 초기 동기화를 시작하기 전에 필터 기능이 켜져 있는지 확인하려면 Adobe 고객 지원 센터에 문의하십시오.


**7단계:** Marketo Engage의 필드 관리 섹션 검토

* 새로 동기화된 필드에 대한 표시 및 API 이름 을 확인/업데이트합니다.
* 다시 매핑이 필요할 수 있는 복제된 필드를 식별합니다. 복제된 필드는 다음과 같은 몇 가지 시나리오에서 발생합니다.
   * CRM의 사용자 지정 필드는 동등한 필드가 Marketo Engage에 이미 있는 경우 처음 동기화할 때 Marketo Engage에 새(잠재적으로 중복된) 필드를 만듭니다.
   * Marketo-Engage-Only 사용자 정의 필드(즉, Marketo Engage에서 직접 만든 필드)이며 CRM에서 이와 동등한 필드가 동기화될 수 있습니다.



**8단계:** 중복된 필드가 나타나면 Adobe 고객 지원 센터에 문의하여 다시 매핑을 수행하십시오

* 다시 매핑해야 하는 필드에 대한 다음 정보를 사용하여 지원 센터에 문의하십시오.
   * CRM에서 만든 새 중복 필드에 대한 표시 및 API 이름.
   * CRM 필드를 매핑할 Marketo Engage 필드의 표시 이름입니다.
   * 이 예제 [여기](https://nation.marketo.com/t5/knowledgebase/re-mapping-sfdc-marketo-fields/ta-p/299284){target="_blank"}를 참조하십시오.
* 재매핑이 완료되면 Marketo Engage에서 재매핑된 필드에 대한 API 이름을 검토하고 데이터 사전의 &quot;API 이름&quot; 열에 있는 값을 업데이트하여 가장 정확한 정보를 포함시킵니다.

## 다음은 무엇입니까?

* CRM 통합을 위해 필드를 구성하려면 데이터 사전을 작성하십시오.
* CRM의 초기 동기화 프로세스 숙지

>[!BEGINTABS]

>[!TAB Salesforce]

Marketo Engage과 Salesforce가 함께 판매와 마케팅 데이터를 동기화하는 방법에 대해 알아봅니다.

>[!VIDEO](https://video.tv.adobe.com/v/3424719/?learn=on)

+++**비디오에 사용된 링크:**

* [Salesforce 동기화 이해](https://experienceleague.adobe.com/docs/marketo/using/product-docs/crm-sync/salesforce-sync/understanding-the-salesforce-sync.html){target="_blank"}

* [Salesforce에 Marketo 필드 추가(Enterprise/Unlimited)](https://experienceleague.adobe.com/docs/marketo/using/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-1-of-3-add-marketo-fields-to-salesforce-enterprise-unlimited.html){target="_blank"}

* [Salesforce에서 Marketo 사용자 만들기(Enterprise/Unlimited)](https://experienceleague.adobe.com/docs/marketo/using/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-2-of-3-create-a-salesforce-user-for-marketo-enterprise-unlimited.html){target="_blank"}

* [Marketo 및 Salesforce(Enterprise/Unlimited) 연결](https://experienceleague.adobe.com/docs/marketo/using/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-3-of-3-connect-marketo-and-salesforce-enterprise-unlimited.html){target="_blank"}

* [사용자가 Marketo 및 Salesforce 동기화로 진행하기 전에 Salesforce 측에서 연결된 앱을 설정해야 합니다.](https://experienceleague.adobe.com/docs/marketo/using/product-docs/crm-sync/salesforce-sync/log-in-using-oauth-2-0.html){target="_blank"}

* [Salesforce 동기화 상태](https://experienceleague.adobe.com/docs/marketo/using/product-docs/crm-sync/salesforce-sync/salesforce-sync-status.html){target="_blank"}

* [필드 숨기기 및 숨기기 취소](https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/field-management/hide-and-unhide-a-field.html){target="_blank"}

* [자습서: Marketo을 CRM과 동기화하는 방법에 대해 알아보기](https://experienceleague.adobe.com/docs/marketo-learn/tutorials/lead-and-data-management/crm-sync-learn.html){target="_blank"}

+++

>[!TAB Microsoft Dynamics]

Microsoft Dynamics 365 동기화 작동 방식을 알아보고 두 시스템이 서로 통신할 수 있도록 설정을 올바르게 구성합니다.

>[!VIDEO](https://video.tv.adobe.com/v/3424737/?learn=on)

+++**비디오에 사용된 링크:**

* [Microsoft Dynamics 동기화 이해](https://experienceleague.adobe.com/docs/marketo/using/product-docs/crm-sync/microsoft-dynamics/understanding-the-microsoft-dynamics-sync.html){target="_blank"}

* [Marketo 리드 관리 솔루션 다운로드](https://experienceleague.adobe.com/docs/marketo/using/product-docs/crm-sync/microsoft-dynamics/sync-setup/download-the-marketo-lead-management-solution.html){target="_blank"}

* [Microsoft Dynamics용 Marketo 솔루션 업데이트](https://experienceleague.adobe.com/docs/marketo/using/product-docs/crm-sync/microsoft-dynamics/sync-setup/update-the-marketo-solution-for-microsoft-dynamics.html){target="_blank"}

* [클라이언트 Id 및 앱 등록에 동의](https://experienceleague.adobe.com/docs/marketo/using/product-docs/crm-sync/microsoft-dynamics/sync-setup/grant-consent-for-client-id-and-app-registration.html)

* [Microsoft Dynamics 동기화 확인](https://experienceleague.adobe.com/docs/marketo/using/product-docs/crm-sync/microsoft-dynamics/sync-setup/validate-microsoft-dynamics-sync.html){target="_blank"}

* [동기화 상태](https://experienceleague.adobe.com/docs/marketo/using/product-docs/crm-sync/microsoft-dynamics/microsoft-dynamics-sync-details/sync-status.html){target="_blank"}

* [Dynamics 유효성 검사 동기화 문제 해결](https://experienceleague.adobe.com/docs/marketo/using/product-docs/crm-sync/microsoft-dynamics/fix-dynamics-validation-sync-issues.html){target="_blank"}

* [사용자 지정 Dynamics 동기화 필터 만들기](https://experienceleague.adobe.com/docs/marketo/using/product-docs/crm-sync/microsoft-dynamics/custom-dynmaics-sync-filter-details/create-a-custom-dynamics-sync-filter.html){target="_blank"}

* [조직 서비스 URL 보기](https://experienceleague.adobe.com/docs/marketo/using/product-docs/crm-sync/microsoft-dynamics/sync-setup/view-the-organization-service-url.html){target="_blank"}

* [Dynamics에서 삭제하기 전에 동기화할 필드 편집](https://experienceleague.adobe.com/docs/marketo/using/product-docs/crm-sync/microsoft-dynamics/microsoft-dynamics-sync-details/editing-fields-to-sync-before-deleting-them-in-dynamics.html){target="_blank"}

* [자습서: Marketo을 CRM과 동기화하는 방법에 대해 알아보기](https://experienceleague.adobe.com/docs/marketo-learn/tutorials/lead-and-data-management/crm-sync-learn.html){target="_blank"}

+++

>[!ENDTABS]

### 작성자

{{peter-livadas}}

{{amy-chiu}}

