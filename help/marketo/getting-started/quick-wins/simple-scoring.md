---
unique-page-id: 2359414
description: 단순 점수 - Marketo 문서 - 제품 설명서
title: 단순 채점
exl-id: 6129d46a-e6d2-4819-9b6c-ccbf37060712
source-git-commit: 74da8ebbd564b11e2795da31321ca47493135f48
workflow-type: tm+mt
source-wordcount: '369'
ht-degree: 0%

---

# 단순 채점 {#simple-scoring}

>[!PREREQUISITES]
>
>* [설정 및 사용자 추가](/help/marketo/getting-started/quick-wins/get-set-up-and-add-a-person.md){target="_blank"}
>* [양식이 있는 랜딩 페이지](/help/marketo/getting-started/quick-wins/landing-page-with-a-form.md){target="_blank"}


## 1단계: 채점 캠페인 만들기 {#step-create-a-scoring-campaign}

1. 로 이동 **[!UICONTROL 마케팅 활동]** 영역입니다.

   ![](assets/simple-scoring-1.png)

1. 을(를) 마우스 오른쪽 버튼으로 클릭합니다. **학습** 폴더 및 클릭 **[!UICONTROL 새 캠페인 폴더]**.

   ![](assets/simple-scoring-2.png)

1. 캠페인 폴더의 이름을 &quot;Scoring&quot;으로 지정하고 **[!UICONTROL 만들기]**.

   ![](assets/simple-scoring-3.png)

   >[!NOTE]
   >
   >채점 폴더가 이미 있는 경우 이 폴더의 이름을 채점 1과 같이 다르게 지정합니다. 폴더 이름은 고유해야 합니다.

1. 을(를) 마우스 오른쪽 버튼으로 클릭합니다. **채점** 폴더 및 선택 **[!UICONTROL 새 스마트 캠페인]**.

   ![](assets/simple-scoring-4.png)

1. 캠페인 이름을 &quot;점수 변경&quot;으로 지정하고 **[!UICONTROL 만들기]**.

   ![](assets/simple-scoring-5.png)

1. 다음을 클릭합니다. **[!UICONTROL 스마트 목록]** 탭.

   ![](assets/simple-scoring-6.png)

   사용자가 다음을 채울 때마다 이 캠페인을 실행하십시오. **체험판 요청 양식**.

1. 을(를) 찾아 드래그합니다. **[!UICONTROL 양식 작성]** 왼쪽 캔버스로 트리거합니다.

   ![](assets/simple-scoring-7.png)

1. 선택 **내 양식**.

   ![](assets/simple-scoring-8.png)

   >[!NOTE]
   >
   >을(를) 완료한 경우 [양식이 있는 랜딩 페이지](/help/marketo/getting-started/quick-wins/landing-page-with-a-form.md){target="_blank"} 빨리 이기세요, 양식이 있어야 합니다. 양식에 다른 이름을 사용한 경우 해당 이름을 선택합니다.

1. 다음을 클릭합니다. **[!UICONTROL 플로우]** 탭.

   ![](assets/simple-scoring-9.png)

1. 드래그 **점수 변경** 플로우 작업을 왼쪽 캔버스에 추가합니다.

   ![](assets/simple-scoring-10.png)

1. 개인의 점수에 추가할 값을 입력할 수 있습니다. 에 &quot;+5&quot;를 입력하겠습니다. **[!UICONTROL 변경]** 필드.

   ![](assets/simple-scoring-11.png)

   >[!TIP]
   >
   >좋은 점수 캠페인은 높은 품질의 인력을 영업에 제공하는 핵심입니다. 읽기 [**잠재 고객 점수에 대한 확실한 가이드**](https://www.marketo.com/definitive-guides/lead-scoring/){target="_blank"}.

1. 다음을 클릭합니다. **[!UICONTROL 예약]** 탭 및 **[!UICONTROL 활성화]** 단추를 클릭합니다.

   ![](assets/simple-scoring-12.png)

1. 클릭 **[!UICONTROL 활성화]** 확인 화면에서 다음을 수행합니다.

   ![](assets/simple-scoring-13.png)

>[!NOTE]
>
>활성화하면 이 캠페인은 사용자가 양식을 작성할 때마다 실행됩니다. 캠페인은 비활성화될 때까지 계속 실행됩니다.

## 2단계: 양식 작성 {#step-fill-out-the-form}

1. 에서 만든 랜딩 페이지 선택 [양식이 있는 랜딩 페이지](/help/marketo/getting-started/quick-wins/landing-page-with-a-form.md){target="_blank"} 빨리 이겼어요

   ![](assets/simple-scoring-14.png)

1. 클릭 **[!UICONTROL 미리 보기]**. 랜딩 페이지가 새 탭에서 열립니다.

   ![](assets/simple-scoring-15.png)

1. 이름, 성 및 이메일 주소로 양식을 작성한 다음 **[!UICONTROL 제출]**.

   ![](assets/simple-scoring-16.png)

   >[!NOTE]
   >
   >처음 인물로 입력했을 때 사용한 것과 동일한 이름과 이메일 주소를 사용하여 &quot;+5&quot; 점수 상승을 적용합니다.

## 3단계: 개인 정보 보기 {#step-view-the-person-info}

1. 로 이동 **[!UICONTROL 데이터베이스]** 영역입니다.

   ![](assets/simple-scoring-17.png)

1. 양식을 작성할 때 사용한 이메일 주소를 검색합니다.

   ![](assets/simple-scoring-18.png)

1. 사용자를 두 번 클릭합니다.

   ![](assets/simple-scoring-19.png)

개인 세부 정보가 새 탭 또는 창에 열립니다. 양식을 작성하는 데 있어서 점수가 5점 상승한 것을 알 수 있습니까?

![](assets/simple-scoring-20.png)

## 임무 완료! {#mission-complete}

<br> 

[◄ 미션 2: 양식이 포함된 랜딩 페이지](/help/marketo/getting-started/quick-wins/landing-page-with-a-form.md)

[미션 4: 이메일 자동 응답 ►](/help/marketo/getting-started/quick-wins/email-auto-response.md)
