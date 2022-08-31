---
unique-page-id: 2359414
description: 단순 점수 - Marketo 문서 - 제품 설명서
title: 단순 점수 책정
exl-id: 6129d46a-e6d2-4819-9b6c-ccbf37060712
source-git-commit: 89ee01fb25e7bc406c198c8e89e6957b3b1e1928
workflow-type: tm+mt
source-wordcount: '379'
ht-degree: 0%

---

# 단순 점수 책정 {#simple-scoring}

>[!PREREQUISITES]
>
>* [설정 및 개인 추가](/help/marketo/getting-started/quick-wins/get-set-up-and-add-a-person.md){target=&quot;_blank&quot;}
>* [양식이 있는 랜딩 페이지](/help/marketo/getting-started/quick-wins/landing-page-with-a-form.md){target=&quot;_blank&quot;}


## 1단계: 점수 책정 캠페인 만들기 {#step-create-a-scoring-campaign}

1. 로 이동합니다. **마케팅 활동** 영역.

   ![](assets/simple-scoring-1.png)

1. 마우스 오른쪽 단추 클릭 **학습** 폴더를 클릭한 다음 **새 캠페인 폴더**.

   ![](assets/simple-scoring-2.png)

1. 캠페인 폴더 이름을 &quot;점수 책정&quot;으로 지정하고 을 클릭합니다 **만들기**.

   ![](assets/simple-scoring-3.png)

   >[!NOTE]
   >
   >채점 폴더가 이미 있는 경우 채점 1과 같이 다른 이름으로 지정합니다. 폴더 이름은 고유해야 합니다.

1. 마우스 오른쪽 단추 클릭 **점수 책정** 폴더를 선택하고 **새로운 스마트 캠페인**.

   ![](assets/simple-scoring-4.png)

1. 캠페인 이름을 &quot;Change Score&quot;로 지정하고 **만들기**.

   ![](assets/simple-scoring-5.png)

1. 을(를) 클릭합니다. **Smart List** 탭.

   ![](assets/simple-scoring-6.png)

   사용자가 다음 작업을 수행할 때마다 이 캠페인을 실행하려고 합니다 **체험판 요청 양식**.

1. 을(를) 찾아 드래그합니다. **양식 채우기** 왼쪽 캔버스에 트리거합니다.

   ![](assets/simple-scoring-7.png)

1. 선택 **내 양식**.

   ![](assets/simple-scoring-8.png)

   >[!NOTE]
   >
   >을(를) 완료한 경우 [양식이 있는 랜딩 페이지](/help/marketo/getting-started/quick-wins/landing-page-with-a-form.md){target=&quot;_blank&quot;} 빠른 승리입니다. 양식이 있어야 합니다. 양식에 다른 이름을 사용한 경우 해당 이름을 선택합니다.

1. 을(를) 클릭합니다. **흐름** 탭.

   ![](assets/simple-scoring-9.png)

1. 을(를) 드래그합니다. **점수 변경** 왼쪽 캔버스로 작업을 이동합니다.

   ![](assets/simple-scoring-10.png)

1. 개인 점수에 추가할 값을 입력할 수 있습니다. 에 &quot;+5&quot;를 입력합니다. **변경** 필드.

   ![](assets/simple-scoring-11.png)

   >[!TIP]
   >
   >좋은 점수 캠페인이 Sales에 고급 인력을 제공하는 데 중요한 역할을 합니다. 읽기 [**리드 점수 책정 최종 가이드**](https://www.marketo.com/definitive-guides/lead-scoring/){target=&quot;_blank&quot;}.

1. 을(를) 클릭합니다. **예약** 탭 및 **활성화** 버튼을 클릭합니다.

   ![](assets/simple-scoring-12.png)

1. 클릭 **활성화** 확인 화면에 표시됩니다.

   ![](assets/simple-scoring-13.png)

>[!NOTE]
>
>활성화되면 사용자가 양식을 작성할 때마다 이 캠페인이 실행됩니다. 캠페인은 비활성화될 때까지 계속 실행됩니다.

## 2단계: 양식 채우기 {#step-fill-out-the-form}

1. 에서 만든 랜딩 페이지를 선택합니다 [양식이 있는 랜딩 페이지](/help/marketo/getting-started/quick-wins/landing-page-with-a-form.md){target=&quot;_blank&quot;} 빠른 승입니다.

   ![](assets/simple-scoring-14.png)

1. 클릭 **미리 보기**. 랜딩 페이지가 새 탭에서 열립니다.

   ![](assets/simple-scoring-15.png)

1. 이름, 성 및 이메일 주소로 양식을 입력한 다음 **제출**.

   ![](assets/simple-scoring-16.png)

   >[!NOTE]
   >
   >&quot;+5&quot; 점수 증가를 적용하려면 처음 개인으로 입력했을 때 사용한 이름과 이메일 주소를 사용하십시오.

## 3단계: 개인 정보 보기 {#step-view-the-person-info}

1. 데이터베이스 영역으로 이동합니다.

   ![](assets/simple-scoring-17.png)

1. 양식을 채울 때 사용한 이메일 주소를 검색합니다.

   ![](assets/simple-scoring-18.png)

1. 사람을 두 번 클릭합니다.

   ![](assets/simple-scoring-19.png)

개인 세부 사항이 새 탭 또는 창에서 열립니다. 양식 작성을 위해 점수가 5점이나 어떻게 올랐는지 보세요.

![](assets/simple-scoring-20.png)

## 임무 완료! {#mission-complete}

<br> 

[◄ 미션 2: 양식이 있는 랜딩 페이지](/help/marketo/getting-started/quick-wins/landing-page-with-a-form.md)

[미션 4: 이메일 자동 응답 ►](/help/marketo/getting-started/quick-wins/email-auto-response.md)
