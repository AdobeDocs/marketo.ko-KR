---
unique-page-id: 12615800
description: 명명된 계정 가져오기 - Marketo 문서 - 제품 설명서
title: 명명된 계정 가져오기
exl-id: 3f40e567-9256-4efd-beea-4e818770759f
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '479'
ht-degree: 0%

---

# 명명된 계정 가져오기 {#import-named-accounts}

이미 잠재적인 타겟 계정이 가득한 CSV를 가지고 있습니까? TAM으로 직접 가져옵니다!

1. 을(를) 클릭합니다. **새로 만들기** 드롭다운 및 선택 **명명된 계정 가져오기**.

   ![](assets/inaone.png)

1. 새 창이 열립니다. 클릭 **찾아보기**&#x200B;을 클릭한 다음 가져올 명명된 계정 파일을 선택합니다.

   ![](assets/inatwo.png)

   >[!TIP]
   >
   >파일에서 [많은 정보](/help/marketo/product-docs/target-account-management/target/named-accounts/named-account-overview.md#named-account-attributes) 가능한 한 첫 번째 정보만 추가할 수 있습니다. Marketo은 계산되지 않습니다(즉, 파이프라인). CRM 계정을 기반으로 명명된 계정을 만들려면 CRM의 계정 이름 및 CRM ID를 CSV 파일로 내보내고 계정 이름 옵션을 사용하여 가져오기 프로세스 중에 CRM ID를 매핑하면 됩니다. CRM 계정을 명명된 계정에 올바르게 연결하려면 CRM 계정의 정확한 이름을 제공해야 합니다.

1. 두 가지 데이터 중복 제거 모드 중에서 선택합니다. 계정 이름 또는 도메인 이름. 이 예제에서는 계정을 선택합니다. 을(를) 클릭합니다. **모드** 드롭다운 및 선택 **계정 이름별**.

   ![](assets/inathree.png)

   >[!NOTE]
   >
   >만약 **도메인 모드별**&#x200B;에는 명명된 계정 필드와 도메인 필드가 모두 포함되어야 합니다.

1. 이름이 지정된 계정이 추가되는 계정 목록을 선택하려면 **계정 목록** 드롭다운을 선택하고 을(를) 선택합니다.

   ![](assets/inafour.png)

   >[!NOTE]
   >
   >드롭다운 상자에 해당 이름을 입력하면 완전히 새로운 계정 목록을 만들 수도 있습니다.

1. 가져오기에 대한 알림을 보내려면 **경고 보내기 대상** 드롭다운을 클릭하고 Marketo 사용자를 선택합니다. 사용자 _사용할 수 없음_ 수동으로 이메일 주소를 입력합니다.

   ![](assets/inafive-2.png)

1. 클릭 **다음**.

   ![](assets/inasix-2.png)

1. 를 두 번 클릭하여 각 필드를 매핑합니다 **Marketo 필드** 드롭다운을 클릭하고 적절한 필드를 선택합니다. 클릭 **다음** 완료 시.

   ![](assets/inaseven.png)

   성공!

   ![](assets/inanine.png)

   >[!NOTE]
   >
   >&quot;가져오기 상태 확인&quot;은 최근 3일 동안의 활동만 표시합니다.

계정 이름별로 데이터 중복 제거 시 시나리오:

<table> 
 <tbody> 
  <tr> 
   <td><strong>기존 명명 계정 이름으로 레코드를 가져오는 중</strong></td> 
   <td><p>기존 레코드를 업데이트할 예정입니다</p></td> 
  </tr> 
  <tr> 
   <td><strong>새 명명된 계정 이름으로 레코드를 가져오는 중</strong></td> 
   <td>새 레코드를 만듭니다</td> 
  </tr> 
 </tbody> 
</table>

도메인 이름별로 데이터 중복 제거 시 시나리오:

<table> 
 <tbody> 
  <tr> 
   <td><strong>새 계정 이름과 새 도메인 이름으로 레코드를 가져오는 중</strong></td> 
   <td>제공된 정보가 있는 새 명명된 계정을 만듭니다</td> 
  </tr> 
  <tr> 
   <td><strong>기존 계정 이름과 기존 도메인 이름으로 레코드를 가져오는 중</strong></td> 
   <td>기존 명명 계정을 업데이트합니다</td> 
  </tr> 
   <tr> 
   <td><strong>새 계정 이름과 기존 도메인 이름으로 레코드를 가져오는 중</strong></td> 
   <td>도메인 이름과 일치하는 기존 명명 계정에 새 계정 이름을 추가하고 다른 정보(즉, 업계, 주 등)를 업데이트합니다</td> 
  </tr> 
  <tr> 
   <td><strong>기존 명명된 계정 이름과 새 도메인 이름으로 레코드를 가져오는 중</strong></td> 
   <td>새 도메인 이름을 기존 명명 계정에 추가하고 계정 이름과 일치하고 다른 정보(즉, 업계, 주 등)를 업데이트합니다</td> 
  </tr> 
 </tbody> 
</table>

>[!NOTE]
>
>Marketo이 명명된 계정을 추가하면, 지정된 계정의 일부가 되어야 하는 사람을 식별할 수 있는 규칙(뒷면)을 업데이트하고 있습니다. 예: &quot;IBM&quot;을 &quot;미국 IBM&quot;으로 업데이트하면 두 회사 이름을 가진 사람이 명명 계정에 연결됩니다.

Marketo이 중복으로 표시되는 레코드를 찾으면 첫 번째 레코드만 처리합니다.
