---
title: 새 Marketo Engage 구현 계획
description: 새로운 Marketo Engage 인스턴스를 성공적으로 구현하기 위한 필수적인 계획 및 다양한 기능의 팀 공동 작업에 대해 자세히 알아보십시오. 이 자습서에서는 원활한 Marketo Engage 구현을 위한 샘플 이정표, 팀 참여 및 리소스 할당을 제공합니다.
role: Admin
level: Beginner
doc-type: Article
solution: Marketo Engage
duration: 0
last: substantial-update- 2024-05-01
jira: KT-14808
thumbnail: KT-14808.jpeg
source-git-commit: 47ab8875bc4e41595cd40550330e43a88357b68d
workflow-type: tm+mt
source-wordcount: '1098'
ht-degree: 5%

---


# 새 Marketo Engage 구현 계획

새로운 Marketo Engage 인스턴스 구현에는 세심한 계획, 팀 간의 공동 작업 및 지속적인 최적화가 포함됩니다. 새로운 인스턴스를 구현하는 완벽한 방법은 없지만, 이를 경험한 대부분의 Marketo Engage 관리자는 향후 계획을 통해 프로세스가 훨씬 더 원활해질 것이라는 데 동의할 수 있습니다.

이 튜토리얼에서는 성공적인 Marketo Engage 롤아웃에 중요한 특정 이정표, 팀 참여 및 리소스 할당에 대해 알아봅니다.

## 새 Marketo Engage 구현 동안의 주요 이정표

### 1단계 - 검색 및 계획

- 마케팅 및 판매 요구 평가 수행
- 목표 또는 주요 성과 지표(KPI) 정의

### 2단계 - 기술 설정 및 구성

- CNAME 및 Munchkin 코드를 포함한 관리 설정을 구성하는 중입니다.
- 리드 관리 프로세스 구성
- 자동화 워크플로 및 데이터 동기화 테스트

### 3단계 - 프로그램 라이브러리 만들기 및 캠페인 설정

- 이메일 템플릿 및 랜딩 페이지 개발. 시작 [시작 프로그램 가져오기](https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/core-marketo-concepts/programs/working-with-programs/import-a-program) 다음에서 [프로그램 가져오기 라이브러리](https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/core-marketo-concepts/programs/program-library/program-import-library-overview).
- 세그먼테이션 및 개인화 규칙 설정
- 리드 생성 및 육성을 위한 초기 캠페인 만들기

### 4단계 - 교육 및 사용자 채택

- 사용자를 위한 교육 세션 및/또는 자료 수행
- 인스턴스 거버넌스 정책 및 모범 사례 수립
- 사용자 채택 지표 및 관련자 피드백 모니터링

### 5단계 - Go-Live 및 최적화

- 최종 시스템 테스트 및 품질 보증
- 초기 캠페인 실행 및 성과 모니터링
- 보고 및 분석을 기반으로 한 반복적인 개선 사항 구현

## 이해 당사자 참여 및 리소스 필요

새 인스턴스를 구현하려면 인스턴스의 이점을 극대화하기 위한 세심한 계획과 실행이 필요합니다. 처음부터 적절한 이해 당사자를 참여시키면 조직의 전반적인 요구 사항에 맞게 구현을 조정할 수 있습니다. 아래 프로젝트에서 주요 관련자와 이들의 잠재적인 역할에 대한 샘플을 참조하여 Marketo Engage을 구현할 올바른 내부 파트너를 찾을 수 있습니다.

<table>
 <thead>
    <tr>
        <th>이해 당사자</th>
        <th>잠재적 역할 및 책임  </th>
    </tr>
 </thead>    
 <tbody>
    <tr>
        <td>마케팅 운영 Director/Manager</td>
        <td>
        <li>프로젝트에 대한 주요 담당자</li>
        <li>인스턴스 거버넌스 규칙</li> 
        <li>보고 및 분석을 위한 데이터 분석 </li> 
        </td>
    </tr>
    <tr>
        <td>CRM 관리자</td>
        <td>
        <li>CRM 동기화 </li>
        <li>리드 플로우</li> 
        </td>
    </tr>
     <tr>
        <td>IT 관리자</td>
        <td>
        <li>먼치킨</li>
        <li>SPF/DKIM </li> 
        <li>웹 도메인 설정</li> 
        <li>CNAME</li> 
        <li>이메일 전달성</li>
        </td>
    </tr>
    <tr>
        <td>엔지니어링</td>
        <td>
        <li>맞춤형 서비스 통합 작업을 위한 개발 </li>
        <li>데이터 매핑 및 마이그레이션을 위한 데이터 엔지니어링</li> 
        </td>
    </tr>
     <tr>
        <td>마케팅 </td>
        <td>
        <li>프로그램 템플릿 제작 및 디자인</li>
        <li>채널 </li>
        <li>잠재 고객/개인 점수 및 라이프사이클</li> 
        <li>프로그램 효과에 대한 보고 및 피드백</li> 
        </td>
    </tr>
     <tr>
        <td>판매</td>
        <td>
        <li>잠재 고객/개인 채점 모델링</li>
        <li>리드 플로우/라우팅</li>  
        <li>라이프사이클 SLA(서비스 수준 계약)</li> 
        </td>
    </tr>
     <tr>
        <td>C-세트</td>
        <td>
        <li>전체 프로젝트 방향  </li>
        <li>높은 수준의 구현 목표</li> 
        </td>
    </tr>
</table>

## 피어 관점 - Marketo Engage 구현

Marketo Engage 챔피언(2019), Kyle McCormick의 Palotos Networks 온보딩 및 구현 경험에 대해 들어보십시오. 그가 직면한 문제와 온보딩 프로세스를 성공적이고 효율적으로 추진하는 방법에 대한 그의 조언에 대해 알아봅니다.

>[!VIDEO](https://video.tv.adobe.com/v/3428771/?quality=12&learn=on)

## 다음은 무엇입니까?

새 구현 프로젝트 계획 및 타임라인을 만듭니다. 다음은 샘플 이정표, 작업, 책임 팀, 기한 및 종속성에 대한 섹션을 포함하는 샘플 프로젝트 타임라인입니다. 이를 사용하여 Marketo Engage 구현 여정을 간소화하고 조직 전체에 대한 성공적인 롤아웃을 보장하십시오.

특정 마일스톤 작업을 편집하고 추적하는 예를 다운로드할 수도 있습니다 [여기](/help/marketo-tutorial-implementing-new-instance/assets/adobe-marketo-engage-implementation-milestones-project-management-template.xlsx).

<table>
 <thead>
    <tr>
        <th>주제</th>
        <th>마일스톤</th>
        <th>상태</th>
        <th>예상 일자</th>
        <th>실제 일자</th>
        <th>필요한 리소스</th>
    </tr>
 </thead>    
 <tbody>
    <tr>
        <td><em>이러한 일반 온보딩 주제를 사용하여 이정표의 단계를 구성합니다.</em></td>
        <td><em>특정 마일스톤 작업을 작성하십시오.</em></td>
        <td><em>작업의 현재 상태는 무엇입니까?</em></td>
        <td><em>이 작업의 계획된 완료 일자는 얼마입니까?</em></td>
        <td><em>이 작업은 실제로 언제 완료되었습니까?</em></td>
        <td><em>이 작업을 완료하는 데 필요한 리소스와 해당 리소스를 필요로 하는 팀은 무엇입니까?</em></td>
    </tr>
    <tr>
        <td rowspan="2">기술 설정</td>
        <td><em>예 -</em> 회사 웹 사이트에 MunchkinID 설치</td>
        <td bgcolor="c6f0cf">완료</td>
        <td>9/5/24</td>
        <td>9/12/24</td>
        <td>웹 개발 팀</td>
    </tr>
    <tr>
        <td><em>예 -</em> 게재 가능성 및 이메일 추적 링크를 위해 DKIM(Domain Keys Identified Mail) 및 2개의 개별 CNAME을 설정합니다.</td>
        <td bgcolor="c6f0cf">완료</td>
        <td>9/15/24</td>
        <td>9/18/24</td>
        <td>IT 팀의 지원 및 설정</td>
    </tr>
    <tr>
        <td rowspan="4">Adobe Admin Console 및 관리 설정</td>
        <td><em>예 -</em> Marketo Engage 사용자 및 역할 만들기</td>
        <td bgcolor="c6f0cf">완료</td>
        <td>8/27/24</td>
        <td>9/15/24</td>
        <td>Marketo Engage 액세스 권한이 필요한 사용자에 대한 마케팅 팀의 정보입니다.</td>
    </tr>
    <tr>
        <td><em>예 -</em> Adobe Admin Console에서 추가 Marketo Engage 제품 관리자 만들기</td>
        <td bgcolor="c6f0cf">완료</td>
        <td>8/27/24</td>
        <td>9/15/24</td>
        <td>Marketo Engage에 대한 관리자 액세스 권한이 필요한 사람에 대한 마케팅 운영 팀의 정보입니다.</td>
    </tr>
    <tr>
        <td><em>예 -</em> 지원 관리자 설정</td>
        <td bgcolor="c6f0cf">완료</td>
        <td>8/27/24</td>
        <td>9/15/24</td>
        <td>지원을 위한 기본 담당자를 확인하기 위한 마케팅 운영 팀의 정보입니다. 지원 관리자 사용자를 할당하기 위한 시스템 관리자의 지원.</td>
    </tr>
    <tr>
        <td><em>예 -</em> 폴더 구조 및 이름 지정 규칙 정의</td>
        <td bgcolor="c6f0cf">완료</td>
        <td>9/7/24</td>
        <td>9/12/24</td>
        <td>프로그램 유형 및 조직 요구 사항에 대한 Marketo Engage을 사용하여 각 팀의 정보를 입력합니다.</td>
    </tr>
    <tr>
        <td rowspan="2">CRM 통합(적용되는 경우)</td>
        <td><em>예 -</em> 동기화 전에 필드 매핑 결정</td>
        <td bgcolor="ffeb9c">진행 중</td>
        <td>10/22/24</td>
        <td>N/A</td>
        <td>사용 가능한 필드를 이해할 수 있도록 CRM 관리자의 지원을 받습니다.</td>
    </tr>
    <tr>
        <td><em>예 -</em> 데이터 감사 수행</td>
        <td bgcolor="ffeb9c">진행 중</td>
        <td>10/26/24</td>
        <td>N/A</td>
        <td>CRM 관리자 또는 예산의 지원.</td>
    </tr>
    <tr>
        <td rowspan="2">운영 프로그램 빌드</td>
        <td><em>예 -</em> 들어오는 데이터를 표준화하는 프로그램 만들기</td>
        <td bgcolor="ffc7cf">시작되지 않음</td>
        <td>11/9/24</td>
        <td>N/A</td>
        <td>Sales Ops 및 CRM 팀의 지원을 받아 데이터 관리 전략을 결정합니다.</td>
    </tr>
    <tr>
        <td><em>예 -</em> 이메일 구독 센터 만들기</td>
        <td bgcolor="ffc7cf">시작되지 않음</td>
        <td>11/19/24</td>
        <td>N/A</td>
        <td>메일링 목록의 콘텐츠 유형 및 세그멘테이션에 대한 마케팅 팀의 입력입니다.</td>
    <tr>
        <td rowspan="2">첫 번째 마케팅 프로그램 빌드</td>
        <td><em>예 -</em> 기본 이메일 프로그램 설정</td>
        <td bgcolor="ffeb9c">진행 중</td>
        <td>11/12/24</td>
        <td>N/A</td>
        <td>이메일 및 랜딩 페이지를 위한 디지털 팀의 크리에이티브 자산입니다.</td>
    </tr>
    <tr>    
        <td><em>예 -</em> 분기별 뉴스레터용 프로그램 만들기</td>
        <td bgcolor="ffc7cf">시작되지 않음</td>
        <td>11/30/24</td>
        <td>N/A</td>
        <td>뉴스레터 이메일에 대한 마케팅 팀의 컨텐츠와 디자인 팀의 크리에이티브 에셋/컨텐츠입니다.</td>
    </tr>
    <tr>
        <td rowspan="2">LaunchPoint 통합 설정</td>
        <td><em>예 -</em> API 전용 사용자 및 역할 만들기</td>
        <td bgcolor="ffc7cf">시작되지 않음</td>
        <td>11/23/24</td>
        <td>   </td>
        <td>마케팅 팀과 함께 새 인스턴스에 필요한 서비스의 범위를 좁힙니다.</td>
    </tr>
    <tr>
        <td><em>예 -</em> Google 광고에 대한 사용자 정의 서비스 만들기</td>
        <td bgcolor="ffc7cf">시작되지 않음</td>
        <td>12/7/24</td>
        <td>   </td>
        <td>Google 광고에 액세스하기 위해 Marketo Engage을 인증하도록 웹 및 유료 미디어 팀의 지원을 제공합니다.</td>
        <td>
    </tr>
    <tr>
        <td rowspan="2">사용자 교육 및 설명서</td>
        <td><em>예 -</em> 내부 사용자를 위한 거버넌스 안내서 만들기</td>
        <td bgcolor="ffc7cf">시작되지 않음</td>
        <td>12/2/24</td>
        <td>N/A</td>
        <td>Marketo Engage 거버넌스 팀을 만들어 지원 거버넌스 문서 또는 예산을 빌드하여 거버넌스 프로젝트를 계약합니다.</td>
    <tr>
        <td><em>예 -</em> 4명의 사용자를 교육하고 표준 Marketo 사용자 액세스를 제공합니다.</td>
        <td bgcolor="ffc7cf">시작되지 않음</td>
        <td>12/13/24</td>
        <td>N/A</td>
        <td>Marketo Engage 액세스에 필수인 교육을 만들도록 마케팅 VP의 지원.</td>
    <tr>
        <td rowspan="2">실행</td>
        <td><em>예 -</em> 첫 번째 뉴스레터 전송</td>
        <td bgcolor="ffc7cf">시작되지 않음</td>
        <td>12/9/24</td>
        <td>N/A</td>
        <td>QA, 예약 및 보내기 마케팅 운영 팀.</td>
    </tr>
    <tr>
        <td><em>예 -</em> 첫 번째 이메일 성과 보고서를 가져옵니다.</td>
        <td bgcolor="ffc7cf">시작되지 않음</td>
        <td>12/16/24</td>
        <td>N/A</td>
        <td>QA, 예약 및 보내기 마케팅 운영 팀.</td>
    </tr>
 </tbody>    
</table>

>[!NOTE]
>제공된 예제는 실제 구현 타임라인을 기반으로 하지 않습니다. 모든 구현은 조직의 요구 사항에 따라 서로 다른 이정표와 요구 사항을 가지고 있으므로 이러한 사항을 Marketo Engage으로 온보딩하기 위한 표준 타임라인으로 사용하지 마십시오.

인스턴스의 Marketo Engage 구현 및 맞춤화에 대한 직접적인 지원이 필요한 경우 Adobe 계정 팀에 문의하거나 [Adobe Professional Services](https://business.adobe.com/customers/consulting-services/main.html){target="_blank"}.

### 작성자

{{amy-chiu}}