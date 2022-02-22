---
description: 대화 상자 - Marketo 문서 - 제품 설명서
title: 대화 상자
exl-id: 5ec17ad0-6d56-4c06-a6ac-4c5771b2d91d
source-git-commit: 8aaa6f5225f7965228c3472c0cf6beb2259f3642
workflow-type: tm+mt
source-wordcount: '745'
ht-degree: 0%

---

# 대화 상자 {#dialogues}

대화 상자는 개별 채팅 대화입니다. 시각적으로 사용자 지정하고, 페이지가 표시되는 페이지를 결정하며, 표시되는 페이지와 이를 보는 사용자를 결정하는 방법을 알아봅니다.

## 새 대화 상자 만들기 {#create-a-new-dialogue}

1. 클릭 **대화 상자**.

   ![](assets/dialogues-1.png)

1. 을(를) 클릭합니다. **새로 만들기** 버튼을 클릭합니다.

   ![](assets/dialogues-2.png)

1. 이름을 입력하고(설명 선택 사항) 우선 순위 수준을 설정한 다음 **저장**.

   ![](assets/dialogues-3.png)

>[!NOTE]
>
>우선 순위는 방문자가 여러 대화 상자에 동시에 적합한 경우 방문자에게 표시할 대화 상자를 결정합니다.

## 대상 기준 {#audience-criteria}

Marketo 스마트 목록과 유사한 대상 기준 속성을 사용하여 타겟 대상을 정의할 수 있습니다. 추론된, 개인 또는 회사 속성(또는 이들의 조합)을 사용하여 알려진 사람 또는 알 수 없는 사람을 타깃팅할 수 있습니다.

**알려진 사람**

있습니다 _많은_ 선택할 속성 조합입니다. 이 예에서는 모두 타겟팅합니다 **알려진 사람** 50명 이상의 직원을 가진 회사에서 일하는 캘리포니아에서.

1. 을 선택합니다. **개인 주** 속성을 지정하고 오른쪽으로 드래그합니다.

   ![](assets/dialogues-4.png)

1. _다음_ 은 기본적으로 설정되어 있습니다. 값 선택 필드에 CA를 입력합니다. 드롭다운을 클릭하고 목록에서 선택할 수도 있습니다.

   ![](assets/dialogues-5.png)

1. 을 선택합니다. **회사 크기** 속성을 지정한 위치로 드래그합니다. _특성을 여기에 끌어다 놓습니다._.

   ![](assets/dialogues-6.png)

   >[!NOTE]
   >
   >속성을 클릭하여 선택할 수도 있습니다 **+** 아이콘.

1. 연산자 드롭다운을 클릭하고 을(를) 선택합니다 **보다 큼**.

   ![](assets/dialogues-7.png)

1. 50을 입력하고 화면의 아무 곳이나 클릭하여 저장합니다.

   ![](assets/dialogues-8.png)

그게 다야!

**익명 사용자**

아직 데이터베이스에 없는 사용자를 대상으로 하는 쉬운 방법이 있습니다. 이 예에서는 모두 타겟팅합니다 **익명의 사람들** 뉴욕 지역에 위치하고 있습니다.

1. 을 선택합니다. **개인 이메일** 속성을 지정하고 오른쪽으로 드래그합니다.

   ![](assets/dialogues-9.png)

1. 연산자 드롭다운을 클릭하고 을(를) 선택합니다 **비어 있음**.

   ![](assets/dialogues-10.png)

1. 을 선택합니다. **유추 상태** 속성을 지정한 위치로 드래그합니다. _특성을 여기에 끌어다 놓습니다._.

   ![](assets/dialogues-11.png)

   >[!NOTE]
   >
   >누군가 여러분의 웹 사이트를 방문하면, [Munchkin](/help/marketo/product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website.md) 쿠키로 구워서 시스템에 넣습니다. 특수 데이터베이스에서 IP를 조회하고 모든 종류의 좋은 정보를 추론합니다.

1. _다음_ 은 기본적으로 설정되어 있습니다. 값 선택 필드에 NY를 입력합니다(드롭다운을 클릭하고 목록에서 선택할 수도 있음).

   ![](assets/dialogues-12.png)

## 그룹 추가 {#add-groups}

다른 속성의 &quot;모두&quot; 또는 &quot;모두&quot;와 함께 모든 특정 속성을 포함하려는 경우 속성을 그룹화하는 옵션이 있습니다. 여러 그룹을 추가할 수 있습니다.

![](assets/dialogues-13.png)

![](assets/dialogues-14.png)

## Target {#target}

여기에서 특정 대화 상자를 표시할 URL을 입력합니다.

허용 가능한 형식:

* `http://website.com`
* `https://*.website.com`
* `http://website.com/folder/*`
* `https://*.website.com/folder/*`

>[!NOTE]
>
>별표를 사용하는 것은 다목적 엽서 역할을 합니다. 그래서 `https://*.website.com` 은 하위 도메인을 포함하여 사이트의 모든 페이지에 대화 상자를 둡니다(예: `support.website.com`). 및 `https://website.com/folder/*` 대화 상자가 후속 폴더의 모든 HTML 페이지에 표시됩니다(예: 이 경우 폴더가 &quot;sports&quot;라고 가정해 보겠습니다. website.com/sports/baseball.html, website.com/sports/football.html 등)

## 스트림 디자이너 {#stream-designer}

스트림 디자이너에는 채팅 대화 모양을 만들기 위해 추가할 수 있는 다른 카드가 포함되어 있습니다.

<table>
 <tr>
  <td><strong>본문</strong></td>
  <td>응답 없이 구문을 만들려면(예: "안녕! SAVE25" 코드를 사용하면 모든 항목이 오늘 25% 할인됩니다.
</td>
 </tr>
 <tr>
  <td><strong>질문</strong></td>
  <td>사용 가능한 응답을 제공하는 다중 선택 질문을 하려면 를 사용합니다(예: 어떤 차종에 관심이 있으십니까? 응답 = SUV, 컴팩트, 트럭 등).</td>
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

**스트림 만들기**

있습니다 _많은_ 가능한 스트림 조합입니다. 한 예를 살펴보겠습니다 [이 문서](/help/marketo/product-docs/demand-generation/dynamic-chat/create-a-stream.md).

## 보고서 {#reports}

보고서 탭에서 지난 90일의 데이터를 봅니다. 각 카테고리는 아래에 정의되어 있습니다.

<table>
 <tr>
  <td><strong>총 트리거됨</strong></td>
  <td>방문자가 자격을 얻거나 대화 상자를 표시할 때마다 증가합니다.
</td>
 </tr>
 <tr>
  <td><strong>참여</strong></td>
  <td>방문자가 chatbot 앵커를 클릭하여 대화 상자를 열 때마다 증가합니다.</td>
 </tr>
 <tr>
  <td><strong>완료됨</strong></td>
  <td>방문자가 대화 상자의 모든 분기 끝에 도달할 때마다 증가합니다.</td>
 </tr>
 <tr>
  <td><strong>잡힌 사람</strong></td>
  <td>방문자가 대화 상자 흐름에서 유효한 이메일 주소를 제공할 때마다 증가합니다.</td>
 </tr>
 <tr>
  <td><strong>예약된 모임</strong></td>
  <td>방문자가 chatbot을 통해 약속을 성공적으로 예약할 때마다 증가합니다.</td>
 </tr>
 <tr>
  <td><strong>목표 달성</strong></td>
  <td>방문자가 모든 대화 상자 흐름에서 목표에 도달할 때마다 증가합니다.</td>
 </tr>
</table>

>[!MORELIKETHIS]
>
>[스트림 만들기](/help/marketo/product-docs/demand-generation/dynamic-chat/create-a-stream.md)
