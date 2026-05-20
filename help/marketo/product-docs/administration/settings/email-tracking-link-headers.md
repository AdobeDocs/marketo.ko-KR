---
description: HTTPS에 대한 Strict-Transport-Security를 포함하여 이메일 아래의 관리에서 IT 검토 지침을 사용하여 이메일 추적 링크 헤더를 맞춤화하는 방법.
title: 이메일 추적 링크 헤더
exl-id: 2db1f1b3-3afe-4710-a8b1-b06fbf09ec8c
feature: Administration
TQID: https://experienceleague.adobe.com/myoUsAnpIvAZVY-ar4iQl9xDHr886vAH-l0YXtM1mfg
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
feature_v2:
  - id: d1d0a9cd-295d-4976-8c39-ddae266f240e
topic_v2:
  - id: d095671a-1355-40aa-8b5f-06c33c68080b
  - id: eddd9b14-83bd-4ff4-9072-54a4a484abb7
source-git-commit: a526f0bf4cbdf888b1c4462ba35dd2bc92316527
workflow-type: tm+mt
source-wordcount: 115
ht-degree: 7%

---

# 이메일 추적 링크 헤더 {#email-tracking-link-headers}

전자 메일 추적 링크 헤더를 사용자 지정하려면 아래 단계를 따르십시오.

1. Marketo에서 **[!UICONTROL Admin]**&#x200B;을(를) 클릭합니다.

   ![](assets/email-tracking-link-headers-1.png)

1. **[!UICONTROL Email]**&#x200B;를 클릭합니다.

   ![](assets/email-tracking-link-headers-2.png)

1. Custom Header Options로 스크롤합니다. 원하는 설정을 선택하고 **[!UICONTROL Save Changes]**&#x200B;을(를) 클릭합니다.

   ![](assets/email-tracking-link-headers-3.png)

<table>
 <tr>
  <td><strong>엄격한 전송 보안</strong></td>
  <td>이 옵션을 사용하여 추적 링크가 항상 HTTPS를 통해 제공되도록 보장(SSL로 보호되는 추적 링크가 있는 구독에만 설정되어야 함)</td>
 </tr>
</table>

>[!CAUTION]
>
>IT 팀과 함께 이러한 설정을 검토하여 조직의 정책을 설정해야 하는 사항을 결정하는 것이 중요합니다. 잘못된 설정으로 인해 일부 방문자가 이메일 링크에 액세스하지 못할 수 있습니다.
