---
unique-page-id: 7511512
description: Salesforce에서 Marketo Sales Insight 설치 및 구성1 - Marketo 문서 - 제품 설명서
title: Salesforce1에서 Marketo Sales Insight 설치 및 구성
exl-id: 9f26e90b-3199-4ef8-92bc-95e8bd81f1c5
feature: Marketo Sales Insights
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '367'
ht-degree: 0%

---

# Salesforce1에서 Marketo Sales Insight 설치 및 구성 {#install-and-configure-marketo-sales-insight-in-salesforce}

>[!NOTE]
>
>기존 고객 [MSI 패키지 업그레이드](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/upgrading/upgrading-your-msi-package.md) 계속하기 전에!

>[!PREREQUISITES]
>
>Salesforce Enterprise/Unlimited가 있는 경우:
>
>* [1단계/3단계: Salesforce에 Marketo 필드 추가(Enterprise/Unlimited)](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-1-of-3-add-marketo-fields-to-salesforce-enterprise-unlimited.md)
>* [2단계/3단계: Marketo용 Salesforce 사용자 만들기(Enterprise/Unlimited)](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-2-of-3-create-a-salesforce-user-for-marketo-enterprise-unlimited.md)
>* [3단계/3: Marketo 및 Salesforce 연결(Enterprise/Unlimited)](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-3-of-3-connect-marketo-and-salesforce-enterprise-unlimited.md)
>* [Salesforce Enterprise/Unlimited에서 Marketo Sales Insight 구성](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/configure-marketo-sales-insight-in-salesforce-enterprise-unlimited.md)
>
>Salesforce Professional이 있는 경우:
>
>* [Salesforce Professional Edition에서 Marketo Sales Insight 구성](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/configure-marketo-sales-insight-in-salesforce-professional-edition.md)
>

>[!NOTE]
>
>Salesforce1의 Marketo Sales Insight에는 최상의 선택, 리드 피드, 흥미로운 순간 및 Marketo 캠페인에 추가 기능이 포함됩니다.

## Salesforce1 모바일 앱 활성화 {#enable-the-salesforce1-mobile-app}

1. 클릭 **설정** 그런 다음 **모바일 관리**.

   ![](assets/image2015-4-21-15-3a29-3a22.png)

1. 클릭 **Salesforce1**.

   ![](assets/image2015-4-21-15-3a30-3a51.png)

1. 클릭 **Salesforce1 설정**.

   ![](assets/image2015-4-21-15-3a32-3a21.png)

1. 클릭 **Salesforce1 모바일 브라우저 앱 활성화**.

   ![](assets/image2015-4-21-15-3a34-3a27.png)

1. 클릭 **저장**.

   ![](assets/image2015-4-21-15-3a42-3a48.png)

1. 선택 **모바일 관리**.

   ![](assets/image2015-4-22-11-3a10-3a14.png)

1. 클릭 **모바일 탐색 메뉴 관리**.

   ![](assets/image2015-4-22-11-3a13-3a10.png)

1. 선택 **Marketo** 및 **추가** 다음으로 이동 **선택됨** 메뉴 항목.

   ![](assets/image2015-4-22-14-3a55-3a37.png)

1. 선택 **Marketo**, 이동 **위로** 원하는 영역으로 이동한 다음 **저장**.

   ![](assets/image2015-4-22-17-3a20-3a56.png)

## 오래된 Marketo 사용자 지정 개체 숨기기 {#hide-outdated-marketo-custom-object}

1. 클릭 **설정**.

   ![](assets/image2015-4-22-15-3a13-3a48.png)

1. 선택 **사용자 관리**.

   ![](assets/image2015-5-5-11-3a13-3a45.png)

1. 선택 **프로필**.

   ![](assets/image2015-5-5-11-3a15-3a21.png)

1. 클릭하여 **편집** 원하는 프로필.

   ![](assets/image2015-5-5-13-3a51-3a36.png)

1. 아래 **탭 설정**&#x200B;를 선택하고 _첫 번째_ **Marketo**.

   ![](assets/image2015-5-5-13-3a55-3a36.png)

1. 선택 **숨겨진 탭**.

   ![](assets/image2015-5-5-14-3a2-3a29.png)

   >[!NOTE]
   >
   >원하는 모든 프로필에 대해 Marketo 탭을 숨기십시오!

## 탭 맞춤화 {#customize-tabs}

1. 클릭 **+**.

   ![](assets/image2015-4-22-17-3a14-3a49.png)

1. 클릭 **내 탭 맞춤화**.

   ![](assets/image2015-4-22-17-3a16-3a22.png)

1. 선택 **Marketo** 및 **추가** 선택한 탭으로 이동합니다.

   ![](assets/image2015-4-22-17-3a17-3a15.png)

1. 선택 **Marketo**, 이동 **위로** 원하는 영역으로 이동한 다음 **저장**.

   ![](assets/image2015-4-22-18-3a29-3a47.png)

## 페이지 레이아웃 사용자 지정 {#customize-page-layouts}

1. 클릭 **설정**.

   ![](assets/image2015-4-22-17-3a26-3a56.png)

1. 클릭 **설정**, 유형 **페이지 레이아웃**, 및 클릭 **페이지 레이아웃** 잠재 고객 아래에

   >[!NOTE]
   >
   >조직에서 사용하는 모든 페이지 레이아웃(마케팅, 판매 등)에 대해 이 단계를 반복합니다 연락처, 계정 및 영업 기회 객체.

   ![](assets/image2015-4-22-17-3a34-3a33.png)

1. 클릭 **편집** 잠재 고객 레이아웃을 변경합니다.

   ![](assets/image2015-4-22-17-3a44-3a0.png)

1. 클릭 **Visualforce 페이지** 드래그하여 **리드 모바일** 모바일 카드 섹션으로 이동합니다.

   ![](assets/image2015-4-22-17-3a49-3a37.png)

1. 높이를 66으로 변경하고 **확인**.

   ![](assets/image2015-4-22-17-3a52-3a15.png)

1. 클릭 **필드** 끌기 **Marketo 캠페인에 추가** (으)로 **Marketo Sales Insight** 섹션.

   ![](assets/configure-step-6.png)

   >[!TIP]
   >
   >Marketo Campaign에 추가를 쉽게 찾을 수 있도록 빠른 찾기에 &quot;추가&quot;를 입력합니다.

1. 클릭 **저장**.

   ![](assets/image2015-4-22-18-3a1-3a56.png)

휴! 드디어 Marketo Sales Insight for Salesforce1 설치를 완료했습니다! 어서 허리를 쓰다듬어 봐.

>[!MORELIKETHIS]
>
>* [Salesforce1의 최상의 선택](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/msi-for-mobile/best-bets-in-salesforce1.md)
>* [Salesforce1의 흥미로운 순간](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/msi-for-mobile/interesting-moments-in-salesforce1.md)
>* [Salesforce1에서 Marketo 이메일, 캠페인 및 관심 목록 작업 보내기](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/msi-for-mobile/send-marketo-email-and-campaign-and-watchlist-actions-in-salesforce1.md)
