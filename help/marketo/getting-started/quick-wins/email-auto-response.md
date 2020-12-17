---
unique-page-id: 2359416
description: 이메일 자동 응답 - 마케팅 문서 - 제품 설명서
title: 이메일 자동 응답
translation-type: tm+mt
source-git-commit: d7d6aee63144c472e02fe0221c4a164183d04dd4
workflow-type: tm+mt
source-wordcount: '384'
ht-degree: 0%

---


# 전자 메일 자동 응답 {#email-auto-response}

## 임무:사용자가 {#mission-send-out-a-thank-you-email-when-a-person-fills-out-a-form} 양식을 작성할 때 감사 인사 이메일을 보냅니다.

>[!PREREQUISITES]
>
>* [설정 및 사람 추가](/help/marketo/getting-started/quick-wins/get-set-up-and-add-a-person.md)
>* [양식이 있는 랜딩 페이지](/help/marketo/getting-started/quick-wins/landing-page-with-a-form.md)


## 1단계:이메일 {#step-create-an-email} 만들기

1. 마케팅 활동 영역으로 이동합니다.

   ![](assets/one-2.png)

1. 왼쪽 메뉴에서 내 프로그램을 선택하고 새로 만들기 드롭다운을 클릭한 다음 새 로컬 에셋을 선택합니다.

   ![](assets/two-3.png)

1. 이메일을 클릭합니다.

   ![](assets/three-2.png)

1. 이메일 이름을 &quot;자동 응답 이메일&quot;으로 지정하고, 템플릿을 선택하고 만들기를 클릭합니다.

   ![](assets/four-1.png)

   이메일 편집기가 새 창이나 탭에 열립니다. 팝업이 차단된 경우 자산 요약 페이지에서 **초안 편집**&#x200B;을 클릭하여 이메일에 액세스합니다.

1. 제목 줄을 입력한 다음, 이메일의 편집 가능 영역을 두 번 클릭합니다.

   ![](assets/five-2.png)

   _이메일 편집기 위에 리치 텍스트 편집기가 열립니다._

1. 기존 이메일 컨텐츠를 강조 표시합니다.

   ![](assets/six-2.png)

1. 이메일 컨텐츠를 입력하고 저장을 클릭합니다.

   ![](assets/seven-2.png)

1. 변경 내용이 자동으로 저장됩니다. 이메일 편집기 탭/창을 닫습니다.

   ![](assets/eight-1.png)

1. 새 이메일을 선택합니다. 이메일 작업에서 승인을 클릭합니다.

   ![](assets/image2014-9-24-11-3a55-3a16.png)

## 2단계:스마트 캠페인 만들기 {#step-create-a-smart-campaign}

1. **내 프로그램**&#x200B;을 마우스 오른쪽 단추로 클릭하고 **새 스마트 캠페인**&#x200B;을 클릭합니다.

   ![](assets/image2014-9-24-11-3a56-3a13.png)

1. **스마트** 캠페인 이름을 &quot;자동 응답 캠페인&quot;으로 지정하고 만들기를  **클릭합니다**.

   ![](assets/image2014-9-24-11-3a56-3a25.png)

1. **스마트 목록** 탭으로 이동합니다.

   ![](assets/image2014-9-24-11-3a56-3a38.png)

   사용자가 [**랜딩 페이지에서 만든 양식을 양식**](/help/marketo/getting-started/quick-wins/landing-page-with-a-form.md)&#x200B;으로 채울 때마다 이 캠페인을 실행하도록 설정합니다.

1. **양식 채우기** 트리거를 찾아 왼쪽 캔버스로 드래그합니다.

   ![](assets/image2014-9-24-11-3a57-3a18.png)

1. 드롭다운에서 **내 양식**&#x200B;을 선택합니다. **흐름** 탭을 클릭합니다.

   ![](assets/image2014-9-24-11-3a57-3a29.png)

1. **이메일 보내기** 흐름 작업을 왼쪽 캔버스로 드래그합니다.

   ![](assets/image2014-9-24-11-3a57-3a41.png)

1. **자동 응답 이메일**&#x200B;을 선택하고 **예약** 탭으로 이동합니다.

   ![](assets/image2014-9-24-11-3a57-3a53.png)

1. **편집**&#x200B;을 클릭합니다.

   ![](assets/8.png)

1. **매번**&#x200B;을 선택하고 **저장**&#x200B;을 클릭합니다.

   ![](assets/9.png)

1. **활성화**&#x200B;를 클릭합니다.

   ![](assets/10.png)

1. 확인 화면에서 **활성화**&#x200B;를 클릭합니다.

   ![](assets/11.png)

>[!NOTE]
>
>활성화되면 사용자가 지정된 양식을 채울 때마다 이 캠페인이 실행됩니다. 캠페인이 비활성화될 때까지 계속 실행됩니다.

## 3단계:양식 {#step-fill-out-the-form} 채우기

1. **내 페이지**&#x200B;를 선택합니다. 이 이름은 [랜딩 페이지에서 양식](/help/marketo/getting-started/quick-wins/landing-page-with-a-form.md) 빠른 승인과 함께 만들어졌습니다.

   ![](assets/image2014-9-24-12-3a0-3a8.png)

1. **승인된 페이지 보기**&#x200B;를 클릭합니다.

   ![](assets/image2014-9-24-12-3a0-3a18.png)

   &quot;무료 시험버전&quot; 랜딩 페이지가 새 탭에 열립니다.

1. 이름, 성 및 이메일 주소로 양식을 작성한 다음 **제출**&#x200B;을 클릭합니다.

   ![](assets/image2014-9-24-12-3a0-3a28.png)

>[!NOTE]
>
>이메일을 받을 수 있도록 실제 이메일 주소를 사용하십시오.

## 임무 완료 {#mission-complete}

단 몇 분 안에 받은 편지함에 자동 응답 이메일이 표시됩니다. 잘했어요!

<br> 

[◄ 미션 3:단순 점수 지정](/help/marketo/getting-started/quick-wins/simple-scoring.md)

[임무 5:리드 목록 ► 가져오기](/help/marketo/getting-started/quick-wins/import-a-list-of-people.md)
