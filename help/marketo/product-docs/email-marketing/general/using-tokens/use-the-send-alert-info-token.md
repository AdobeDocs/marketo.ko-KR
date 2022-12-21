---
unique-page-id: 2952678
description: 경고 정보 토큰 보내기 사용 {{SP_Send_Alert_Info}} - Marketo 문서 - 제품 설명서
title: 경고 정보 토큰 보내기 사용
exl-id: 950eb4d1-35d5-4e5c-9624-a38284bff987
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '260'
ht-degree: 0%

---

# 경고 정보 토큰 보내기 사용 {#use-the-send-alert-info-token-sp-send-alert-info}

다음 `{{SP_Send_Alert_Info}}` 토큰은 영업 팀에 대한 경고 이메일을 만들 때 사용할 특별 토큰입니다.

>[!TIP]
>
>이 토큰은 토큰이 포함된 이메일을 [경고 보내기](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/send-alert.md) 흐름 단계. 이메일 보내기 흐름 단계에서 사용하면 작동하지 않습니다.

경고 예:

![](assets/image2014-9-25-15-3a17-3a58.png)

>[!NOTE]
>
>고개 들어! 경고의 URL에는 만료 날짜가 있으므로 이러한 유형의 메시지를 지원하는 케이던스가 있는지 확인하십시오. 만료 날짜는 다음과 같습니다 [관리자가 구성](/help/marketo/product-docs/administration/settings/edit-link-expiration-in-reports-and-alerts.md).

다음 정보는 `{{SP_Send_Alert_Info}}`:

* Marketo의 개인 세부 사항에 대한 링크로서 이름 및 성
* CRM에서 사용자에 대한 링크
* 경고를 보낸 Marketo의 캠페인 이름
* 경고를 보낸 시간

>[!NOTE]
>
>CRM에 연결된 링크는 사용자가 CRM 시스템(현재 Dynamics CRM에서는 사용할 수 없음)에 있는 경우에만 나타납니다. 링크는 Marketo 사용자와 Marketo 사용자가 아닌 사용자 모두가 액세스할 수 있습니다.

## 전자 메일에 SP_Send_Alert_Info 토큰 추가 {#add-the-sp-send-alert-info-token-to-an-email}

1. 이메일을 선택하고 을(를) 클릭합니다 **초안 편집**.

   ![](assets/one-3.png)

1. 토큰을 추가할 편집 가능한 영역을 두 번 클릭합니다.

   ![](assets/two-3.png)

1. 토큰을 지정할 위치에 커서를 놓고 **토큰 삽입** 버튼을 클릭합니다.

   ![](assets/three-3.png)

1. 을(를) 찾아 선택합니다 **`{{SP_Send_Alert_Info}}`** 토큰을 선택하고 를 클릭합니다. **삽입**.

   ![](assets/image2014-9-25-15-3a19-3a11.png)

1. 클릭 **저장**.

   ![](assets/image2014-9-25-15-3a19-3a24.png)

>[!NOTE]
>
>이메일 승인 잊지 마십시오.

잘했어요! 이 토큰은 매우 유용하며 영업 팀을 위해 만든 모든 경고에서 이 토큰을 사용해야 합니다.
