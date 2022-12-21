---
unique-page-id: 37355602
description: Microsoft Dynamics Online에서 Marketo Sales Insight 설치 및 구성 - Marketo 문서 - 제품 설명서
title: Microsoft Dynamics Online에서 Marketo Sales Insight 설치 및 구성
exl-id: 3b58b109-96f9-427e-be5c-a8db270ffe69
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '496'
ht-degree: 0%

---

# Microsoft Dynamics Online에서 Marketo Sales Insight 설치 및 구성 {#install-and-configure-marketo-sales-insight-in-microsoft-dynamics-online}

Marketo Sales Insight는 마케팅 팀이 보유한 데이터의 가치를 영업 팀에 &quot;창&quot;으로 제공하는 환상적인 도구입니다. Microsoft Dynamics Online에서 설치하고 구성하는 방법은 다음과 같습니다.

>[!PREREQUISITES]
>
>Marketo-Microsoft 통합을 완료합니다.
>
>[올바른 솔루션 다운로드](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/installing/download-the-marketo-sales-insight-solution-for-microsoft-dynamics.md) 최신 버전의 Microsoft Dynamics CRM에 대해 알아보십시오.

## 솔루션 가져오기 {#import-solution}

>[!NOTE]
>
>통합 인터페이스를 사용하는 경우 아래 1단계 전에 오른쪽 상단 모서리의 설정 아이콘을 클릭하고 을(를) 선택합니다 **고급 설정**.

1. Microsoft Dynamics CRM에서 **설정**.

   ![](assets/image2014-12-12-9-3a4-3a56-1.png)

1. 설정에서 을 클릭합니다. **사용자 지정**.

   ![](assets/image2015-4-29-14-3a22-3a1-1.png)

1. 클릭 **솔루션**.

   ![](assets/image2014-12-12-9-3a5-3a17-1.png)

   >[!NOTE]
   >
   >앞으로 이동하기 전에 이미 Marketo 솔루션을 설치 및 구성했어야 합니다.

1. 클릭 **가져오기**.

   ![](assets/image2014-12-12-9-3a5-3a27-1.png)

1. 새 창에서 **찾아보기**.

   ![](assets/image2014-12-12-9-3a5-3a36-1.png)

1. 컴퓨터에서 방금 다운로드한 솔루션을 찾아서 설치합니다.

1. 클릭 **다음**.

   ![](assets/seven.png)

1. 솔루션이 업로드됩니다. 원할 경우 패키지 콘텐츠를 볼 수 있습니다. 클릭 **다음**.

   ![](assets/image2014-12-12-9-3a6-3a10-1.png)

1. 상자를 선택된 상태로 두고 를 클릭합니다. **가져오기**.

   ![](assets/image2014-12-12-9-3a6-3a19-1.png)

1. 자유롭게 로그 파일을 다운로드한 다음 **닫기**.

   ![](assets/image2014-12-12-9-3a6-3a29-1.png)

1. 끝내줘! 이제 해결 방법이 표시됩니다. 화면이 표시되지 않으면 화면을 새로 고칩니다.

   ![](assets/eleven.png)

1. 클릭 **게시 사용자 지정**.

   >[!NOTE]
   >
   >글로벌 MS Dynamics 동기화를 사용하도록 설정해야 합니다.

## Marketo 및 Sales Insight 연결 {#connect-marketo-and-sales-insight}

Marketo 인스턴스를 Dynamics의 Sales Insight에 연결합니다. 방법은 다음과 같습니다.

>[!NOTE]
>
>**관리 권한 필요**

1. Marketo에 로그인하고 **관리** 섹션을 참조하십시오.

   ![](assets/image2014-12-12-9-3a6-3a50-1.png)

1. Sales Insight 섹션에서 **API 구성 편집**.

   ![](assets/image2014-12-12-9-3a7-3a0-1.png)

1. 를 복사합니다. **Marketo 호스트**, **API URL**, 및 **API 사용자 Id** 을 참조하십시오. 선택한 API 암호 키를 입력하고 를 클릭합니다. **저장**.

   >[!CAUTION]
   >
   >API 암호 키에 앰퍼샌드(&amp;)를 사용하지 마십시오.

   ![](assets/image2014-12-12-9-3a7-3a9-1.png)

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

   ![](assets/image2014-12-12-9-3a7-3a25-1.png)

1. 아래 **설정**&#x200B;를 클릭합니다. **Marketo API 구성**.

   ![](assets/image2014-12-12-9-3a7-3a34-1.png)

1. 클릭 **새로 만들기**.

   ![](assets/image2014-12-12-9-3a8-3a8-1.png)

1. 이전에 Marketo에서 가져온 정보를 입력하고 **저장**.

   ![](assets/image2014-12-12-9-3a8-3a17-1.png)

## 동기화 활성화 {#enable-sync}

1. Marketo에서 **관리**.

   ![](assets/enable-one.png)

1. 통합에서 을 선택합니다 **Microsoft Dynamics**.

   ![](assets/enable-two.png)

1. 클릭 **동기화 활성화**.

   ![](assets/enable-three.png)

1. 클릭 **편집** 필드 동기화 세부 정보 옆에 있습니다.

   ![](assets/enable-four.png)

1. 이 작업은 _자동으로_ 이전에 비활성화된 MSI 필드(긴급성, 상대 점수 및 우선 순위)를 선택합니다. 간단히 **저장** 데이터 동기화를 시작하려면 다음을 수행하십시오.

   ![](assets/enable-five.png)

## 사용자 액세스 설정 {#set-user-access}

마지막으로 특정 사용자에게 Marketo Sales Insight를 사용할 수 있는 액세스 권한을 제공해야 합니다.

1. 이동 **설정**.

   ![](assets/image2014-12-12-9-3a8-3a34-1.png)

1. 이동 **보안**.

   ![](assets/image2015-4-29-14-3a56-3a33-1.png)

1. 클릭 **사용자**.

   ![](assets/image2015-4-29-14-3a57-3a46-1.png)

1. 영업 인사이트에 액세스할 사용자를 선택하고 **역할 관리**.

   ![](assets/image2015-4-29-14-3a59-3a31-1.png)

1. Marketo Sales Insight 역할을 선택하고 **확인**.

   ![](assets/image2014-12-12-9-3a9-3a22-1.png)

   그리고 넌 모두 해야 해! 마지막으로 테스트하려면 Marketo Sales Insight에 액세스할 수 있는 사용자로 Dynamics에 로그인하여 잠재 고객 또는 연락처를 확인합니다.

   ![](assets/image2015-4-29-15-3a2-3a27-1.png)

>[!MORELIKETHIS]
>
>[리드/연락처 레코드에 대한 별과 불길 설정](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/setting-up-and-using/setting-up-stars-and-flames-for-lead-contact-records.md)
