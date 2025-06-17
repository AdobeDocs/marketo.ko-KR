---
unique-page-id: 11377395
description: 추가 브랜딩 도메인 추가 - Marketo 문서 - 제품 설명서
title: 추가 브랜딩 도메인 추가
exl-id: df6e5afe-dbb0-4fbe-bf06-79d92a91b986
feature: Email Setup
source-git-commit: dafac137a6c626794f3b9b2bfaa2fc2de9f2cb75
workflow-type: tm+mt
source-wordcount: '598'
ht-degree: 0%

---

# 추가 브랜딩 도메인 추가 {#add-an-additional-branding-domain}

단일 Marketo 인스턴스에서 여러 브랜드를 실행하고 각 브랜드마다 고유한 브랜드 추적 링크를 원하는 경우 추가 브랜딩 도메인을 추가합니다.

>[!PREREQUISITES]
>
>브랜드 도메인을 추가하기 전에 일반 추적 링크를 [브랜드 도메인으로 바꾸기](/help/marketo/product-docs/administration/email-setup/add-multiple-branding-domains/edit-your-default-branding-domain.md){target="_blank"}해야 합니다.

1. **[!UICONTROL Admin]** 영역으로 이동합니다.

   ![](assets/add-an-additional-branding-domain-1.png)

1. **[!UICONTROL Email]**&#x200B;을(를) 클릭합니다.

   ![](assets/add-an-additional-branding-domain-2.png)

1. 브랜딩 도메인을 추가하려면 **[!UICONTROL Add]**&#x200B;을(를) 클릭하십시오.

   ![](assets/add-an-additional-branding-domain-3.png)

1. 새 브랜딩 도메인의 이름을 입력하고 _기본 도메인 만들기_ 및/또는 _SSL 인증서 생성_(둘 다 선택 사항)을 선택한 다음 **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

   ![](assets/add-an-additional-branding-domain-4.png)

>[!NOTE]
>
>* _주 도메인으로 설정_: 주 도메인과 기존의 모든 미전송 전자 메일을 &quot;기본값&quot;으로 설정하고 새로 만든 모든 전자 메일은 기본적으로 주 도메인으로 설정됩니다. [전자 메일을 기준으로 덮어쓸 수 있습니다](/help/marketo/product-docs/administration/email-setup/add-multiple-branding-domains/overwrite-primary-domain-for-emails.md){target="_blank"}.
>
>* _SSL 인증서 생성_: 도메인 생성으로 SSL(Secure Sockets Layer)을 만들 수 있습니다. 첫 번째 추적 도메인은 몇 시간이 걸릴 수 있는 인프라 1회 설정을 시작합니다. 완료 시 알림이 전송되며 첫 번째 도메인을 설정할 수 있습니다. 기존 도메인에 SSL을 추가하려면 [Marketo 지원](https://nation.marketo.com/t5/support/ct-p/Support){target="_blank"}에 문의하세요.

## 오류 메시지 {#error-messages}

<table><thead>
  <tr>
    <th>오류</th>
    <th>세부 사항</th>
  </tr></thead>
<tbody>
  <tr>
    <td><i>도메인을 생성하는 도중 예기치 않은 오류가 발생했습니다. 도움이 필요하면 지원 센터에 문의하십시오.</i></td>
    <td>예기치 않은 오류가 발생했습니다. 로그와 오류 세부 정보를 수집하고 문제를 <a href="https://nation.marketo.com/t5/support/ct-p/Support" target="_blank">Marketo 지원</a>(으)로 에스컬레이션하십시오.</td>
  </tr>
  <tr>
    <td><i>SSL 인증서가 이미 발급되었습니다.</i></td>
    <td>이 사용자 정의 도메인에 대한 SSL 인증서가 이미 있습니다. 인증서가 만료되었거나 다시 발급해야 하는 경우가 아니면 추가 작업이 필요하지 않습니다.</td>
  </tr>
  <tr>
    <td><i>도메인이 기본 도메인에 매핑되지 않습니다.</i></td>
    <td>사용자 정의 도메인이 기본 도메인에 올바르게 매핑되지 않습니다. 도메인 매핑 설정을 확인하고 DNS 구성이 올바른 기본 도메인을 가리켜야 합니다.</td>
  </tr>
  <tr>
    <td><i>Cloudflare 설정이 시작되었습니다. 나중에 다시 시도하십시오.</i></td>
    <td>인스턴스에 대한 첫 번째 추적 도메인을 만들면 Cloudfare에서 일회성 인프라 설정이 발생합니다. 이 메시지는 설치가 시작되었음을 나타내며 최대 3시간 정도 소요될 수 있습니다.</td>
  </tr>
  <tr>
    <td><i>Cloudflare 설정이 아직 진행 중입니다. 나중에 다시 시도하십시오.</i></td>
    <td>위 참조</td>
  </tr>
  <tr>
    <td><i>예기치 않은 오류로 인해 Cloudflare를 설정하지 못했습니다. 고객 지원 센터에 문의하십시오.</i></td>
    <td>초기 Cloudfare 인프라 설정에 실패했습니다. 도움이 필요하면 <a href="https://nation.marketo.com/t5/support/ct-p/Support" target="_blank">Marketo 지원</a>에 문의하십시오.</td>
  </tr>
</tbody></table>

## 참고할 사항 {#things-to-note}

* **Marketo Engage에 대한 도메인에 대한 DNS 매핑**: UI에 도메인을 추가하기 전에 CNAME을 Marketo 제공 도메인에 매핑[&#128279;](https://experienceleague.adobe.com/ko/docs/marketo/using/getting-started/initial-setup/setup-steps#customize-your-landing-page-urls-with-a-cname){target="_blank"}해야 합니다.

* **사용자 지정 SSL**: 사용자 지정 SSL이 필요한 경우 [지원 티켓](https://nation.marketo.com/t5/support/ct-p/Support){target="_blank"}을 제출하세요. SSL 생성을 위해 셀프서비스 확인란을 사용하지 마십시오.

* **기존 SSL**: 도메인을 추가하는 동안 시스템은 이전에 수동으로 생성했을 수 있는 기존 SSL을 확인합니다. 이 유효성 검사가 발생하면 SSL 생성을 선택하지 않고 도메인을 생성하면 자동으로 연결됩니다. [지원 센터에 문의](https://nation.marketo.com/t5/support/ct-p/Support){target="_blank"} 추가 세부 정보/옵션을 제공합니다.

* **처음 추적 도메인**: 전자 메일 추적 링크 도메인을 처음 만드는 경우 [Marketo 지원](https://nation.marketo.com/t5/support/ct-p/Support){target="_blank"}에서 수동으로 조작해야 합니다. UI에서는 동일한 도메인 아래에 후속 하위 도메인을 만들 수 있습니다.

* **기존 도메인에 인증서를 추가**: 기존 도메인에 인증서를 추가하는 것은 현재 지원되지 않습니다. 기존 도메인의 경우 또는 SSL 인증서 상자를 확인하지 못한 경우의 경우 인증서를 추가하려면 [Marketo 지원](https://nation.marketo.com/t5/support/ct-p/Support){target="_blank"}에 연결해야 합니다.

* **기존 도메인에서 인증서 편집 또는 제거**: 기존 SSL을 업데이트하거나 제거해야 하는 경우 [Marketo 지원](https://nation.marketo.com/t5/support/ct-p/Support){target="_blank"}에 문의하십시오.

* **도메인 삭제**: 현재 도메인을 삭제해도 SSL 인증서가 자동으로 삭제되지 않습니다. 이 문제는 향후 릴리스에서 해결될 예정입니다.

>[!MORELIKETHIS]
>
>[기본 브랜딩 도메인 편집](/help/marketo/product-docs/administration/email-setup/add-multiple-branding-domains/edit-your-default-branding-domain.md){target="_blank"}
