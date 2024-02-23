---
description: 스트림 디자이너 - Marketo 문서 - 제품 설명서
title: 스트림 디자이너
feature: Dynamic Chat
exl-id: 310b1dff-dd93-48a6-85c2-64c58494ce48
source-git-commit: f5f93a993d5b13c1fda0b31172393eff0bc65fd4
workflow-type: tm+mt
source-wordcount: '1108'
ht-degree: 1%

---

# 스트림 디자이너 {#stream-designer}

다음 항목이 있습니다. _많음_ 스트림 조합이 가능합니다. 이 문서에는 마케터가 사이트 방문자에게 제품 관련 질문이 있는지 묻는 예제가 포함되어 있습니다. 그렇다면 방문자는 약속을 예약할 수 있습니다. 없는 경우, 방문자에게 향후 서신을 보낼 메일링 목록에 가입할 수 있는 옵션이 제공됩니다. 무료 PDF도 제공됩니다. 최종 목표는 약속을 예약하거나 방문자의 이메일을 수집하는 것입니다.

>[!PREREQUISITES]
>
>문서 카드를 사용하려면 먼저 다음을 수행해야 합니다 [설정](/help/marketo/product-docs/demand-generation/dynamic-chat/integrations/adobe-pdf-embed-api.md){target="_blank"} Adobe 계정에서.

## 스트림 디자이너 카드 {#stream-designer-cards}

스트림 디자이너에는 채팅 대화를 형성하는 데 추가할 수 있는 여러 카드가 포함되어 있습니다.

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
  <td>대화 상자에 PDF 문서를 포함하고 방문자의 문서 참여 활동(문서를 다운로드한 경우 본 페이지 수 및/또는 사용된 검색어)을 추적할 수 있습니다.</td>
 </tr>
 <tr>
  <td style="width:25%"><strong>정보 캡처</strong></td>
  <td>정보(예: 이름, 이메일 주소, 직함 등)를 수집하려는 경우 사용합니다. 응답을 지정할 필드를 선택한 후 방문자가 해당 응답에 입력할 수 있도록 하거나 사용자가 결정한 선택 목록에서 옵션을 선택할 수 있습니다(팁: 후자가 데이터베이스 청결도에 도움이 될 수 있음). 현재 나열된 모든 데이터를 해당 응답과 함께 덮어쓰거나 이미 값이 있는 경우 질문을 완전히 건너뛰도록 선택할 수도 있습니다.</td>
 </tr>
 <tr>
  <td style="width:25%"><strong>모임 예약</strong></td>
  <td>방문자에게 회의 일정을 잡을 수 있는 날짜 일정을 제공합니다. 라운드 로빈, 특정 에이전트를 통해 또는 사용자 지정 규칙을 사용하여 일정 가용성을 선택합니다. 클릭 <b>속성 추가</b> 에이전트의 이름 또는 이메일 주소를 캡처하고 나중에 쿼리하기 위해 채팅 방문자의 개인 레코드에 할당하려는 경우(팁: <a href="/help/marketo/product-docs/administration/field-management/create-a-custom-field-in-marketo.md" target="_blank">사용자 정의 필드</a> 표준 Marketo Engage 필드를 덮어쓰지 않도록 에이전트의 정보를 로 매핑).</td>
 </tr>
 <tr>
  <td style="width:25%"><strong>목표</strong></td>
  <td>방문자가 볼 수 없는 유일한 카드입니다. 특정 채팅 내에서 어느 시점에 목표가 달성되었는지 확인하는 것입니다(예: 방문자의 이메일을 수집하는 것이 본인의 목표인 경우 스트림에서 정보 캡처 바로 뒤에 목표 카드를 놓으십시오).</td>
 </tr>
 <tr>
  <td style="width:25%"><strong>액션</strong></td>
  <td>양식의 숨겨진 필드와 유사하며 작업 카드로 잠재 고객 또는 회사 속성(이 있는 경우 <a href="/help/marketo/product-docs/administration/field-management/custom-field-type-glossary.md#string">문자열 데이터 형식</a>잠재 고객 레코드와 비교하여 캡처할 암시적 값이 있는 대화의 어느 시점에서든 작업 카드를 추가하고 각 속성을 값 또는 해당 값을 자동으로 채우는 기본 토큰으로 업데이트할 수 있습니다.</td>
 </tr>
 <tr>
  <td style="width:25%"><strong>라이브 채팅</strong></td>
  <td>방문자가 라이브 에이전트와 채팅하도록 하려면 라이브 채팅 카드를 사용하십시오.
  <li>라이브 채팅 카드가 분기의 마지막 카드여야 합니다.</li>
  <li>방문자는 스트림의 이 카드에 도달하면 에이전트로 라우팅됩니다. 따라서 방문자에게 라이브 에이전트와 채팅할 것인지 묻는 질문 카드와 함께 이 카드 앞에 서는 것이 좋습니다.</li></td>
 </tr>
</table>

## 스트림 디자이너 아이콘 {#stream-designer-icons}

스트림 디자이너의 오른쪽 상단에는 몇 가지 아이콘이 표시됩니다. 그들이 하는 일은 다음과 같습니다.

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

대화 상자 또는 [대화형 Forms](/help/marketo/product-docs/demand-generation/dynamic-chat/automated-chat/conversational-flow-overview.md){target="_blank"}. 이 예제에서는 대화 상자에 대해 하나를 만들겠습니다.

1. 다음 작업을 수행한 후 [이(가) 내 대화 상자를 만들었습니다.](/help/marketo/product-docs/demand-generation/dynamic-chat/automated-chat/create-a-dialogue.md){target="_blank"}를 클릭하고 **[!UICONTROL 스트림 디자이너]** 탭.

   ![](assets/stream-designer-6.png)

1. 을(를) 끌어다 놓습니다. [!UICONTROL 질문] 카드.

   ![](assets/stream-designer-7.png)

1. 아래 [!UICONTROL 챗봇 응답], 원하는 방식으로 질문에 답변합니다.

   ![](assets/stream-designer-8.png)

   >[!TIP]
   >
   >토큰을 사용하여 알려진 채팅 방문자에 대한 경험을 개인화할 수 있습니다(예: Hello `{{lead.leadFirstName:""}}`). 오른쪽에 있는 중괄호 아이콘을 클릭하고 원하는 항목을 선택하십시오. 익명 방문자에게 일반적인 것을 표시하려면 따옴표 사이에 기본값을 추가합니다(예: Hello `{{lead.leadFirstName:"there"}}`).

   >[!NOTE]
   >
   >Poke는 기본적으로 on으로 설정되어 있으며, 방문자가 채팅 아이콘을 클릭하여 보지 않아도 채팅 아이콘 옆에 열린 질문을 표시합니다. Poke는 대화의 첫 번째 카드에서만 사용할 수 있습니다.

1. 사용자 응답을 입력하고 **[!UICONTROL 저장]**.

   ![](assets/stream-designer-9.png)

   >[!NOTE]
   >
   >**[!UICONTROL 저장된 값 편집]** 는 질문 카드에서 매핑된 속성을 위해 챗봇의 방문자에게 표시되는 것과 다른 값을 데이터베이스에 저장하려는 사용자를 위한 선택적 단계입니다(예: 방문자에게 &quot;검색 엔진 최적화&quot;가 표시되면 해당 값을 &quot;SEO&quot;로 저장).

1. &quot;예&quot;의 경우 약속을 예약하려고 하므로 해당 옵션 아래에 약속 스케줄러 카드로 끌어서 놓습니다.

   ![](assets/stream-designer-10.png)

1. 오른쪽 열에서 **[!UICONTROL 저장]**.

   ![](assets/stream-designer-11.png)

1. 목표이므로 을(를) 드래그합니다. [!UICONTROL 목표] 약속 스케줄러 아래의 카드.

   ![](assets/stream-designer-12.png)

1. 목표에 이름을 지정하고(또는 기존 목표를 선택) **[!UICONTROL 저장]**.

   ![](assets/stream-designer-13.png)

1. &quot;아니요&quot;에 대해서는 메일링 목록에 추가될지 확인하고 싶으므로 해당 옵션 아래는 다른 옵션을 끌어서 놓습니다 [!UICONTROL 질문] 카드.

   ![](assets/stream-designer-14.png)

1. 응답을 입력하고 방문자에 대한 응답 선택 사항을 추가합니다. 클릭 **[!UICONTROL 저장]** 완료 시.

   ![](assets/stream-designer-15.png)

   >[!NOTE]
   >
   >다음을 클릭하여 응답을 추가할 수 있습니다. **[!UICONTROL 응답 추가]**.

1. &quot;예&quot; 응답 아래에서 방문자의 이메일을 수집할 수 있도록 정보 캡처 카드 위로 드래그합니다.

   ![](assets/stream-designer-16.png)

1. 다음을 클릭합니다. **[!UICONTROL 유형]** 드롭다운 및 선택 **[!UICONTROL 이메일]**.

   ![](assets/stream-designer-17.png)

1. 챗봇 메시지 및 자리 표시자를 입력합니다. 속성이 Marketo의 적절한 필드에 매핑되어 있는지 확인하고 **[!UICONTROL 저장]**.

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
     <td>Marketo 구독에서 방문자의 응답을 개인 레코드의 해당 필드에 동기화할 수 있습니다.</td>
    </tr>
   </table>

1. 이메일 수집이 목표이므로 을(를) 드래그합니다. [!UICONTROL 목표] 정보 캡처 아래에 있는 카드.

   ![](assets/stream-designer-19.png)

1. 목표에 이름을 지정하고(또는 기존 목표를 선택) **[!UICONTROL 저장]**.

   ![](assets/stream-designer-20.png)

1. &quot;아니요&quot;라고 말하면 응답을 추가하는 것을 잊지 마십시오. 한 가지 옵션은 아래에 메시지 카드를 드래그하여 &quot;어쨌든 감사합니다.&quot;라고 말하는 것입니다. 그러나 이 예제에서는 무료 PDF 문서를 대신 제공합니다.

   ![](assets/stream-designer-21.png)

1. 이 예제에서는 새 문서를 만듭니다. 이름을 지정하고 이미 호스팅된 PDF의 URL을 입력한 다음 을 클릭합니다. **[!UICONTROL 저장]**.

   ![](assets/stream-designer-22.png)

1. 다음 항목 선택 **[!UICONTROL 미리 보기]** 대화 상자를 미리 보려면 전환합니다.

   ![](assets/stream-designer-23.png)

1. 대화 상자를 활성화할 준비가 되면 다음을 클릭하십시오. **[!UICONTROL 게시]**.

   ![](assets/stream-designer-24.png)

>[!NOTE]
>
>클릭 전 [!UICONTROL 게시], 다음을 했는지 확인하십시오. [대상 URL을 입력했습니다.](/help/marketo/product-docs/demand-generation/dynamic-chat/automated-chat/audience-criteria.md#target){target="_blank"}.

>[!MORELIKETHIS]
>
>* [대화 상자 만들기](/help/marketo/product-docs/demand-generation/dynamic-chat/automated-chat/create-a-dialogue.md){target="_blank"}
>* [대상 기준](/help/marketo/product-docs/demand-generation/dynamic-chat/automated-chat/audience-criteria.md){target="_blank"}
>* [Adobe PDF 포함 API](/help/marketo/product-docs/demand-generation/dynamic-chat/integrations/adobe-pdf-embed-api.md){target="_blank"}
