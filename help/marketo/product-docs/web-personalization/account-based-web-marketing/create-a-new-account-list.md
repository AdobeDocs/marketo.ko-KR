---
unique-page-id: 4720232
description: 새 계정 목록 만들기 - Marketo 문서 - 제품 설명서
title: 새 계정 목록 만들기
exl-id: 644c5b3b-852a-4dd9-8e55-b434505504ea
feature: Web Personalization
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '392'
ht-degree: 0%

---

# 새 계정 목록 만들기 {#create-a-new-account-list}

조직 및 도메인 이름 목록을 만들고 업로드하여 이러한 주요 계정을 개인화된 캠페인으로 타깃팅할 수 있습니다.

>[!NOTE]
>
>이 문서는 기존 Web ABM 고객에게만 적용됩니다. 2016년 9월 이후에 Web ABM을 획득한 경우 대신 [이 문서](https://docs.marketo.com/display/DOCS/Account+Lists#AccountLists-CreateaNewAccountList)의 단계를 따르세요.

## 새 계정 목록 만들기 {#create-a-new-account-list-1}

1. **[!UICONTROL Account Lists]**(으)로 이동합니다.

   ![](assets/dropdown-account-lists-hand.jpg)

1. **[!UICONTROL Create New]**&#x200B;를 선택합니다.

   ![](assets/create-new-account-list-hand.jpg)

1. **[!UICONTROL Browse]**&#x200B;을(를) 선택하고 CSV 파일을 업로드합니다(csv 파일이 조건을 충족하는지 확인). **[!UICONTROL List Name]** 및 **[!UICONTROL Description]**&#x200B;을(를) 추가합니다. **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

   ![](assets/create-account-list-hands.jpg)

   >[!NOTE]
   >
   >**CSV 파일의 형식은 무엇입니까?**
   >
   >명명된 계정 CSV 파일이 다음 요구 사항을 충족하는지 확인하십시오.
   >
   >* CSV 형식으로 저장됨
   >* 10MB 이하
   >* 열 A: 이름, 열 B: 도메인, 열 C: 국가, 열 D: 미국 주 헤더가 있는 4개의 열만 있습니다.
   >* 업로드된 파일은 승인까지 영업일 기준으로 최대 2일이 소요될 수 있습니다.
   >* 명명된 계정 페이지에서 승인 이메일 알림을 받거나 파일 상태를 확인할 수 있습니다.
   >* 업로드된 모든 목록에 대해 누적된 레코드/행의 총 수는 10K에서 시작하며 최대 패키지는 총 10K입니다.

   >[!NOTE]
   >
   >**CSV 파일의 예**
   >
   >* 행 1 열 A 값 = 조직
   >* 행 1 열 B 값 = 도메인
   >* 행 1 열 C 값 = 국가
   >* 행 1 열 D 값 = 미국 주
   >* 열 값 중 하나는 필수입니다. 그러나 조직과 도메인 이름을 모두 제공하면 계정 목록의 일치율이 향상됩니다.
   >* 국가 및 주는 선택적 값입니다.
   >
   >   * 국가 이름은 전체 국가 이름이나 약어 코드를 사용하십시오. 예: 미국 또는 미국.
   >   * 미국 주의 경우 두 문자로 된 약어 코드(예: CA)를 사용합니다. 미국 주만 인정됩니다.
   >
   >![](assets/image2015-2-25-12-3a19-3a10.png)

## 계정 목록 편집 {#edit-an-account-list}

**계정 목록** 페이지에서 목록의 **편집** 아이콘을 클릭합니다.

![](assets/create-new-account-list-edit.jpg)

**[!UICONTROL Browse...]**&#x200B;을(를) 선택하고 새 CSV 파일을 업로드하십시오. 이 파일은 원본 파일을 대체합니다. **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다. 새로 업로드한 파일은 Marketo 지원에서 승인할 때까지 보류 중인 상태가 되며, 보류 중인 상태에서는 원래 파일이 활성 상태로 유지됩니다.

![](assets/set-account-list-edit-hands.jpg)

CSV 파일이 기존 파일을 대체합니다. 새 파일의 처리가 완료될 때까지 기존 목록이 활성 상태로 유지됩니다.

## 명명된 계정 목록 삭제 {#delete-a-named-account-list}

1. **[!UICONTROL Account Lists]** 페이지에서 삭제하려는 목록의 삭제 아이콘을 클릭합니다.

   ![](assets/create-new-account-list-delete.jpg)

1. 목록을 삭제할 것인지 확인하는 메시지가 나타납니다. **[!UICONTROL OK]**&#x200B;을(를) 클릭합니다.

   ![](assets/delete-notification-hand.jpg)

>[!MORELIKETHIS]
>
>[계정 목록을 사용하여 세그먼트 만들기](/help/marketo/product-docs/web-personalization/account-based-web-marketing/create-a-segment-using-an-account-list.md)
