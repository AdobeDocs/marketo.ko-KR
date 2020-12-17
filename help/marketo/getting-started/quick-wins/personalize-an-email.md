---
unique-page-id: 2359422
description: 이메일 개인화 - 마케팅 문서 - 제품 설명서
title: 이메일 개인화
translation-type: tm+mt
source-git-commit: d7d6aee63144c472e02fe0221c4a164183d04dd4
workflow-type: tm+mt
source-wordcount: '335'
ht-degree: 0%

---


# 이메일 {#personalize-an-email} 개인화

## 임무:데이터 토큰 {#mission-make-your-emails-personal-by-adding-data-tokens}을 추가하여 개인 이메일 만들기

>[!PREREQUISITES]
>
>* [설정 및 사람 추가](/help/marketo/getting-started/quick-wins/get-set-up-and-add-a-person.md)
>* [이메일 폭발 보내기](/help/marketo/getting-started/quick-wins/send-an-email.md)
>* [드립, 드립, 배드](/help/marketo/getting-started/quick-wins/drip-drip-nurture.md)


## 1단계:{#step-select-an-email-to-personalize} 개인화할 이메일 선택

1. [이전 빠른 win](/help/marketo/getting-started/quick-wins/drip-drip-nurture.md)에서 만든 육성형 이메일 중 하나를 선택하고 **초안 편집**&#x200B;을 클릭합니다.

   ![](assets/one-4.png)

   >[!NOTE]
   >
   >그러면 이메일의 복사본이 초안으로 만들어집니다. 변경 내용을 적용하려면 초안을 승인해야 합니다.

팝업 차단을 활성화하지 않은 경우 이메일 편집기가 새 탭/창에서 열립니다. 그렇지 않은 경우 **초안 편집**&#x200B;을 두 번 클릭합니다.

## 2단계:영업사원을 발송자 {#step-make-the-salesperson-the-sender}

1. **From** 필드를 선택하고 현재 이름을 강조 표시하고 **delete**&#x200B;합니다.

   ![](assets/two-5.png)

1. **보낸 사람** 필드의 오른쪽에 있는 **토큰** 아이콘을 클릭합니다.

   ![](assets/three-4.png)

1. **`{{lead.Lead Owner First Name}}`** 토큰을 찾아 선택합니다.

   ![](assets/four-3.png)

1. **기본값**&#x200B;에 대한 회사 이름과 대시를 입력하여 판매 담당자 이름을 사용할 수 없는 경우에 어떤 것이 표시되는지 확인합니다. **삽입**&#x200B;을 클릭합니다.

   ![](assets/five-4.png)

1. **보낸 사람** 필드의 스페이스바를 눌러 방금 삽입한 토큰 뒤 커서가 하나의 공간을 깜박이게 합니다. 그런 다음 **토큰** 아이콘을 다시 클릭합니다.

   ![](assets/six-4.png)

1. **`{{lead.Lead Owner Last Name}}`** 토큰을 찾아 선택합니다.

   ![](assets/seven-5.png)

1. **기본값**&#x200B;에 &quot;Sales&quot;를 입력하고 **삽입**&#x200B;을 클릭합니다.

   ![](assets/eight-3.png)

## 3단계:이메일 {#step-add-the-leads-name-to-the-email}에 리드의 이름 추가

1. 편집 가능한 상단 섹션을 선택하고 톱니바퀴 아이콘을 클릭한 다음 **편집**&#x200B;을 선택합니다.

   ![](assets/nine-2.png)

1. &quot;Hello&quot; 뒤에 공백을 추가하고 커서를 쉼표 앞에 놓은 다음 **토큰 삽입** 아이콘을 클릭합니다.

   ![](assets/ten-4.png)

1. **`{{lead.First Name}}`** 토큰을 찾아 선택합니다.

   ![](assets/eleven-4.png)

1. **기본값** 필드에 &quot;친구&quot;(또는 원하는 레이블)를 입력하고 **삽입**&#x200B;을 클릭합니다.

   ![](assets/twelve-3.png)

   >[!TIP]
   >
   >항상 토큰에 대한 기본값을 포함합니다.그러면 개인 정보의 일부가 누락된 경우 기본값이 이메일에 표시됩니다.

1. **저장**&#x200B;을 클릭합니다.

   ![](assets/thirteen-3.png)

1. 이메일 편집기 탭/창을 닫습니다.

   ![](assets/fourteen-3.png)

1. **이메일 작업**&#x200B;에서 **초안 승인**&#x200B;을 선택합니다.

   ![](assets/fifteen-3.png)

>[!TIP]
>
>이메일을 보내는 방법에 대한 신속한 재교육이 필요하십니까? [이메일 폭발 보내기](/help/marketo/getting-started/quick-wins/send-an-email.md)를 참조하십시오.

### 임무 완료 {#mission-complete}

축하합니다. 이메일을 개인화했습니다!

<br> 

[◄ 미션 6:드립, 드립, 배드](/help/marketo/getting-started/quick-wins/drip-drip-nurture.md)

[임무 8:영업 담당자에게 ► 알림](/help/marketo/getting-started/quick-wins/alert-the-sales-rep.md)
