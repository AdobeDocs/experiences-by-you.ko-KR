---
title: 인스턴스 거버넌스 및 설명서 시작
description: Marketo Engage 거버넌스 및 설명서를 시작하기 위한 필수 전략과 모범 사례에 대해 알아봅니다. 확장 가능한 설명서를 만들고, 사용자 교육을 간소화하고, Marketo Engage 인스턴스의 구조를 빌드하는 방법을 알아봅니다.
role: Admin
level: Beginner
doc-type: Article
solution: Marketo Engage
duration: 0
last-substantial-update: 2024-05-08T00:00:00Z
jira: KT-14815
thumbnail: KT-14815.jpeg
exl-id: b3dd05e1-c522-4631-a6b4-c0c6309f25d3
source-git-commit: 1205848b1985a99b91f9d4d25e1a79f0df379589
workflow-type: tm+mt
source-wordcount: '815'
ht-degree: 0%

---

# 인스턴스 거버넌스 및 설명서 시작하기

유용한 설명서는 실제 인스턴스 구현 자체만큼 중요할 수 있습니다. 거버넌스 가이드는 프로그램/폴더 구조, 통신 제한 등과 같은 주제에 대해 Marketo Engage 인스턴스 설정 세부 사항을 대략적으로 설명하는 중요한 리소스입니다. 이 라이브 문서는 Marketo Engage 관리자 또는 고급 사용자를 위한 참조로서, Marketo Engage 인스턴스 및 조직에 맞는 특정 모범 사례와 관리 표준을 소개합니다.

하지만 거기서 멈추지 않습니다. Marketo Engage 숙련도를 높이기 위해 보충 지원 문서 또는 교육 자료가 필요할 수 있습니다. 이러한 리소스에는 대화형 연습, 액세스 퀴즈 또는 Marketo Engage 내의 허용되는 작업에 대한 지침이 포함될 수 있으므로 조직 내의 모든 Marketo Engage 사용자에게 도움이 됩니다. 포괄적인 거버넌스 가이드를 만들거나 주요 설정 측면을 처음에 문서화하든, 온보딩 중에 결정된 사항을 기록하는 것은 현재 팀과 미래 세대의 새로운 채용을 위한 Marketo Engage을 성공적으로 수행하는 데 핵심적입니다.

이 튜토리얼에서는 설명서 및 거버넌스의 중요성을 이해함으로써 전문가 동료가 제공한 모범 사례를 살펴봅니다. [Marketo Engage 거버넌스 및 교육 설명서 시작하기](https://nation.marketo.com/t5/product-blogs/getting-started-on-your-marketo-governance-and-training/ba-p/242421){target="_blank} 및 [인스턴스를 어떻게 문서화합니까?](https://nation.marketo.com/t5/product-discussions/how-do-you-document-your-instance/td-p/72877){target="_blank}을(를) 통해 프로세스를 구축하고 내부 사용자와 관련된 문서를 유지할 수 있습니다.

## 인스턴스 구현 중 변경 사항 및 결정을 문서화하는 것이 중요한 이유

기술에 익숙하지 않은 신규 직원을 인스턴스에 온보딩하도록 안내하는 것처럼 Marketo Engage 설명서에 접근합니다. 일단 Marketo Engage 경험을 쌓으면 기본 지식을 간과하기 쉽다. 관리자는 초보자에게 적합한 활성화 및 거버넌스 문서를 제공해야 합니다. 신규 사용자의 학습을 용이하게 하기 위해 실용적인 방법은 정의 및 모범 사례를 교육 자료에 직접 통합하는 것입니다.

인스턴스 설정 중에 인스턴스 설명서를 만들면 다음과 같은 몇 가지 이점이 있습니다.

* 확장 가능한 방식으로 신규 사용자를 위한 교육 프로세스를 간소화합니다.
* 견고한 문서 기반을 구축하여 Marketo Engage에서 장기적인 프로그램 개발을 용이하게 합니다.
* 시간이 지남에 따라 인스턴스의 상태와 구성을 유지합니다.
* 팀 이직 시 새 Marketo Engage 관리자를 위한 원활한 전환을 수행합니다.

궁극적으로, 구현 중에 결정한 사항을 기록하면 프로세스를 실행하기 위해 한 명 또는 몇 명에 의존하지 않고 귀사와 팀이 Marketo Engage을 성공적으로 수행하는 데 도움이 됩니다.

## Marketo Engage 인스턴스 거버넌스 및 설명서를 구축하는 방법

### 1단계 - 인스턴스 설명서의 주요 항목 개요

문서화할 항목과 문서화할 필요가 없는 항목에 대한 표준 설정을 정의합니다. 이렇게 하면 조직에서 프로세스를 채택할 수 있습니다. 문서를 확장할 때 설정의 원인을 문서화하는 것이 중요합니다. 이는 자신만큼 다른 관리자가 결과를 내지 못한 의사 결정에 시간을 낭비하지 않도록 하는 데 도움이 됩니다.

아래 샘플 개요부터 시작하여 거버넌스 및 설명서 계획을 안내합니다.

1. 조직의 Marketo Engage 목적
1. 이 설명서의 목적
1. 거버넌스 안내서의 유지 관리/변경 프로세스
1. 관리 설정
   * 구독
   * 작업 공간 및 파티션(적용되는 경우)
   * 기술 설정(DKIM/SPF/Munchkin)
   * 역할 및 책임*
   * 사용자*
   * 스마트 캠페인/이메일/프로그램 설정
   * 커뮤니케이션 제한
   * 보안
   * 채널*
   * 태그
1. 데이터 구조
   * 필드 구조
   * 사용자 지정 개체
1. 운영 프로그램
   * 개인 채점
   * 개인 라이프사이클
   * 데이터 관리
1. Marketo Engage 인스턴스에서 빌드 중
   * [COE(Center of Excellence)](https://business.adobe.com/blog/perspectives/center-of-excellence-top-10-questions-to-ask-yourself){target="_blank}
   * 폴더 구조
   * 이름 지정 규칙
   * 프로그램 조직
   * 프로그램 템플릿*
   * Design Studio Assets(이메일 템플릿, 랜딩 페이지 템플릿, 코드 조각, 양식)
   * 표준화된 프로세스
   * 체크리스트
   * 세그먼트화
   * 보관 정책
   * 구독 센터
1. CRM 통합
   * 동기화 작동 방식
   * Campaign 동기화
   * 데이터 사전
1. 기타 통합
1. GDPR 및 규정 준수

\* 설정이 완료되면 설명서에 사용자 및 역할, 프로그램 템플릿 및 채널에 대한 세부 정보가 포함되어야 합니다.

### 2단계 - 변경 로그 만들기

인스턴스 거버넌스의 또 다른 중요한 방법은 변경 로그를 만들고 이를 사용하는 것입니다. &#39;관리&#39; 섹션 또는 운영 프로그램의 설정을 변경할 때마다 팀은 공유 스프레드시트와 같은 중앙 집중화된 위치에서 이를 확인해야 합니다. 이는 변화를 준 이유와 그 이전에 어땠는지 기억하는 데 도움이 될 수 있다. 변경 로그에 작성해야 하는 필드는 다음과 같습니다.

1. 날짜
1. 프로그램 이름
1. 프로그램 링크
1. 스마트 캠페인 이름
1. 스마트 캠페인 링크
1. 변경 완료
1. 변경 이유
1. 누가 변경했습니까

## 다음은 무엇입니까?

* [샘플 설명서 및 변경 로그](/help/marketo-tutorial-implementing-new-instance/assets/template-adobe-marketo-engage-instance-documentation.xlsx)를 다운로드하고 조직의 필요에 따라 조정하십시오.
* 조직에서 참조하고 정기적으로 업데이트하기를 원하는 액세스 가능한 플랫폼에 설명서를 저장합니다. 예를 들어 일부 Marketo Engage 챔피언은 Confluence(Atlassian의 설명) 또는 Excel 스프레드시트를 사용합니다.
* 거버넌스에 대해 만드는 모든 규칙에 이를 적용하고 설명서를 조정하여 시간이 지남에 따라 최신 상태로 유지할 수 있는 소유자가 있는지 확인합니다.

### 작성자

{{amy-chiu}}
