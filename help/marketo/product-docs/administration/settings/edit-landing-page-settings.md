---
unique-page-id: 2359918
description: 랜딩 페이지 설정 편집 - Marketo 문서 - 제품 설명서
title: 랜딩 페이지 설정 편집
exl-id: 019b4651-3a66-46f9-8722-66af30194380
feature: Administration, Landing Pages
source-git-commit: 26573c20c411208e5a01aa7ec73a97e7208b35d5
workflow-type: tm+mt
source-wordcount: '203'
ht-degree: 2%

---

# 랜딩 페이지 설정 편집 {#edit-landing-page-settings}

도메인 이름과 대체 페이지를 편집하고, 양식 미리 채우기를 활성화하거나 비활성화하고, 랜딩 페이지의 오용을 방지하는 등의 작업을 수행할 수 있습니다. 방법은 다음과 같습니다.

>[!NOTE]
>
>**관리자 권한 필요**

1. **[!UICONTROL Admin]** 영역으로 이동합니다.

   ![](assets/edit-landing-page-settings-1.png)

1. **[!UICONTROL Landing Pages]**&#x200B;을(를) 클릭합니다.

   ![](assets/edit-landing-page-settings-2.png)

1. **[!UICONTROL Landing Pages]** 섹션에서 **[!UICONTROL Edit]**&#x200B;을(를) 클릭합니다.

   ![](assets/edit-landing-page-settings-3.png)

1. 도메인 및 페이지 정보를 입력합니다.

   ![](assets/edit-landing-page-settings-4.png)

   | 용어 | 정의 |
   |---|---|
   | [!UICONTROL Domain name for landing pages] | CNAME입니다. CNAME은 랜딩 페이지에 사용자에게 제공하는 URL의 첫 번째 부분입니다. 예를 들어 `https://go.yourCompany.com`에서 &quot;go&quot;라는 단어는 CNAME입니다. 여러 개를 사용할 수 있지만 대부분의 사용자는 하나를 사용합니다. |
   | [!UICONTROL Fallback page] | 랜딩 페이지가 없거나 다운된 경우 이 위치로 이동해야 합니다. [대체 페이지](/help/marketo/product-docs/administration/settings/set-a-fallback-page.md)에 대해 자세히 알아보세요. |
   | [!UICONTROL Homepage] | 회사 사이트 URL을 입력합니다. |

1. **[!UICONTROL Form Prefill]** 확인란을 선택하여 알려진(쿠키) 사용자에 대한 정보를 양식에 미리 채울 수 있도록 합니다. 차단하려면 선택을 취소합니다.

   ![](assets/edit-landing-page-settings-5.png)

   >[!NOTE]
   >
   >미리 채우기 `<script>` 태그가 코드의 `<head>` 태그 끝에 표시되도록 하려면 **[!UICONTROL Inject Prefill Script at End of Head]** 상자를 선택합니다. 시작 부분에 표시하려면 선택하지 않은 상태로 둡니다.
   >
   >Marketo에서 패비콘 링크를 코드에 삽입하지 못하도록 하려면 **[!UICONTROL Remove default favicon links]**&#x200B;을(를) 선택합니다.

1. 선택한 후 **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

   ![](assets/edit-landing-page-settings-6.png)

   좋습니다! 이제 랜딩 페이지에 올바른 정보가 있으므로 즉시 작업을 시작해야 합니다.
