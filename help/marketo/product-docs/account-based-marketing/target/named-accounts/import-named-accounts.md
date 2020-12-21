---
unique-page-id: 12615800
description: 지정된 계정 가져오기 - 마케팅 문서 - 제품 설명서
title: 명명된 계정 가져오기
translation-type: tm+mt
source-git-commit: e125f8469239a026aefb703fdb6ba99c32e33565
workflow-type: tm+mt
source-wordcount: '479'
ht-degree: 0%

---


# 명명된 계정 가져오기 {#import-named-accounts}

잠재적인 타겟 계정이 포함된 CSV가 이미 있습니까? ABM으로 바로 가져올 수 있습니다.

1. **새로 만들기** 드롭다운을 클릭하고 **명명된 계정 가져오기**&#x200B;를 선택합니다.

   ![](assets/inaone.png)

1. 새 창이 열립니다. **찾아보기**&#x200B;를 클릭한 다음 가져올 이름의 계정의 파일을 선택합니다.

   ![](assets/inatwo.png)

   >[!TIP]
   >
   >파일에서 [가능한 많은 정보](/help/marketo/product-docs/account-based-marketing/target/named-accounts/named-account-overview.md#named-account-attributes)를 제공합니다. 첫 번째 정보만 추가할 수 있습니다.Marketing To가 계산하지 않습니다(예: 파이프라인). CRM 계정을 기반으로 지정된 계정을 만들려면 CRM에서 계정 이름 및 CRM ID를 CSV 파일로 내보내고 계정 이름 옵션을 사용하여 가져오기 프로세스 동안 CRM ID를 매핑하면 됩니다. CRM 계정을 명명된 계정에 제대로 연결하려면 CRM 계정의 정확한 이름을 제공해야 합니다.

1. 두 가지 데이터 중복 제거 모드 중 선택:계정 이름 또는 도메인 이름. 이 예에서는 계정을 선택합니다. **모드** 드롭다운을 클릭하고 **계정 이름별**&#x200B;을 선택합니다.

   ![](assets/inathree.png)

   >[!NOTE]
   >
   >**도메인 모드별**&#x200B;을 선택하는 경우 지정된 계정과 도메인 필드를 모두 포함해야 합니다.

1. 이름이 지정된 계정을 추가할 계정 목록을 선택하려면 **계정 목록** 드롭다운을 클릭하고 선택합니다.

   ![](assets/inafour.png)

   >[!NOTE]
   >
   >드롭다운 상자에 계정 이름을 간단히 입력하여 새 계정 목록을 만들 수도 있습니다.

1. 가져오기에 대한 알림을 보내려면 **경고 보내기** 드롭다운을 클릭하고 Marketing 사용자를 선택합니다. _은(는) 이메일 주소를 수동으로 입력할 수 없습니다._

   ![](assets/inafive-2.png)

1. **다음**&#x200B;을 클릭합니다.

   ![](assets/inasix-2.png)

1. **마케팅 필드** 드롭다운을 두 번 클릭하고 적절한 필드를 선택하여 각 필드를 매핑합니다. 완료되면 **다음**&#x200B;을 클릭합니다.

   ![](assets/inaseven.png)

   성공!

   ![](assets/inanine.png)

   >[!NOTE]
   >
   >&quot;가져오기 상태 확인&quot;은 최근 3일 활동만 표시합니다.

계정 이름별로 중복 제거되는 시나리오:

<table> 
 <tbody> 
  <tr> 
   <td><strong>기존 명명 계정 이름으로 레코드 가져오기</strong></td> 
   <td><p>기존 레코드를 업데이트합니다.</p></td> 
  </tr> 
  <tr> 
   <td><strong>새 명명 계정 이름으로 레코드 가져오기</strong></td> 
   <td>새 기록을 만들 예정입니다</td> 
  </tr> 
 </tbody> 
</table>

도메인 이름으로 중복 제거되는 시나리오:

<table> 
 <tbody> 
  <tr> 
   <td><strong>새 계정 이름 및 새 도메인 이름으로 레코드 가져오기</strong></td> 
   <td>제공된 정보와 함께 새 네임드 계정을 만듭니다.</td> 
  </tr> 
  <tr> 
   <td><strong>기존 계정 이름 및 기존 도메인 이름으로 레코드 가져오기</strong></td> 
   <td>기존 명명 계정을 업데이트합니다.</td> 
  </tr> 
   <tr> 
   <td><strong>새 계정 이름과 기존 도메인 이름을 사용하여 레코드 가져오기</strong></td> 
   <td>도메인 이름과 일치하고 다른 정보(예: 업계, 주 등)를 업데이트하는 기존 네임드 계정에 새 계정 이름을 추가합니다.</td> 
  </tr> 
  <tr> 
   <td><strong>기존 명명 계정 이름 및 새 도메인 이름으로 레코드 가져오기</strong></td> 
   <td>계정 이름과 일치하고 다른 정보(예: 업계, 주 등)를 업데이트하는 기존 네임드 계정에 새 도메인 이름을 추가합니다.</td> 
  </tr> 
 </tbody> 
</table>

>[!NOTE]
>
>Marketing에서 명명된 계정을 추가할 때, Adobe는 명명 계정의 일부가 되어야 하는 사람을 식별할 수 있는 규칙(백그라운드에서) 업데이트 중입니다. 예:&quot;IBM&quot;을 &quot;IBM, USA&quot;로 업데이트하면 두 회사 이름을 가진 사용자가 지정된 계정에 연결됩니다.

Marketing Cloud에서 중복으로 표시되는 레코드를 찾으면 첫 번째 레코드만 처리됩니다.
