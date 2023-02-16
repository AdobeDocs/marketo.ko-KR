---
unique-page-id: 2359918
description: 랜딩 페이지 설정 편집 - Marketo 문서 - 제품 설명서
title: 랜딩 페이지 설정 편집
exl-id: 019b4651-3a66-46f9-8722-66af30194380
source-git-commit: 07899e541b3624e99e0ead59d898ced2ab4e57af
workflow-type: tm+mt
source-wordcount: '259'
ht-degree: 0%

---

# 랜딩 페이지 설정 편집 {#edit-landing-page-settings}

도메인 이름 및 대체 페이지를 편집하고, 양식 미리 채우기를 활성화하거나 비활성화하고, 랜딩 페이지 오용을 방지할 수 있습니다. 방법은 다음과 같습니다.

>[!NOTE]
>
>**관리 권한 필요**

1. 로 이동합니다. **관리** 영역.

   ![](assets/edit-landing-page-settings-1.png)

1. 클릭 **랜딩 페이지**.

   ![](assets/edit-landing-page-settings-2.png)

1. 에서 **랜딩 페이지** 섹션을 클릭합니다. **편집**.

   ![](assets/edit-landing-page-settings-3.png)

1. 도메인 및 페이지 정보를 입력합니다.

   ![](assets/edit-landing-page-settings-4.png)

   | 용어 | 정의 |
   |---|---|
   | 랜딩 페이지의 도메인 이름 | CNAME입니다. CNAME은 랜딩 페이지에 대해 사용자에게 제공하는 URL의 첫 번째 부분입니다. 예, 에서 `https://go.yourCompany.com`를 검색하는 경우, &quot;go&quot;라는 단어는 CNAME입니다. 여러 개를 사용할 수 있지만 대부분의 사용자가 여러 개를 사용합니다. |
   | 대체 페이지 | 랜딩 페이지가 존재하지 않거나 다운된 경우 이 단계에서 이동해야 합니다. 추가 정보 [대체 페이지](/help/marketo/product-docs/administration/settings/set-a-fallback-page.md). |
   | 홈페이지 | 회사 사이트 URL을 입력합니다. |

1. 을(를) 확인합니다. **양식 미리 채우기** 알려진(쿠키) 사용자의 정보를 양식에 미리 채울 수 있도록 하는 확인란을 선택합니다. 블록의 선택을 취소합니다.

   ![](assets/edit-landing-page-settings-5.png)

1. 악성 사이트가 사용자의 콘텐츠를 호스팅하는 것처럼 보이지 않게 하려면 **Marketo 페이지를 외부 웹 페이지에 임베드할 수 없음** 확인란을 선택합니다.

   ![](assets/edit-landing-page-settings-6.png)

   >[!NOTE]
   >
   >미리 채우려면 `<script>` 태그에 다음 코드를 배치하십시오 `<head>` 태그에 있는 태그에서 **헤드 끝에 미리 채우기 스크립트 삽입** 상자. 맨 처음에 나타나도록 하려면 선택 취소하십시오.
   >
   >확인 **기본 favicon 링크 제거** Marketo이 favicon 링크를 코드에 삽입하지 못하도록 합니다.

1. 선택한 후 **저장.**

   ![](assets/edit-landing-page-settings-7.png)

   잘했어요! 이제 랜딩 페이지에 올바른 정보가 있으므로 바로 작업을 시작해야 합니다.
