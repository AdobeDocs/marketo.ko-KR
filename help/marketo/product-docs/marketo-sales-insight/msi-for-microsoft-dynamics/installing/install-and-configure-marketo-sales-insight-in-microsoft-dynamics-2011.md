---
unique-page-id: 3571735
description: Microsoft Dynamics 2011에서 Marketing To Sales Insight 설치 및 구성 - Marketing Docs - 제품 설명서
title: Microsoft Dynamics 2011에서 Marketing To Sales Insight 설치 및 구성
translation-type: tm+mt
source-git-commit: e149133a5383faaef5e9c9b7775ae36e633ed7b1
workflow-type: tm+mt
source-wordcount: '412'
ht-degree: 0%

---


# Microsoft Dynamics 2011에서 Marketing To Sales Insight 설치 및 구성 {#install-and-configure-marketo-sales-insight-in-microsoft-dynamics}

Marketing To Sales Insight는 세일즈 팀에 탁월한 툴입니다. 다음은 Microsoft Dynamics 2011 온-프레미스에서 설치 및 구성하는 방법에 대한 단계별 지침입니다.

>[!PREREQUISITES]
>
>Marketing- [Microsoft 통합을 완료합니다](http://docs.marketo.com/x/DoA2).
>
>[사용 중인 Microsoft Dynamics CRM 버전에 맞는 솔루션을](http://docs.marketo.com/x/LoJo) 다운로드하십시오.

## 솔루션 가져오기 {#import-solution}

1. Microsoft Dynamics CRM에 로그인합니다. 왼쪽 **아래** 메뉴에서 설정을 클릭합니다.

   ![](assets/image2015-5-4-10-3a39-3a44.png)

1. 트리에서 **솔루션을** 선택합니다.

   ![](assets/image2015-5-4-10-3a41-3a56.png)

1. 가져오기 **** ()를 ![](assets/image2015-5-4-10-3a45-3a44.png)클릭합니다.

   ![](assets/image2015-5-4-10-3a42-3a38.png)

   >[!NOTE]
   >
   >**미리 알림**
   >
   >
   >앞으로 이동하기 전에 Marketing [To 솔루션을](install-and-configure-marketo-sales-insight-in-microsoft-dynamics-2011.md) 이미 설치하고 구성해야 합니다.

1. 찾아보기를 **클릭합니다**. 다운로드한 Marketing To Sales Insight 솔루션을 [선택합니다](download-the-marketo-sales-insight-solution-for-microsoft-dynamics.md). 다음을 **클릭합니다**.

   ![](assets/image2015-5-4-10-3a55-3a15.png)

1. 솔루션의 세부 사항을 확인하고 [다음]을 **클릭합니다**.

   ![](assets/image2015-5-4-10-3a57-3a31.png)

1. SDK 메시지 옵션이 선택되어 있는지 확인합니다. 다음을 **클릭합니다**.

   ![](assets/image2015-5-4-11-3a43-3a37.png)

1. 이제 가져오기가 완료될 때까지 기다립니다.

   ![](assets/image2015-5-4-11-3a0-3a58.png)

1. 닫기를 **클릭합니다**.

   ![](assets/crmhand.png)

1. 이제 Marketing Sales Insight가 솔루션 목록에 표시됩니다. 야호!

   ![](assets/image2015-5-4-11-3a2-3a37.png)

1. Marketing to Sales Insight를 선택하고 **모든 사용자 지정 게시** ()를 클릭합니다 ![](assets/image2015-5-4-11-3a7-3a8.png).

   ![](assets/image2015-5-4-11-3a8-3a27.png)

## Connect Marketing 및 Sales Insight  {#connect-marketo-and-sales-insight}

>[!NOTE]
>
>**관리자 권한 필요**

1. Marketing에 로그인하고 관리를 **클릭합니다**.

   ![](assets/image2014-12-12-9-3a6-3a50.png)

1. **Sales Insight **섹션에서 API 구성 **편집을 클릭합니다**.

   ![](assets/image2014-12-12-9-3a7-3a0.png)

1. Marketing **To 호스트**, **API URL**&#x200B;및 **API 사용자 ID를** 복사하여 이후 단계에서 사용할 수 있습니다. 원하는 **API 암호** 키를 입력하고 **저장을 클릭합니다**.

   >[!CAUTION]
   >
   >API 암호 키에 앰퍼샌드(&amp;)를 사용하지 마십시오.

   ![](assets/image2015-5-4-11-3a16-3a3.png)

   >[!NOTE]
   >
   >다음 필드를 Sales Insight의 리드 및 담당자 *모두* Marketing과 동기화해야 합니다.
   >
   >    
   >    
   >    * 우선 순위
   >    * 긴급성
   >    * 상대 점수

   >    
   >    
   >이러한 필드가 누락된 경우, Marketing To에 누락된 필드 이름이 있는 오류 메시지가 표시됩니다. 이 문제를 해결하려면 [이 절차를 수행하십시오](../../../../product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/setting-up-and-using/required-fields-for-syncing-marketo-with-dynamics.md).

1. Dynamics로 돌아가 설정을 **선택합니다**.

   ![](assets/image2015-5-4-10-3a39-3a44.png)

1. 트리에서 **Marketing API** 구성을 선택합니다.

   ![](assets/image2015-5-4-11-3a22-3a41.png)

1. 기본 **구성을 클릭합니다**.

   ![](assets/image2015-5-4-11-3a26-3a10.png)

1. Marketing to에서 이전에 입수한 정보를 입력합니다.

   ![](assets/image2015-5-4-11-3a27-3a16.png)

1. 저장을 **클릭합니다.**

   ** ![](assets/image2015-5-4-11-3a28-3a13.png)

   **

## 사용자 액세스 설정 {#set-user-access}

특정 사용자가 Sales Insight에 액세스할 수 있도록 사용자 역할을 설정합니다.

1. 설정을 **선택합니다**.

   ![](assets/image2015-5-4-11-3a30-3a54.png)

1. 트리에서 **관리를** 선택합니다.

   ![](assets/image2015-5-4-11-3a31-3a39.png)

1. 사용자를 **클릭합니다**.

   ![](assets/image2015-5-4-11-3a32-3a25.png)

1. 액세스 권한을 부여할 사용자를 선택하고 역할 **관리를 클릭합니다**.

   ![](assets/image2015-5-4-11-3a35-3a8.png)

1. Marketing **to Sales Insight** 역할을 선택하고 **확인을 클릭합니다**.

   ![](assets/image2015-5-4-11-3a36-3a59.png)

   그게 다야! 이제 액세스 권한이 있는 모든 사용자는 리드/연락처 세부 정보 보기에서 판매 통찰력 섹션을 볼 수 있습니다.

   ![](assets/image2015-5-4-11-3a39-3a23.png)

   축하합니다. Adobe Marketing To Sales Insight의 강력한 기능을

>[!NOTE]
>
>**관련 문서**
>
>[리드/연락처 레코드에 대한 별과 불꽃 설정](http://docs.marketo.com/x/BICMAg)

