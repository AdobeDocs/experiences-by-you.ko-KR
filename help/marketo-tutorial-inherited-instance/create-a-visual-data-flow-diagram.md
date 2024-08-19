---
title: 마케팅 기술 스택을 이해하는 데이터 흐름 다이어그램 만들기
description: 데이터 세계를 이해하고, 인스턴스를 효율적으로 감사하고 정리하기 위해 "리드 및 데이터 소스"의 다이어그램을 만드는 방법을 알아봅니다.
feature-set: Marketo Engage
feature: Administration
role: Admin
level: Intermediate, Experienced
doc-type: Tutorial
last-substantial-update: 2023-10-16T00:00:00Z
jira: KT-13877
thumbnail: KT-13877.jpeg
hide: false
exl-id: 088bdcf1-4e49-44a7-ac78-a03742ff680b
source-git-commit: 1205848b1985a99b91f9d4d25e1a79f0df379589
workflow-type: tm+mt
source-wordcount: '569'
ht-degree: 2%

---

# 마케팅 기술 스택을 이해하는 데이터 흐름 다이어그램 만들기

수년 동안 라이브된 [!DNL Marketo Engage] 인스턴스를 인수하는 관리자로서 인스턴스를 효율적으로 감사하고 정리하는 것은 불가능한 임무와 같습니다. [!DNL Adobe] [!DNL Marketo Champion](2019), Kelly Jo Horton이 오래 지속된 인스턴스에 발을 들였을 때 [잠재 고객 및 데이터 소스 다이어그램 만들기](https://nation.marketo.com/t5/employee-blogs/understand-your-marketing-technology-and-data-create-this/ba-p/296774){target="_blank"}를 통해 데이터 세계를 숙지하는 방식으로 이 문제를 해결했습니다. 이 자습서에서는 Kelly Jo Horton이 공유하는 예제를 기반으로 빌드하여 고유한 데이터 흐름 다이어그램을 만드는 방법을 알아봅니다. 귀하의 MarTech 생태계에 대해 알아보겠습니다!

## 상속된 인스턴스에 대해 아키텍처 다이어그램을 만드는 이유는 무엇입니까?

1. **라이브 인스턴스에서 상속받은 마케팅 기술 스택에 대해 숙지합니다.** 새 회사에서 시작할 때 모든 마케팅 작업 관리자/플랫폼 작업 관리자가 이 연습을 수행하는 것이 좋습니다. 이 만들기 프로세스를 통해 관리자는 외부 통합에서 [!DNL Marketo Engage](으)로 전송된 데이터 및 활동의 전체 그림을 보고 API 오류를 쉽게 해결할 수 있습니다.
2. **외부 통합을 관리하는 주요 이해 당사자에 대해 숙지하십시오.** Kelly Jo Horton이 이해 당사자를 빠르게 식별하는 데 사용하는 팁은 API 사용자 목록을 참조하는 것입니다.
   1. **&#39;관리&#39; 섹션의 &#39;통합>LaunchPoint&#39; 탭으로 이동합니다.** &#39;LaunchPoint&#39; 탭으로 이동하는 방법에 대해 자세히 알아보세요. [REST API에 사용할 사용자 지정 서비스를 만듭니다](https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/additional-integrations/create-a-custom-service-for-use-with-rest-api.html){target="_blank"}.
   2. API 호출 정보 섹션의 통합>웹 서비스 탭에서 API 사용자별 API 사용 통계를 찾습니다. API 호출 번호를 클릭하면 각 사용자가 수행한 특정 개별 호출을 볼 수 있습니다.

## 이 시각적 데이터 흐름 다이어그램 연습을 수행하는 방법

### 1단계: 현재 상태 다이어그램

&quot;현재 상태&quot; 다이어그램을 만듭니다. 다음은 한 예입니다.

![현재 상태 다이어그램](/help/marketo-tutorial-inherited-instance/_assets/data-flow-diagram/Current_State_Lead_Data_Sources_KellyJo_Horton.png){align="center"}


### 2단계: 향후 상태 다이어그램

기술 및 시스템 로드맵을 비기술 이해 당사자에게 제시할 때 사용할 수 있는 &quot;미래 상태&quot; 다이어그램을 만듭니다. 다음은 한 예입니다.

![향후 상태 다이어그램](/help/marketo-tutorial-inherited-instance/_assets/data-flow-diagram/Future-State-Lead-Data-Sources-KellyJo-Horton.png){align="center"}

### 3단계: 기술 버전

각 통합에 대한 API 사용자 이름, [!DNL Marketo Engage](으)로 푸시되거나 [!DNL Marketo Engage]에서 가져오는 데이터 유형에 대한 간단한 설명, 미들웨어 흐름 및 트리거에 대한 세부 다이어그램과 같은 세부 정보를 표시하는 기술 버전을 만듭니다.  다음은 한 예입니다.

![기술 버전](/help/marketo-tutorial-inherited-instance/_assets/data-flow-diagram/Lead-Data-Source-Diagram-KellyJo-Horton.png){align="center"}


## 다음은 무엇입니까?

**예제 시작:**
샘플 데이터 흐름 다이어그램 중 하나를 다운로드하여 마케팅 기술 스택의 현재 상태, 개인 및 데이터 흐름을 매핑하거나 인스턴스를 감사할 때 데이터 전체에 대한 다이어그램을 처음부터 만듭니다.


<table style="table-layout:fixed">
   <tr>  
      <td style="border: 0;">
      <div style="text-align: center;">
          <a href="./_assets/downloads/Current_Future_State_Lead_Data_Sources.zip">
            <strong>현재 상태 및 향후 상태</strong>
         </a>
      </div>
      </td>
      <td style="border: 0;">
      <div style="text-align: center;">
         <a href="./_assets/downloads/Detailed_Layers_by_Functional_Category_Stacked_Technologies.zip">
         기능 범주 </strong>별 <strong>자세한 레이어   
         </a>
      </div>
      </td>
      <td style="border: 0;">
         <div style="text-align: center;">
         <a href="./_assets/downloads/Lead_Data_Source.zip">
           <strong>리드 및 데이터 Source 흐름 </strong>  
         </a>
         </div>
       </td> 
       <td style="border: 0;">
         <div style="text-align: center;">
         <a href="./_assets/downloads/Simple_World_Class_Stage_Stack.zip">
          <strong>간소화된 다이어그램</strong>  
         </a>
         </div>
        </td>  
   </tr>
   <tr>
    <td style="border: 0;">
         <div>
          <img alt="현재 상태 및 향후 상태 다이어그램" src="./_assets/Thumbnail_Current-Future State Lead_Data Sources_KellyJo_Horton.png"/>
         </a>
      </div>
      </td>
      <td style="border: 0;">
         <div>
         <a href="./_assets/downloads/Detailed_Layers_by_Functional_Category_Stacked_Technologies.zip">
         <img alt="기능 범주 다이어그램별 세부 계층" src="./_assets/Thumbnail_Detailed_Layers_by_Functional_Category_Stacked_Technologies_KellyJo_Horton.png" />
       </a>
         </div>
      </td>
       <td style="border: 0;">
         <div>
            <a href="./_assets/downloads/Lead_Data_Source.zip">
         <img alt="리드 및 데이터 Source 흐름 다이어그램" src="./_assets/Thumbnail_Lead-Data Source Diagram_KellyJo_Horton.png" />
         </a>
         </div>
      </td>
     <td style="border: 0;">
         <div>
            <a href="./_assets/downloads/Simple_World_Class_Stage_Stack.zip">
             <img alt="간소화된 다이어그램" src="./_assets/Thumbnail_Simple_World_Class_Stage_Stack.png" />
         </a>
         </div>
      </td>
</table>

사용할 수 있는 몇 가지 도구는 다음과 같습니다. draw.io(Google 문서), [!DNL Adobe] XD, Figma, Gliffy(Confluence)

**아키텍처 다이어그램이 이미 있으면 어떻게 합니까?**&#x200B;명의 새 팀원은 다양한 관점을 가질 수 있습니다. 새 [!DNL Marketo Engage] 관리자가 온보딩 프로세스의 일부로 이 연습을 수행하고 다른 사용자와 공유하도록 하는 것은 가치가 있습니다.

## 작성자

**켈리 조 호튼**\
[!DNL Adobe] Marketo 챔피언(2019)
*Etumos의 선임 클라이언트 파트너*

![켈리 조 호튼](/help/marketo-tutorial-inherited-instance/_assets/authors/Customer_Author_Kelly_Jo_Horton.png){width="30%"}

**에이미 추**
*채택 및 유지 마케팅 관리자,[!DNL Adobe]*

(/help/marketo-tutorial-inherited-instance/_assets/authors/[!DNL Adobe]_Author_Amy_Chiu.png){width=30%}
