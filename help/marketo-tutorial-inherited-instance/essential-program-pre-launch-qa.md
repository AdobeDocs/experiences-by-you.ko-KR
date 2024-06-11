---
title: 필수 프로그램 사전 실행 품질 보증 QA 프로세스
description: 내부 팀이 프로그램을 보다 정확하고 효율적으로 구축하고 실행할 수 있도록 프로그램 실행 전 QA 프로세스를 개발하는 방법에 대해 알아봅니다.
feature-set: Marketo Engage
feature: Administration
role: Admin
level: Intermediate, Experienced
doc-type: Tutorial
last-substantial-update: 2023-10-16T00:00:00Z
jira: KT-13888
thumbnail: KT-13888.jpeg
hide: false
exl-id: c377fe5f-2d77-4fd0-9ac4-5ad65506f582
source-git-commit: b2e05ff39e065691dda530ed17762a55cf2e6778
workflow-type: tm+mt
source-wordcount: '4903'
ht-degree: 2%

---

# 성공을 위한 필수 프로그램 출시 전 품질 보증 프로세스

다음과 같은 경우 [!DNL Marketo Engage] 관리자 또는 마케팅 운영 팀에서 프로그램 구성을 제대로 검토하는 것은 고객에게 닥친 실수를 피하기 위해 중요합니다. 실수를 제한하는 과정에서 실수를 통해 배울 수 있지만 확장 가능한 프로세스는 아닙니다. 빌더와 고급 사용자/검토자 간에 프로그램 사전 실행 품질 보증(QA) 프로세스를 설계 및 실행하는 방법은 시간을 절약하고, 오류를 방지하며, 내부 사용자를 보다 신속하게 교육하는 데 도움이 됩니다.

이 튜토리얼에서는 [!DNL Marketo Engage] 관리자는 프로그램 시작 전 QA 프로세스를 개발하여 내부 팀의 확장을 지원할 수 있습니다. 다음에서 가져온 프로그램 실행 전 체크리스트 [!DNL Adobe] Marketo 챔피언(2021), [그레이스 브레브너의 블로그 게시물](https://nation.marketo.com/t5/champion-program-blogs/the-ultimate-go-live-checklist/ba-p/245759)는 주요 요소 및 요구 사항을 안내하는 예제로 사용됩니다.

## 프로그램 사전 실행 QA 프로세스를 디자인해야 하는 이유는 무엇입니까?

보다 최신 버전인 경우 [!DNL Marketo Engage], 프로그램을 작성할 때 확인해야 할 사항을 모를 수 있습니다. 계절에도 [!DNL Marketo Engage] 당신의 기억에 근거한 프로그램을 검토하는 것은 위험합니다. 이 때 프로그램 실행 전 확인 목록 이 실행됩니다. 이는 프로그램 QA 프로세스를 보다 원활하게 수행하는 데 도움이 될 뿐만 아니라 빌더가 일반적인 문제를 주의하도록 교육합니다.

* **시간 절약:** QA 프로세스가 확립되지 않으면 궁극적으로 프로그램 빌드 프로세스에 시간이 추가되고 마케팅 프로그램을 시장에 내놓는 데 더 많은 시간이 걸립니다. 자체 프로그램 실행 전 목록을 설정하고 내부 사용자가 QA 프로세스를 숙지하도록 하면 이를 사용하여 프로그램 구성을 보다 정확하게 만들 수 있습니다.
* **자체 지원:** 마케팅 팀이 빌드하고 있는 프로그램과 관련된 체크리스트를 검토하도록 하는 것은 내부 사용자를 교육하기 위한 구조화된 교육 과정을 제공합니다. 체크리스트를 통해 자가 검토를 할 때마다 근육 기억력이 쌓인다. 당신이 경험이 많은 사람일지라도 [!DNL Marketo Engage] 관리자가 다른 사람의 프로그램을 검토하고, 확인할 체크리스트를 가지고 있으면 일반적인 위험을 간과할 수 없습니다.

## 프로그램 사전 실행 QA 프로세스 디자인을 시작합니다.

### 1단계: QA 프로세스를 통해 고려

QA 프로세스를 통해 생각해 보려면 다음 질문에 답하십시오.

* **검토자 및 승인자 역할을 수행할 수 있는 사람은 누구입니까?**
소규모 조직에 속해 있는 경우 [!DNL Marketo Engage] 관리자는 마케팅 및 마케팅 운영의 하이브리드 역할을 수행할 수 있습니다. 빌더가 아닌 것이 좋습니다 [!DNL Marketo Engage] 고급 사용자가 프로그램을 감사하도록 고려하십시오. 새로운 눈 한 쌍은 문제를 발견하는 데 도움이 된다.

* **빌더와 검토자는 어떻게 공동 작업하고 메모 및 변경 사항을 문서화합니까?**
스프레드시트나 프로젝트 관리 플랫폼 내에 정리된 내용을 유지할 수 있습니다. 아래 체크리스트를 참조하고 템플릿을 조직에 가장 적합한 형식으로 변환하십시오. 팀이 프로그램을 빌드하고 시작할 때마다 템플릿을 복제하면 됩니다.

### 2단계: 사전 실행 프로그램 진행

프로그램 실행 전 확인 목록 을 차례로 검토하여 프로그램 QA 범위에 대해 숙지하십시오.

**염두에 두어야 할 경험칙:**

* 이 프로그램 출시 전 확인 목록은 한 가지 크기가 모두 적합하도록 설계되지 않았습니다. 관련 항목을 사용하고, 관련되지 않은 항목은 무시하거나 삭제하고, 조직의 필요에 따라 사용자 정의합니다. 프로그램 빌드와 관련된 부분만 사용하도록 체크리스트를 나눌 수도 있습니다.
* 요구 사항을 명확히 정의합니다. 각 요소에 대한 허용 기준을 고려하여 오프라인 템플릿에서 편집하십시오.

### 3단계: 내부 팀에 대한 지침 개발

프로그램 실행 전 체크리스트를 사용할 내부 팀에 대한 지침을 개발하고 QA 프로세스가 보다 간소화될 때까지 테스트합니다.

예를 들면 다음과 같습니다.

* 빌더는 프로그램 실행 전 확인 목록을 복제하여 확인 목록을 아래로 내려가면서 확인, 메모 및 승인해야 합니다.
* 빌더가 한 열에서 자체 검토를 수행하고 검토자가 요구 사항 옆에 있는 다른 열에서 메모를 문서화하도록 합니다.
* 검토자만 &#39;최종 확인&#39; 섹션을 작성하게 합니다. 이 섹션에서는 검토자에게 QA 프로세스 전체에서 변경 사항이 제대로 수행되도록 몇 가지 키 검사를 반복할 것을 요청합니다.

### 4단계: 정기적으로 체크리스트 재방문

팀이 이 연습을 몇 번 실행할 때 누락되었거나 적용할 수 없는 항목이 있을 수 있습니다. 이 체크리스트(예: 분기별)를 다시 방문하여 검토 항목과 승인 기준을 업데이트하여 프로그램 QA 프로세스를 세부 조정합니다.

## 예제 템플릿: 프로그램 실행 전 검사 목록 {#pre-launch-checklist}

>[!NOTE]
>더 작은 화면에 있는 경우 아래 탭을 스크롤하여 더 많은 항목을 볼 수 있습니다.

>[!BEGINTABS]

>[!TAB 주요 세부 정보 및 계획]

| # | 리뷰 영역 | 질문할 사항 | 예 | 수락 기준 | 추가 리소스 |
|---|---|---|---|---|---|
| 1 | **프로그램 유형** | 적절한가? | 참여 프로그램이 논리적입니까? 기본값인 경우 논리적입니까? | **예:** <br>이 질문에 예로 대답할 수 없는 경우 프로그램 유형을 변경해야 할 수 있습니다. | [프로그램 이해](https://experienceleague.adobe.com/docs/marketo/using/product-docs/core-marketo-concepts/programs/creating-programs/understanding-programs.html){target="_blank"} |
| 2 | **채널** | 적절한 채널입니까? 채널 단계/프로그램 상태가 프로그램의 성공 관리를 지원합니까? | 뉴스레터로 설정된 경우, 이 방법이 적절하고 프로그램 상태가 프로그램의 목적을 지원합니까? 또는 기존 것이지만 적합하지 않은 것을 수정하려고 합니까? | **예:** <br>이 질문에 예로 답할 수 없는 경우 채널을 변경하거나 와 새 채널 만들기에 대해 논의해야 합니다. [!DNL Marketo Engage] 관리자 | [프로그램 채널 만들기](https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/tags/create-a-program-channel.html){target="_blank"}<br><br> [채널 이해](https://experienceleague.adobe.com/docs/marketo/using/product-docs/core-marketo-concepts/programs/working-with-programs/understanding-tags.html#channel){target="_blank"} |
| 3 | **프로그램 명명 규칙** | 이 세트가 이름 지정 규칙에 맞게 설정되었습니까? 명명 규칙 도구 또는 스프레드시트가 있는 경우 해당 도구 또는 스프레드시트에 연결합니다. | 공식: [프로그램 유형] - [날짜] [범주]: [간단한 설명] | **예:** <br>이 질문에 예로 답할 수 없거나 확실하지 않은 경우 이름 지정 규칙을 검토하고 필요한 경우 프로그램 이름을 업데이트합니다. | [새 항목 구성 모범 사례 [!DNL Marketo Engage] 인스턴스](https://experienceleague.adobe.com/docs/marketo-learn/tutorials/fundamentals/best-practices-to-organize-a-new-instance.html){target="_blank"} |
| 4 | **기간 비용** | 프로그램에 기간 비용 태그를 할당했습니까? | 7월에 시작되는 eBook을 제작하기 위해 \$1000을 사용하는 경우, 7월에는 프로그램 기간 비용이 \$1000이 됩니다. | **예:** <br>이 질문에 예로 답할 수 없는 경우, 단지 0일지라도 기간 비용을 추가하십시오. | [프로그램에서 기간 원가 사용](https://experienceleague.adobe.com/docs/marketo/using/product-docs/core-marketo-concepts/programs/working-with-programs/using-period-costs-in-a-program.html){target="_blank"} |
| 5 | **성공** | 프로그램의 목표 및 성공 지표를 식별했습니까? 그 프로그램을 어떻게 측정할 지 아세요? 프로그램 상태 변경으로 표시해 두셨나요? | &#39;채팅&#39; 채널인 경우 상태 진행이 &#39;구성원&#39;, &#39;참여&#39; 및 &#39;전환됨&#39;일 수 있습니다. | **예:** <br>이 질문에 예로 답할 수 없는 경우 캠페인에 영향이 있는지 쉽게 이해할 수 없습니다. 7일 후 수동 목록 가져오기라도 기본 목표가 무엇인지 확인한 다음 이를 측정하는 방법을 선택합니다. | [프로그램 상태](https://experienceleague.adobe.com/docs/marketo/using/product-docs/core-marketo-concepts/programs/creating-programs/understanding-program-membership.html#program-statuses){target="_blank"} |
| 6 | **대상자** | 그 프로그램의 시청자를 확인해 봤니? |  | **예:** <br>이 질문에 예로 답할 수 없는 경우 보내기 전에 알아보십시오. |  |
| 7 | **토큰** | 모든 필수 프로그램 토큰을 업데이트했습니까? | 웨비나 프로그램이라면 이벤트 날짜, 이벤트 제목, 설명, 일정 파일 등은 업데이트했습니까? | **예 또는 해당되지 않음** <br>예로 대답할 수 없거나 적용 여부를 알 수 없는 경우 프로그램 &#39;토큰&#39; 탭을 확인하십시오. 프로그램에 업데이트해야 하는 로컬 토큰이 포함되어 있는지 확인합니다 | [프로그램의 내 토큰 이해](https://experienceleague.adobe.com/docs/marketo/using/product-docs/core-marketo-concepts/programs/tokens/understanding-my-tokens-in-a-program.html){target="_blank"} |

>[!TAB 웹 개인화 캠페인]

| # | 리뷰 영역 | 질문할 사항 | 수락 기준 | 추가 리소스 |
|---|---|---|---|---|
| 1 | **디자인** | 디자인이 브랜드 가이드라인과 일치합니까? | **예:** <br>예로 대답할 수 없는 경우 에셋을 다시 디자인하거나 합당한 이유가 필요합니다. |
| 2 | **테스트** | 여러 장치에서 테스트되었습니까? 브라우저? 렌더링이 깔끔하고 기능도 괜찮은가요? | **예:** <br>예로 대답할 수 없는 경우 디바이스와 브라우저에서 테스트해야 합니다. |
| 3 | **데이터** | 캠페인에 양식이 있다면 양식을 테스트했습니까? 모든 트리거가 예상대로 진행됩니까? 모든 양식 필드가 정확하게 매핑됩니까? 필드뿐 아니라 개인 사용자의 활동 기록을 확인함으로써 이를 증명할 수 있습니까? | **예:** <br>예로 대답할 수 없는 경우 이를 테스트해야 합니다. | [양식 필드를 숨김으로 설정](https://experienceleague.adobe.com/docs/marketo/using/product-docs/demand-generation/forms/form-fields/set-a-form-field-as-hidden.html){target="_blank"}<br><br> [숨겨진 양식 필드 값 설정](https://experienceleague.adobe.com/docs/marketo/using/product-docs/demand-generation/forms/form-fields/set-a-hidden-form-field-value.html){target="_blank"} |
| 4 | **추적** | 캠페인에 양식이 있는 경우 제출 소스를 추적하기 위해 숨겨진 UTM 필드가 있습니까? 테스트를 거쳤습니까? | **예 또는 아니요:** 아니요로 답한 경우, 이 양식으로 사용자를 안내하는 소스를 추적하는 기능이 제한되어 있음을 이해하십시오. | [레퍼러 매개 변수](https://experienceleague.adobe.com/docs/marketo/using/product-docs/demand-generation/forms/form-fields/set-a-hidden-form-field-value.html#referrer-parameter){target="_blank"} |
| 5 | **GDPR/CASL 규정 준수** | <li>양식을 통해 데이터를 캡처하는 경우 옵트인이 기업 정책을 준수합니까? <li>작동하는 개인정보 처리방침 링크가 있는 컬렉션 문을 제공합니까? | **예:** <br>관련 준수 환경 이해: 이 질문에 예로 답할 수 없는 경우 준수되도록 개인정보 처리방침 섹션을 업데이트해야 합니다. **모르는 경우 법률 팀에 적절한 조언을 구하십시오.** | [개인 정보 관리](https://experienceleague.adobe.com/docs/marketo/using/product-docs/core-marketo-concepts/miscellaneous/privacy-management.html){target="_blank"} |
| 6 | **Google [!DNL Analytics] 통합** | 웹 개인화가 Google과 통합되었습니까? [!DNL Analytics]? | **예 또는 아니요:**<br>&#x200B;아니요로 답하는 경우, 웹 개인화 영향을 추적하는 기능이 제한되어 있음을 이해하십시오. | [Google의 개인화된 리마케팅](https://experienceleague.adobe.com/docs/marketo/using/product-docs/web-personalization/website-retargeting/personalized-remarketing-in-google.html){target="_blank"} |
| 7 | **웹 세그먼트** | <li>선택한 세그먼트가 적절하며, 올바른 도메인에 적용됩니까? <li>세그먼트가 Google으로 전송됩니까 [!DNL Analytics]? | **예:** <br> 예로 대답할 수 없는 경우 업데이트해야 합니다. | [웹 세그먼트](https://experienceleague.adobe.com/docs/marketo/using/product-docs/web-personalization/using-web-segments/web-segments.html){target="_blank"}<br><br>[웹 찾기 [!DNL Campaign]특정 세그먼트를 사용하는](https://experienceleague.adobe.com/docs/marketo/using/product-docs/web-personalization/using-web-segments/find-web-campaigns-that-are-using-a-specific-segment.html){target="_blank"} |

>[!TAB 랜딩 페이지]

| # | 리뷰 영역 | 질문할 사항 | 수락 기준 | 추가 리소스 |
|---|---|---|---|---|
| 1 | **디자인** | 디자인은 브랜드와 일치합니까? 적절한 템플릿을 사용합니까? | **예:** <br> 예로 대답할 수 없는 경우 이에 대한 합당한 이유가 필요하거나 재설계를 해야 합니다. | [Marketo 랜딩 페이지 템플릿 편집](https://experienceleague.adobe.com/docs/marketo/using/product-docs/demand-generation/landing-pages/landing-page-templates/edit-a-marketo-landing-page-template.html){target="_blank"} |
| 2 | **테스트** | 디바이스 및 브라우저에서 테스트되었습니까? 렌더링이 깔끔하고 기능도 괜찮은가요? | **예:** <br>예로 대답할 수 없는 경우 디바이스 및 브라우저 간 미리 보기 링크를 테스트해야 합니다. | [랜딩 페이지 미리보기](https://experienceleague.adobe.com/docs/marketo/using/product-docs/demand-generation/landing-pages/landing-page-actions/preview-a-landing-page.html){target="_blank"} |
| 3 | **URL** | 페이지 URL을 사용자 지정했습니까? 논리적입니까?/명명 규칙을 준수합니까? | **예:** <br>예로 대답할 수 없는 경우 페이지 URL을 업데이트해야 합니다. | [랜딩 페이지 URL 변경](https://experienceleague.adobe.com/docs/marketo/using/product-docs/demand-generation/landing-pages/landing-page-actions/change-the-landing-page-url.html){target="_blank"} |
| 4 | **Meta/OG 태그** | OG 태그가 설정되어 있습니까? 제목, 설명, 이미지 등입니다. 이는 소셜 공유에서 페이지가 표시되는 방식에 영향을 줍니다. | **예:** <br>예로 대답할 수 없는 경우 모든 태그를 업데이트해야 합니다. | [랜딩 페이지 제목 및 메타데이터 편집](https://experienceleague.adobe.com/docs/marketo/using/product-docs/demand-generation/landing-pages/landing-page-actions/edit-landing-page-title-and-metadata.html){target="_blank"} |
| 5 | **로봇** | 설정은 무엇입니까? 당신의 필요에 의해 그것이 말이 됩니까? | **예:** <br>예로 대답할 수 없는 경우 업데이트해야 합니다. | [로봇은 무엇을 의미합니까?](https://experienceleague.adobe.com/docs/marketo/using/product-docs/demand-generation/landing-pages/landing-page-actions/edit-landing-page-title-and-metadata.html){target="_blank"} |
| 6 | **개인화** | 페이지에 개인화된 요소(예: 다이내믹 콘텐츠, 코드 조각)가 있는 경우 테스트해 보셨나요? 모두 예상대로 작동합니까? | **예 / 해당되지 않음:** <br>예 또는 해당 없음에 답할 수 없으면 테스트로 이동하십시오. | [랜딩 페이지에서 동적 콘텐츠 사용](https://experienceleague.adobe.com/docs/marketo/using/product-docs/demand-generation/landing-pages/personalizing-landing-pages/use-dynamic-content-in-a-landing-page.html){target="_blank"}<br><br> [다이내믹 콘텐츠를 사용하여 랜딩 페이지 미리 보기](https://experienceleague.adobe.com/docs/marketo/using/product-docs/demand-generation/landing-pages/landing-page-actions/preview-a-landing-page-with-dynamic-content.html){target="_blank"} |
| 7 | **이미지** | 사용된 모든 이미지가 제대로 압축되었습니까? 이미지가 겹쳐진 텍스트가 있다면 분명히 읽을 수 있습니까? 이 이미지를 사용할 권리가 있으며 브랜드에 명시되어 있습니까? | **예 / 해당되지 않음:** <br> 이메일 로드 속도를 향상시키기 위해 모든 이미지(있는 경우)를 압축해야 합니다. | [업로드한 이미지 또는 파일 바꾸기](https://experienceleague.adobe.com/docs/marketo/using/product-docs/demand-generation/images-and-files/replace-an-uploaded-image-or-file.html){target="_blank"} |
| 8 | **복사** | 그 사본에 문법 오류가 있는지 검토해 봤니? 당신 브랜드의 음색을 위한 복사가 있나요? 복사본이 페이지의 목표가 무엇인지 명확하게 보여주나요? | **예 / 해당되지 않음:** <br> 예 또는 해당 없음에 대답할 수 없는 경우 복사본을 검토하십시오. |
| 9 | **양식** | 랜딩 페이지에 양식이 있는 경우, 올바른 양식을 참조하고 있습니까? Marketo 이외 랜딩 페이지를 사용하는 경우, 양식 에셋 페이지에서도 포함 코드를 확인하여 영향을 받지 않는지 확인하십시오. [이전 URL 구조는 2023년 8월에 더 이상 사용되지 않습니다.](https://nation.marketo.com/t5/product-documents/upcoming-changes-to-design-studio-urls/ta-p/306632){target="_blank"}. | **예 / 해당되지 않음:** <br> 예(또는 해당되지 않음)라고 대답할 수 없는 경우 수정하십시오! | [양식이 있는 랜딩 페이지](https://experienceleague.adobe.com/docs/marketo/using/getting-started-with-marketo/quick-wins/landing-page-with-a-form.html){target="_blank"}<br><br> [웹 사이트에 양식 포함](https://experienceleague.adobe.com/docs/marketo/using/product-docs/demand-generation/forms/form-actions/embed-a-form-on-your-website.html){target="_blank"}<br><br>[Design Studio URL 변경 사항](https://nation.marketo.com/t5/product-documents/upcoming-changes-to-design-studio-urls/ta-p/306632)<br> |
| 10 | **감사합니다.** | 페이지에 양식이 있는 경우 제출 시 페이지에 성공 메시지/감사 페이지로 리디렉션되는 것이 적절합니까? | **예 / 해당되지 않음:** <br> 예(또는 해당 없음)로 대답할 수 없는 경우 사후 제출 설정을 수정합니다. | [랜딩 페이지 리디렉션](https://experienceleague.adobe.com/docs/marketo/using/getting-started-with-marketo/quick-wins/redirect-a-landing-page.html){target="_blank"} |
| 11 | **GDPR/CASL 규정 준수** | 양식을 통해 데이터를 캡처하는 경우 은 옵트인을 준수하며 작동하는 개인정보 처리방침 링크가 포함된 컬렉션 문을 제공합니까? | **예:** <br>관련 규정 준수 환경 파악: 이 질문에 예로 답할 수 없는 경우 준수되도록 업데이트해야 합니다. 모르면 적절한 조언을 구하라. | [개인 정보 관리](https://experienceleague.adobe.com/docs/marketo/using/product-docs/core-marketo-concepts/miscellaneous/privacy-management.html){target="_blank"} |
| 12 | **추적** | 가지고 계세요 [!DNL Google Analytics], 태그 관리자 및/또는 Munchkin 설정이 의도한 대로 페이지에 적용됩니까? 이 랜딩 페이지에 기본적으로 Munchkins가 켜져 있거나 꺼져 있어야 합니까? | **예 / 해당되지 않음:**<br>&#x200B;예 또는 해당되지 않는다고 대답할 수 없는 경우 [!DNL Marketo Engage] 관리자. | [Munchkin 코드가 작동하는지 테스트](https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website.html#test-if-your-munchkin-code-is-working){target="_blank"} |

>[!TAB 양식]

| # | 리뷰 영역 | 질문할 사항 | 수락 기준 | 추가 리소스 |
|---|---|---|---|---|
| 1 | **반응형** | 양식 장치가 응답형입니까? | **예:** <br>예로 대답할 수 없는 경우 CSS가 응답하도록 업데이트해야 합니다. 그렇지 않으면 성능에 영향을 줄 수 있습니다. |  |
| 2 | **디자인** | 양식 브랜드 디자인은 일관적입니까? | **예:** <br>예로 대답할 수 없는 경우 이에 대한 합당한 이유가 필요하거나 CSS를 업데이트하여 브랜드에서 만들어야 합니다. |  |
| 3 | **데이터 흐름** | 모든 데이터가 의도한 대로 필드에 매핑됩니까? 이를 입증하기 위해 테스트 기록의 활동 로그를 확인했습니까? | **예:** <br>예로 대답할 수 없는 경우 매핑을 수정하고 테스트해야 합니다. | [사용자에 대한 활동 로그 찾기](https://experienceleague.adobe.com/docs/marketo/using/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/locate-the-activity-log-for-a-person.html){target="_blank"} |
| 4 | **추적** | 이 양식에 대한 제출 소스를 추적할 숨겨진 UTM 필드가 있습니까? 테스트를 거쳤습니까? | **예 또는 아니요:** <br>아니요로 답하는 경우 이 양식으로 사람들을 유도한 소스를 추적하는 기능이 제한되어 있음을 이해하십시오. | [양식 필드를 숨김으로 설정](https://experienceleague.adobe.com/docs/marketo/using/product-docs/demand-generation/forms/form-fields/set-a-form-field-as-hidden.html){target="_blank"}<br><br>[숨겨진 양식 필드 값 설정](https://experienceleague.adobe.com/docs/marketo/using/product-docs/demand-generation/forms/form-fields/set-a-hidden-form-field-value.html){target="_blank"} |
| 5 | **GDPR/CASL 규정 준수** | 데이터를 양식을 통해 캡처하는 경우 은 옵트인을 준수합니까? 그리고 작동하는 개인정보 처리방침 링크가 포함된 컬렉션 문을 제공합니까? | **예:** <br>관련 규정 준수 환경 파악: 이 질문에 예로 답할 수 없는 경우 준수되도록 업데이트해야 합니다. **모르면 적절한 조언을 구하라.** | [개인 정보 관리](https://experienceleague.adobe.com/docs/marketo/using/product-docs/core-marketo-concepts/miscellaneous/privacy-management.html){target="_blank"} |

>[!TAB 스마트 캠페인]

| # | 리뷰 영역 | 질문할 사항 | 수락 기준 | 추가 리소스 |
|---|---|---|---|---|
| 1 | **정확도** | 필요한 모든 스마트 기능 [!DNL Campaign]확인, 검토 및 정확한 것으로 간주됩니까? | **예:** <br>예로 대답할 수 없는 경우 계속 진행하기 전에 이를 수정하고 확인해야 합니다. | [스마트 [!DNL Campaign] 체크리스트](https://experienceleague.adobe.com/docs/marketo/using/product-docs/core-marketo-concepts/smart-campaigns/creating-a-smart-campaign/smart-campaign-checklist.html){target="_blank"} |
| 2 | **전송 카운트** | 이메일 전송 캠페인이 일괄 캠페인(트리거되지 않음)인 경우 &#39;예약&#39; 탭에서 리드 수를 확인합니다. 예상한 수치에 맞게 수치가 정렬됩니까? 중단 임계값보다 작습니까? | **예:** <br>예로 대답할 수 없는 경우 계속 진행하기 전에 이를 수정하고 확인해야 합니다. | [이메일 프로그램 예약](https://experienceleague.adobe.com/docs/marketo/using/product-docs/email-marketing/email-programs/email-program-actions/schedule-your-email-program.html){target="_blank"} |
| 3 | **기본 규칙** | 적절한 경우 기본 세그먼트/목록이 사용됩니까? 아니면 적절한 위치에 있습니까? | **예 또는 해당 사항 없음:**<br> 기본 목록/세그먼트는 참조해야 하는 필드의 수를 줄이고 사람의 오류 위험을 줄이도록 설계되었습니다. 기본 목록/세그먼테이션을 사용하지 않는 경우 규칙을 신뢰해야 합니다. |  |
| 4 | **속성** | 프로그램에서 새 잠재 고객을 가져오는 경우(예: 이벤트 프로그램) 필요에 따라 속성 설정이 포함됩니까? 획득 프로그램이 매핑되고 있습니까? | **예 또는 해당 사항 없음:** <br>프로그램으로 사람을 가져오는 경우 또는 프로그램에서 새 사람을 가져오는 경우 획득 프로그램 설정을 사용해야 합니다. |  |
| 5 | **참여 프로그램** | 스마트한 경우 [!DNL Campaign] 은 참여 프로그램에서 사용되며 구성원이 추가, 일시 중지 및 재시작되도록 하는 단계가 있습니까? 다른 사용자가 이러한 단계를 검토했습니까? | **예 또는 해당 사항 없음:**<br> 참여 프로그램이며 정당한 이유 없이 예로 대답할 수 없는 경우 이 프로그램이 적용될 때까지 활성화하지 마십시오. | [참여 프로그램에 사람 추가](https://experienceleague.adobe.com/docs/marketo/using/product-docs/email-marketing/drip-nurturing/creating-an-engagement-program/add-people-to-an-engagement-program.html){target="_blank"} |
| 6 | **구독 환경 설정** | 필요한 구독 환경 설정 요소가 모두 포함되었습니까? | **예 또는 해당 사항 없음:**<br> 확실하지 않은 경우 [!DNL Marketo Engage] 관리자. N/A(예: 작동 전송)를 진행하려면 상당한 이유가 필요합니다. | [구독 센터 설정 및 관리 방법](https://experienceleague.adobe.com/docs/marketo-learn/tutorials/lead-and-data-management/subscription-center-watch.html){target="_blank"} |
| 7 | **프로그램 상태** | 프로그램 상태를 업데이트하는 흐름 단계가 포함되어 있습니까? | **예:** <br>예로 대답할 수 없는 경우 Smart에 추가해야 합니다. [!DNL Campaign] 흐름 단계. | [프로그램 상태 변경](https://experienceleague.adobe.com/docs/marketo/using/product-docs/core-marketo-concepts/smart-campaigns/program-flow-actions/change-program-status.html){target="_blank"} |
| 8 | **광범위한 영향** | <li>다른 팀/시스템과 동기화하는 필드에 경고/쓰기를 전송하는 흐름 단계가 있습니까? <li>그렇다면 볼륨을 고려하고 해당 팀/시스템에 대한 이해 당사자에게 조언을 제공했습니까? | **예, 아니오 또는 해당 사항 없음:**<br> 어떤 대답이든 좋지만 만약 그것이 지도라면 보통 시스템을 소유한 팀에 알려야 한다. 확실하지 않은 경우 관리자에게 문의하십시오. |  |
| 9 | **채점 영향** | 잠재 고객/개인 채점을 고려하는 데 영향을 미칩니까? | **예 또는 해당 사항 없음:** <br>예 또는 해당 없음으로 대답할 수 없는 경우 관리자에게 문의하십시오. | [단순 채점](https://experienceleague.adobe.com/docs/marketo/using/getting-started-with-marketo/quick-wins/simple-scoring.html){target="_blank"}<br><br>[잠재 고객 스코어 프로그램을 구축하는 방법](https://experienceleague.adobe.com/docs/marketo-learn/tutorials/lead-and-data-management/lead-scoring-watch.html){target="_blank"} |
| 10 | **RCM(Revenue Cycle Modeler) 영향** | 개인 라이프사이클 모델에 대한 영향을 고려했습니까? | **예 또는 해당 사항 없음:** 예 또는 해당 비용에 대해 답변할 수 없는 경우 관리자에게 문의하십시오. | [수익 주기 모델러 구성](https://experienceleague.adobe.com/docs/marketo/using/product-docs/demand-generation/facebook/set-up-facebook-offline-conversions.html){target="_blank"} |
| 11 | **참여 프로그램에 미치는 영향** | <li>기존 참여 프로그램에 대한 영향을 고려했습니까? <li>당신은 사람들이 여러 통신에 의해 폭격을 받지 않을 것을 보장했습니까? | **예 또는 해당 사항 없음:**<br>&#x200B;예 또는 해당 없음으로 대답할 수 없는 경우 관리자에게 문의하십시오. | [중복 컨텐츠 전송 방지](https://experienceleague.adobe.com/docs/marketo/using/product-docs/email-marketing/drip-nurturing/using-engagement-programs/avoid-sending-duplicate-content.html){target="_blank"} <br><br>[Smart에 통신 제한 적용 [!DNL Campaign]](https://experienceleague.adobe.com/docs/marketo/using/product-docs/core-marketo-concepts/smart-campaigns/using-smart-campaigns/apply-communication-limits-to-smart-campaign.html){target="_blank"} |
| 12 | **보고 성공** | 프로그램의 성공은 논리적으로 측정되고 있습니까? 성공 여부가 과연 합당한가 - 그 과정에서 너무 가깝지 않은가? 달성하기에 너무 멀지 않은가? 내부적으로 커뮤니케이션하기 위해 성공을 보고하고 측정하는 방법에 대한 전략이 있습니까? | **예:** <br>예로 대답할 수 없는 경우 성공 지표 정의를 다시 생각해 보십시오. | [프로그램 변경 성공](https://experienceleague.adobe.com/docs/marketo/using/product-docs/core-marketo-concepts/smart-campaigns/program-flow-actions/change-program-success.html){target="_blank"} |

>[!TAB 목록]

| # | 리뷰 영역 | 질문할 사항 | 수락 기준 | 추가 리소스 |
|---|---|---|---|---|
| 1 | **논리** | 스마트 목록을 사용하여 대상의 일부를 식별하는 경우 로직이 확인 및 검토되고 정확한 것으로 간주됩니까? | **예:** <br>예로 대답할 수 없는 경우 스마트 목록 설정을 수정하고 계속하기 전에 이러한 사항을 확인해야 합니다. |  |
| 2 | **목록 가져오기 프로세스** | 정적 목록을 사용하여 대상의 일부를 식별하는 경우 데이터 소스는 신뢰할 수 있으며 목록 가져오기 프로세스에 따라 가져오기가 정확하게 수행되었습니까? | **예:** <br>예로 대답할 수 없는 경우 목록 데이터를 수정하고 확인한 후 진행해야 합니다. | [정적 목록에서 사람을 추가/제거하는 방법](https://experienceleague.adobe.com/docs/marketo/using/product-docs/core-marketo-concepts/smart-lists-and-static-lists/static-lists/understanding-static-lists.html){target="_blank"}<br><br>[사람 목록 가져오기](https://experienceleague.adobe.com/docs/marketo/using/getting-started-with-marketo/quick-wins/import-a-list-of-people.html#step-import-your-spreadsheet-into-marketo) |
| 3 | **제외** | 필수 제외가 포함되어 있습니까(예: 경쟁업체, 구독 취소 차단 목록) | **예 또는 해당 사항 없음:** <br>법적으로 규정을 준수하고, 그렇지 않은 경우 가입 해지서를 필터링해야 합니다. 이러한 규칙을 포함하지 않을 경우 콘텐츠, 캠페인 규칙 및 법적 근거에 대해 신뢰해야 합니다. | [구독 취소 이해](https://experienceleague.adobe.com/docs/marketo/using/product-docs/email-marketing/deliverability/understanding-unsubscribe.html){target="_blank"}<br><br>[데이터 값 변경](https://experienceleague.adobe.com/docs/marketo/using/product-docs/email-marketing/deliverability/understanding-unsubscribe.html){target="_blank"} |
| 4 | **기본 목록** | 적절한 경우 기본 목록/세그먼테이션이 사용됩니까? | **예 또는 해당 사항 없음:** 기본 목록/세그먼트는 참조해야 하는 필드의 수를 줄이고 사람의 오류 위험을 줄이도록 설계되었습니다. 기본 목록/세그먼테이션을 사용하지 않는 경우 규칙을 신뢰해야 합니다. | [세그먼트 규칙 정의](https://experienceleague.adobe.com/docs/marketo/using/product-docs/personalization/segmentation-and-snippets/segmentation/define-segment-rules.html) |

>[!TAB 대상자]

| # | 리뷰 영역 | 질문할 사항 | 수락 기준 | 추가 리소스 |
|---|---|---|---|---|
| 1 | **법적 근거:**<br>&#x200B;대상자에게 연락할 수 있는 적절한 법적 근거가 있습니다. | <ul><li>**명시적:** 브랜드에서 마케팅 커뮤니케이션을 수신하기 위해 명시적으로 옵트인했습니까? </li><li>**유추(준수하는 경우):** 그들이 귀하에게 연락처 세부 정보를 제공했으며 귀하가 이 정보를 사용하여 연락하는 것을 합리적으로 기대할 수 있습니까? </li><li>**간주(준수하는 경우):** 공개 소스에서 연락처 세부 정보를 가져왔으며 공개 소스로 볼 때 콘텐츠가 사용자와 관련이 있다고 합리적으로 가정할 수 있습니까?</li></ul> | **예, 기준을 명시합니다.** 선택한 모든 기준이 규정 준수 환경에서 유효한지 확인하십시오. 예로 대답할 수 없는 경우 프로그램 시작을 보류하고 이 대상자에게 연락하는 법적 근거에 대한 설명을 요청하십시오. | [개인 정보 관리](https://experienceleague.adobe.com/docs/marketo/using/product-docs/core-marketo-concepts/miscellaneous/privacy-management.html){target="_blank"} |
| 2 | **데이터 소스** | 가져오기 목록을 통해 대상자를 식별하는 경우 데이터 소스를 신뢰할 수 있습니까? | **예 또는 해당 사항 없음:**<br>&#x200B;예로 대답할 수 없는 경우 데이터 소스에 대한 설명을 확인하십시오. | [목록을 가져와서 대상자 정의](https://experienceleague.adobe.com/docs/marketo/using/product-docs/email-marketing/email-programs/managing-people-in-email-programs/define-an-audience-by-importing-a-list.html){target="_blank"} |
| 3 | **목록 구매** | 대상자가 목록 구매 또는 후원 활동을 통해 소싱되었습니까? | **출처 = 목록 구매인 경우 아니오**<br> 목록 구매는 잘못된 관행이며, 많은 곳에서 불법이며, 종종 Marketing Automation 플랫폼과의 계약을 위반하는 경우가 많습니다.<br><br>**예, source = sponsorship인 경우** <br>후원 및 경쟁 사례에서 데이터 캡처가 준수되었는지 확인합니다. 첫 번째 커뮤니케이션에서 정보를 받은 방식을 명확히 하고 사람들이 쉽게 옵트아웃할 수 있도록 하는 것이 좋습니다. |
| 4 | **관련성** | 이 대상자를 전송하려는 정보는 대상자 및 사용자와의 관계와 관련이 있습니다. | **예:** <br>예로 대답할 수 없는 경우 중지하고 이러한 사람에게 이메일을 보내는 이유를 신중하게 고려하십시오. 귀하와 관련이 없는 정보를 보내면 성능 및 전달성에 부정적인 영향을 미칠 수 있으며 규정 준수 환경에 위반이 될 수 있습니다. |
| 5 | **기대** | 이 대상자는 사용자의 의견을 듣기를 기대합니다. | **예:** <br>예로 대답할 수 없는 경우 중지하고 이러한 사람에게 이메일을 보내는 이유를 신중하게 고려하십시오. 사용자의 의견을 듣기를 원하거나 원하지 않는 대상자에게 이메일을 보내면 성능 및 전달성에 부정적인 영향을 미칠 수 있으며 규정 준수 환경에 위반이 될 수 있습니다. |


>[!TAB 이메일 자산]

| # | 리뷰 영역 | 질문할 사항 | 수락 기준 | 추가 리소스 |
|---|---|---|---|---|
| 1 | **보낸 사람 이메일 주소** | 브랜드 소유자와 확인해보셨고 이메일 주소는 안전한 사용인지 확인하셨습니까? | **예:** <br>예로 대답할 수 없는 경우 계속하기 전에 발신자 이메일을 확인해야 합니다. | [이메일 헤더 편집](https://experienceleague.adobe.com/docs/marketo/using/product-docs/email-marketing/general/creating-an-email/edit-your-email-header.html){target="_blank"}<br><br>[기본 보낸 사람 이메일 및 보낸 사람 레이블 변경](https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/email-setup/change-the-default-from-email-and-from-label.html){target="_blank"} |
| 2 | **보낸 사람 이름** | 브랜드 소유자와 확인해보셨고, 명칭은 안전하게 사용 가능한지 확인해보셨나요? | **예:** <br>예로 대답할 수 없는 경우 계속 진행하기 전에 확인해야 합니다. | [이메일 헤더 편집](https://experienceleague.adobe.com/docs/marketo/using/product-docs/email-marketing/general/creating-an-email/edit-your-email-header.html){target="_blank"}<br><br>[기본 보낸 사람 이메일 및 보낸 사람 레이블 변경](https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/email-setup/change-the-default-from-email-and-from-label.html){target="_blank"} |
| 3 | **회신 주소** | 브랜드 소유자와 확인해보셨고, 안전한 사용인지 확인하셨나요? | **예:** <br> 예로 대답할 수 없는 경우 계속 진행하기 전에 확인해야 합니다. | [이메일 헤더 편집](https://experienceleague.adobe.com/docs/marketo/using/product-docs/email-marketing/general/creating-an-email/edit-your-email-header.html){target="_blank"} |
| 4 | **사전 머리글 설정** | 모범 사례에 따라 사전 헤더를 설정했습니까(예: min). 80자, 전체 문장, 앞에 중요한 비트)? | **예:** <br><br>예로 대답할 수 없는 경우 계속하기 전에 업데이트해야 합니다. | [이메일 설정](https://experienceleague.adobe.com/docs/marketo/using/product-docs/email-marketing/general/email-editor-2/email-editor-v2-0-overview.html){target="_blank"} |
| 5 | **증명 복사** | 맞춤법이나 문법 문제가 있습니까? <br>당신 브랜드에 맞는 톤인가요? | **예:** <br>예로 대답할 수 없는 경우 계속 진행하기 전에 수정해야 합니다. |  |
| 6 | **훑어보기** | 이 이메일의 주요 정보를 스캔할 때 이해할 수 있습니까? | **예 또는 해당 사항 없음:** <br>이메일 모범 사례에서는 스캔할 때 이메일의 주요 메시지를 이해할 수 있도록 하는 것이 중요하다고 제안합니다. 이 방법을 적용하지 않도록 선택하는 경우 이메일의 성능에 영향을 줄 수 있습니다. |  |
| 7 | **구독 취소** | 이메일에는 테스트한 기능 구독 취소 링크가 있습니까? | **예 또는 해당 사항 없음:**<br>&#x200B;이메일이 다음과 같은 경우에만 해당되지 않습니다. [작동-](https://experienceleague.adobe.com/docs/marketo/using/product-docs/email-marketing/general/functions-in-the-editor/make-an-email-operational.html){target="_blank"}. 구독 취소가 필요하지 않습니다. 확실하지 않은 경우 포함이 더 안전합니다. | [구독 취소 이해](https://experienceleague.adobe.com/docs/marketo/using/product-docs/email-marketing/deliverability/understanding-unsubscribe.html){target="_blank"} |  |
| 8 | **텍스트 버전** | <li>이메일의 텍스트 버전을 만들었습니까? <li>본문의 버전을 테스트해 봤니? | **예:**<br> 예로 대답할 수 없는 경우 계속 진행하기 전에 테스트해야 합니다. |
| 9 | **텍스트 버전 최적화** | <li>텍스트 버전의 레이아웃이 최적화되었습니까?<li>표시되는 HTML 주석이 있습니까?<li>모든 관련 콘텐츠가 포함되어 있습니까? | **예:**<br> 자동 생성된 텍스트 버전은 읽기가 매우 어려울 수 있으므로 최적화할 가치가 있습니다. | [이메일의 텍스트 버전 편집](https://experienceleague.adobe.com/docs/marketo/using/product-docs/email-marketing/general/creating-an-email/edit-the-text-version-of-an-email.html){target="_blank"} |
| 10 | **텍스트 버전 하이퍼링크 및 UTMS** | 하이퍼링크가 작동하고 이러한 영역에 UTM을 포함합니까? :<ul><li>헤더 섹션</li><li>이미지 영역(포함된 경우)</li><li>본문</li><li>CTA</li>바닥글</li></ul> | **예:**<br> 예로 대답할 수 없는 경우 계속 진행하기 전에 이를 수정하고 확인해야 합니다. 자동 텍스트 버전은 변수를 안정적으로 가져오지 않습니다. |  |
| 11 | **HTML/주 버전** | <li>이메일의 HTML/주 버전을 생성했습니까?<li>직접 테스트해 보셨나요? | **예(일반 텍스트만 제외):**<br> 예로 대답할 수 없는 경우 진행하기 전에 테스트를 직접 전송해야 합니다. | [이메일 HTML 편집](https://experienceleague.adobe.com/docs/marketo/using/product-docs/email-marketing/general/functions-in-the-editor/edit-an-emails-html.html){target="_blank"} |
| 12 | **이미지** | <li>모든 이미지에 대체 텍스트가 있습니까? <li>깨진 이미지가 있습니까? | **예 또는 해당 사항 없음:**<br>. 예로 대답할 수 없는 경우 계속 진행하기 전에 이미지를 수정하고 확인해야 합니다(이미지가 없는 경우). |  |
| 13 | **이미지 압축** | <li>이미지 편집 소프트웨어에서 웹용으로 모든 이미지가 저장되었습니까? <li>업로드하기 전에 압축되었습니까? <li>이메일 로드 시간이 허용됩니까? | **예 또는 해당 사항 없음:**<br>&#x200B;로드 속도를 향상시키기 위해 모든 이미지(있는 경우)를 압축해야 합니다. | hero images은 120kb 미만이어야 하며 모든 작은 이미지는 더 작아야 합니다. 높은 로드 시간은 성능에 영향을 줍니다. |
| 14 | **HTML 버전 하이퍼링크 및 UTM** | 모든 하이퍼링크가 작동하고 이러한 영역에 UTM을 포함합니까? :<ul><li>헤더 섹션</li><li>이미지 영역(포함된 경우)</li><li>본문</li><li>CTA</li>바닥글</li></ul> | **예:**<br> 끊어진 링크를 보내지 마십시오. 예라고 대답할 수 없는 경우 계속하기 전에 수정하십시오. |  |
| 15 | **다이내믹 콘텐츠** | <li>이메일에 다이내믹 콘텐츠가 포함되어 있습니까?<li>여러 시나리오에서 테스트했습니까? | **예:**<br> 예로 대답할 수 없는 경우 계속하기 전에 이를 테스트해야 합니다. | [이메일에서 동적 콘텐츠 사용](https://experienceleague.adobe.com/docs/marketo/using/product-docs/email-marketing/general/functions-in-the-editor/using-dynamic-content-in-an-email.html){target="_blank"}<br><br>[다이내믹 콘텐츠를 사용하여 이메일 미리 보기](https://experienceleague.adobe.com/docs/marketo/using/product-docs/email-marketing/general/functions-in-the-editor/preview-an-email-with-dynamic-content.html){target="_blank"} |
| 16 | **법적 요구 사항** | <ul><li>오퍼 표시한 거 있어요?</li><li>규정 준수 환경에 따라 필요한 면책조항이 포함되어 있습니까?</li></ul> | **예:**<br> 예로 대답할 수 없는 경우 계속 진행하기 전에 이를 수정하고 확인해야 합니다. |  |
| 17 | **피어가 검토됨** | 또 드셨습니까 [!DNL Marketo Engage] 사용자 피어가 테스트 이메일을 검토하시겠습니까? | **예:**<br> 예로 대답할 수 없는 경우 보내기 전에 이 작업을 수행해야 합니다. |  |
| 18 | **운영 전송** | <ul><li>이메일을 작동(구독 취소 설정을 무시함)으로 설정했습니까?<li>그렇다면 타당한 이유가 있나요?</li> | **예 또는 아니요:**<br> yes로 답하는 경우, 유효한 운영 이메일로 보내는 이유가 있어야 합니다. 확실하지 않은 경우 [!DNL Marketo Engage] 관리자. | [이메일을 작동 상태로 만들기](https://experienceleague.adobe.com/docs/marketo/using/product-docs/email-marketing/general/functions-in-the-editor/make-an-email-operational.html){target="_blank"} |
| 19 | **A/B 및 Champ/Challenger 테스트** | 이메일에서 챔피언/챌린저 테스트를 실행하고 있습니까? | **예 또는 아니요:**<br>&#x200B;테스트를 수행하지 않는 경우 대상자에 대해 자세히 알아볼 수 있는 기회를 놓치고 있는지 생각해 보십시오. | [A/B 테스트 만들기](https://experienceleague.adobe.com/docs/marketo-learn/tutorials/email-marketing/ab-testing-watch.html)<br><br>[이메일 챔피언/챌린저 추가](https://experienceleague.adobe.com/docs/marketo/using/product-docs/email-marketing/general/functions-in-the-editor/email-tests-champion-challenger/add-an-email-champion-challenger.html){target="_blank"} |
| 20 | **클라이언트 테스트** | 클라이언트 테스트 소프트웨어를 통해 이메일을 실행했습니까?<li>주요 이메일 클라이언트에서 디스플레이 문제를 확인했습니까? <li>긴급하지 않은 템플릿 수정 사항을 수정하거나 기록했습니까? <li>로드 속도 문제를 식별하고 개선하려고 시도했습니까?<li>제목란/미리 보기 라인 문제를 식별했습니까? 해결되었습니까? | **예 또는 해당 사항 없음:**<br> 예(테스트 소프트웨어가 없는 경우)로 대답할 수 없는 경우 보내기 전에 이 작업을 수행해야 합니다. | 클라이언트 테스트 소프트웨어의 예로는 Litmus 또는 Email on Acid 또는 [Marketo 이메일 전달성 Power Pack](https://experienceleague.adobe.com/docs/marketo/using/product-docs/email-marketing/deliverability/email-deliverability-power-pack-how-to-import-a-seed-list.html)<br><br>[받은 편지함 추적기 Tutorials](https://experienceleague.adobe.com/docs/marketo/using/product-docs/email-marketing/deliverability/inbox-tracker/inbox-tracker-tutorials.html){target="_blank"} |
| 21 | **스팸 테스트** | 이메일을 스팸 처리로 실행했습니까?<li>인식을 위해 차단 목록에 추가 플래그가 있습니까?<li>받은 편지함 배치/이메일 클라이언트 플래그를 식별했습니까? <li>잠재적 원인을 찾고 해결하려고 시도한 적이 있습니까? | **예 또는 해당 사항 없음:**<br>&#x200B;예(테스트 소프트웨어가 없는 경우)로 대답할 수 없는 경우 보내기 전에 이 작업을 수행해야 합니다. | 사용 [Marketo의 받은 편지함 추적기 기능](https://experienceleague.adobe.com/docs/marketo/using/product-docs/email-marketing/deliverability/inbox-tracker/inbox-tracker-tutorials.html){target="_blank"} 이를 위해 계약에 포함되어 있거나 Litmus 또는 Email on Acid와 같은 도구가 있을 수 있습니다. |
| 22 | **추가[!DNL Analytics]** | 이메일에는 추가 분석 코드가 포함되어 있습니까? | **예 또는 해당 사항 없음:**<br>       예(추가 분석 소프트웨어가 없는 경우)로 대답할 수 없는 경우 보내기 전에 이 작업을 수행해야 합니다. |

>[!TAB 최종 검사]

| # | 검토 | 질문할 사항 | 수락 기준 |
|---|---|---|---|
| 1 | **자산 승인** | 완료된 프로그램 에셋 및 챔피언/챌린저 테스트가 완전히 승인되었으며 초안 모드에서 최종 변경 사항이 없는지 확인합니다. | **예:**<br> 예로 대답할 수 없는 경우 보내기 전에 이 작업을 수행해야 합니다. |
| 2 | **스마트 [!DNL Campaign] 정확도** | 스마트 캠페인이 올바른 자산을 참조합니까? | **예:**<br> 예로 대답할 수 없는 경우 보내기 전에 이 문제를 해결해야 합니다. |
| 3 | **체크리스트 단계** | 위의 모든 검사를 완료했습니까? | **예:**<br> 예로 대답할 수 없는 경우 보내기 전에 이 작업을 수행해야 합니다. |
| 4 | **관련자 승인** | 캠페인이 이해 당사자로부터 최종 승인을 받았습니까? | **예:**<br> 예로 대답할 수 없는 경우 보내기 전에 이 작업을 수행해야 합니다. |

>[!ENDTABS]

## 다음은 무엇입니까?

클릭 [여기](/help/marketo-tutorial-inherited-instance/_assets/downloads/[!DNL Adobe]_Marketo_Engage_Inherited_Instance_Program_Prelaunch_QA_Checklist.xlsx)를 클릭하여 사용자 정의할 수 있는 편집 가능한 프로그램 실행 전 체크리스트를 다운로드합니다. 조직의 워크플로에 맞게 조정해야 합니다. 효과적인 QA 프로세스를 개발하면 고객의 실수를 책임지고 제한할 수 있습니다.

### 작성자

**그레이스 브레브너**
[!DNL Adobe] Marketo 챔피언(2021)
*고객 전략, APAC 지역, 디지털 Pi, LLC - A Merkle Company의 Director*

![그레이스 브레브너](/help/marketo-tutorial-inherited-instance/_assets/authors/Customer_Author_Grace_Brebner.png){width=30%}

**에이미 추**
*채택 및 유지 마케팅 관리자,[!DNL Adobe]*

![에이미 추](/help/marketo-tutorial-inherited-instance/_assets/authors/Adobe_Author_Amy_Chiu.png){width=30%}
