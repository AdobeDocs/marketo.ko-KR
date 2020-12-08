---
unique-page-id: 7513865
description: Microsoft Dynamics 2015에서 Marketing To Sales Insight 설치 및 구성 - Marketing Docs - 제품 설명서
title: Microsoft Dynamics 2015에서 Marketing To Sales Insight 설치 및 구성
translation-type: tm+mt
source-git-commit: 47b2fee7d146c3dc558d4bbb10070683f4cdfd3d
workflow-type: tm+mt
source-wordcount: '458'
ht-degree: 0%

---


# Microsoft Dynamics 2015에서 Marketing To Sales Insight 설치 및 구성 {#install-and-configure-marketo-sales-insight-in-microsoft-dynamics}

Marketing Sales Insight는 세일즈 팀에 마케팅 팀이 가진 데이터의 &quot;창&quot;을 제공할 수 있는 멋진 툴입니다. Microsoft Dynamics 201에서 설치하고 구성하는 방법은 다음과 같습니다

>[!NOTE]
>
>**사전 요구 사항**
>
>Marketing- [Microsoft 통합을 완료합니다](http://docs.marketo.com/x/ZwBd).
>
>[사용 중인 Microsoft Dynamics CRM 버전에 맞는 솔루션을](http://docs.marketo.com/x/LoJo) 다운로드하십시오.

## 솔루션 가져오기 {#import-solution}

이제 Marketing To Sales Insight 솔루션을 Microsoft Dynamics로 가져올 차례입니다. 방법은 다음과 같습니다.

1. Microsoft Dynamics CRM에서 설정을 **클릭합니다**.

   ![](assets/image2014-12-12-9-3a4-3a56.png)

1. 설정에서 사용자 지정을 **클릭합니다**.

   ![](assets/image2015-4-29-14-3a22-3a1.png)

1. 솔루션을 **클릭합니다**.

   ![](assets/image2014-12-12-9-3a5-3a17.png)

   >[!NOTE]
   >
   >**미리 알림**
   >
   >
   >앞으로 이동하기 전에 Marketing To 솔루션을 이미 설치하고 구성해야 합니다.

1. 가져오기를 **클릭합니다**.

   ![](assets/image2014-12-12-9-3a5-3a27.png)

1. 새 창에서 찾아보기를 **클릭합니다**.

   ![](assets/image2014-12-12-9-3a5-3a36.png)

1. 위에서 다운로드한 솔루션을 찾아 선택합니다.

   ![](assets/image2014-12-12-9-3a5-3a45.png)

1. 다음을 **클릭합니다**.

   ![](assets/image2014-12-12-9-3a5-3a55.png)

1. 솔루션이 업로드됩니다. 원할 경우 패키지 내용을 볼 수 있습니다. 다음을 **클릭합니다**.

   ![](assets/image2014-12-12-9-3a6-3a10.png)

1. 상자를 선택된 상태로 두고 가져오기를 **클릭합니다**.

   ![](assets/image2014-12-12-9-3a6-3a19.png)

1. 로그 파일을 다운로드한 다음 닫기를 **클릭합니다**.

   ![](assets/image2014-12-12-9-3a6-3a29.png)

1. 대단해! 지금 해결 방법을 살펴보십시오. 없는 경우 화면을 새로 고칩니다.

   ![](assets/image2014-12-12-9-3a6-3a40.png)

## Connect Marketing 및 Sales Insight {#connect-marketo-and-sales-insight}

Dynamics의 Sales Insight에 Marketing 인스턴스를 연결하겠습니다. 방법은 다음과 같습니다.

>[!NOTE]
>
>관리자 권한이 필요합니다.

1. Marketing에 로그인하고 **Admin **섹션으로 이동합니다.

   ![](assets/image2014-12-12-9-3a6-3a50.png)

1. Sales Insight 섹션에서 API 구성 **편집을 클릭합니다**.

   ![](assets/image2014-12-12-9-3a7-3a0.png)

1. Marketing **To 호스트**, **API URL**&#x200B;및 **API 사용자 ID를** 복사하여 이후 단계에서 사용할 수 있습니다. 원하는 API 암호 키를 입력하고 **저장을 클릭합니다**.

   >[!CAUTION]
   >
   >API 암호 키에 앰퍼샌드(&amp;)를 사용하지 마십시오.

   ![](assets/image2014-12-12-9-3a7-3a9.png)

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

1. Microsoft Dynamics로 돌아가 **설정으로 이동합니다**.

   ![](assets/image2014-12-12-9-3a7-3a25.png)

1. 설정 **에서****Marketing API 구성을 클릭합니다**.

   ![](assets/image2014-12-12-9-3a7-3a34.png)

1. 새로 **만들기를 클릭합니다**.

   ![](assets/image2014-12-12-9-3a8-3a8.png)

1. Marketing to에서 이전에 입수한 정보를 입력하고 **저장을 클릭합니다**.

   ![](assets/image2014-12-12-9-3a8-3a17.png)

## 사용자 액세스 설정 {#set-user-access}

마지막으로 특정 사용자에게 Marketing to Sales Insight를 사용할 수 있는 액세스 권한을 부여해야 합니다.

1. 설정으로 **이동합니다**.

   ![](assets/image2014-12-12-9-3a8-3a34.png)

1. 보안 **으로 이동합니다**.

   ![](assets/image2015-4-29-14-3a56-3a33.png)

1. 사용자를 **클릭합니다**.

   ![](assets/image2015-4-29-14-3a57-3a46.png)

1. Sales Insight에 액세스할 사용자를 선택하고 역할 **관리를 클릭합니다**.

   ![](assets/image2015-4-29-14-3a59-3a31.png)

1. Marketing to Sales Insight 역할을 선택하고 **확인을 클릭합니다**.

   ![](assets/image2014-12-12-9-3a9-3a22.png)

   그리고 넌 모두 해야 돼! 마지막으로 테스트하려면 Marketing To Sales Insight에 액세스할 수 있는 사용자로 Dynamics에 로그인하여 리드 또는 담당자를 확인하십시오.

   ![](assets/image2015-4-29-15-3a2-3a27.png)

이제 세일즈 팀에 대한 Marketing To Sales Insight의 강력한 기능을 사용할 수 있습니다.

>[!NOTE]
>
>**관련 문서**
>
>[리드/연락처 레코드에 대한 별과 불꽃 설정](http://docs.marketo.com/x/BICMAg)

