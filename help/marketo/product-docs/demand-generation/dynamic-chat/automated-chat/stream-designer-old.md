---
description: Stream Designer - Marketo 문서 - 제품 설명서
title: 스트림 디자이너
hide: true
hidefromtoc: true
feature: Dynamic Chat
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '1103'
ht-degree: 2%

---

# 스트림 디자이너 {#stream-designer}

가능한 _많은_ 스트림 조합이 있습니다. 이 문서에는 마케터가 사이트 방문자에게 제품 관련 질문이 있는지 묻는 예제가 포함되어 있습니다. 그렇다면 방문자는 약속을 예약할 수 있습니다. 없는 경우, 방문자에게 향후 서신을 보낼 메일링 목록에 가입할 수 있는 옵션이 제공됩니다. 무료 PDF도 제공됩니다. 최종 목표는 약속을 예약하거나 방문자의 이메일을 수집하는 것입니다.

>[!PREREQUISITES]
>
>문서 카드를 사용하려면 먼저 Adobe 계정에서 [설정](/help/marketo/product-docs/demand-generation/dynamic-chat/integrations/adobe-pdf-embed-api.md){target="_blank"}해야 합니다.

## Designer 카드 스트리밍 {#stream-designer-cards}

스트림 Designer에는 채팅 대화를 형성하는 데 추가할 수 있는 여러 카드가 포함되어 있습니다.

<table>
 <tr>
  <td style="width:25%"><strong>메시지</strong></td>
  <td>응답이 필요하지 않은 명령문을 만들고자 할 때 사용합니다(예: "안녕하세요! 모든 품목은 오늘 25% 할인 코드 SAVE25").
</td>
 </tr>
 <tr>
  <td style="width:25%"><strong>질문</strong></td>
  <td>사용 가능한 응답(예: 어떤 유형의 차량에 관심이 있습니까?)을 제공하는 객관식 질문을 하려는 경우 사용합니다. 응답 = SUV, 소형, 트럭 등).</td>
 </tr>
 <tr>
  <td style="width:25%"><strong>문서</strong></td>
  <td>대화 상자에 PDF 문서를 임베드하고 방문자의 문서 참여 활동(문서가 다운로드된 경우 본 페이지 수 및/또는 사용된 검색어)을 추적할 수 있습니다.</td>
 </tr>
 <tr>
  <td style="width:25%"><strong>정보 캡처</strong></td>
  <td>정보(예: 이름, 이메일 주소, 직함 등)를 수집하려는 경우 사용합니다. 응답을 지정할 필드를 선택한 후 방문자가 해당 응답에 입력할 수 있도록 하거나 사용자가 결정한 선택 목록에서 옵션을 선택할 수 있습니다(팁: 후자가 데이터베이스 청결도에 도움이 될 수 있음). 현재 나열된 모든 데이터를 해당 응답과 함께 덮어쓰거나 이미 값이 있는 경우 질문을 완전히 건너뛰도록 선택할 수도 있습니다.</td>
 </tr>
 <tr>
  <td style="width:25%"><strong>모임 예약</strong></td>
  <td>방문자에게 회의 일정을 잡을 수 있는 날짜 일정을 제공합니다. 라운드 로빈, 특정 에이전트를 통해 또는 사용자 지정 규칙을 사용하여 일정 가용성을 선택합니다. 에이전트의 이름 또는 전자 메일 주소를 캡처하고 나중에 쿼리할 수 있도록 채팅 방문자의 개인 레코드에 할당하려면 <b>특성 추가</b>를 클릭합니다(팁: 에이전트의 정보를 매핑하여 표준 Marketo Engage 필드를 덮어쓰지 않도록 <a href="/help/marketo/product-docs/administration/field-management/create-a-custom-field-in-marketo.md" target="_blank">사용자 지정 필드 만들기</a>).</td>
 </tr>
 <tr>
  <td style="width:25%"><strong>목표</strong></td>
  <td>방문자가 볼 수 없는 유일한 카드입니다. 특정 채팅 내에서 어느 시점에 목표가 달성되었는지 확인하는 것입니다(예: 방문자의 이메일을 수집하는 것이 본인의 목표인 경우 스트림에서 정보 캡처 바로 뒤에 목표 카드를 놓으십시오).</td>
 </tr>
 <tr>
  <td style="width:25%"><strong>작업*</strong></td>
  <td>양식의 숨겨진 필드와 마찬가지로 작업 카드를 사용하여 잠재 고객 또는 회사 특성(<a href="/help/marketo/product-docs/administration/field-management/custom-field-type-glossary.md#string">문자열 데이터 형식</a>이 있음)을 잠재 고객 레코드에 대해 캡처하려는 암시적 값으로 채울 수 있습니다. 대화의 어느 시점에서든 작업 카드를 추가하고 각 속성을 값 또는 해당 값을 자동으로 채우는 기본 토큰으로 업데이트할 수 있습니다.
  <p><i>* 작업 카드에는 Dynamic Chat Prime이 필요합니다. 자세한 내용은 Adobe 계정 팀(계정 관리자)에 문의하십시오.</i></td>
 </tr>
 <tr>
  <td style="width:25%"><strong>라이브 채팅</strong></td>
  <td>방문자가 라이브 에이전트와 채팅하도록 하려면 라이브 채팅 카드를 사용하십시오.
  <li>라이브 채팅 카드가 분기의 마지막 카드여야 합니다.</li>
  <li>방문자는 스트림의 이 카드에 도달하면 에이전트로 라우팅됩니다. 따라서 방문자에게 라이브 에이전트와 채팅할 것인지 묻는 질문 카드와 함께 이 카드 앞에 서는 것이 좋습니다.</li></td>
 </tr>
</table>

## 스트림 Designer 아이콘 {#stream-designer-icons}

스트림 Designer 오른쪽 상단에 아이콘이 표시됩니다. 그들이 하는 일은 다음과 같습니다.

<table>
 <tr>
  <td style="width:10%"><img src="assets/stream-designer-1.png"></td>
  <td>확대하기, 더 큰 카드 만들기</td>
 </tr>
 <tr>
  <td style="width:10%"><img src="assets/stream-designer-2.png"></td>
  <td>축소하여 더 작은 카드 만들기</td>
 </tr>
 <tr>
  <td style="width:10%"><img src="assets/stream-designer-3.png"></td>
  <td>채팅을 테스트할 수 있는 창을 엽니다(닫으려면 동일한 버튼 누름).</td>
 </tr>
 <tr>
  <td style="width:10%"><img src="assets/stream-designer-4.png"></td>
  <td>스트림 내에서 카드 유형 또는 콘텐츠를 검색할 수 있습니다.</td>
 </tr>
 <tr>
  <td style="width:10%"><img src="assets/stream-designer-5.png"></td>
  <td>스트림에 있는 모든 카드 정렬</td>
 </tr>
</table>

## 스트림 만들기 {#create-a-stream}

대화 상자 또는 [대화형 Forms](/help/marketo/product-docs/demand-generation/dynamic-chat/automated-chat/conversational-flow-overview.md){target="_blank"}에 대한 스트림을 만들 수 있습니다. 이 예제에서는 대화 상자에 대해 하나를 만들겠습니다.

1. [대화 상자를 만든](/help/marketo/product-docs/demand-generation/dynamic-chat/automated-chat/create-a-dialogue.md){target="_blank"}후 **[!UICONTROL Stream Designer]** 탭을 클릭합니다.

   ![](assets/stream-designer-6.png)

1. [!UICONTROL Question] 카드를 끌어서 놓습니다.

   ![](assets/stream-designer-7.png)

1. [!UICONTROL Chatbot Response]에서 원하는 방식으로 질문하세요.

   ![](assets/stream-designer-8.png)

   >[!TIP]
   >
   >토큰을 사용하여 알려진 채팅 방문자에 대한 환경을 개인화할 수 있습니다(예: `{{lead.leadFirstName:""}}` 님 안녕하세요). 오른쪽에 있는 중괄호 아이콘을 클릭하고 원하는 항목을 선택하십시오. 익명 방문자에게 일반적인 내용을 보려면 따옴표 사이에 기본값을 추가하십시오(예: `{{lead.leadFirstName:"there"}}` 안녕하세요.).

   >[!NOTE]
   >
   >Poke는 기본적으로 on으로 설정되어 있으며, 방문자가 채팅 아이콘을 클릭하여 보지 않아도 채팅 아이콘 옆에 열린 질문을 표시합니다. Poke는 대화의 첫 번째 카드에서만 사용할 수 있습니다.

1. 사용자 응답을 입력하고 **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

   ![](assets/stream-designer-9.png)

   >[!NOTE]
   >
   >**[!UICONTROL Edit Stored Values]**&#x200B;은(는) 질문 카드에서 매핑된 속성을 위해 챗봇의 방문자에게 표시되는 내용과 다른 값을 데이터베이스에 저장하려는 사용자를 위한 선택적 단계입니다(예: 방문자에게 &quot;검색 엔진 최적화&quot;가 표시되고 해당 값을 &quot;SEO&quot;로 저장함).

1. &quot;예&quot;의 경우 약속을 예약하려고 하므로 해당 옵션 아래에 약속 스케줄러 카드로 끌어서 놓습니다.

   ![](assets/stream-designer-10.png)

1. 오른쪽 열에서 **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

   ![](assets/stream-designer-11.png)

1. 목표이므로 약속 스케줄러 아래에 있는 [!UICONTROL Goal] 카드를 끌어서 놓습니다.

   ![](assets/stream-designer-12.png)

1. 목표의 이름을 지정하거나 기존 목표를 선택하고 **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

   ![](assets/stream-designer-13.png)

1. &quot;아니요&quot;의 경우 메일 그룹에 가입할 것인지 확인하고 싶으므로 해당 옵션 아래에 다른 [!UICONTROL Question] 카드를 끌어 놓습니다.

   ![](assets/stream-designer-14.png)

1. 응답을 입력하고 방문자에 대한 응답 선택 사항을 추가합니다. 완료되면 **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

   ![](assets/stream-designer-15.png)

   >[!NOTE]
   >
   >**[!UICONTROL Add Response]**&#x200B;을(를) 클릭하여 응답을 더 추가할 수 있습니다.

1. &quot;예&quot; 응답 아래에서 방문자의 이메일을 수집할 수 있도록 정보 캡처 카드 위로 드래그합니다.

   ![](assets/stream-designer-16.png)

1. **[!UICONTROL Type]** 드롭다운을 클릭하고 **[!UICONTROL Email]**&#x200B;를 선택합니다.

   ![](assets/stream-designer-17.png)

1. 챗봇 메시지 및 자리 표시자를 입력합니다. 특성이 Marketo Engage의 적절한 필드에 매핑되어 있는지 확인하고 **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

   ![](assets/stream-designer-18.png)

   <table>
    <tr>
     <td style="width:30%"><strong>유형</strong></td>
     <td>캡처할 정보 유형(전화, 텍스트, 이메일)입니다.</td>
    </tr>
    <tr>
     <td style="width:30%"><strong>챗봇 메시지</strong></td>
     <td>방문자에게 정보를 입력하라는 메시지가 표시됩니다.</td>
    </tr>
    <tr>
     <td style="width:30%"><strong>플레이스홀더</strong></td>
     <td>방문자가 입력할 내용을 확인하는 데 도움이 되는 샘플 텍스트입니다.</td>
    </tr>
    <tr>
     <td style="width:30%"><strong>속성에 대한 응답 매핑</strong></td>
     <td>Marketo Engage 구독에서 방문자의 응답을 개인 레코드의 해당 필드에 동기화할 수 있습니다.</td>
    </tr>
   </table>

1. 전자 메일 수집이 목표이므로 [!UICONTROL Goal] 카드를 정보 캡처 아래에 끌어 놓으십시오.

   ![](assets/stream-designer-19.png)

1. 목표의 이름을 지정하거나 기존 목표를 선택하고 **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

   ![](assets/stream-designer-20.png)

1. &quot;아니요&quot;라고 말하면 응답을 추가하는 것을 잊지 마십시오. 한 가지 옵션은 아래에 메시지 카드를 드래그하여 &quot;어쨌든 감사합니다.&quot;라고 말하는 것입니다. 그러나 이 예제에서는 무료 PDF 문서를 대신 제공합니다.

   ![](assets/stream-designer-21.png)

1. 이 예제에서는 새 문서를 만듭니다. 이름을 지정하고 이미 호스팅한 PDF의 URL을 입력한 다음 **[!UICONTROL Save]**&#x200B;을(를) 클릭합니다.

   ![](assets/stream-designer-22.png)

1. 대화 상자를 미리 보려면 **[!UICONTROL Preview]** 전환을 선택하십시오.

   ![](assets/stream-designer-23.png)

1. 대화 상자를 활성화할 준비가 되면 **[!UICONTROL Publish]**&#x200B;을(를) 클릭합니다.

   ![](assets/stream-designer-24.png)

>[!NOTE]
>
>[!UICONTROL Publish]을(를) 클릭하기 전에 [대상 URL](/help/marketo/product-docs/demand-generation/dynamic-chat/automated-chat/audience-criteria.md#target){target="_blank"}을(를) 입력했는지 확인하십시오.

>[!MORELIKETHIS]
>
>* [대화 상자 만들기](/help/marketo/product-docs/demand-generation/dynamic-chat/automated-chat/create-a-dialogue.md){target="_blank"}
>* [대상 기준](/help/marketo/product-docs/demand-generation/dynamic-chat/automated-chat/audience-criteria.md){target="_blank"}
>* [Adobe PDF 포함 API](/help/marketo/product-docs/demand-generation/dynamic-chat/integrations/adobe-pdf-embed-api.md){target="_blank"}
