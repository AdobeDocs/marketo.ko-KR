---
unique-page-id: 3571737
description: Microsoft Dynamics 2013에서 Marketo Sales Insight 설치 및 구성 - Marketo 문서 - 제품 설명서
title: Microsoft Dynamics 2013에서 Marketo Sales Insight 설치 및 구성
exl-id: 290db451-47a6-4cfa-a36f-bc12ef7d3482
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '429'
ht-degree: 0%

---

# Microsoft Dynamics 2013에서 Marketo Sales Insight 설치 및 구성 {#install-and-configure-marketo-sales-insight-in-microsoft-dynamics}

Marketo Sales Insight는 마케팅 팀이 보유한 데이터의 가치를 영업 팀에 &quot;창&quot;으로 제공하는 환상적인 도구입니다. 설치 및 구성 방법은 다음과 같습니다.

>[!PREREQUISITES]
>
>Marketo-Microsoft 통합을 완료합니다.
>
>[올바른 솔루션 다운로드](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/installing/download-the-marketo-sales-insight-solution-for-microsoft-dynamics.md) 최신 버전의 Microsoft Dynamics CRM에 대해 알아보십시오.

## 솔루션 가져오기 {#import-solution}

이제 Marketo Sales Insight 솔루션을 Microsoft Dynamics로 가져올 차례입니다.

1. 아래 **Microsoft Dynamics CRM** click **설정**.

   ![](assets/image2014-12-12-9-3a4-3a56.png)

1. 아래 **설정**&#x200B;를 클릭합니다. **사용자 지정**.

   ![](assets/image2014-12-12-9-3a5-3a6.png)

1. 클릭 **솔루션**.

   ![](assets/image2014-12-12-9-3a5-3a17.png)

   >[!NOTE]
   >
   >앞으로 이동하기 전에 이미 Marketo을 설치 및 구성했어야 합니다

1. 클릭 **가져오기**.

   ![](assets/image2014-12-12-9-3a5-3a27.png)

1. 새 창에서 **찾아보기**.

   ![](assets/image2014-12-12-9-3a5-3a36.png)

1. 위에서 다운로드한 솔루션을 찾아 선택합니다.

   ![](assets/image2014-12-12-9-3a5-3a45.png)

1. 클릭 **다음**.

   ![](assets/image2014-12-12-9-3a5-3a55.png)

1. 솔루션이 업로드됩니다. 원할 경우 패키지 콘텐츠를 볼 수 있습니다. 클릭 **다음**.

   ![](assets/image2014-12-12-9-3a6-3a10.png)

1. 상자를 선택된 상태로 두고 를 클릭합니다. **가져오기**.

   ![](assets/image2014-12-12-9-3a6-3a19.png)

1. 자유롭게 로그 파일을 다운로드할 수 있습니다. Click **Close**.

   ![](assets/image2014-12-12-9-3a6-3a29.png)

1. 끝내줘! 이제 해결 방법이 표시됩니다. 화면이 표시되지 않으면 화면을 새로 고칩니다.

   ![](assets/image2014-12-12-9-3a6-3a40.png)

## Marketo 및 Sales Insight 연결 {#connect-marketo-and-sales-insight}

Marketo 인스턴스를 Dynamics의 Sales Insight에 연결합니다.

>[!NOTE]
>
>관리 권한이 필요합니다.

1. Marketo에 로그인하고 **관리** 섹션을 참조하십시오.

   ![](assets/image2014-12-12-9-3a6-3a50.png)

1. 아래에 **Sales Insight** 섹션 클릭 **API 구성 편집**.

   ![](assets/image2014-12-12-9-3a7-3a0.png)

1. 를 복사합니다. **Marketo 호스트**, **API URL**, 및 **API 사용자 Id** 을 참조하십시오. 을(를) 입력합니다. **API 암호 키** 선택한 후 **저장**.

   >[!CAUTION]
   >
   >API 암호 키에 앰퍼샌드(&amp;)를 사용하지 마십시오.

   ![](assets/image2014-12-12-9-3a7-3a9.png)

   >[!NOTE]
   >
   >다음 필드는 다음에 대한 Marketo과 동기화해야 합니다. _리드 및 연락처 모두_ 영업 통찰력 작동 방법:
   >
   >* 우선 순위
   >* 긴급성
   >* 상대 점수

   >
   >이러한 필드가 누락된 경우 누락된 필드의 이름이 있는 오류 메시지가 Marketo에 표시됩니다. 이 문제를 해결하려면 다음을 수행하십시오. [이 절차](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/setting-up-and-using/required-fields-for-syncing-marketo-with-dynamics.md).

1. Microsoft Dynamics로 돌아가 **설정**.

   ![](assets/image2014-12-12-9-3a7-3a25.png)

1. 아래 **설정**&#x200B;를 클릭합니다. **Marketo API 구성**.

   ![](assets/image2014-12-12-9-3a7-3a34.png)

1. 클릭 **새로 만들기**.

   ![](assets/image2014-12-12-9-3a8-3a8.png)

1. 이전에 Marketo에서 가져온 정보를 입력하고 **저장**.

   ![](assets/image2014-12-12-9-3a8-3a17.png)

## 사용자 액세스 설정 {#set-user-access}

마지막으로 특정 사용자에게 Marketo Sales Insight에 액세스할 수 있는 권한을 제공할 수 있습니다.

1. 이동 **설정**.

   ![](assets/image2014-12-12-9-3a8-3a34.png)

1. 클릭 **사용자**.

   ![](assets/image2014-12-12-9-3a8-3a42.png)

1. Sales Insight에 액세스할 사용자를 선택하고 **역할 관리**.

   ![](assets/image2014-12-12-9-3a9-3a13.png)

1. 을(를) 선택합니다 **Marketo Sales Insight** 역할 및 클릭 **확인**.

   ![](assets/image2014-12-12-9-3a9-3a22.png)

   그리고 넌 모두 해야 해! 마지막으로 테스트하려면 Marketo Sales Insight에 액세스할 수 있는 사용자로 Dynamics에 로그인하여 잠재 고객 또는 담당자를 확인합니다.

   ![](assets/image2014-12-12-9-3a9-3a31.png)

이제 영업 팀을 위한 Marketo Sales Insight 의 기능을 해제했습니다.

>[!MORELIKETHIS]
>
>[리드/연락처 레코드에 대한 별과 불길 설정](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/setting-up-and-using/setting-up-stars-and-flames-for-lead-contact-records.md)
