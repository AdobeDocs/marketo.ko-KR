---
unique-page-id: 2952678
description: 알림 정보 토큰 보내기 {{SP_Send_Alert_Info} - Marketing Docs - 제품 설명서 사용
title: 알림 정보 토큰 보내기 사용
translation-type: tm+mt
source-git-commit: d7d6aee63144c472e02fe0221c4a164183d04dd4
workflow-type: tm+mt
source-wordcount: '265'
ht-degree: 0%

---


# 알림 정보 토큰 보내기 사용 {#use-the-send-alert-info-token-sp-send-alert-info}

토큰은 `{{SP_Send_Alert_Info}}` 영업 팀에 대한 경고 이메일을 만들 때 사용할 특별한 토큰입니다.

>[!TIP]
>
>이 토큰은 경고 보내기 [흐름 단계를 사용하여 포함된 이메일을 보낼 때만](../../../../product-docs/core-marketo-concepts/smart-campaigns/flow-actions/send-alert.md) 작동합니다. 이메일 보내기 흐름 단계에서 사용하면 작동하지 않습니다.

경고 예:   ![](assets/image2014-9-25-15-3a17-3a58.png)

>[!NOTE]
>
>어서! 경고의 URL에는 만료 날짜가 있으므로 이러한 유형의 메시지를 지원하는 케이지가 있는지 확인합니다. 만료 날짜는 [관리자가 구성합니다](../../../../product-docs/administration/settings/edit-link-expiration-in-reports-and-alerts.md).

다음 정보가 다음 정보의 일부로 포함됩니다 `{{SP_Send_Alert_Info}}`.

* Marketing To에서 개인 세부 사항에 대한 링크로 이름 및 성
* CRM의 사용자에 대한 링크
* 경고를 보낸 마케팅의 캠페인 이름
* 경고가 전송된 시간

>[!NOTE]
>
>CRM에 대한 링크는 사용자가 CRM 시스템(현재 Dynamics CRM에서는 사용할 수 없음)에 있는 경우에만 나타납니다. 이 링크는 Marketing 사용자와 Marketing이 아닌 사용자 모두 액세스할 수 있습니다.

## SP_Send_Alert_Info 토큰을 이메일에 추가 {#add-the-sp-send-alert-info-token-to-an-email}

1. 이메일을 선택하고 초안 **편집을 클릭합니다**.

   ![](assets/one-3.png)

1. 토큰을 추가할 편집 가능 영역을 두 번 클릭합니다.

   ![](assets/two-3.png)

1. 토큰을 배치할 위치에 커서를 놓고 토큰 **삽입 버튼을** 클릭합니다.

   ![](assets/three-3.png)

1. 토큰을 찾아 선택하고 **`{{SP_Send_Alert_Info}}`** 삽입을 **클릭합니다**.

   ![](assets/image2014-9-25-15-3a19-3a11.png)

1. 저장을 **클릭합니다**.

   ![](assets/image2014-9-25-15-3a19-3a24.png)

>[!NOTE]
>
>**미리 알림**
>
>이메일 승인을 잊지 마십시오.

잘됐다! 이 토큰은 매우 유용하며 영업 팀을 위해 만드는 모든 경고에 이 토큰을 사용해야 합니다.