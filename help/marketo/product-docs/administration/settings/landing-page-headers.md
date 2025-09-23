---
description: 랜딩 페이지 헤더 - Marketo 문서 - 제품 설명서
title: 랜딩 페이지 헤더
exl-id: 58eaa0cd-2a2b-4abe-9180-f60a2a1dcc87
feature: Administration, Landing Pages
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '122'
ht-degree: 5%

---

# 랜딩 페이지 헤더 {#landing-page-headers}

랜딩 페이지 도메인에서 HTTP 헤더 중 일부를 사용자 지정하려면 아래 단계를 따르십시오.

1. Marketo에서 **[!UICONTROL Admin]**&#x200B;을(를) 클릭합니다.

   ![](assets/landing-page-headers-1.png)

1. **[!UICONTROL Landing Pages]**&#x200B;를 클릭합니다.

   ![](assets/landing-page-headers-2.png)

1. 랜딩 페이지 HTTP 헤더 옆의 **[!UICONTROL Edit]**&#x200B;을(를) 클릭합니다.

   ![](assets/landing-page-headers-3.png)

1. 원하는 설정을 선택하고 완료되면 **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

   ![](assets/landing-page-headers-4.png)

<table>
 <tr>
  <td><strong>[!UICONTROL Strict-Transport-Security]</strong></td>
  <td>이 항목을 사용하여 랜딩 페이지에 대한 연결이 항상 HTTPS를 통해 제공되도록 합니다(SSL로 보호된 랜딩 페이지를 사용하는 구독에 대해서만 설정해야 함).</td>
 </tr>
 <tr>
  <td><strong>[!UICONTROL X-Frame-Options]</strong></td>
  <td>Marketo Engage에서 호스팅하는 자산을 외부 웹 페이지에 포함할 수 있는지 여부를 정의할 수 있습니다</td>
 </tr>
</table>

>[!CAUTION]
>
>IT 팀과 함께 이러한 설정을 검토하여 조직의 정책을 설정해야 하는 사항을 결정하는 것이 중요합니다. 잘못된 설정으로 인해 일부 방문자가 랜딩 페이지에 액세스하지 못할 수 있습니다.
