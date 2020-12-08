---
unique-page-id: 3571830
description: 3단계 중 3단계 - Microsoft Dynamics와 Marketing(온라인) - Marketing Docs - 제품 설명서
title: 3단계 중 3단계 - Microsoft Dynamics와 Marketing(온라인) 연결
translation-type: tm+mt
source-git-commit: dc20aede0894a09e6c0bcd3d1580859b5fecb5f1
workflow-type: tm+mt
source-wordcount: '369'
ht-degree: 0%

---


# 3단계 중 3단계:Microsoft Dynamics와 Marketing(온라인) 연결 {#step-of-connect-microsoft-dynamics-with-marketo-online}

>[!NOTE]
>
>**FYI**
>
>Marketing은 이제 모든 구독 간의 언어를 표준화하므로 구독에 리드/리드 및 docs.markto.com에 있는 사람/사람을 볼 수 있습니다. 이 용어는 같은 것을 의미한다.아티클 지침에는 영향을 주지 않습니다. 다른 변화도 있습니다 [자세한](http://docs.marketo.com/display/DOCS/Updates+to+Marketo+Terminology)내용

동기화 마지막 단계입니다. 거의 다 왔어!

>[!NOTE]
>
>**사전 요구 사항**
>
>* [3단계 중 1단계:Marketing To 솔루션(온라인) 설치](step-1-of-3-install.md)
   >
   >
* [3단계 중 2단계:Dynamics에서 Marketing To 동기화 사용자 설정](step-2-of-3-set-up.md)

>



>[!NOTE]
>
>**관리자 권한 필요**

## Dynamics 사용자 정보 입력 {#enter-dynamics-sync-user-information}

1. Marketing에 로그인하고 관리를 **클릭합니다**.

   ![](assets/login-admin.png)

1. CRM을 **클릭합니다**.

   ![](assets/image2015-3-16-9-3a47-3a34.png)

1. Microsoft **를 선택합니다**.

   ![](assets/image2015-3-16-9-3a50-3a6.png)

1. 1단계에서 **편집을** **클릭합니다.자격 증명을 입력합니다**.

   ![](assets/image2015-3-16-9-3a48-3a43.png)

   >[!CAUTION]
   >
   >제출 후 스키마 변경 사항을 되돌릴 수 없으므로 자격 증명이 올바른지 확인하십시오. 잘못된 자격 증명이 저장된 경우 새 Marketing To 구독을 구해야 합니다.

1. 사용자 **이름**, **암호**&#x200B;및 Microsoft Dynamics **URL** (클라이언트 ID 및 클라이언트 암호선택 사항)을 입력합니다. 완료되면 **저장을** 클릭합니다.

   ![](assets/five-1.png)

   >[!NOTE]
   >
   >Marketing의 사용자 이름은 CRM의 동기화 사용자의 사용자 이름과 일치해야 합니다. 형식은 DOMAIN\user [`[email protected]`](http://docs.marketo.com/cdn-cgi/l/email-protection#bcc9cfd9cefcd8d3d1ddd5d292dfd3d1) 일 수 있습니다.

## 동기화할 필드 선택 {#select-fields-to-sync}

1. 2단계에서 **편집을** **클릭합니다.동기화할 필드를 선택합니다**.

   ![](assets/image2015-3-16-9-3a51-3a28.png)

1. Marketing To에 동기화할 필드를 선택하여 미리 선택합니다. 저장을 **클릭합니다**.

   ![](assets/image2016-8-25-15-3a6-3a11.png)

## 사용자 정의 필터의 필드 동기화 {#sync-fields-for-a-custom-filter}

사용자 지정 필터를 만든 경우 Marketing To와 동기화할 새 필드를 선택해야 합니다.

1. 관리자로 이동하고 **Microsoft Dynamics를 선택합니다**.

   ![](assets/image2015-10-9-9-3a50-3a9.png)

1. 필드 **동기화** 세부 정보에서 편집을 클릭합니다.

   ![](assets/image2015-10-9-9-3a52-3a23.png)

1. 아래로 스크롤하여 확인합니다. 실제 이름은 new_synctomto여야 하지만 표시 이름은 무엇이든 될 수 있습니다. 저장을 **클릭합니다**.

   ![](assets/image2016-8-25-15-3a7-3a35.png)

## 동기화 사용 {#enable-sync}

1. 3단계에서 **편집을** **클릭합니다.동기화를 활성화합니다**.

   ![](assets/image2015-3-16-9-3a52-3a2.png)

   >[!CAUTION]
   >
   >Microsoft Dynamics 동기화에 대해 또는 수동으로 사람 또는 리드를 입력할 때 Marketing To에서 자동으로 데이터 중복 제거가 되지 않습니다.

1. 팝업에서 모든 내용을 읽고 이메일 주소를 입력한 다음 [동기화 **시작]을 클릭합니다**.

   ![](assets/image2015-3-16-9-3a55-3a10.png)

1. 첫 번째 동기화에는 몇 시간이 걸릴 수 있습니다. 완료되면 알림 이메일을 수신하게 됩니다.

   ![](assets/image2015-3-16-9-3a59-3a51.png)

탁월한 작품!
