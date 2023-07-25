---
unique-page-id: 2359918
description: 랜딩 페이지 설정 편집 - Marketo 문서 - 제품 설명서
title: 랜딩 페이지 설정 편집
exl-id: 019b4651-3a66-46f9-8722-66af30194380
feature: Administration, Landing Pages
source-git-commit: 02b2e39580c5eac63de4b4b7fdaf2a835fdd4ba5
workflow-type: tm+mt
source-wordcount: '259'
ht-degree: 0%

---

# 랜딩 페이지 설정 편집 {#edit-landing-page-settings}

도메인 이름과 대체 페이지를 편집하고, 양식 미리 채우기를 활성화하거나 비활성화하고, 랜딩 페이지의 오용을 방지하는 등의 작업을 수행할 수 있습니다. 방법은 다음과 같습니다.

>[!NOTE]
>
>**관리자 권한 필요**

1. 로 이동 **[!UICONTROL 관리자]** 영역입니다.

   ![](assets/edit-landing-page-settings-1.png)

1. 클릭 **[!UICONTROL 랜딩 페이지]**.

   ![](assets/edit-landing-page-settings-2.png)

1. 다음에서 **[!UICONTROL 랜딩 페이지]** 섹션, 클릭 **[!UICONTROL 편집]**.

   ![](assets/edit-landing-page-settings-3.png)

1. 도메인 및 페이지 정보를 입력합니다.

   ![](assets/edit-landing-page-settings-4.png)

   | 용어 | 정의 |
   |---|---|
   | [!UICONTROL 랜딩 페이지의 도메인 이름] | CNAME입니다. CNAME은 랜딩 페이지에 사용자에게 제공하는 URL의 첫 번째 부분입니다. 예를 들어, `https://go.yourCompany.com`, &quot;go&quot;라는 단어는 CNAME입니다. 여러 개를 사용할 수 있지만 대부분의 사용자는 하나를 사용합니다. |
   | [!UICONTROL 대체 페이지] | 랜딩 페이지가 없거나 다운된 경우 이 위치로 이동해야 합니다. 자세히 알아보기 [대체 페이지](/help/marketo/product-docs/administration/settings/set-a-fallback-page.md). |
   | [!UICONTROL 홈페이지] | 회사 사이트 URL을 입력합니다. |

1. 다음 확인: **[!UICONTROL 양식 미리 채우기]** 확인란을 선택하여 알려진(쿠키) 사용자의 정보를 양식에 미리 채울 수 있습니다. 차단하려면 선택을 취소합니다.

   ![](assets/edit-landing-page-settings-5.png)

1. 악성 사이트가 콘텐츠를 호스팅하지 못하도록 하려면 **[!UICONTROL Marketo 페이지를 외부 웹 페이지에 포함할 수 없음]** 확인란.

   ![](assets/edit-landing-page-settings-6.png)

   >[!NOTE]
   >
   >미리 채우기를 원하는 경우 `<script>` 태그 끝에 표시 `<head>` 코드에서 태그를 지정한 경우 **[!UICONTROL 헤드 끝에 미리 채우기 스크립트 삽입]** 상자. 시작 부분에 표시하려면 선택하지 않은 상태로 둡니다.
   >
   >확인 **[!UICONTROL 기본 favicon 링크 제거]** Marketo이 패비콘 링크를 코드에 삽입하지 못하도록 하려는 경우.

1. 선택한 후 다음을 클릭합니다. **[!UICONTROL 저장]**.

   ![](assets/edit-landing-page-settings-7.png)

   잘했어! 이제 랜딩 페이지에 올바른 정보가 있으므로 즉시 작업을 시작해야 합니다.
