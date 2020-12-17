---
unique-page-id: 3571739
description: Microsoft Dynamics 365에서 Marketing To Sales Insight 설치 및 구성 - Marketing To Docs - 제품 설명서
title: Microsoft Dynamics 365에서 Marketing To Sales Insight 설치 및 구성
translation-type: tm+mt
source-git-commit: e149133a5383faaef5e9c9b7775ae36e633ed7b1
workflow-type: tm+mt
source-wordcount: '474'
ht-degree: 0%

---


# Microsoft Dynamics 365에서 Marketing To Sales Insight 설치 및 구성 {#install-and-configure-marketo-sales-insight-in-microsoft-dynamics}

Marketing To Sales Insight는 마케팅 팀이 보유하고 있는 데이터의 &quot;창&quot;을 세일즈 팀에 제공할 수 있는 환상적인 도구입니다. 설치 및 구성 방법

>[!PREREQUISITES]
>
>[Marketing-Microsoft 통합](http://docs.marketo.com/x/E4A2)을 완료합니다.
>
>[사용 중인 ](http://docs.marketo.com/x/LoJo) 버전의 Microsoft Dynamics CRM에 맞는 솔루션을 다운로드합니다.

## 솔루션 가져오기 {#import-solution}

1. [Microsoft Office 365](https://login.microsoftonline.com/)에 로그인합니다.

   ![](assets/image2015-3-16-15-58-55.png)

1. ![—](assets/image2015-3-16-16-1-13.png) 메뉴를 클릭하고 **CRM**&#x200B;을 선택합니다.

   ![](assets/image2015-3-16-16-0-10.png)

1. ![—](assets/image2015-5-13-10-5-8.png) 메뉴를 클릭합니다. 드롭다운에서 **설정**&#x200B;을 선택한 다음 **솔루션**&#x200B;을 선택합니다.

   ![](assets/image2015-5-13-10-4-1.png)

   >[!NOTE]
   >
   >**미리 알림**
   >
   >
   >앞으로 이동하기 전에 이미 [이(가) 설치되어 있고 Marketing 솔루션](../../../../product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365/step-1-of-3-install.md)을(를) 구성해야 합니다.

   가져오기를 클릭합니다.
   ![](assets/image2014-12-12-9-3a5-3a27.png)

1. 새 창에서 **찾아보기**&#x200B;를 클릭합니다. 1단계](#msi)에서 다운로드한 [Marketing to Sales Insight 솔루션을 선택합니다. **다음**&#x200B;을 클릭합니다.

   ![](assets/image2015-5-13-15-3a38-3a49.png)

1. 솔루션이 업로드됩니다. 원할 경우 패키지 내용을 볼 수 있습니다. **다음**&#x200B;을 클릭합니다.

   ![](assets/image2014-12-12-9-3a6-3a10.png)

1. **checked** 상자를 떠나 **가져오기**&#x200B;를 클릭합니다.

   ![](assets/image2014-12-12-9-3a6-3a19.png)

1. 로그 파일을 다운로드할 수 있습니다. **닫기**&#x200B;를 클릭합니다.

   ![](assets/image2014-12-12-9-3a6-3a29.png)

1. 굉장해! 지금 해결 방법을 살펴보십시오. 없는 경우 화면을 새로 고칩니다.

   ![](assets/image2015-5-13-15-3a42-3a29.png)

1. **모든 사용자 지정 게시**&#x200B;를 클릭합니다.

   ![](assets/image2015-11-10-11-3a15-3a40.png)

## Connect Marketing &amp; Sales Insight {#connect-marketo-and-sales-insight}

Dynamics에서 Marketing To 인스턴스를 Sales Insight에 연결합니다. 방법은 다음과 같습니다.

>[!NOTE]
>
>**관리자 권한 필요**

1. Marketing에 로그인하고 **관리** 섹션으로 이동합니다.

   ![](assets/image2014-12-12-9-3a6-3a50.png)

1. **Sales Insight** 섹션에서 **API 구성 편집**&#x200B;을 클릭합니다.

   ![](assets/image2014-12-12-9-3a7-3a0.png)

1. 나중 단계에서 사용할 **Marketing To 호스트**, **API URL** 및 **API 사용자 ID**&#x200B;를 복사합니다. 원하는 **API 비밀 키**&#x200B;를 입력하고 **저장**&#x200B;을 클릭합니다.

   >[!CAUTION]
   >
   >API 비밀 키에 앰퍼샌드(&amp;)를 사용하지 마십시오.

   ![](assets/image2014-12-12-9-3a7-3a9.png)

   >[!NOTE]
   >
   >Sales Insight가 작동하려면 *Lead 및 Contact*&#x200B;에 대해 다음 필드를 Markto와 동기화해야 합니다.
   >
   > * 우선 순위
   > * 긴급성
   > * 상대 점수

   >
   >이러한 필드가 누락된 경우, 누락된 필드의 이름이 있는 오류 메시지가 Marketing에 표시됩니다. 이 문제를 해결하려면 [이 절차](../../../../product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/setting-up-and-using/required-fields-for-syncing-marketo-with-dynamics.md)를 수행하십시오.

1. Microsoft Dynamics로 돌아가 설정 옆에 있는 ![](assets/image2015-5-13-15-3a49-3a19.png) 아이콘을 클릭한 다음 드롭다운에서 **Marketing API 구성**&#x200B;을 선택합니다.

   ![](assets/image2015-5-13-16-3a4-3a1.png)

1. **기본 구성**&#x200B;을 클릭합니다.

   ![](assets/image2015-5-13-16-3a5-3a2.png)

1. Marketing에서 이전에 복사했던 정보를 입력합니다.

   ![](assets/image2015-5-13-16-3a7-3a6.png)

1. 오른쪽 하단 모서리에 있는 ![](assets/image2015-5-13-16-3a8-3a51.png) 아이콘을 클릭하여 변경 내용을 저장합니다.

## 사용자 액세스 설정 {#set-user-access}

사용자에게 Sales Insight를 사용할 수 있는 권한을 부여해야 합니다.

1. ![](assets/image2015-5-13-10-3a5-3a8.png) 메뉴를 클릭합니다. 드롭다운 메뉴에서 **설정**&#x200B;을 선택하고 **보안**&#x200B;을 선택합니다.

   ![](assets/image2015-5-13-16-3a12-3a12.png)

1. **사용자**&#x200B;를 클릭합니다.

   ![](assets/image2015-4-29-14-3a57-3a46.png)

1. Sales Insight에 액세스할 사용자를 선택하고 **역할 관리**&#x200B;를 클릭합니다.

   ![](assets/image2015-4-29-14-3a59-3a31.png)

1. **Marketing To Sales Insight** 역할을 선택하고 **확인**&#x200B;을 클릭합니다.

   ![](assets/image2014-12-12-9-3a9-3a22.png)

   그리고 너는 모두 해야 한다! 마지막으로 Dynamics에 로그인하면 Marketing To Sales Insight에 액세스하여 리드 또는 담당자를 확인할 수 있습니다.

   ![](assets/image2015-4-29-15-3a2-3a27.png)

이제 영업 팀에 대한 Marketing To Sales Insight의 강력한 기능을 사용할 수 있습니다.

>[!NOTE]
>
>**관련 문서**
>
>[리드/연락처 레코드에 대한 별과 불꽃 설정](http://docs.marketo.com/x/BICMAg)