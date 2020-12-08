---
unique-page-id: 557312
description: 스마트 목록 필터 연산자 용어집 - Marketing Docs - 제품 설명서
title: 스마트 목록 필터 연산자 용어집
translation-type: tm+mt
source-git-commit: 47b2fee7d146c3dc558d4bbb10070683f4cdfd3d
workflow-type: tm+mt
source-wordcount: '611'
ht-degree: 0%

---


# 스마트 목록 필터 연산자 용어집 {#smart-list-filter-operators-glossary}

연산자는 [고급 목록의](http://docs.marketo.com/display/docs/smart+lists+and+static+lists) 일부이며, 이를 통해 정보를 얻을 수 있습니다. 필터를 설명하거나 간단한 언어로 트리거할 수 있습니다. 사용 가능한 연산자는 각 필드 유형에 따라 다릅니다.\
여기 용어집이 있습니다. 각 연산자에 대해 설명하죠.

## 날짜 필드 {#date-fields}

![](assets/image2014-9-10-17-3a15-3a47.png)

연산자를 선택하면 오른쪽이 동적으로 변경됩니다.

| 연산자 | 오른쪽 | 설명 |
|---|---|---|
| is | 단일 날짜 | 정확한 날짜 일치 |
| not | 단일 날짜 | 지정된 날짜를 제외한 모든 날짜 |
| between | 두 날짜 필드 | 지정된 두 날짜 사이의 모든 날짜 |
| 과거 | 자연어 입력* | 아래 다이어그램 보기 |
| 과거 | 자연어 입력* | 아래 다이어그램 보기 |
| 미래 | 자연어 입력* | 아래 다이어그램 보기 |
| 미래 | 자연어 입력* | 아래 다이어그램 보기 |
| 시간 프레임 | 사전 설정(지난 분기, 어제 등) | 선택 목록에 정의됨 |
| after | 단일 날짜 | 지정된 날짜 이후의 모든 레코드 |
| before | 단일 날짜 | 지정한 레코드 이전의 모든 레코드 |
| on 또는 after | 단일 날짜 | &quot;after&quot;와 동일하지만 포함 |
| 또는 그 전 | 단일 날짜 | &quot;before&quot;와 동일하지만 포함 |
| 비어 있음 | 없음 | 날짜가 없는 모든 레코드 |
| 비어 있지 않음 | 없음 | 날짜가 있는 모든 레코드 |

* 자연어 입력은 좋다. 다음은 입력할 수 있는 패턴입니다.

* 1시간
* 82일
* 3주
* 14개월
* 1년

번호와 단위를 함께 입력하시면 됩니다

>[!NOTE]
>
>이전에는 **** 스마트 목록을 만드는 일(시간이 아니라 이후까지)을 포함합니다.

>[!CAUTION]
>
>날짜 필드 필터(예: 생년월일, SFDC 생성 날짜)를 사용하여 스마트 목록을 만들고 **이전** 또는 제한 **에** 사용하는 경우, 스마트 목록에는 같은 날짜 필드에 값이 없는 사람도 포함됩니다.

날짜 연산자 간의 차이를 이해하려면 다음 다이어그램을 사용하십시오.

![](assets/image2014-9-10-17-3a15-3a58.png)

>[!NOTE]
>
>**예**
>
>이전 및 향후 이벤트를 사용하여 작업할 때 날짜 필드가 까다로울 수 있습니다. 여기 몇 가지 예가 있습니다.
>
>**과거**
>
>새로운 프로모션의 경우 이 연산자를 사용하여 1년 이내에 서비스에 가입하지 않았거나 구독하지 않은 사람에게만 이메일을 보냅니다.
>
>**In future after**
>
>90일 이내에 갱신하려는 고객을 확인하고자 합니다. 두 개의 개별 필터를 사용합니다. 먼저 &quot;In Future After 90 days&quot; 및 &quot;In Future 91days&quot;를 사용합니다. 그러면 누가 90일 후에 데이트할 사람을 잡을수 있어

## 문자열 필드 {#string-fields}

![](assets/image2014-9-10-17-3a16-3a6.png)

| 연산자 | 설명 |
|---|---|
| is | 정확히 일치(대/소문자 구분 안 함) |
| not | EXACT와 정확히 일치하는 것 이외의 모든 것 |
| 다음으로 시작 | 문자열 일치 첫 문자 |
| 다음으로 시작 안 함 | 문자열 DO NOT 일치 |
| contains | 문자열 일치에 있는 모든 문자(예:california, fortune, gfor) |
| 포함하지 않음 | 문자열과 일치하는 문자가 없습니다. (reverse &quot;contains&quot;) |
| 비어 있음 | 값이 없는 레코드(NULL) |
| 비어 있지 않음 | ANY 값으로 기록 |

>[!TIP]
>
>부정 연산자에 양수를 사용합니다. &quot;Is not&quot; 필터는 인스턴스에 있는 전체 데이터 세트를 검색해야 하므로 시간이 많이 소요될 수 있습니다. 긍정적인 &quot;is&quot; 필터는 보다 효과적인 검색 알고리즘을 활용할 수 있습니다.

## 정수 필드 {#integer-fields}

![](assets/image2014-9-10-17-3a16-3a14.png)

<table> 
 <thead> 
  <tr> 
   <th colspan="1" rowspan="1">연산자</th> 
   <th colspan="1" rowspan="1"><p>설명</p></th> 
  </tr> 
 </thead> 
 <tbody> 
  <tr> 
   <td colspan="1" rowspan="1">is</td> 
   <td colspan="1" rowspan="1">정확한 숫자 일치( = 0은 0과 NULL이 있는 두 리드 <em>를</em> 반환합니다.)</td> 
  </tr> 
  <tr> 
   <td colspan="1" rowspan="1">not</td> 
   <td colspan="1" rowspan="1">정확한 숫자를 제외한 모든 것</td> 
  </tr> 
  <tr> 
   <td colspan="1" rowspan="1">between</td> 
   <td colspan="1" rowspan="1">두 값을 정의하여 그 사이(포함)에 있는 모든 사람 찾기</td> 
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
   <td colspan="1" rowspan="1">지정된 값보다 작음(포함)</td> 
  </tr> 
  <tr> 
   <td colspan="1" rowspan="1">비어 있음</td> 
   <td colspan="1" rowspan="1">값이 없는 레코드(NULL) - 0은 숫자입니다. 0은 NULL이 <em>아닙니다</em> .</td> 
  </tr> 
  <tr> 
   <td colspan="1" rowspan="1">비어 있지 않음</td> 
   <td colspan="1" rowspan="1">ANY 값이 있는 레코드(0 포함)</td> 
  </tr> 
 </tbody> 
</table>

보시다시피 이 이동통신사는 Marketing-to-Ese를 유창하게 구사할 수 있습니다.
