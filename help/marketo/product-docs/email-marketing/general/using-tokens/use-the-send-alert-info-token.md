---
unique-page-id: 2952678
description: 경고 정보 보내기 토큰 {{SP_Send_Alert_Info}} 사용 - Marketo 문서 - 제품 설명서
title: 경고 정보 보내기 토큰 사용
exl-id: 950eb4d1-35d5-4e5c-9624-a38284bff987
feature: Tokens
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '257'
ht-degree: 0%

---

# 경고 정보 보내기 토큰 사용 {#use-the-send-alert-info-token-sp-send-alert-info}

`{{SP_Send_Alert_Info}}` 토큰은 영업 팀에 대한 경고 이메일을 만들 때 사용할 특수 토큰입니다.

>[!TIP]
>
>이 토큰은 [경고 보내기](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/send-alert.md) 흐름 단계를 사용하여 토큰이 포함된 이메일을 보낼 때만 의도한 대로 작동합니다. 이메일 전송 흐름 단계에서 사용하는 경우 작동하지 않습니다.

경고 예:

![](assets/image2014-9-25-15-3a17-3a58.png)

>[!NOTE]
>
>앞장 서! 경고의 URL에 만료 날짜가 있으므로 이러한 유형의 메시지를 지원하는 케이던스가 있는지 확인하십시오. 만료 날짜가 [관리자가 구성함](/help/marketo/product-docs/administration/settings/edit-link-expiration-in-reports-and-alerts.md)입니다.

다음 정보가 `{{SP_Send_Alert_Info}}`의 일부로 포함되어 있습니다.

* Marketo의 개인 세부 정보에 대한 링크로서의 이름 및 성
* CRM의 사용자에 대한 링크
* 경고를 보낸 Marketo의 캠페인 이름
* 경고가 전송된 시간입니다

>[!NOTE]
>
>CRM에 대한 링크는 해당 사용자가 CRM 시스템에 있는 경우에만 표시됩니다(현재 Dynamics CRM에서는 사용할 수 없음). 이 링크는 Marketo 사용자와 Marketo 사용자가 아닌 사용자 모두가 액세스할 수 있습니다.

## 이메일에 SP_Send_Alert_Info 토큰 추가 {#add-the-sp-send-alert-info-token-to-an-email}

1. 이메일을 선택하고 **초안 편집**&#x200B;을 클릭합니다.

   ![](assets/one-3.png)

1. 토큰을 추가할 편집 가능 영역을 두 번 클릭합니다.

   ![](assets/two-3.png)

1. 토큰을 넣을 위치에 커서를 놓은 다음 **토큰 삽입** 단추를 클릭합니다.

   ![](assets/three-3.png)

1. **`{{SP_Send_Alert_Info}}`** 토큰을 찾아 선택한 다음 **삽입**&#x200B;을 클릭합니다.

   ![](assets/image2014-9-25-15-3a19-3a11.png)

1. **저장**&#x200B;을 클릭합니다.

   ![](assets/image2014-9-25-15-3a19-3a24.png)

>[!NOTE]
>
>이메일 승인 잊지 마세요.

잘됐네! 이 토큰은 매우 유용하며 영업팀에 대해 생성하는 모든 경고에 사용해야 합니다.
