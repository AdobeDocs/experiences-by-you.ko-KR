---
title: 표준화된 이름 지정 규칙 만들기
description: 표준화된 이름 지정 규칙은 AA 관리 UI에서 활성화된 경우 변수 이름 자체와 차원으로 전달된 값에 모두 적용됩니다.
solution: Analytics
feature-set: Analytics
feature: Implementation Basics
topic: Administration
role: Admin
level: Beginner
doc-type: article
thumbnail: 10531.jpg
kt: 10531
exl-id: 79cec21e-2b52-4e7b-88ad-db137a8cef4e
source-git-commit: c568ed0a06551d910b6f533698ec47c15adecf6c
workflow-type: tm+mt
source-wordcount: '322'
ht-degree: 0%

---

# 표준화된 이름 지정 규칙 만들기

**내용:** 표준화된 이름 지정 규칙은 [!DNL Adobe Analytics](AA) 관리 UI에서 활성화된 경우 변수 이름 자체와 차원으로 전달된 값에 모두 적용됩니다. (즉, 페이지 이름은 변수 이름으로 &quot;page name (v1)&quot;이 되고 전달된 페이지 이름 값은 균일해야 하며 &quot;sitename|homepage&quot; 또는 &quot;sitename|search|searchresults&quot;와 같은 특정 구조/계층 구조를 따라야 합니다.)

**이유:** 이름 지정 규칙은 일관성을 유지하고 사용자가 인터페이스를 쉽게 이해할 수 있도록 하는 좋은 방법입니다. 처음부터 이를 만들고 플랫폼과 코드에서 적용하면 확장이 더 쉬워집니다.

**방법:** 인터페이스와 태그 지정 문서는 &#39;이름&#39;과 &#39;설명&#39; 모두에 대해 일치해야 합니다. 이렇게 하면 사용자가 Excel 문서를 가져올 필요가 없고 인터페이스에서 직접 데이터를 이해할 수 있습니다. 일관성을 위해 모든 항목을 소문자로 유지하는 것이 좋습니다.

플랫폼(또는 앱의 화면 이름)에서도 페이지 이름을 일관되게 유지하는 것이 가장 좋습니다. 예를 들어 &quot;`property:section:sub section:sub sub section:unique page name`&quot;을(를) 변수/차원으로 설정할 수 있습니다. 이러한 모든 필드가 데이터 레이어의 별도 필드인 경우 JS 파일/실행에서 직접 페이지 이름을 작성할 수도 있습니다. 이러한 모든 요소를 자체 차원으로 설정함으로써 사이트/앱의 특정 속성이나 영역을 보다 쉽게 분류하고 트래픽과 흐름을 더 잘 이해할 수 있습니다.

이름 지정 규칙과 같은 간단한 것을 포함하여 사용자가 데이터를 더 쉽게 찾고 이해할 수 있도록 해 주는 모든 것이 [!DNL Adobe Analytics]의 사용을 증가시키고 비즈니스에 대한 더 나은 통찰력을 제공합니다.

## 작성자

이 문서는 다음에 의해 공동 작성되었습니다.

![Christel 안내서](assets/Christel-Headshot-150.png)

Christel Guidon, NortonLifeLock의 디지털 [!DNL Analytics] 플랫폼 관리자
[!DNL Adobe Analytics] 챔피언

![Rachel Fenwick](assets/Rachel-Fenwick-150.png)

Rachel Fenwick, [!DNL Adobe]의 수석 컨설턴트
