---
unique-page-id: 2359422
description: 이메일 개인화 - 마케팅 문서 - 제품 설명서
title: 이메일 개인화
translation-type: tm+mt
source-git-commit: 5c9683c6b00ccbf9e9d606fd4513432c9872ad00
workflow-type: tm+mt
source-wordcount: '390'
ht-degree: 0%

---


# 이메일 개인화 {#personalize-an-email}

## 임무:데이터 토큰을 추가하여 개인화된 이메일 만들기 {#mission-make-your-emails-personal-by-adding-data-tokens}

>[!NOTE]
>
>**FYI**
>
>Marketing은 이제 모든 구독 간의 언어를 표준화하므로 구독에 리드/리드 및 docs.markto.com에 있는 사람/사람을 볼 수 있습니다. 이 용어는 같은 것을 의미한다.아티클 지침에는 영향을 주지 않습니다. 다른 변화도 있습니다 [자세한](http://docs.marketo.com/display/DOCS/Updates+to+Marketo+Terminology)내용

>[!NOTE]
>
>**사전 요구 사항**
>
>* [설정 및 사람 추가](get-set-up-and-add-a-person.md)
>* [이메일 발포 보내기](send-an-email.md)
>* [드립, 드립, 양육](drip-drip-nurture.md)


## 1단계:개인화할 이메일 선택 {#step-select-an-email-to-personalize}

1. 이전 빠른 [윈](drip-drip-nurture.md) 에서 만든 인육 이메일 중 하나를 선택하고 초안 **편집을 클릭합니다**.

   ![](assets/one-4.png)

   >[!NOTE]
   >
   >그러면 이메일의 사본이 초안으로 만들어집니다. 변경 사항이 라이브로 적용되려면 초안을 승인해야 합니다.

   **초안 편집**

팝업 차단을 활성화하지 않은 경우 이메일 편집기가 새 탭/창에서 열립니다. 그렇지 않으면 두 번 클릭합니다.

## 2단계:영업사원을 발송자로 지정 {#step-make-the-salesperson-the-sender}

1. 보낸 사람 **필드를** 선택하고 현재 이름을 **강조** 표시하고삭제합니다.

   ![](assets/two-5.png)

1. 시작 필드 **오른쪽의** 토큰 **아이콘을** 클릭합니다.

   ![](assets/three-4.png)

1. 토큰을 찾아 **`{{lead.Lead Owner First Name}}`** 선택합니다.

   ![](assets/four-3.png)

1. 판매 담당자 이름을 사용할 수 없는 경우 어떤 것이 **표시되는지 확인하려면** 기본값(Default Value)에 대한 회사 이름과 대시(dash)를 입력합니다. 삽입을 **클릭합니다**.

   ![](assets/five-4.png)

1. 시작 필드의 스페이스바를 **눌러** 방금 삽입한 토큰 후에 커서가 하나의 공간을 깜박이게 합니다. 그런 다음 **토큰** 아이콘을 다시 클릭합니다.

   ![](assets/six-4.png)

1. 토큰을 찾아 **`{{lead.Lead Owner Last Name}}`** 선택합니다.

   ![](assets/seven-5.png)

1. 기본값(Default Value)에 &quot;Sales&quot;를 **입력하고 삽입(Insert)을** 클릭합니다 ****.

   ![](assets/eight-3.png)

## 3단계:이메일에 리드 이름 추가 {#step-add-the-leads-name-to-the-email}

1. 편집 가능한 상단 섹션을 선택하고 톱니바퀴 아이콘을 클릭한 다음 **편집을 선택합니다**.

   ![](assets/nine-2.png)

1. &quot;Hello&quot; 뒤에 공백을 추가하고 커서를 쉼표 앞에 놓은 다음 토큰 **삽입** 아이콘을 클릭합니다.

   ![](assets/ten-4.png)

1. 토큰을 찾아 **`{{lead.First Name}}`** 선택합니다.

   ![](assets/eleven-4.png)

1. 기본값(Default Value) 필드에 &quot;Friend&quot;(또는 원하는 레이블)를 **입력하고 삽입(Insert)을** 클릭합니다 ****.

   ![](assets/twelve-3.png)

   >[!TIP]
   >
   >항상 토큰에 대한 기본값 포함;그러면 개인 정보의 일부가 누락된 경우 이메일에 기본값이 표시됩니다.

1. 저장을 **클릭합니다**.

   ![](assets/thirteen-3.png)

1. 이메일 편집기 탭/창을 닫습니다.

   ![](assets/fourteen-3.png)

1. [ **이메일 작업**]에서 **초안 승인을 선택합니다**.

   ![](assets/fifteen-3.png)

>[!TIP]
>
>이메일을 보내는 방법에 대한 신속한 재교육이 필요하십니까? 이메일 [폭발 전송을 참조하십시오](send-an-email.md).

### 비디오 보기 {#watch-a-video}

`<iframe width="630" height="470" src="//play.vidyard.com/iRnqxMyJg6VKyuPeuxmHFb.html?v=3.1.1" frameborder="0" allowfullscreen></iframe>`

### 임무 완료 {#mission-complete}

축하합니다. 이메일을 개인화했습니다.

<br> 

[임무 ◄ 6:드립, 드립,](drip-drip-nurture.md) 인육 [임무 8:영업 담당자에게 알림](alert-the-sales-rep.md)