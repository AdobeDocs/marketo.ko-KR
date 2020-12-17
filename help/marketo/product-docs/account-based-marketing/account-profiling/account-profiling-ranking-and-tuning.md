---
unique-page-id: 15695924
description: 계정 프로파일링 등급 및 조정 - 마케팅 문서 - 제품 설명서
title: 계정 프로파일링 등급 및 조정
translation-type: tm+mt
source-git-commit: 5c9683c6b00ccbf9e9d606fd4513432c9872ad00
workflow-type: tm+mt
source-wordcount: '394'
ht-degree: 0%

---


# 계정 프로파일링 등급 및 조정 {#account-profiling-ranking-and-tuning}

계정 프로파일링은 이상적인 고객 프로필(ICP)을 식별하고 ICP를 기반으로 데이터베이스의 회사에 등급을 매기고 ICP 지표 데이터를 지정된 계정으로 추가합니다.

## 모델 결과 {#model-results}

결과가 알려진 모든 계정을 등급별로 분류한 것을 보여줍니다. A는 최고 등급이고 D는 가장 낮은 등급이다.

![](assets/results.png)

선택 사항이지만 자동 승격 확인란을 선택하면 작업 시간을 크게 절약할 수 있습니다. 그러나 각 계정을 통과하고 [수동으로 ](http://docs.marketo.com/display/DOCS/Discover+Accounts#DiscoverAccounts-DiscoverCRMAccounts)추가하려는 경우, 상자를 선택 취소하기만 하면 됩니다.

<table> 
 <tbody> 
  <tr> 
   <td><strong>등급</strong></td> 
   <td> 
    <div>
      이상적인 고객 프로필을 기반으로 한 계정 등급. A가 가장 잘 맞는데 D가 가장 잘 맞지 않는다. 
    </div></td> 
  </tr> 
  <tr> 
   <td><strong>성향</strong></td> 
   <td> 
    <div>
      ICP가 아닌 계정 선택에 비해 전환율 증가가 예상됨. 
    </div></td> 
  </tr> 
  <tr> 
   <td><strong>계정(%)</strong></td> 
   <td> 
    <div>
      이 등급을 가진 모델 입력의 계정 비율입니다. 
    </div></td> 
  </tr> 
  <tr> 
   <td><strong>모델 기준 %</strong></td> 
   <td> 
    <div>
      이 등급을 가진 모델 기반 계정의 비율입니다. 
    </div></td> 
  </tr> 
 </tbody> 
</table>

## 모델 조정 {#model-tuning}

모델(Model) 탭에서 모델 조정(Tune Model) 버튼을 클릭합니다.

![](assets/two.png)

선택할 수 있는 여러 개의 탭이 있어 심층적인 사용자 지정을 할 수 있습니다.

![](assets/tuning-page.png)

표시기 범주

| **규정 준수** | 인증, 규정 준수 관련 직위/고용 |
|---|---|
| **작업** | 업무 관련 직책/고용. |
| **HR** | 인사 또는 급여 소프트웨어, 인사 관련 직위/고용 |
| **엔지니어링** | 기술, 프레임워크, 엔지니어링 관련 직위/채용 |
| **세일즈** | 영업, 영업 관련 직위/채용을 위한 솔루션 및 소프트웨어 |
| **의도** | 의도 표시기. |
| **IT** | 하드웨어 및 소프트웨어 솔루션, 기술, IT 관련 직위/채용 |
| **재무** | 재무 소프트웨어, 금융 관련 직위/고용. |
| **마케팅** | 마케팅 기술 및 소프트웨어, 마케팅 관련 직위/채용 |
| **비즈니스** | Forbes 또는 Inc 목록 또는 비즈니스 파트너 |
| **고객 경험 및 관계** | 고객 성공 및 고객 관계 직위/채용 |

각 열에 대한 설명을 보려면 도구 설명 위로 마우스를 가져갑니다.

![](assets/tool-tip.png)

ICP 표시기 추가 드롭다운을 클릭하여 모델에 추가 표시기를 삽입합니다.

![](assets/add-icp.png)

내보내기 상자를 선택하면 지정된 계정 세부 사항 페이지에서 ICP 표시기를 볼 수 있을 뿐만 아니라 선택한 ICP 표시기를 [명명된 계정 필터](http://docs.marketo.com/display/DOCS/Account+Filters)에 있는 제한 사항으로 사용할 수 있습니다.

![](assets/export.png)

>[!NOTE]
>
>ICP 표시기는 **명명된 계정의 구성원** 필터 및 트리거에 제약 조건으로 포함됩니다.

표시기 가중치는 각 표시기가 모델에서 받는 중요도 레벨을 제어하는 것입니다.

![](assets/weightage.png)

이러한 변경 사항을 적용하려면 모델 새로 고침을 클릭합니다.

![](assets/refresh-button.png)

모델 조정이 완료되면(새로 고친 후) 모델 결과 탭으로 돌아가서 **등급 저장 및 적용**&#x200B;을 클릭합니다.

![](assets/ranks.png)

