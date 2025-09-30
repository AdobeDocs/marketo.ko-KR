---
unique-page-id: 2359422
description: 이메일 개인화 - Marketo Docs - 제품 설명서
title: 이메일 개인화
exl-id: 1562796e-da47-4305-b950-3bed1d36d339
feature: Getting Started
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: ht
source-wordcount: '319'
ht-degree: 100%

---

# 이메일 개인화 {#personalize-an-email}

## 미션: 데이터 토큰을 추가하여 이메일을 개인화합니다. {#mission-make-your-emails-personal-by-adding-data-tokens}

>[!PREREQUISITES]
>
>* [설정 및 사용자 추가](/help/marketo/getting-started/quick-wins/get-set-up-and-add-a-person.md){target="_blank"}
>* [이메일 일괄 발송](/help/marketo/getting-started/quick-wins/send-an-email.md){target="_blank"}
>* [드립, 드립, 육성](/help/marketo/getting-started/quick-wins/drip-drip-nurture.md){target="_blank"}

## 1단계: 개인화할 이메일 선택 {#step-select-an-email-to-personalize}

1. [이전 빠른 승리](/help/marketo/getting-started/quick-wins/drip-drip-nurture.md){target="_blank"}에서 만든 육성 이메일 중 하나를 선택하고 **[!UICONTROL Create draft]**&#x200B;를 클릭합니다.

   ![](assets/personalize-an-email-1.png)

   >[!NOTE]
   >
   >이렇게 하면 이메일의 사본이 초안으로 생성됩니다. 변경 사항을 적용하려면 초안을 승인해야 합니다.

팝업 차단기를 활성화하지 않은 경우 이메일 편집기가 새 탭/창에서 열립니다. 그렇지 않은 경우, **[!UICONTROL Create Draft]**&#x200B;를 더블 클릭합니다.

## 2단계: 판매 담당자를 발신자로 지정 {#step-make-the-salesperson-the-sender}

1. **[!UICONTROL From]** 필드를 선택하고 현재 이름을 강조 표시한 다음 **삭제**&#x200B;합니다.

   ![](assets/personalize-an-email-2.png)

1. **[!UICONTROL From]** 필드 오른쪽에 있는 **토큰** 아이콘을 클릭합니다.

   ![](assets/personalize-an-email-3.png)

1. **`{{lead.Lead Owner First Name}}`** 토큰을 찾아 선택합니다.

   ![](assets/personalize-an-email-4.png)

1. 영업 담당자의 이름을 알 수 없는 경우에도 무언가 표시되도록 **기본값**&#x200B;에 회사 이름과 대시를 입력합니다. **삽입**&#x200B;을 클릭합니다.

   ![](assets/personalize-an-email-5.png)

1. **[!UICONTROL From]** 필드에서 스페이스바를 누르고, 방금 삽입한 토큰 뒤에서 커서가 한 칸 깜빡이는지 확인합니다. 그런 다음 **토큰** 아이콘을 다시 클릭합니다.

   ![](assets/personalize-an-email-6.png)

1. **`{{lead.Lead Owner Last Name}}`** 토큰을 찾아 선택합니다.

   ![](assets/personalize-an-email-7.png)

1. **기본값**&#x200B;에 “세일즈”를 입력하고 **삽입**&#x200B;을 클릭합니다.

   ![](assets/personalize-an-email-8.png)

## 3단계: 이메일에 리드 이름 추가 {#step-add-the-leads-name-to-the-email}

1. 가장 위의 편집 가능한 섹션을 선택하고 톱니바퀴 아이콘을 클릭한 다음 **[!UICONTROL Edit]**&#x200B;을 선택합니다.

   ![](assets/personalize-an-email-9.png)

1. “안녕하세요” 뒤에 공백을 추가하고 커서를 쉼표 앞에 놓은 다음 **토큰 삽입** 아이콘을 클릭합니다.

   ![](assets/personalize-an-email-10.png)

1. **`{{lead.First Name}}`** 토큰을 찾아 선택합니다.

   ![](assets/personalize-an-email-11.png)

1. **[!UICONTROL Default Value]** 필드에 “친구”(또는 원하는 레이블)를 입력하고 **[!UICONTROL Insert]**&#x200B;를 클릭합니다.

   ![](assets/personalize-an-email-12.png)

   >[!TIP]
   >
   >토큰에는 항상 기본값을 포함합니다. 이렇게 하면 개인 정보의 일부가 누락된 경우에도 이메일에 기본값이 표시됩니다.

1. **[!UICONTROL Save]**&#x200B;를 클릭합니다.

   ![](assets/personalize-an-email-13.png)

1. **[!UICONTROL Email Actions]**&#x200B;에서 **[!UICONTROL Approve and Close]**&#x200B;를 선택합니다.

   ![](assets/personalize-an-email-14.png)

>[!TIP]
>
>이메일을 자신에게 보내는 방법을 빠르게 다시 알아보고 싶습니까? [이메일 일괄 발송](/help/marketo/getting-started/quick-wins/send-an-email.md){target="_blank"}을 참조하십시오.

### 미션 완료 {#mission-complete}

축하합니다. 이메일이 개인화되었습니다.

<br> 

[◄ 미션 6: 드립, 드립, 육성](/help/marketo/getting-started/quick-wins/drip-drip-nurture.md)

[미션 8: 영업 담당자에게 알림 ►](/help/marketo/getting-started/quick-wins/alert-the-sales-rep.md)
