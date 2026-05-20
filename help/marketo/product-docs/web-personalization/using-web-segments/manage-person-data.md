---
unique-page-id: 7504051
description: 개인 데이터 관리 - 개인 데이터 관리를 포함하여 Marketo Engage에서 개인 데이터 관리에 대해 알아봅니다. 이 안내서를 사용하여 다음 단계를 완료하십시오.
title: 사용자 데이터 관리
exl-id: 40f4aac8-c6e5-4cf3-9573-cac2fdf9bcad
feature: Web Personalization
TQID: https://experienceleague.adobe.com/rIiC-JXLkaMByk7GizVOcCEcUHN8AL-8Hy66-U2GZhs
product_v2: id: b27e5950-9033-45ac-9f86-eb22e567f615
feature_v2: id: c5f60233-d5ea-4453-a799-0ad258b4d399id: ed6be6bb-75bb-4ea9-9a42-3bcaa65e1bcc
subfeature_v2: id: a1d50dda-6d94-4e16-8c30-5eb7181c4650
topic_v2: id: e0eb8757-182f-49f3-94a4-1587d16f5094
source-git-commit: a526f0bf4cbdf888b1c4462ba35dd2bc92316527
workflow-type: tm+mt
source-wordcount: 209
ht-degree: 12%

---

# 사용자 데이터 관리 {#manage-person-data}

세분화에 사용할 개인 필드를 선택하여 [!DNL Web Personalization]의 개인 데이터를 활용하십시오.

1. **[!UICONTROL Account Settings]** 으로 이동합니다.

   ![](assets/image2015-5-7-15-3a17-3a23.png)

1. **[!UICONTROL Database]** 으로 이동합니다.

   ![](assets/account-settings-dropdown-database.jpg)

## 새 사용자 필드 추가 {#adding-a-new-person-field}

1. 목록에 개인 데이터 필드를 추가하려면 드롭다운에서 **추가할 필드**&#x200B;를 선택하십시오.

   ![](assets/add-a-person-field-hand.jpg)

   >[!NOTE]
   >
   >새 필드는 보류 중 상태로 추가되며 활성화하는 데 최대 24시간이 걸릴 수 있습니다.

## 개인 필드 삭제 {#deleting-a-person-field}

1. 목록에서 필드를 제거하려면 삭제 아이콘(![—](assets/image2015-3-24-13-3a45-3a56.png))을 클릭하십시오. 필드를 삭제하려면 **[!UICONTROL Yes]**&#x200B;을(를) 클릭하십시오.

   ![](assets/web-engagement-settings-delete.jpg)

   >[!NOTE]
   >
   >**개인 데이터 필드 관리**
   >
   >* 개인 데이터 필드만 포함할 수 있습니다.
   >* 최대 30개의 개인 데이터 필드를 추가할 수 있습니다.
   >* 새 필드를 추가하는 데 최대 24시간이 걸릴 수 있습니다.
   >* 문자열 유형의 최대 길이는 255자입니다.
   >* 숨겨진 필드는 자동으로 제거됩니다.

<table>
 <tbody>
  <tr>
   <th><p>REST API 이름</p></th>
   <th><p>SOAP API 이름</p></th>
   <th><p>알기 쉬운 이름</p></th>
  </tr>
  <tr>
   <td><p>부서</p></td>
   <td><p>부서</p></td>
   <td><p>부서</p></td>
  </tr>
  <tr>
   <td><p>제목</p></td>
   <td><p>직함</p></td>
   <td><p>직위</p></td>
  </tr>
  <tr>
   <td><p>등급</p></td>
   <td><p>등급</p></td>
   <td><p>등급</p></td>
  </tr>
  <tr>
   <td><p>잠재 고객 스코어</p></td>
   <td><p>잠재 고객 스코어</p></td>
   <td><p>스코어</p></td>
  </tr>
  <tr>
   <td><p>잠재 고객 상태</p></td>
   <td><p>잠재 고객 상태</p></td>
   <td><p>상태</p></td>
  </tr>
  <tr>
   <td><p>우선 순위</p></td>
   <td><p>우선 순위</p></td>
   <td><p>우선 순위</p></td>
  </tr>
  <tr>
   <td><p>리드 역할</p></td>
   <td><p>잠재 고객 역할</p></td>
   <td><p>역할</p></td>
  </tr>
  <tr>
   <td><p>구독 취소됨</p></td>
   <td><p>구독 취소</p></td>
   <td><p>구독 취소</p></td>
  </tr>
 </tbody>
</table>

새 [!DNL Web Personalization] 계정에 대해 다음 리드 필드가 즉시 제공됩니다.

>[!MORELIKETHIS]
>
>[알려진 사용자 데이터를 사용하여 세그먼트 만들기](/help/marketo/product-docs/web-personalization/using-web-segments/create-a-segment-using-known-person-data.md)
