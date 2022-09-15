---
unique-page-id: 2359424
description: 영업 담당자 - Marketo 문서 - 제품 설명서에 경고
title: 영업 담당자에게 경고
exl-id: 4ad7d7b8-ee1e-4605-b4e0-e72a7e573c05
source-git-commit: 1127928b43762086ed4d157719ff80d6c3de9ee3
workflow-type: tm+mt
source-wordcount: '404'
ht-degree: 0%

---

# 영업 담당자에게 경고 {#alert-the-sales-rep}

## 임무: 사용자가 웹 사이트에서 양식을 작성하면 영업 담당자에게 알립니다 {#mission-alert-the-sales-rep-when-a-person-fills-out-a-form-on-your-web-site}

영업 담당자에게 경고 이메일을 자동으로 보내려면 경고 이메일과 이메일 캠페인이 필요합니다. 어떻게 하는지 알려드리겠습니다.

>[!PREREQUISITES]
>
>[양식이 있는 랜딩 페이지](/help/marketo/getting-started/quick-wins/landing-page-with-a-form.md){target=&quot;_blank&quot;}

## 1단계: 경고 이메일 만들기 {#step-create-an-alert-email}

1. 로 이동합니다. **마케팅 활동** 영역.

   ![](assets/alert-the-sales-rep-1.png)

1. 선택 **내 프로그램** 여기서 생성한 [양식이 있는 랜딩 페이지](/help/marketo/getting-started/quick-wins/landing-page-with-a-form.md){target=&quot;_blank&quot;} 빠른 우승 후 아래 **새로 만들기** click **새 로컬 자산**.

   ![](assets/alert-the-sales-rep-2.png)

1. 클릭 **이메일**.

   ![](assets/alert-the-sales-rep-3.png)

1. **이름** 이메일 &quot;내 이메일 경고&quot;에서 템플릿을 선택하고 **만들기**.

   ![](assets/alert-the-sales-rep-4.png)

1. 을(를) 입력합니다. **이름**, **이메일에서**, **회신**, 및 **제목** 영업 팀이 직접 보고 싶어합니다.

   ![](assets/alert-the-sales-rep-5.png)

1. 전자 메일 텍스트를 편집하려면 두 번 클릭합니다.

   ![](assets/alert-the-sales-rep-6.png)

1. 이메일 콘텐츠를 입력합니다.

   ![](assets/alert-the-sales-rep-7.png)

1. 연락처 정보를 삽입할 위치에 커서를 놓고 **토큰 삽입** 아이콘.

   ![](assets/alert-the-sales-rep-8.png)

1. 을(를) 찾아 선택합니다 `{{SP_Send_Alert_Info}}` **토큰** 을(를) 클릭합니다. **삽입**.

   ![](assets/alert-the-sales-rep-9.png)

   >[!NOTE]
   >
   >{{SP_Send_Alert_Info}} 는 경고 이메일에 대한 특수 토큰입니다. 자세한 내용은 [경고 정보 토큰 보내기 사용](/help/marketo/product-docs/email-marketing/general/using-tokens/use-the-send-alert-info-token.md)자세한 내용은 {target=&quot;_blank&quot;}{target=&quot;_blank&quot;} 를 참조하십시오.

1. 클릭 **저장**.

   ![](assets/alert-the-sales-rep-10.png)

1. 을(를) 클릭합니다. **이메일 작업** 드롭다운 및 선택 **승인 및 닫기**.

   ![](assets/alert-the-sales-rep-11.png)

## 2단계: 경고 트리거 캠페인 만들기 {#step-create-an-alert-trigger-campaign}

1. 선택 **내 프로그램** 이전에 만든 후 **새로 만들기** click **새로운 스마트 캠페인**.

   ![](assets/alert-the-sales-rep-12.png)

1. **이름** 캠페인 &quot;내 경고 캠페인&quot;을 클릭하고 **만들기**.

   ![](assets/alert-the-sales-rep-13.png)

1. 아래에 **Smart List** 탭에서 을(를) 찾아 드래그합니다. **양식 채우기** 캔버스에 트리거합니다.

   ![](assets/alert-the-sales-rep-14.png)

1. 앞에서 만든 양식을 선택합니다.

   ![](assets/alert-the-sales-rep-15.png)

1. 아래에 **흐름** 탭에서 을(를) 찾아 드래그합니다. **경고 보내기** 캔버스로 이동 작업을 이동합니다.

   ![](assets/alert-the-sales-rep-16.png)

1. 선택 **내 경고 이메일** 일찍 작성 및 종료 **보내기** 로서의 **영업 소유자**.

   ![](assets/alert-the-sales-rep-17.png)

1. 에 이메일 주소를 입력합니다 **다른 전자 메일로 보내기** 필드.

   ![](assets/alert-the-sales-rep-18.png)

1. 로 이동합니다. **예약** 탭을 클릭하고 **활성화** 버튼을 클릭합니다.

   ![](assets/alert-the-sales-rep-19.png)

   >[!TIP]
   >
   >설정 **자격 규칙** to **항상** (Smart Campaign을 편집하여) 동일한 사람이 경고를 여러 번 트리거할 수 있도록 합니다.

1. 클릭 **활성화** 확인 화면에 표시됩니다.

   ![](assets/alert-the-sales-rep-20.png)

## 3단계: 테스트해 보십시오! {#step-test-it-out}

1. 랜딩 페이지를 선택하고 을(를) 클릭합니다. **승인된 페이지 보기**.

   ![](assets/alert-the-sales-21.png)

   >[!NOTE]
   >
   >랜딩 페이지 승인 잊지 마십시오. 승인될 때까지 라이브로 전환되지 않습니다.

1. 양식을 작성하고 **제출**.

   ![](assets/alert-the-sales-22.png)

1. 곧 이메일이 전송됩니다. 모든 것이 제대로 작동하는지 확인했으면 경고 보내기 흐름에서 이메일 주소를 제거합니다(위의 2.7단계 참조).

   >[!NOTE]
   >
   >을(를) 클릭합니다. **개인 정보** 연락처 정보를 보려면 Marketo에서 탭을 클릭하십시오.

## 임무 완료! {#mission-complete}

<br> 

[◄ 미션 7: 이메일 개인화](/help/marketo/getting-started/quick-wins/personalize-an-email.md)

[미션 9: 개인 데이터 업데이트 ►](/help/marketo/getting-started/quick-wins/update-person-data.md)
