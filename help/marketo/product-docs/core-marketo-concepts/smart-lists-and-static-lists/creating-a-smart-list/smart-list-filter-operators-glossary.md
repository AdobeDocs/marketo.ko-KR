---
unique-page-id: 557312
description: 스마트 목록 필터 연산자 용어집 - 마케팅 문서 - 제품 설명서
title: 스마트 목록 필터 연산자 용어집
translation-type: tm+mt
source-git-commit: 5b9f48c98464c79bcdca2e335f6a4a2edce98ce4
workflow-type: tm+mt
source-wordcount: '602'
ht-degree: 0%

---


# 스마트 목록 필터 연산자 용어집 {#smart-list-filter-operators-glossary}

연산자는 특정 정보를 얻을 수 있는 스마트 목록의 일부입니다. 필터를 설명하거나 간단한 언어로 트리거할 수 있습니다. 사용 가능한 연산자는 각 필드 유형에 따라 다릅니다.

각 연산자 집합을 설명하는 용어집이 있습니다.

## 날짜 필드 {#date-fields}

![](assets/image2014-9-10-17-3a15-3a47.png)

연산자를 선택하면 오른쪽이 동적으로 변경됩니다.

| 연산자 | 오른쪽 | 설명 |
|---|---|---|
| is | 단일 날짜 | 정확한 날짜 일치 |
| is not | 단일 날짜 | 지정된 날짜를 제외한 모든 날짜 |
| between | 두 날짜 필드 | 지정된 두 날짜 사이의 모든 날짜 |
| 과거 | 자연어 입력* | 아래 다이어그램 참조 |
| 과거 | 자연어 입력* | 아래 다이어그램 참조 |
| 미래 | 자연어 입력* | 아래 다이어그램 참조 |
| 미래 | 자연어 입력* | 아래 다이어그램 참조 |
| 시간 프레임 | 사전 설정(지난 분기, 어제 등) | 선택 목록에 정의됨 |
| after | 단일 날짜 | 지정된 날짜 이후의 모든 레코드 |
| before | 단일 날짜 | 지정된 레코드 이전의 모든 레코드 |
| 또는 그 이후에 | 단일 날짜 | &quot;after&quot;와 동일하지만 포함 |
| 또는 그 전에 | 단일 날짜 | &quot;before&quot;와 동일하지만 포함 |
| 비어 있음 | 없음 | 날짜가 없는 모든 레코드 |
| 비어 있지 않음 | 없음 | 날짜가 있는 모든 레코드 |

* 자연어 입력은 좋다. 다음은 입력할 수 있는 패턴입니다.

* 1시간
* 82일
* 3주
* 14개월
* 1년

숫자와 단위를 함께 입력하기만 하면 됩니다!

>[!NOTE]
>
>&quot;과거&quot; **는 날짜를 포함시킵니다(시간이 아닌 이후까지).**

>[!CAUTION]
>
>날짜 필드 필터(예: 생년월일, SFDC 만든 날짜)를 사용하여 스마트 목록을 만들고 **이전 또는**&#x200B;에 **을(를) 사용하고** 이전 또는 제약 조건을 사용하는 경우 스마트 목록에는 같은 날짜 필드에 값이 없는 사람도 포함됩니다.

날짜 연산자 간의 차이를 이해하려면 다음 다이어그램을 사용하십시오.

![](assets/image2014-9-10-17-3a15-3a58.png)

>[!NOTE]
>
>**예**
>
>이전 및 향후 이벤트를 사용하여 작업할 때 날짜 필드를 복잡하게 만들 수 있습니다. 다음은 몇 가지 예입니다.
>
>**과거**
>
>새로운 판촉 행사의 경우, 이 연산자를 사용하여 1년 이내에 서비스에 가입하지 않았거나 구독하지 않은 사람에게만 이메일을 보냅니다.
>
>**In future after**
>
>90일 이내에 갱신하려는 고객을 확인하시기 바랍니다. 두 개의 개별 필터를 사용합니다. 먼저 &quot;In Future After 90일&quot; 및 &quot;In Future 91일&quot;을 사용합니다. 그러면 누가 90일 후에 데이트를 할 수 있죠

## 문자열 필드 {#string-fields}

![](assets/image2014-9-10-17-3a16-3a6.png)

| 연산자 | 설명 |
|---|---|
| is | 정확히 일치(대/소문자 구분 안 함) |
| is not | 정확히 일치하는 것을 제외한 모든 것 |
| 다음으로 시작 | 문자열 일치 첫 문자 |
| 다음으로 시작 안 함 | 문자열 DO의 첫 번째 문자가 일치하지 않음 |
| contains | 문자열 일치에 있는 모든 문자(예:캘리포니아, 포춘, 유포) |
| 포함하지 않음 | 문자열에서 일치하는 문자가 없습니다. (포함) |
| 비어 있음 | 값이 없는 레코드(NULL) |
| 비어 있지 않음 | 모든 값으로 기록 |

>[!TIP]
>
>네거티브 연산자에 양수를 사용합니다. &quot;not&quot; 필터는 인스턴스에 있는 전체 데이터 세트를 검색해야 하므로 시간이 많이 걸릴 수 있습니다. 긍정적인 &quot;is&quot; 필터는 보다 효과적인 검색 알고리즘을 활용할 수 있습니다.

## 정수 필드 {#integer-fields}

![](assets/image2014-9-10-17-3a16-3a14.png)

<table> 
 <thead> 
  <tr> 
   <th colspan="1" rowspan="1">연산자</th> 
   <th colspan="1" rowspan="1">설명</th> 
  </tr> 
 </thead> 
 <tbody> 
  <tr> 
   <td colspan="1" rowspan="1">is</td> 
   <td colspan="1" rowspan="1">정확한 숫자 일치( = 0은 0 <em>과 </em> NULL이 있는 두 리드 모두 반환합니다.)</td> 
  </tr> 
  <tr> 
   <td colspan="1" rowspan="1">is not</td> 
   <td colspan="1" rowspan="1">정확한 숫자를 제외한 모든 것 일치</td> 
  </tr> 
  <tr> 
   <td colspan="1" rowspan="1">between</td> 
   <td colspan="1" rowspan="1">두 값을 정의하여 (포함) 사이의 모든 사용자를 찾습니다.</td> 
  </tr> 
  <tr> 
   <td colspan="1" rowspan="1">보다 큼</td> 
   <td colspan="1" rowspan="1">지정된 항목 위</td> 
  </tr> 
  <tr> 
   <td colspan="1" rowspan="1">보다 작음</td> 
   <td colspan="1" rowspan="1">지정된 값보다 작음</td> 
  </tr> 
  <tr> 
   <td colspan="1" rowspan="1">적어도</td> 
   <td colspan="1" rowspan="1">지정된 항목 위(포함)</td> 
  </tr> 
  <tr> 
   <td colspan="1" rowspan="1">거의</td> 
   <td colspan="1" rowspan="1">지정된(포함)보다 작음</td> 
  </tr> 
  <tr> 
   <td colspan="1" rowspan="1">비어 있음</td> 
   <td colspan="1" rowspan="1">값이 없는 레코드(NULL) - 0은 숫자입니다. 0은 <em>not</em> NULL입니다.</td> 
  </tr> 
  <tr> 
   <td colspan="1" rowspan="1">비어 있지 않음</td> 
   <td colspan="1" rowspan="1">ANY 값이 있는 레코드(영 포함)</td> 
  </tr> 
 </tbody> 
</table>

보시다시피 이 이동통신사는 Marketing-to-Ese를 유창하게 말하는데 편리합니다.
