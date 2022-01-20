---
description: 랜딩 페이지 머리글 - Marketo 문서 - 제품 설명서
title: 랜딩 페이지 머리글
exl-id: 58eaa0cd-2a2b-4abe-9180-f60a2a1dcc87
source-git-commit: 05129f546cf2ba0df5c608485adf73c26d4b4f1e
workflow-type: tm+mt
source-wordcount: '129'
ht-degree: 0%

---

# 랜딩 페이지 머리글 {#landing-page-headers}

랜딩 페이지 도메인에서 HTTP 헤더 중 일부를 사용자 지정하려면 아래 단계를 따르십시오.

1. Marketo에서 **관리**.

   ![](assets/landing-page-headers-1.png)

1. 클릭 **랜딩 페이지**.

   ![](assets/landing-page-headers-2.png)

1. 클릭 **편집** ( 랜딩 페이지 HTTP 헤더) 옆에 있습니다.

   ![](assets/landing-page-headers-3.png)

1. 원하는 설정을 선택하고 를 클릭합니다 **저장** 완료 시.

   ![](assets/landing-page-headers-4.png)

<table>
 <tr>
  <td><strong>Strict-Transport-Security</strong></td>
  <td>이 옵션을 사용하면 랜딩 페이지에 대한 연결이 항상 HTTPS를 통해 제공될 것임을 보장합니다(SSL로 보호되는 랜딩 페이지를 구독에 대해서만 설정되어야 함)</td>
 </tr>
 <tr>
  <td><strong>X-Frame-Options</strong></td>
  <td>호스팅된 자산을 외부 웹 페이지에 포함할 수 있는지 여부를 정의할 수 있습니다</td>
 </tr>
</table>

>[!CAUTION]
>
>IT 팀과 함께 이러한 설정을 검토하여 조직의 정책을 어느 것으로 설정해야 하는지 결정하는 것이 중요합니다. 설정이 잘못되면 일부 방문자가 랜딩 페이지에 액세스하지 못할 수 있습니다.
