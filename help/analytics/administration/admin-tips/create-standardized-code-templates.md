---
title: 표준화된 코드 템플릿 만들기
description: 기본 구현(즉, 회사에서 모든 [!DNL Adobe Analytics] 개 사이트에 대해 필수 KPI를 고려하는 것)의 경우 조직에는 가능한 한 단일 구현 방법이 있어야 합니다.
solution: Analytics
feature-set: Analytics
feature: Implementation Basics
topic: Administration
role: Admin
level: Beginner
doc-type: article
thumbnail: 10532.jpg
kt: 10532
exl-id: edd3df73-6d1a-4a26-a984-810cc7dd382f
source-git-commit: 058d26bd99ab060df3633fb32f1232f534881ca4
workflow-type: tm+mt
source-wordcount: '355'
ht-degree: 0%

---

# 표준화된 코드 템플릿 만들기

**내용:** &quot;기준&quot; 구현(즉, 회사에서 모든 [!DNL Adobe Analytics] 사이트에 대해 필수 KPI를 고려하는 것)의 경우 조직에는 가능한 한 단일 구현 방법이 있어야 합니다. 예를 들어 사이트 간에 동일한 데이터 레이어 구조를 사용하고 동일한 태그 관리자 규칙/사용자 지정 코드를 사용하여 내부 검색 또는 방문자 프로필 정보와 같은 항목을 캡처합니다.

**이유:** 반복 가능하고 확장 가능한 기초 구현을 통해 새로운 요소 또는 사이트/앱을 간소화하고 쉽게 추가할 수 있을 뿐만 아니라 깔끔한 구현과 손쉬운 문제 해결을 수행할 수 있습니다. 또한 균일한 방법을 사용하면 새로운 관리자/개발자가 온라인에 접속하여 작업 내용을 더 쉽게 이해할 수 있습니다.

**방법:** 새 사이트 또는 태그 지정 개선 기능이 온라인으로 전환될 때 개발자에게 전달할 단일 형식 템플릿을 채택합니다. 일반적으로 Word 문서는 다음 항목에 대한 개요를 제공할 수 있는 경우에 적합합니다.

* 구현 중인 변수, 변수 목적 및 설정 시기. 예:

| AA 변수 | 설명 | 설정 시기/장소 | 설정 방법 |
|--- |--- |--- |--- |
| eVar | 내부 검색 키워드 | 내부 검색 결과 페이지 랜딩 시 | 데이터 레이어 |
| event8 | 내부 검색 수 | 내부 검색 결과 페이지 랜딩 시 | 규칙 실행 |

* 설정 방법에 대한 세부 정보. 여기에서 필요한 데이터 레이어 오브젝트와 해당 구문 및 구성해야 하는 TMS 규칙과 규칙 설정의 세부 정보를 지정할 수 있습니다.
* 확인해야 할 테스트 사례는 QA와 성공적인 테스트 사례에서 확인할 수 있는 모든 변수에 포함되어 있습니다. 개발자가 이 개선 사항을 테스트할 때 성공적인 구현에 포함되어야 하는 사항을 간략히 설명합니다.

이상적으로, 이 문서는 속성 이름, 페이지 이름 지정 규칙 등과 같은 기본 사항을 업데이트하는 다음 사이트에 대해서만 조정하면 됩니다. 매번 쓸데없는 시간을 허비할 필요 없이 더 많은 시간을 절약할 수 있습니다.

## 작성자

이 문서는 다음에 의해 공동 작성되었습니다.

![Christel 안내서](assets/Christel-Headshot-150.png)

Christel Guidon, NortonLifeLock의 디지털 [!DNL Analytics] 플랫폼 관리자
[!DNL Adobe Analytics] 챔피언

![Rachel Fenwick](assets/Rachel-Fenwick-150.png)

Rachel Fenwick, [!DNL Adobe]의 수석 컨설턴트
