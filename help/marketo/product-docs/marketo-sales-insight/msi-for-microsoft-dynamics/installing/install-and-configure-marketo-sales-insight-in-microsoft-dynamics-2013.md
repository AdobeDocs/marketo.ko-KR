---
unique-page-id: 3571737
description: Microsoft Dynamics 2013에서 Marketo Sales Insight 설치 및 구성 - Marketo 문서 - 제품 설명서
title: Microsoft Dynamics 2013에서 Marketo Sales Insight 설치 및 구성
exl-id: 290db451-47a6-4cfa-a36f-bc12ef7d3482
feature: Marketo Sales Insights
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '432'
ht-degree: 0%

---

# Microsoft Dynamics 2013에서 Marketo Sales Insight 설치 및 구성 {#install-and-configure-marketo-sales-insight-in-microsoft-dynamics}

Marketo Sales Insight는 영업 팀에 마케팅 팀이 보유한 풍부한 데이터를 &quot;창&quot;으로 볼 수 있는 환상적인 도구입니다. 설치 및 구성 방법은 다음과 같습니다.

>[!PREREQUISITES]
>
>Marketo-Microsoft 통합을 완료합니다.
>
>사용 중인 Microsoft Dynamics CRM 버전에 대해 [올바른 솔루션을 다운로드합니다](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/installing/download-the-marketo-sales-insight-solution-for-microsoft-dynamics.md).

## 솔루션 가져오기 {#import-solution}

이제 Marketo Sales Insight 솔루션을 Microsoft Dynamics로 가져올 차례입니다.

1. **Microsoft Dynamics CRM**&#x200B;에서 **설정**&#x200B;을 클릭합니다.

   ![](assets/image2014-12-12-9-3a4-3a56.png)

1. **설정**&#x200B;에서 **사용자 지정**&#x200B;을 클릭합니다.

   ![](assets/image2014-12-12-9-3a5-3a6.png)

1. **솔루션**&#x200B;을 클릭합니다.

   ![](assets/image2014-12-12-9-3a5-3a17.png)

   >[!NOTE]
   >
   >계속 진행하기 전에 이미 Marketo을 설치 및 구성했어야 합니다.

1. **가져오기**&#x200B;를 클릭합니다.

   ![](assets/image2014-12-12-9-3a5-3a27.png)

1. 새 창에서 **찾아보기**&#x200B;를 클릭합니다.

   ![](assets/image2014-12-12-9-3a5-3a36.png)

1. 위에서 다운로드한 솔루션을 찾아 선택합니다.

   ![](assets/image2014-12-12-9-3a5-3a45.png)

1. **다음**&#x200B;을 클릭합니다.

   ![](assets/image2014-12-12-9-3a5-3a55.png)

1. 솔루션이 업로드됩니다. 원한다면 패키지 콘텐츠를 볼 수 있습니다. **다음**&#x200B;을 클릭합니다.

   ![](assets/image2014-12-12-9-3a6-3a10.png)

1. 상자를 선택한 상태로 두고 **가져오기**&#x200B;를 클릭합니다.

   ![](assets/image2014-12-12-9-3a6-3a19.png)

1. 언제든지 로그 파일을 다운로드할 수 있습니다. Click **Close**.

   ![](assets/image2014-12-12-9-3a6-3a29.png)

1. 멋지다! 이제 해결 방법을 확인해야 합니다. 없는 경우 화면을 새로 고칩니다.

   ![](assets/image2014-12-12-9-3a6-3a40.png)

## Marketo 및 Sales Insight 연결 {#connect-marketo-and-sales-insight}

Marketo 인스턴스를 Dynamics의 Sales Insight에 연결하겠습니다.

>[!NOTE]
>
>관리자 권한이 필요합니다.

1. Marketo에 로그인하고 **관리자** 섹션으로 이동합니다.

   ![](assets/image2014-12-12-9-3a6-3a50.png)

1. **영업 인사이트** 섹션에서 **API 구성 편집**&#x200B;을 클릭합니다.

   ![](assets/image2014-12-12-9-3a7-3a0.png)

1. 이후 단계에서 사용할 **Marketo 호스트**, **API URL** 및 **API 사용자 ID**&#x200B;를 복사하십시오. 선택한 **API 비밀 키**&#x200B;를 입력하고 **저장**&#x200B;을 클릭합니다.

   >[!CAUTION]
   >
   >API 비밀 키에 앰퍼샌드(&amp;)를 사용하지 마십시오.

   ![](assets/image2014-12-12-9-3a7-3a9.png)

   >[!NOTE]
   >
   >Sales Insight가 작동하려면 _리드 및 연락처_&#x200B;를 위해 다음 필드를 Marketo과 동기화해야 합니다.
   >
   >* 우선 순위
   >* 긴급도
   >* 상대 스코어
   >
   >이러한 필드 중 하나가 누락된 경우 누락된 필드 이름과 함께 Marketo에 오류 메시지가 표시됩니다. 이 문제를 해결하려면 [이 절차](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/setting-up-and-using/required-fields-for-syncing-marketo-with-dynamics.md)를 수행하십시오.

1. Microsoft Dynamics로 돌아가 **설정**(으)로 이동합니다.

   ![](assets/image2014-12-12-9-3a7-3a25.png)

1. **설정**&#x200B;에서 **Marketo API 구성**&#x200B;을 클릭합니다.

   ![](assets/image2014-12-12-9-3a7-3a34.png)

1. **새로 만들기**&#x200B;를 클릭합니다.

   ![](assets/image2014-12-12-9-3a8-3a8.png)

1. 이전에 Marketo에서 가져온 정보를 입력하고 **저장**&#x200B;을 클릭합니다.

   ![](assets/image2014-12-12-9-3a8-3a17.png)

## 사용자 액세스 설정 {#set-user-access}

마지막으로 특정 사용자에게 Marketo Sales Insight에 대한 액세스 권한을 부여할 수 있습니다.

1. **설정**(으)로 이동합니다.

   ![](assets/image2014-12-12-9-3a8-3a34.png)

1. **사용자**&#x200B;를 클릭합니다.

   ![](assets/image2014-12-12-9-3a8-3a42.png)

1. Sales Insight에 대한 액세스 권한을 부여할 사용자를 선택하고 **역할 관리**&#x200B;를 클릭합니다.

   ![](assets/image2014-12-12-9-3a9-3a13.png)

1. **Marketo Sales Insight** 역할을 선택하고 **확인**&#x200B;을 클릭합니다.

   ![](assets/image2014-12-12-9-3a9-3a22.png)

   그리고 넌 다 끝내야 해! 마지막으로 테스트하려면 Marketo Sales Insight에 액세스할 수 있는 사용자로 Dynamics에 로그인하여 잠재 고객 또는 연락처를 확인합니다.

   ![](assets/image2014-12-12-9-3a9-3a31.png)

이제 영업 팀을 위한 Marketo Sales Insight의 기능을 잠금 해제했습니다.

>[!MORELIKETHIS]
>
>[잠재 고객/연락처 레코드에 대한 별과 불꽃놀이 설정](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/setting-up-and-using/setting-up-stars-and-flames-for-lead-contact-records.md)
