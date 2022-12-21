---
unique-page-id: 15695924
description: 계정 프로파일링 순위 및 조정 - Marketo 문서 - 제품 설명서
title: 계정 프로파일링 순위 및 조정
exl-id: 9c5d0a03-0ebe-43cc-95ef-faab19a7f673
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '381'
ht-degree: 0%

---

# 계정 프로파일링 순위 및 조정 {#account-profiling-ranking-and-tuning}

계정 프로파일링은 이상적인 고객 프로필(ICP)을 식별하고, ICP를 기반으로 데이터베이스의 회사에 대해 등급을 매기고, ICP 지표 데이터를 명명 계정으로 승격된 계정에 추가합니다.

## 모델 결과 {#model-results}

그 결과, 등급별로 분류된 모든 알려진 계정이 표시됩니다. A는 가장 높은 등급이고 D는 가장 낮은 등급입니다.

![](assets/results.png)

선택 사항이지만 자동 홍보 확인란을 선택하면 많은 시간을 절약할 수 있습니다. 하지만 각 계정을 살펴보고 싶다면 [수동으로 추가](/help/marketo/product-docs/target-account-management/target/named-accounts/discover-accounts.md#discover-crm-accounts)확인란을 선택 취소하면 됩니다.

<table> 
 <tbody> 
  <tr> 
   <td><strong>순위</strong></td> 
   <td> 
    <div>
      이상적인 고객 프로필을 기반으로 한 계정 등급입니다. A가 가장 잘 맞는데 D가 가장 잘 맞지 않는다. 
    </div></td> 
  </tr> 
  <tr> 
   <td><strong>성향</strong></td> 
   <td> 
    <div>
      비ICP 기반 계정 선택과 비교하여 전환율의 예상 증가. 
    </div></td> 
  </tr> 
  <tr> 
   <td><strong>계정 (%)</strong></td> 
   <td> 
    <div>
      이 등급을 가진 모델 입력의 계정 비율입니다. 
    </div></td> 
  </tr> 
  <tr> 
   <td><strong>모델 기준 %</strong></td> 
   <td> 
    <div>
      이 등급을 갖는 모델 기반의 계정 비율입니다. 
    </div></td> 
  </tr> 
 </tbody> 
</table>

## 모델 조정 {#model-tuning}

모델 탭에서 모델 조정 단추를 클릭합니다.

![](assets/two.png)

선택할 수 있는 탭이 여러 개 있어 심층적인 사용자 지정을 허용합니다.

![](assets/tuning-page.png)

**지표 카테고리**

<table> 
 <tbody> 
  <tr> 
   <td><strong>규정 준수</strong></td> 
   <td> 
    <div>
      인증, 규정 준수 관련 직책/채용 
    </div></td> 
  </tr> 
  <tr> 
   <td><strong>작업</strong></td> 
   <td> 
    <div>
      업무 관련 직책/채용 
    </div></td> 
  </tr> 
  <tr> 
   <td><strong>HR</strong></td> 
   <td> 
    <div>
      HR 또는 급여 소프트웨어, HR 관련 직책/채용
    </div></td> 
  </tr> 
  <tr> 
   <td><strong>엔지니어링</strong></td> 
   <td> 
    <div>
      기술, 프레임워크, 엔지니어링 관련 위치/채용 
    </div></td> 
  </tr> 
  <tr> 
   <td><strong>영업</strong></td> 
   <td> 
    <div>
      영업, 영업 관련 직책/고용 솔루션 및 소프트웨어 
    </div></td> 
  </tr> 
  <tr> 
   <td><strong>의도</strong></td> 
   <td> 
    <div>
      의도 표시기. 
    </div></td> 
  </tr> 
  <tr> 
   <td><strong>IT</strong></td> 
   <td> 
    <div>
      하드웨어 및 소프트웨어 솔루션, 기술, IT 관련 직책/채용
    </div></td> 
  </tr> 
  <tr> 
   <td><strong>재무</strong></td> 
   <td> 
    <div>
      금융 소프트웨어, 금융 관련 직책/고용 
    </div></td> 
  </tr> 
  <tr> 
   <td><strong>마케팅</strong></td> 
   <td> 
    <div>
      마케팅 기술 및 소프트웨어, 마케팅 관련 직책/채용 
    </div></td> 
  </tr> 
  <tr> 
   <td><strong>비즈니스</strong></td> 
   <td> 
    <div>
      Forbes 또는 Inc 목록 또는 비즈니스 파트너십입니다. 
    </div></td> 
  </tr> 
  <tr> 
   <td><strong>고객 경험 및 관계</strong></td> 
   <td> 
    <div>
      고객 성공 및 고객 관계 직책/채용
    </div></td> 
  </tr> 
 </tbody> 
</table>

도구 설명 위로 마우스를 가져가면 각 열에 대한 설명이 표시됩니다.

![](assets/tool-tip.png)

모델에 추가 표시기를 삽입하려면 ICP 표시기 추가 드롭다운을 클릭합니다.

![](assets/add-icp.png)

내보내기 상자를 선택하면 지정된 계정 세부 정보 페이지에서 ICP 표시기를 볼 수 있을 뿐만 아니라 선택한 ICP 표시기를 의 제약으로 사용할 수 있습니다 [명명된 계정 필터](/help/marketo/product-docs/target-account-management/engage/account-filters.md).

![](assets/export.png)

>[!NOTE]
>
>ICP 지표는 의 제한으로 포함됩니다 **명명 계정 멤버** 필터 및 트리거.

지표 가중치는 각 표시기가 모델에서 받는 중요도 수준을 제어하는 것입니다.

![](assets/weightage.png)

이러한 변경 사항을 적용하려면 모델 새로 고침 을 클릭합니다.

![](assets/refresh-button.png)

모델 튜닝이 완료되면(새로 고친 후) 모델 결과 탭으로 돌아가서 를 클릭합니다 **등급 저장 및 적용**.

![](assets/ranks.png)
