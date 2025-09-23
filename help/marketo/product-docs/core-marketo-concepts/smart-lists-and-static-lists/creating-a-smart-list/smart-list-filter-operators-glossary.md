---
unique-page-id: 557312
description: 스마트 목록 필터 연산자 용어집 - Marketo 문서 - 제품 설명서
title: 스마트 목록 필터 연산자 용어집
exl-id: 5a370482-f214-4909-bb49-801c1a36b153
feature: Smart Lists
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '603'
ht-degree: 14%

---

# 스마트 목록 필터 연산자 용어집 {#smart-list-filter-operators-glossary}

연산자는 특정 항목을 가져오는 데 도움이 되는 스마트 목록의 일부입니다. 필터 또는 트리거를 간단한 언어로 설명할 수 있습니다. 사용 가능한 연산자는 각 필드 유형에 따라 다릅니다.

여기 각 연산자 집합을 설명하는 용어집이 있습니다.

## 날짜 필드 {#date-fields}

![](assets/smart-list-filter-operators-glossary-1.png)

연산자를 선택하면 오른쪽이 동적으로 변경됩니다.

<table><thead>
  <tr>
    <th>연산자</th>
    <th>오른쪽</th>
    <th>설명</th>
  </tr></thead>
<tbody>
  <tr>
    <td>은(는)</td>
    <td>단일 날짜</td>
    <td>정확한 날짜 일치</td>
  </tr>
  <tr>
    <td>이(가) 아님</td>
    <td>단일 날짜</td>
    <td>지정된 날짜를 제외한 모든 날짜</td>
  </tr>
  <tr>
    <td>사이</td>
    <td>두 개의 날짜 필드</td>
    <td>지정된 두 날짜 사이의 및 날짜를 포함하는 모든 날짜</td>
  </tr>
  <tr>
    <td>이전</td>
    <td>자연어 입력*</td>
    <td>아래 다이어그램 참조</td>
  </tr>
  <tr>
    <td>이전</td>
    <td>자연어 입력*</td>
    <td>아래 다이어그램 참조</td>
  </tr>
  <tr>
    <td>향후</td>
    <td>자연어 입력*</td>
    <td>아래 다이어그램 참조</td>
  </tr>
  <tr>
    <td>향후</td>
    <td>자연어 입력*</td>
    <td>아래 다이어그램 참조</td>
  </tr>
  <tr>
    <td>시간대</td>
    <td>사전 설정(지난 분기, 어제 등)</td>
    <td>선택 목록에 정의됨</td>
  </tr>
  <tr>
    <td>다음 이후</td>
    <td>단일 날짜</td>
    <td>지정된 날짜 이후의 모든 레코드</td>
  </tr>
  <tr>
    <td>다음 이전</td>
    <td>단일 날짜</td>
    <td>지정된 레코드 이전의 모든 레코드</td>
  </tr>
  <tr>
    <td>다음 또는 이후</td>
    <td>단일 날짜</td>
    <td>"이후"와 동일하지만 포함</td>
  </tr>
  <tr>
    <td>다음 또는 이전</td>
    <td>단일 날짜</td>
    <td>"이전"과 동일하지만 다음을 포함</td>
  </tr>
  <tr>
    <td>비어 있음</td>
    <td>None</td>
    <td>날짜가 없는 모든 레코드</td>
  </tr>
  <tr>
    <td>비어 있지 않음</td>
    <td>None</td>
    <td>모든 날짜가 포함된 모든 레코드</td>
  </tr>
</tbody></table>

**&#42;** 자연어 입력이 멋집니다. 다음은 입력할 수 있는 몇 가지 패턴입니다.

* 1시간
* 82일
* 3주
* 14개월
* 1년

번호와 단위를 함께 입력하기만 하면 됩니다!

>[!NOTE]
>
>&quot;지난&quot; _does_&#x200B;에는 스마트 목록을 만드는 날(이후가 아닌 시간까지)이 포함됩니다.

>[!CAUTION]
>
>날짜 필드 필터(예: 생년월일, SFDC 생성 날짜)를 사용하여 스마트 목록을 만들고 **[!UICONTROL before]**, **[!UICONTROL on or before]** 또는 **[!UICONTROL in past before]** 제약 조건을 사용하면 해당 날짜 필드에 값이 없는 사람도 스마트 목록에 포함됩니다.

다음 다이어그램을 사용하여 날짜 연산자 간의 차이점을 이해합니다.

![](assets/smart-list-filter-operators-glossary-2.png)

>[!NOTE]
>
>**예**
>
>과거 및 미래 이벤트로 작업할 때 날짜 필드가 까다로워질 수 있습니다. 여기 몇 가지 예가 있습니다.
>
>**[!UICONTROL In past before]**
>
>새 프로모션을 위해 이 연산자를 사용하여 1년 이내에 서비스에 가입하거나 서비스를 갱신하지 않은 사람 또는 아직 가입하지 않은 사람에게만 이메일을 보냅니다.
>
>**[!UICONTROL In future after]**
>
>90일 후에 재계약을 체결하는 고객을 확인하고자 합니다. 두 개의 별도 필터를 사용합니다. 먼저 &quot;In Future After 90 Days&quot;를 사용하고 두 번째 &quot;In Future 91 Days&quot;를 사용합니다. 그러면 지금으로부터 90일 후에 날짜를 갖는 모든 사람이 캡처됩니다.

## 문자열 필드 {#string-fields}

![](assets/smart-list-filter-operators-glossary-3.png)

<table><thead>
  <tr>
    <th>연산자</th>
    <th>설명</th>
  </tr></thead>
<tbody>
  <tr>
    <td>은(는)</td>
    <td>정확한 일치(대/소문자 구분 안 함)</td>
  </tr>
  <tr>
    <td>이(가) 아님</td>
    <td>정확히 일치하는 항목을 제외한 모든 항목</td>
  </tr>
  <tr>
    <td>다음으로 시작</td>
    <td>문자열 일치의 첫 번째 문자</td>
  </tr>
  <tr>
    <td>다음으로 시작 안 함</td>
    <td>문자열의 첫 문자가 일치하지 않음</td>
  </tr>
  <tr>
    <td>포함</td>
    <td>문자열에 있는 모든 문자 일치(예: california, fortune, for)</td>
  </tr>
  <tr>
    <td>포함하지 않음</td>
    <td>문자열에 일치하는 문자가 없습니다. ("포함"의 역방향)</td>
  </tr>
  <tr>
    <td>비어 있음</td>
    <td>값이 없는 레코드(NULL)</td>
  </tr>
  <tr>
    <td>비어 있지 않음</td>
    <td>모든 값이 있는 레코드</td>
  </tr>
</tbody>
</table>

>[!TIP]
>
>음수 연산자에 양수를 사용합니다. &quot;아님&quot; 필터는 인스턴스에 있는 전체 데이터 세트를 검색해야 하므로 시간이 많이 걸릴 수 있습니다. 긍정적인 &quot;is&quot; 필터는 더 효과적인 검색 알고리즘을 활용할 수 있습니다.

## 정수 필드 {#integer-fields}

![](assets/smart-list-filter-operators-glossary-4.png)

<table><thead>
  <tr>
    <th>연산자</th>
    <th>설명</th>
  </tr></thead>
<tbody>
  <tr>
    <td>은(는)</td>
    <td>정확한 숫자 일치( = 0은 0과 NULL이 있는 두 리드를 모두 반환합니다.)</td>
  </tr>
  <tr>
    <td>이(가) 아님</td>
    <td>정확한 숫자 일치를 제외한 모든 항목</td>
  </tr>
  <tr>
    <td>사이</td>
    <td>다음 사이에 있는 모든 사람을 찾을 두 개의 값을 정의합니다(포함).</td>
  </tr>
  <tr>
    <td>다음보다 큼</td>
    <td>지정한 날짜 이상</td>
  </tr>
  <tr>
    <td>다음보다 작음</td>
    <td>다음보다 작음:</td>
  </tr>
  <tr>
    <td>최소</td>
    <td>지정된 항목(포함) 이상</td>
  </tr>
  <tr>
    <td>최대</td>
    <td>다음보다 작음: 지정(포함)</td>
  </tr>
  <tr>
    <td>비어 있음</td>
    <td>값이 없는 레코드(NULL) - 0은 숫자입니다. NULL이 아닙니다.</td>
  </tr>
  <tr>
    <td>비어 있지 않음</td>
    <td>ANY 값이 있는 레코드(0 포함)</td>
  </tr>
</tbody>
</table>

보시다시피, 이러한 연산자들은 Marketo-ese를 유창하게 구사할 수 있게 해줍니다!
