---
unique-page-id: 2953188
description: 필터 유추 - Marketo 문서 - 제품 설명서
title: 필터 유추
exl-id: 6db4ff4d-7fab-4722-94b1-1bf92ba4651d
feature: Smart Lists
source-git-commit: 8a5903fa5313e34f448f833f20ab8e3624cf23e6
workflow-type: tm+mt
source-wordcount: '198'
ht-degree: 0%

---

# 필터 유추 {#inferred-filters}

누군가가 귀하의 웹 사이트를 방문할 때, [먼치킨](/help/marketo/product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website.md){target="_blank"} 쿠키를 만들어 시스템에 넣습니다. 우리는 특별한 데이터베이스에서 그들의 IP를 찾고 모든 종류의 좋은 정보를 추론한다.

>[!NOTE]
>
>유추된 필드 값이 최신 상태를 유지하도록 IP 주소 조회에 사용되는 데이터베이스를 주기적으로 업데이트합니다. 데이터베이스 업데이트로 인해 스마트 목록 필터 정의에 추가해야 할 수 있는 유추된 새 필드 값이 도입될 수 있습니다.
>
>다음 기간 동안 데이터베이스 업데이트가 발생할 수 있음: [Marketo Engage 제품 릴리스](/help/marketo/release-notes/release-schedule.md){target="_blank"}. When an update does occur, the [Marketo Engage release notes](/help/marketo/release-notes/current.md){target="_blank"} 유추된 필드 값의 변경 사항에 대한 설명이 포함됩니다.

![](assets/image2015-4-27-13-3a25-3a46.png)

![](assets/image2015-4-27-16-3a58-3a53.png)

![](assets/image2015-4-27-16-3a59-3a35.png)

![](assets/image2015-4-27-17-3a0-3a12.png)

![](assets/image2015-4-27-13-3a36-3a9.png)

![](assets/image2015-4-27-13-3a30-3a48.png)

스마트 목록에서 이러한 필터를 사용하면 이러한 추론된 정보가 있는 사용자에게 결과가 표시됩니다.

>[!TIP]
>
>웹 활동 보고서에서 이러한 필터를 사용합니다. Sales Rep 의 영역을 사용하여 지난 24 시간 동안 웹 사이트 방문자가 있는 Custom Daily Report 를 구독합니다. 그들은 그것을 좋아할 것입니다!
>
>* 방문한 웹 페이지 - 지난 24시간
>* 상태 유추: [영역 선택]

이러한 익명 방문자는 이메일 링크를 클릭하거나 양식을 작성할 때 자동으로 사용자로 변환됩니다. 그러나, 그들은 추론된 모든 정보를 보관한다.

>[!NOTE]
>
>자세히 알아보기 [익명 활동 및 리드](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/understanding-anonymous-activity-and-people.md){target="_blank"}.
