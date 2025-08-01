---
unique-page-id: 15695924
description: 계정 프로파일링 순위 및 조정 - Marketo 문서 - 제품 설명서
title: 계정 프로파일링 순위 및 조정
exl-id: 9c5d0a03-0ebe-43cc-95ef-faab19a7f673
feature: Target Account Management
source-git-commit: 26573c20c411208e5a01aa7ec73a97e7208b35d5
workflow-type: tm+mt
source-wordcount: '380'
ht-degree: 1%

---

# 계정 프로파일링 순위 및 조정 {#account-profiling-ranking-and-tuning}

계정 프로파일링을 통해 ICP(Ideal Customer Profile)를 식별하고, ICP를 기준으로 데이터베이스의 회사 등급을 매기고, ICP 지표 데이터를 [!UICONTROL Named Accounts]&#x200B;(으)로 승격된 계정에 추가합니다.

>[!IMPORTANT]
>
>2025년 현재는 새 사용자에 대해 계정 프로파일링을 더 이상 사용할 수 없습니다. 기존 사용자에 대해 계속 작동합니다.

## 모델 결과 {#model-results}

결과는 등급별로 분류된 모든 알려진 계정을 보여줍니다. A는 최고 등급이고, D는 최저 등급이다.

![](assets/results.png)

선택 사항이지만 자동 승격 확인란을 선택하는 것이 좋습니다. 이렇게 하면 시간이 많이 절약되기 때문입니다. 그러나 각 계정을 살펴보고 [수동으로 추가](/help/marketo/product-docs/target-account-management/target/named-accounts/discover-accounts.md#discover-crm-accounts)하려면 상자를 선택하지 않은 상태로 두면 됩니다.

<table>
 <tbody>
  <tr>
   <td><strong><span class="uicontrol">순위</span></strong></td>
   <td>
    <div>
      이상적인 고객 프로필을 기반으로 한 계정 순위. A가 가장 적합하고 D가 가장 적다.
    </div></td>
  </tr>
  <tr>
   <td><strong><span class="uicontrol">성향</span></strong></td>
   <td>
    <div>
      비ICP 기반 계정 선택과 비교하여 예상되는 전환율 증가.
    </div></td>
  </tr>
  <tr>
   <td><strong><span class="uicontrol">계정 (%)</span></strong></td>
   <td>
    <div>
      모델 입력의 해당 등급이 있는 계정의 백분율입니다.
    </div></td>
  </tr>
  <tr>
   <td><strong><span class="uicontrol">모델 기준 %</span></strong></td>
   <td>
    <div>
      모델 기준 계정 중 이 등급을 가진 계정의 백분율입니다.
    </div></td>
  </tr>
 </tbody>
</table>

## 모델 조정 {#model-tuning}

모델 탭에서 **[!UICONTROL Tune Model]** 단추를 클릭합니다.

![](assets/two.png)

선택할 수 있는 여러 탭이 있어 심층적인 맞춤화를 가능하게 합니다.

![](assets/tuning-page.png)

**지표 범주**

<table>
 <tbody>
  <tr>
   <td><strong><span class="uicontrol">규정 준수</span></strong></td>
   <td>
    <div>
      인증, 규정 준수 관련 직책/채용.
    </div></td>
  </tr>
  <tr>
   <td><strong><span class="uicontrol">작업</span></strong></td>
   <td>
    <div>
      운영 관련 직책/채용.
    </div></td>
  </tr>
  <tr>
   <td><strong><span class="uicontrol">시간</span></strong></td>
   <td>
    <div>
      HR 또는 Payroll 소프트웨어, HR 관련 직책/채용.
    </div></td>
  </tr>
  <tr>
   <td><strong><span class="uicontrol">엔지니어링</span></strong></td>
   <td>
    <div>
      기술, 프레임워크, 엔지니어링 관련 직책/채용.
    </div></td>
  </tr>
  <tr>
   <td><strong><span class="uicontrol">판매</span></strong></td>
   <td>
    <div>
      영업, 영업 관련 직책/채용을 위한 솔루션 및 소프트웨어.
    </div></td>
  </tr>
  <tr>
   <td><strong><span class="uicontrol">의도</span></strong></td>
   <td>
    <div>
      의도 표시기.
    </div></td>
  </tr>
  <tr>
   <td><strong><span class="uicontrol">IT</span></strong></td>
   <td>
    <div>
      하드웨어 및 소프트웨어 솔루션, 기술, IT 관련 직책/채용.
    </div></td>
  </tr>
  <tr>
   <td><strong><span class="uicontrol">재무</span></strong></td>
   <td>
    <div>
      금융 소프트웨어, 금융 관련 직책/채용.
    </div></td>
  </tr>
  <tr>
   <td><strong><span class="uicontrol">마케팅</span></strong></td>
   <td>
    <div>
      마케팅 기술 및 소프트웨어, 마케팅 관련 직책/채용.
    </div></td>
  </tr>
  <tr>
   <td><strong><span class="uicontrol">비즈니스</span></strong></td>
   <td>
    <div>
      Forbes 또는 Inc 목록 또는 비즈니스 파트너십
    </div></td>
  </tr>
  <tr>
   <td><strong><span class="uicontrol">고객 경험 및 관계</span></strong></td>
   <td>
    <div>
      고객 성공 및 고객 관계 직책/채용.
    </div></td>
  </tr>
 </tbody>
</table>

도구 설명에 마우스를 가져다 대면 각 열에 대한 설명이 표시됩니다.

![](assets/tool-tip.png)

모델에 추가 지표를 삽입하려면 [!UICONTROL Add ICP Indicator] 드롭다운을 클릭하세요.

![](assets/add-icp.png)

[!UICONTROL Export] 상자를 선택하면 [!UICONTROL Named Account] 세부 정보 페이지에서 ICP 표시기를 볼 수 있으며 [명명된 계정 필터](/help/marketo/product-docs/target-account-management/engage/account-filters.md)에서 선택한 ICP 표시기를 제약 조건으로 사용할 수 있습니다.

![](assets/export.png)

>[!NOTE]
>
>ICP 지표가 **[!UICONTROL Member of Named Account]** 필터 및 트리거에 제약 조건으로 포함되어 있습니다.

[!UICONTROL Indicator Weightage]은(는) 각 표시기가 모델에서 받는 중요도를 제어합니다.

![](assets/weightage.png)

변경 내용을 적용하려면 **[!UICONTROL Refresh Model]**&#x200B;을(를) 클릭하십시오.

![](assets/refresh-button.png)

모델을 새로 고친 후 조정을 완료하면 [모델 결과] 탭으로 돌아가서 **[!UICONTROL Save & Apply Ranks]**&#x200B;을(를) 클릭합니다.

![](assets/ranks.png)
