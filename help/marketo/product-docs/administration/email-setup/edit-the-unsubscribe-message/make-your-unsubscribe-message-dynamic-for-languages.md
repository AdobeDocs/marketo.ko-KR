---
unique-page-id: 6848782
description: 언어 - Marketing To Docs - 제품 설명서를 통해 구독 취소 메시지를 동적으로 만들기
title: 언어를 지원하는 구독 취소 메시지를 동적으로 만들기
translation-type: tm+mt
source-git-commit: 5c9683c6b00ccbf9e9d606fd4513432c9872ad00
workflow-type: tm+mt
source-wordcount: '548'
ht-degree: 0%

---


# 언어를 지원하는 구독 취소 메시지를 동적으로 만들기 {#make-your-unsubscribe-message-dynamic-for-languages}

>[!NOTE]
>
>**FYI**
>
>Marketing은 이제 모든 구독 간의 언어를 표준화하므로 구독에 리드/리드 및 docs.markto.com에 있는 사람/사람을 볼 수 있습니다. 이 용어는 같은 것을 의미한다.아티클 지침에는 영향을 주지 않습니다. 다른 변화도 있습니다 [자세한](http://docs.marketo.com/display/DOCS/Updates+to+Marketo+Terminology)내용

기본 구독 취소 메시지와 링크는 영어로 제공됩니다. 동적 컨텐츠를 사용하여 다른 언어로 표시할 수 있습니다.

>[!NOTE]
>
>아래 튜토리얼을 통해 유용한 정보를 얻을 수 있습니다. 이는 모범 사례지만 다른 방법으로 이루어질 수 있다.

1. 데이터 준비
1. [&quot;기본](../../../../product-docs/administration/field-management/create-a-custom-field-in-marketo.md)언어&quot;라는 사용자 정의 필드를 만듭니다. 이 필드를 동기화하려면 CRM에서 설정합니다.

   >[!TIP]
   >
   >나중에 양식을 [만들어 언어 기본 설정을 캡처할](../../../../product-docs/demand-generation/forms/creating-a-form/create-a-form.md) 때 이 필드를 사용하십시오.

1. 세그멘테이션 만들기
1. 데이터베이스로 **이동합니다**.** ![](assets/db.png)

   **

1. 새로 **만들기** 드롭다운에서 **새 세그멘테이션을 클릭합니다**.

   ![](assets/two.png)

1. 세그멘테이션의 이름을 **기본 언어로 지정합니다**. 세그먼트 **추가를 클릭합니다**. 언어 입력

   ![](assets/image2015-3-9-8-3a33-3a44.png)

   >[!NOTE]
   >
   >기본 세그먼트는 영문입니다.

1. 모든 언어가 표시될 때까지 세그먼트를 계속 추가합니다. 만들기를 **클릭합니다**.

   ![](assets/image2015-3-9-8-3a38-3a5.png)

1. 세그먼트를 선택합니다.

   ![](assets/image2015-3-9-8-3a38-3a17.png)

1. 스마트 목록 **탭으로** 이동합니다. 검색 **필드에 기본 언어** 를 입력합니다. 필터를 캔버스에 드래그하여 놓습니다.

   ![](assets/six.png)

1. 해당 언어를 설정합니다.

   ![](assets/seven.png)

1. 다른 모든 언어로 반복합니다. 그런 다음 **세그멘테이션 작업** 드롭다운을 선택하고 승인을 **클릭합니다**.

   ![](assets/image2015-3-9-8-3a39-3a36.png)

1. 코드 조각 만들기
1. Design **Studio로 이동합니다**.

   ![](assets/ds.png)

1. [ **새로 만들기** ] 드롭다운에서 **새 코드 조각을 클릭합니다**.

   ** ![](assets/ten.png)

   **

1. 코드 조각 이름을 **구독 취소 메시지**. 만들기를 **클릭합니다**.

   ![](assets/image2015-3-9-8-3a40-3a54.png)

1. 기본 구독 취소 메시지를 입력하고 강조 표시한 다음 하이퍼링크 아이콘을 클릭합니다.

   ![](assets/image2015-3-9-8-3a41-3a47.png)

1. 이 토큰을 복사하고 붙여 넣습니다. **`{{system.unsubscribeLink}}`** 을 **클릭합니다** . 삽입을 **클릭합니다**.

   ![](assets/image2015-3-9-8-3a43-3a17.png)

1. 세그멘테이션 **섹션에서** 세그먼트 기준 을 선택합니다.

   ![](assets/image2015-3-9-8-3a44-3a16.png)

1. 세그멘테이션 드롭다운에서 기본 **언어** 를 입력하고 기본 **언어를 선택합니다**. 저장을 **클릭합니다**.

   ![](assets/image2015-3-9-8-3a44-3a32.png)

1. 트리에서 세그먼트를 선택합니다. 구독 취소 메시지를 해당 언어로 입력합니다.

   ![](assets/image2015-3-9-8-3a45-3a43.png)

1. 동일한 토큰 복사 및 붙여넣기: **`{{system.unsubscribeLink}}`** 을 **클릭합니다** . 삽입을 **클릭합니다**.

   ![](assets/image2015-3-9-8-3a47-3a4.png)

1. 모든 세그먼트에 대해 반복합니다. 그런 다음 Design Studio로 돌아가 코드 조각 작업 **** 드롭다운을 클릭하고 승인을 **클릭합니다**.

   ![](assets/image2015-3-9-8-3a47-3a34.png)

   멋지네요 거의 다 왔어

1. 이메일에 코드 조각 사용
1. 이메일 편집기 내에서 편집 가능한 요소를 클릭합니다. 톱니바퀴 아이콘을 클릭하고 코드 조각으로 **바꾸기를 선택합니다**. 편집 가능한 조각 요소를 선택하는 경우 톱니바퀴 아이콘을 클릭하고 편집을 **선택합니다**.

   ![](assets/4.1.png)

1. 드롭다운에서 코드 조각을 찾아 선택하고 저장을 **클릭합니다**.

   ![](assets/image2015-3-9-8-3a50-3a16.png)

1. 테스트하려면 **뒤로**..

   ![](assets/4.3.png)

1. ...그런 다음 **동적** 탭을 클릭합니다.

   ![](assets/4.4.png)

1. 다른 언어를 클릭하여 코드 조각 변경을 확인합니다.

   ![](assets/4.5.png)

   >[!TIP]
   >
   >물론 나머지 이메일도 동적 언어로 편집할 수 있습니다. 가입 해지 페이지와 동일한 방법을 사용하십시오.

1. 동적 콘텐츠로 가입 해지 페이지 사용자 지정

   사람들이 원하는 언어로 가입 해지 페이지를 방문하게 하려면 랜딩 페이지와 확인 페이지에서 동적 컨텐츠를 사용할 수 있습니다.

   Design Studio로 이동합니다.

   ![](assets/ds.png)

   검색 필드에 가입 해지를 입력합니다. 구독 취소 페이지를 찾아야 합니다.

   ![](assets/image2015-3-9-8-3a51-3a53.png)

   초안 편집을 클릭합니다.

   ![](assets/image2015-3-9-8-3a52-3a23.png)

   세그먼트 기준 을 선택합니다.

   ![](assets/image2015-3-9-8-3a52-3a57.png)

   기본 언어 세그먼트를 찾습니다. 저장을 클릭합니다.

   ![](assets/image2015-3-9-8-3a53-3a54.png)

   각 랜딩 페이지에 대한 컨텐츠를 편집하고 승인하면 됩니다.

   >[!NOTE]
   >
   >**딥 다이브**
   >
   >
   >다이내믹한 컨텐츠 [](../../../../product-docs/personalization/segmentation-and-snippets/segmentation/understanding-dynamic-content.md) 및 멋진 작업에 대한 자세한 내용을 살펴볼 수 있습니다.

