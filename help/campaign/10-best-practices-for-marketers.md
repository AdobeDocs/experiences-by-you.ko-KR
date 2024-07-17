---
title: 마케터의  [!DNL Adobe] [!DNL Campaign] 성공을 위한 10가지 모범 사례
description: ' [!DNL Adobe] [!DNL Campaign]명의 전문가가 디지털 소비자 전환과 더 나은 고객 경험을 제공하고 가속화하는 데 도움이 되는 10가지 모범 사례에 대해 알아봅니다.'
doc-type: article
solution: Campaign
feature-set: Campaign
feature: Personalization, Campaigns, Subscriptions, Deliverability
role: User
level: Beginner
jira: KT-11772
last-substantial-update: 2023-01-31T00:00:00Z
exl-id: add6ed84-892d-4901-9dd2-b0cba0c57290
source-git-commit: ec621f6e118292a3f8448c0e21abe8a1284cb10e
workflow-type: tm+mt
source-wordcount: '1262'
ht-degree: 77%

---

# 마케터를 위한 [!DNL [!DNL Adobe] [!DNL Campaign]] 성공 사례 10개

Christian Klimczyk는 7년간의 [!DNL [!DNL Adobe] Experience Cloud] 전문 지식을 갖춘 &quot;[!DNL Adobe] Nerd&quot;로, 주로 [!DNL [!DNL Adobe] [!DNL Campaign]]에 중점을 둡니다. 대규모 CPG 회사의 [!DNL Adobe] 플랫폼 소유자로서 Christian과 그의 팀은 모든 소비자 커뮤니케이션 및 상호 작용에 [!DNL [!DNL Campaign]]을(를) 사용합니다. 이들은 다이렉트 메일, 이메일, SMS/MMS에서 까다로운 규정 상 요건과 멀티채널 소비자 마케팅 캠페인을 원활하게 조정 및 관리합니다.

이 문서에서 Christian은 [!DNL Adobe] [!DNL Campaign] 실무 담당자들이 디지털 소비자 전환과 더 나은 고객 경험을 제공하고 가속화할 수 있도록 돕기 위한 모범 사례를 공유합니다.


## 1. 중심이 되는 통합 마케팅 및 게재 계획 수립

[!DNL [!DNL Adobe] [!DNL Campaign]]을(를) 통해 성공을 보장하기 위한 첫 번째 단계는 도구 및 고객 기대치를 이해하는 것입니다. 이는 모든 유형의 마케팅에서 적용됩니다. 소비자에게 연락하는 데 사용할 채널을 명확히 정의하고 이해하며 이 채널을 사용해야 하는 시점과 그 이유를 알아 두어야 합니다.

[!DNL Adobe] [!DNL Campaign]은(는) 다양한 방법으로 커뮤니케이션을 실행하고 오케스트레이션할 수 있는 유연한 도구입니다. [고객 중 절반은 구매 여정 한 번에 채널을 3개에서 5개까지 활용합니다](https://www.mckinsey.com/capabilities/operations/our-insights/redefine-the-omnichannel-approach-focus-on-what-truly-matters). 따라서 미리 이 채널을 이해하고 어떻게 사용할지에 대한 계획을 갖추는 것이 플랫폼의 잠재력을 최대한 실현하고 고객의 마음을 움직이는 데 중요합니다.

## 2. 고객 데이터 기록 및 파악

<!-- Sandra, this paragraph opens as if it's going to discuss the advantages of segmentation, but it left me hanging. So, I hit the Hubspot link and dug into it a bit, and it seemed to me like the juicy information is this quote: 

"A study by Hubspot revealed that 30% of the marketers who participated in it used market segmentation techniques to improve email engagement. Segmented campaigns had 14.31% higher open rates and saw 101% more clicks than non-segmented campaigns.

"Email marketers who segmented their audience before campaigning stated that the revenue generated increased to up to 760%. Targeted and segmented emails bring in 58% of all revenue." [Link](https://www.notifyvisitors.com/blog/segmentation-statistics/) 

I added that second paragraph about 760% revenue and broke up the rest of the section, touched it up to help make the Hubspot example a little more impactful. If I altered this section too much, you can reject the change. It didn't have mistakes, but it felt like it didn't tie the segment example strongly enough to the point about data design. See if this is okay...-->

[Hubspot의 연구](https://www.linkedin.com/pulse/customer-segmentation-effective-b2b-business-industry-sabreen)에 따르면 세분화를 활용한 캠페인이 세분화하지 않은 캠페인보다 14.31% 높은 오픈율과 101% 많은 클릭 수를 기록했습니다. 캠페인을 시작하기 전에 대상자를 세분화한 이메일 마케터들은 매출이 최대 760%까지 증가했다고 말했습니다.

[!DNL Adobe] [!DNL Campaign]에서 세그먼테이션을 빠르고 쉽게 조정할 수 있습니다. 그러나 이 과정을 간소화하고 용이하게 하려면 캠페인 운영자와 마케팅 전문가가 캠페인 작성 및 실행을 디자인하고 요청할 때 기저가 되는 데이터를 파악하여 기록해야 합니다. [!DNL [!DNL Campaign]] 인스턴스를 지원하는 관리자 및 개발자와 파트너 관계를 맺을 때 현재 데이터를 이해하고 필요한 데이터를 예측하는 방법을 이해하는 것이 중요합니다.

캠페인을 지지하는 기저 데이터 구조가 캠페인의 성과를 좌우합니다. 이 데이터 구조를 파악하여 기록해 두면 플랫폼을 통합하거나 소비자 데이터 플랫폼으로 이동할 때 문제가 발생하는 경우에도 도움이 됩니다.

## 3. 캠페인 실행 시점 기획

고객과 마찬가지로 캠페인 관리자에게도 매일 따를 일정이 있습니다. 캠페인을 보내고 오케스트레이션하는 시점이 이 리듬에 맞아야 합니다. 그렇지 않은 경우에는 [보낸 메일의 85%가 열리지 않으며 보낸 메일의 98%가 클릭스루로 이어지지 않습니다](https://www.validity.com/resource-center/state-of-email-2021/).

예를 들어 고객이 아침에 전화기로 좋은 세일이 있는지 확인하면 문자로 프로모션을 보내는 방안을 고려해 보세요. 밤에 다음에 유행할 제품을 찾아보는 고객에게는 후속 이메일로 무료 배송 프로모션 코드를 보내는 것도 생각해 보세요. 또한 워크플로우 및 전송을 실행하는 시기를 추적하기 위해 [!DNL [!DNL Campaign]]에서 히트맵 도구를 사용하는 것이 중요합니다. 여러 브랜드 간의 커뮤니케이션을 조정하고 촉진하는 일은 어려울 수 있습니다. [전자 메일의 리듬, 케이던스 및 타이밍을 주시하고 알아봅니다](https://experienceleaguecommunities.adobe.com/t5/adobe-campaign-classic-blogs/predictive-send-time-optimization-with-adobe-campaign/ba-p/561554?profile.language=ko)은(는) 메시지 및 [!DNL Campaign] 인스턴스의 전반적인 안정성과 강도에 매우 유용합니다.

## 4. 필요한 경우 개인화 사용

오늘날 소비자들은 자신이 받는 메시지가 어느 정도 개인화되어 있을 것을 기대합니다. [고객의 80%는 개인화된 경험을 제공하는 브랜드에서 구매할 가능성이 높습니다](https://us.epsilon.com/power-of-me). 제목에 고객의 이름을 넣는 것은 훌륭한 전략입니다. 하지만 개인화를 제대로 활용하면 그보다 훨씬 놀라운 일을 해낼 수 있습니다. 메시지 내용에 고객이 찾아본 제품을 넣거나, 유사한 제품 구매 링크로 연결하거나, 브랜드가 제공하는 일관적 경험과 디자인을 지속적으로 강화할 수도 있습니다. 모든 디테일이 중요하며 고객 충성도와 메시지 오픈율을 높이는 데 도움이 됩니다.

## 5. 충분한 크리에이티브 자산 보유

캠페인 게재가 엔진이라면 크리에이티브 자산은 그 엔진이 효과적이고 원활하게 돌아가게 하는 연료가 되는 가솔린 역할을 합니다. 성공적인 마케팅을 통해 고객에게 도달하고 마케팅 프로세스가 확장 및 발전할수록 크리에이티브 콘텐츠가 더 많이 필요합니다. 소비자들이 보다 많은 크리에이티브 콘텐츠를 기대하기 때문입니다.

이를 제공할 수 있는 속도는 팀이 다음 게재를 구성하는 속도에 달려 있습니다. 그렇게 하려면 새롭고 흥미진진한 콘텐츠가 필요한 경우가 많습니다. [!DNL [!DNL Adobe] [!DNL Campaign]]을(를) 사용하면 템플릿을 구성하고 이러한 게재를 받고 쉽게 준비할 수 있습니다. 그러나 [Litmus 보고서](https://www.litmus.com/resources/state-of-email/)에 따르면 마케터의 58%가 단일 이메일 캠페인을 만드는 데 2주 이상이 걸린다고 언급했기 때문에 건강한 크리에이티브 파이프라인을 보유하는 것이 중요합니다.

## 6. 구독 및 환경 설정의 이해와 관리

구독 환경 설정의 유지 관리 작업은 순식간에 혼동을 일으켜 다양한 수준의 위험을 초래할 수 있습니다. 고객이 응답하지 않는 채널을 통해 잘못된 메시지를 보내는 것과 마찬가지로, 부정적인 경험을 한 경우 향후 그 브랜드에서 구매할 가능성이 낮아진다고 10명 중 9명의 소비자가 밝혔습니다. 문제가 커지면 규정을 준수하지 못하여 벌금을 물게 될 수도 있습니다.

[!DNL [!DNL Adobe] [!DNL Campaign]] 및 기타 마케팅 기술 도구의 전문가 사용을 통해 옵트인을 관리하고 지속적으로 발전하는 에코시스템을 육성하기 위한 전략을 미리 수립하십시오. 이는 가장 큰 캠페인 성공 지표 중 하나가 되는 경우가 많으므로, 신중한 기획은 캠페인 전략이 성장하고 발전함에 따라 값진 결과를 가져다 줍니다.

## 7. 게재 가능성의 이해와 계획

_게재 가능성_&#x200B;은 신비롭고 복잡한 개념처럼 보이곤 합니다. 게재 가능성의 중요한 기저 규칙은 전략적 기획입니다. IP 주소를 준비하고 좋은 평판을 얻는 데는 시간이 소요됩니다. 이 평판은 빠르게 감소할 수 있으므로 손상이 발생한 경우 복구하기 어렵습니다. 사실 **이메일 6개 중 1개는 받은 편지함에 도달하지 못합니다**.

게재 가능성 문제는 기술 요소나 소비자가 마케팅에 어떻게 반응하는지에 따른 문제 등 여러 요소로 인해 발생할 수 있습니다. 캠페인을 만들고 실행할 때와 이를 재검토하는 과정에서 [게재 가능성](https://business.adobe.com/ko/products/campaign/email-deliverability.html)을 염두에 두면 건강하고 안정된 환경을 유지하고 고객에게 계속 긍정적인 경험을 제공할 수 있습니다.

## 8. 캠페인 재검토 과정 기획 및 개발

캠페인을 게재하고 오케스트레이션하느라 바쁜 와중에도, 그간의 성취를 돌아보고 캠페인의 프로세스와 세분화를 재평가하는 작업은 매우 유용한 경우가 많습니다. 캠페인 실행의 규모 및 속도에 따라 2~4주에 한 번씩 캠페인을 재검토하세요.

여러 질문을 정리해 양식으로 만들어 놓으면 여러 다른 주제 중에서 캠페인의 리드 타임, 크리에이티브 또는 세분화를 개선하는 방법에 대해 깊이 있고 세심한 대화를 안내하는 데 도움이 됩니다. 때로는 전에 실행한 작업으로부터 배워야만 보다 우수하고 빠르게 작업할 수 있습니다.

## 9. 테스트와 반복

새로운 것을 시도할 때에는 처음부터 제대로 해내기 어려운 경우도 있습니다. 따라서, 프로세스와 전략을 실험하고 반복하는 과정이 중요합니다. 가능성이 낮아 보이거나 잘 맞을 듯한 고객 그룹을 대상으로 시도하세요. 크리에이티브를 전환하세요. 새로운 콜 투 액션(call to action)을 사용해 보세요. 변화를 목적으로 하는 변화는 생산적이지 않지만 장기간에 걸쳐 작고 정확한 실험을 여러 가지 진행하다 보면 여러분과 고객에게 앞으로 큰 성공을 가져다 줄 가능성을 높일 수 있습니다.

## 10. 최대한 기민한(애자일) 조직 만들기

시장은 점점 빠른 속도로 계속 변화하며 움직입니다. 시장에서 경쟁하며 높아지는 고객의 기대를 계속 충족하려면 캠페인 팀이 계속 최대한 가볍고 기민하게 유지되도록 유도하는 것이 중요합니다.

[디지털 마케팅 리더의 35%가 가장 큰 어려움은 조직 내에서 발생한다고 생각합니다](https://www.gartner.com/en/newsroom/press-releases/gartner-says-35--of-digital-marketing-leaders-believe-the-bigges). 이를 위해 몇 개의 플랫폼에서 교차 트레이닝을 수행하고 데이터 흐름 및 구조 또는 기타 [!DNL Adobe] 솔루션에 대한 이해를 높이며 캠페인에 대한 긴급 계획을 만듭니다. 이런 사고방식은 여러 방법으로 성취할 수 있지만, 장단기적 성공을 달성하는 데에는 기민함과 기획을 위한 전반적 노력이 매우 중요합니다.
