---
description: 스트림 디자이너 - Marketo 문서 - 제품 설명서
title: 스트림 디자이너
exl-id: aa44c7a5-f81b-4029-a1a4-5439bea83847
source-git-commit: 24075208786077797f4917a2907b6dcfec7ed7bf
workflow-type: tm+mt
source-wordcount: '866'
ht-degree: 2%

---

# 스트림 디자이너 {#stream-designer}

있습니다 _많은_ 가능한 스트림 조합입니다. 이 문서에는 마케터가 제품 관련 질문이 있는지 사이트 방문자에게 묻는 예제가 포함되어 있습니다. 예라면 방문자가 약속을 예약할 수 있습니다. 없을 경우 방문자에게 향후 서신에 대한 메일링 목록에 가입할 수 있는 옵션이 제공됩니다. 무료 PDF도 제공됩니다. 최종 목표는 약속을 예약하거나 방문자의 이메일을 수집하는 것입니다.

>[!PREREQUISITES]
>
>문서 카드를 사용하려면 먼저 [설정](/help/marketo/product-docs/demand-generation/dynamic-chat/integrations/using-the-document-card.md)Adobe 계정의 {target=&quot;_blank&quot;}.

## 스트림 디자이너 카드 {#stream-designer-cards}

스트림 디자이너에는 채팅 대화 모양을 만들기 위해 추가할 수 있는 여러 카드가 포함되어 있습니다.

<table>
 <tr>
  <td><strong>메시지</strong></td>
  <td>응답 없이 구문을 만들려면(예: "안녕! SAVE25" 코드를 사용하면 모든 항목이 오늘 25% 할인됩니다.
</td>
 </tr>
 <tr>
  <td><strong>질문</strong></td>
  <td>사용 가능한 응답을 제공하는 다중 선택 질문을 하려면 를 사용합니다(예: 어떤 차종에 관심이 있으십니까? 응답 = SUV, 컴팩트, 트럭 등).</td>
 </tr>
 <tr>
  <td><strong>문서</strong></td>
  <td>대화 상자에 PDF 문서를 포함하고 방문자의 문서 참여 활동(문서를 다운로드한 경우 본 페이지 수 및/또는 사용된 검색어)을 추적할 수 있습니다.</td>
 </tr>
 <tr>
  <td><strong>정보 캡처</strong></td>
  <td>정보를 수집하려면 를 사용하십시오. 선택할 수 있는 세 개의 필드는 이메일 주소, 전화 번호 및 텍스트(방문자가 고유한 메시지를 작성할 수 있음)입니다.</td>
 </tr>
 <tr>
  <td><strong>약속 스케줄러</strong></td>
  <td>방문자에게 후속 작업을 예약하기 위해 사용 가능한 날짜 달력을 제공합니다. 달력 사용 가능 여부는 <a href="/help/marketo/product-docs/demand-generation/dynamic-chat/dynamic-chat-overview.md#routing">다음 에이전트가 연결됨</a>.</td>
 </tr>
 <tr>
  <td><strong>목표</strong></td>
  <td>방문자가 볼 수 없는 유일한 카드입니다. 특정 채팅(예: 방문자의 이메일을 수집하는 것이 목표인 경우 스트림에서 정보 캡처 바로 뒤에 목표 카드를 배치합니다.</td>
 </tr>
</table>

## 스트림 디자이너 아이콘 {#stream-designer-icons}

스트림 디자이너의 오른쪽 상단에 몇 가지 아이콘이 표시됩니다. 여기 그들이 하는 일이 있습니다.

<table>
 <tr>
  <td><img src="assets/stream-designer-1.png"></td>
  <td>해당 보기를 선호하는 사용자를 위해 배경에 격자를 추가합니다</td>
 </tr>
 <tr>
  <td><img src="assets/stream-designer-2.png"></td>
  <td>확대, 더 큰 카드 만들기</td>
 </tr>
 <tr>
  <td><img src="assets/stream-designer-3.png"></td>
  <td>확대/축소하여 더 작은 카드 만들기</td>
 </tr>
 <tr>
  <td><img src="assets/stream-designer-4.png"></td>
  <td>채팅을 테스트할 창을 엽니다(닫으려면 동일한 단추를 누릅니다.)</td>
 </tr>
 <tr>
  <td><img src="assets/stream-designer-5.png"></td>
  <td>스트림에 모든 카드를 정렬합니다.</td>
 </tr>
</table>

## 스트림 만들기 {#create-a-stream}

1. 당신이 [대화 상자를 만들었습니다.](/help/marketo/product-docs/demand-generation/dynamic-chat/dialogues/create-a-dialogue.md){target=&quot;_blank&quot;}, **스트림 디자이너** 탭.

   ![](assets/stream-designer-6.png)

1. 질문 카드를 드래그하여 놓습니다.

   ![](assets/stream-designer-7.png)

1. Chatbot 응답 아래에서 원하는 방식에 대해 질문합니다.

   ![](assets/stream-designer-8.png)

   >[!TIP]
   >
   >토큰을 사용하여 알려진 채팅 방문자에 대한 경험을 개인화할 수 있습니다(예: Hello `{{lead.leadFirstName:""}}`). 오른쪽의 중괄호 아이콘을 클릭하여 선택하기만 하면 됩니다. 익명 방문자가 일반적인 항목(예: Hello `{{lead.leadFirstName:"there"}}`).

   >[!NOTE]
   >
   >포크는 기본적으로 켜짐으로 설정되어 방문자가 보지 않고 채팅 아이콘 옆에 열기 질문을 표시합니다. 포크는 대화의 첫 번째 카드에서만 사용할 수 있습니다.

1. 사용자 응답 입력 및 클릭 **저장**.

   ![](assets/stream-designer-9.png)

   >[!NOTE]
   >
   >**저장된 값 편집** 은 질문 카드에서 매핑된 속성을 위해 차트봇의 방문자에게 표시되는 것과 다른 값을 데이터베이스에 저장하려는 사용자를 위한 선택 단계입니다(예: 방문자에게는 &quot;검색 엔진 최적화&quot;가 표시되고, 그 값을 &quot;SEO&quot;로 저장합니다.

1. &quot;예&quot;의 경우 약속을 예약하려고 하므로 아래의 옵션 을 약속 스케줄러 카드 위로 드래그합니다.

   ![](assets/stream-designer-10.png)

1. 오른쪽 열의 **저장**.

   ![](assets/stream-designer-11.png)

1. 이것이 목표이므로 약속 일정 아래의 목표 카드를 드래그합니다.

   ![](assets/stream-designer-12.png)

1. 목표에 이름을 지정하고(또는 기존 목표를 선택) 을 클릭한 다음 **저장**.

   ![](assets/stream-designer-13.png)

1. &quot;아니요&quot;의 경우 메일링 목록에 추가될 것인지 확인하려고 하므로, 해당 옵션 아래의 다른 질문 카드 위로 드래그합니다.

   ![](assets/stream-designer-14.png)

1. 응답을 입력하고 방문자에 대한 응답 선택 사항을 추가합니다. 클릭 **저장** 완료 시.

   ![](assets/stream-designer-15.png)

   >[!NOTE]
   >
   >을 클릭하여 응답을 더 추가할 수 있습니다 **응답 추가**.

1. &quot;예&quot; 응답 아래에서 정보 캡처 카드 위로 드래그하여 방문자의 이메일을 수집할 수 있습니다.

   ![](assets/stream-designer-16.png)

1. 을(를) 클릭합니다. **유형** 드롭다운 및 선택 **이메일**.

   ![](assets/stream-designer-17.png)

1. 차트 보트 메시지와 자리 표시자를 입력합니다. 속성이 Marketo의 해당 필드에 매핑되어 있는지 확인하고 를 클릭합니다 **저장**.

   ![](assets/stream-designer-18.png)

   <table>
    <tr>
     <td><strong>유형</strong></td>
     <td>캡처할 정보 유형: 전화, 텍스트, 이메일.</td>
    </tr>
    <tr>
     <td><strong>챗봇 메시지</strong></td>
     <td>방문자에게 정보를 제공하라는 메시지가 표시되는 메시지입니다.</td>
    </tr>
    <tr>
     <td><strong>플레이스홀더</strong></td>
     <td>방문자가 입력할 내용을 확인하는 데 도움이 되는 샘플 텍스트입니다.</td>
    </tr>
    <tr>
     <td><strong>속성에 대한 응답 매핑</strong></td>
     <td>방문자의 응답을 Marketo 구독의 개인 레코드에 있는 해당 필드에 동기화할 수 있습니다.</td>
    </tr>
   </table>

1. 전자 메일 수집은 목표이므로 정보 캡처 아래에 목표 카드를 드래그합니다.

   ![](assets/stream-designer-19.png)

1. 목표에 이름을 지정하고(또는 기존 목표를 선택) 을 클릭한 다음 **저장**.

   ![](assets/stream-designer-20.png)

1. &quot;아니요&quot;라고 하는 경우 응답을 추가해야 합니다. 한 가지 옵션은 아래에 메시지 카드를 드래그하고 &quot;어쨌든 감사합니다&quot;라고 말하는 것입니다. 그러나 이 예에서는 대신 무료 PDF 문서를 제공합니다.

   ![](assets/stream-designer-21.png)

1. 이 예제에서는 새 문서를 만듭니다. 이름을 지정하고 이미 호스팅한 PDF의 URL을 입력한 다음 를 클릭합니다 **저장**.

   ![](assets/stream-designer-22.png)

1. 을(를) 선택합니다 **미리 보기** 대화 상자 미리 보기로 전환합니다.

   ![](assets/stream-designer-23.png)

1. 대화 상자를 활성화할 준비가 되면 **게시**.

   ![](assets/stream-designer-24.png)

>[!NOTE]
>
>게시를 클릭하기 전에 [대상 URL을 입력했습니다.](/help/marketo/product-docs/demand-generation/dynamic-chat/dialogues/audience-criteria.md#target){target=&quot;_blank&quot;}.

>[!MORELIKETHIS]
>
>* [대화 상자 만들기](/help/marketo/product-docs/demand-generation/dynamic-chat/dialogues/create-a-dialogue.md){target=&quot;_blank&quot;}
>* [대상 기준](/help/marketo/product-docs/demand-generation/dynamic-chat/dialogues/audience-criteria.md){target=&quot;_blank&quot;}
>* [보고서](/help/marketo/product-docs/demand-generation/dynamic-chat/dialogues/reports.md){target=&quot;_blank&quot;}
>* [문서 카드 사용](/help/marketo/product-docs/demand-generation/dynamic-chat/integrations/using-the-document-card.md){target=&quot;_blank&quot;}

