---
unique-page-id: 2359422
description: 이메일 개인화 - Marketo 문서 - 제품 설명서
title: 이메일 개인화
exl-id: 1562796e-da47-4305-b950-3bed1d36d339
source-git-commit: 80512816eaf0a70a3f10a50c34aeea14edd9046b
workflow-type: tm+mt
source-wordcount: '331'
ht-degree: 0%

---

# 이메일 개인화 {#personalize-an-email}

## 미션: 데이터 토큰을 추가하여 이메일을 개인용으로 만들기 {#mission-make-your-emails-personal-by-adding-data-tokens}

>[!PREREQUISITES]
>
>* [설정 및 사용자 추가](/help/marketo/getting-started/quick-wins/get-set-up-and-add-a-person.md){target="_blank"}
>* [이메일 전송](/help/marketo/getting-started/quick-wins/send-an-email.md){target="_blank"}
>* [드립, 드립, 육성](/help/marketo/getting-started/quick-wins/drip-drip-nurture.md){target="_blank"}


## 1단계: 개인화할 이메일 선택 {#step-select-an-email-to-personalize}

1. 에서 만든 육성 이메일 중 하나를 선택합니다. [이전 빠른 성공](/help/marketo/getting-started/quick-wins/drip-drip-nurture.md){target="_blank"} 및 클릭 **[!UICONTROL 초안 만들기]**.

   ![](assets/personalize-an-email-1.png)

   >[!NOTE]
   >
   >이렇게 하면 이메일 사본이 초안으로 만들어집니다. 변경 내용을 적용할 초안을 승인해야 합니다.

팝업 차단을 활성화하지 않은 경우 이메일 편집기가 새 탭/창에서 열립니다. 그렇지 않으면 **[!UICONTROL 초안 만들기]** 두 번

## 2단계: 영업 사원을 발신자로 설정 {#step-make-the-salesperson-the-sender}

1. 다음 항목 선택 **[!UICONTROL 출처:]** 필드, 강조 표시 및 **삭제** 현재 이름입니다.

   ![](assets/personalize-an-email-2.png)

1. 다음을 클릭합니다. **토큰** 아이콘 의 오른쪽 **[!UICONTROL 출처:]** 필드.

   ![](assets/personalize-an-email-3.png)

1. 다음 항목을 찾아 선택합니다. **`{{lead.Lead Owner First Name}}`** 토큰.

   ![](assets/personalize-an-email-4.png)

1. 회사 이름과 대시보드를 입력합니다. **기본값** 영업 담당자의 이름을 사용할 수 없는 경우 표시되는 항목이 있는지 확인합니다. 클릭 **삽입**.

   ![](assets/personalize-an-email-5.png)

1. 의 스페이스 바를 누릅니다. **[!UICONTROL 출처:]** 필드: 방금 삽입한 토큰 바로 뒤에 커서가 깜박이고 있는지 확인합니다. 그런 다음 **토큰** 아이콘을 다시 클릭합니다.

   ![](assets/personalize-an-email-6.png)

1. 다음 항목을 찾아 선택합니다. **`{{lead.Lead Owner Last Name}}`** 토큰.

   ![](assets/personalize-an-email-7.png)

1. 에 대해 &quot;Sales&quot;를 입력합니다. **기본값** 및 클릭 **삽입**.

   ![](assets/personalize-an-email-8.png)

## 3단계: 잠재 고객의 이름을 이메일에 추가 {#step-add-the-leads-name-to-the-email}

1. 편집 가능한 상위 섹션을 선택하고 톱니바퀴 아이콘을 클릭한 다음 을(를) 선택합니다 **[!UICONTROL 편집]**.

   ![](assets/personalize-an-email-9.png)

1. &quot;Hello&quot; 뒤에 공백을 추가하고 커서를 쉼표 앞에 놓은 다음 **토큰 삽입** 아이콘.

   ![](assets/personalize-an-email-10.png)

1. 다음 항목을 찾아 선택합니다. **`{{lead.First Name}}`** 토큰.

   ![](assets/personalize-an-email-11.png)

1. 에 &quot;Friend&quot;(또는 원하는 레이블)를 입력합니다. **[!UICONTROL 기본값]** 필드 및 클릭 **[!UICONTROL 삽입]**.

   ![](assets/personalize-an-email-12.png)

   >[!TIP]
   >
   >항상 토큰에 대한 기본값을 포함하십시오. 이렇게 하면 개인 정보의 일부가 누락된 경우 이메일에 기본값이 표시됩니다.

1. 클릭 **[!UICONTROL 저장]**.

   ![](assets/personalize-an-email-13.png)

1. 아래 **[!UICONTROL 이메일 작업]** 및 선택 **[!UICONTROL 승인 및 닫기]**.

   ![](assets/personalize-an-email-14.png)

>[!TIP]
>
>전자 메일을 보내는 방법에 대한 빠른 새로 고침이 필요하십니까? 다음을 참조하십시오 [이메일 전송](/help/marketo/getting-started/quick-wins/send-an-email.md){target="_blank"}.

### 임무 완료 {#mission-complete}

축하합니다. 이메일을 개인화했습니다!

<br> 

[◄ 미션 6: 드립, 드립, 육성](/help/marketo/getting-started/quick-wins/drip-drip-nurture.md)

[미션 8: 영업 담당자에게 알림 ►](/help/marketo/getting-started/quick-wins/alert-the-sales-rep.md)
