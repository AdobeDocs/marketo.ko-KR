---
description: 호출 동기화 및 호출 키 메시지 - Marketo 문서 - 제품 설명서
title: 호출 및 호출 키 메시지 동기화
exl-id: a8df5b77-e594-4e06-8194-1758a3582cda
source-git-commit: bb020cba0bb0cb65761e15cba05147b6e9fffe50
workflow-type: tm+mt
source-wordcount: '0'
ht-degree: 0%

---

# 호출 및 호출 키 메시지 동기화 {#syncing-call-and-call-key-messages}

Vec CRM의 호출 및 호출 키 메시지 개체는 기본적으로 Marketo Engage에 동기화됩니다. Marketo은 호출 생성일을 기준으로 최대 6개월 된 데이터를 동기화합니다.

>[!NOTE]
>
>Marketo은 호출 일로부터 최대 6개월 동안 호출 데이터를 유지합니다.

**호출 및 호출 키 메시지와 관련된 트리거/필터는 무엇입니까?**

트리거:

* 호출에 추가됨
* 호출에서 제거됨
* 호출 키 메시지에 추가됨
* 통화 키 메시지에서 제거됨
* 업데이트된 호출
* 업데이트된 호출 키 메시지

필터:

* 호출 있음
* 호출 키 메시지 있음

호출 및 호출 키 메시지의 팔로우 필드는 동기화되며 제한 및 트리거로 사용할 수 있습니다.

<table>
  <colgroup>
    <col>
    <col>
    <col>
    <col>
    <col>
  </colgroup>
  <thead>
    <tr>
      <th>
        개체
      </th>
      <th>
        필드 레이블
      </th>
      <th>
        설명
      </th>
      <th>
        필드 이름
      </th>
      <th>
        데이터 유형
      </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>호출</td>
      <td>회계사</td>
      <td>호출이 연결된 계정을 조회합니다.</td>
      <td>Account_vod__c</td>
      <td>조회(계정)</td>
    </tr>
    <tr>
      <td>호출</td>
      <td>호출 유형</td>
      <td>호출의 유형 및 내용에 따라 시스템이 유지 관리하는 호출 유형입니다. 이 필드는 보고 목적으로 사용됩니다. 유효한 값은 다음과 같습니다. 세부 사항만, 세부 정보(샘플 포함), 그룹 세부 사항, 샘플이 있는 그룹 세부 사항, 샘플만 해당. 이러한 값은 변경하지 말아야 하지만 이러한 선택사항에 대한 번역은 변경될 수 있습니다. 참석자는 헤더 호출과 동일한 호출 유형을 갖습니다. 3명의 전문가가 있는 그룹 호출의 경우 4개의 모든 레코드는 "그룹 세부 사항"의 호출 유형을 갖습니다</td>
      <td>Call_Type_vod__c</td>
      <td>선택 목록</td>
    </tr>
    <tr>
     <td>호출</td>
      <td>연락처</td>
      <td>호출이 연결된 연락처(있는 경우)를 조회합니다.</td>
      <td>Contact_vod__c</td>
      <td>조회(연락처)</td>
    </tr>
    <tr>
      <td>호출</td>
      <td>날짜</td>
      <td>처음 저장하거나 제출한 호출 날짜입니다. 이 필드는 date 또는 datetime 필드가 모두 제공되지 않을 경우 현재 날짜로의 트리거를 통해 설정됩니다.</td>
      <td>Call_Date_vod__c</td>
      <td>날짜</td>
    </tr>
    <tr>
      <td>호출</td>
      <td>부모 호출입니까?</td>
      <td>공식 필드 : 호출 레코드가 상위 호출인지 또는 참석자 호출 레코드인지 확인합니다. 1은 레코드가 상위 호출임을 나타냅니다. 0은 참석자 호출임을 나타냅니다.</td>
      <td>Is_Parent_Call_vod__c</td>
      <td>공식(숫자)</td>
    </tr>
    <tr>
      <td>호출</td>
      <td>상태</td>
      <td>호출 상태 - 계획, 저장 또는 제출됨. 번역 워크벤치를 사용하여 표시 값을 변경합니다. 호출에 대한 트리거는 이 필드를 확인하여 호출이 잠겨 있는지(제출됨) 확인합니다. 이 값은 저장 또는 제출 단추를 누를 때 사용자에 대해 설정됩니다.</td>
      <td>Status_vod__c</td>
      <td>선택 목록</td>
    </tr>
    <tr>
      <td>호출</td>
      <td>레코드 유형</td>
      <td> </td>
      <td>RecordTypeId</td>
      <td>레코드 유형</td>
    </tr>
    <tr>
      <td>호출 키 메시지</td>
      <td>호출</td>
      <td>호출에 대한 조회. 각 주요 메시지는 호출과 연결됩니다.</td>
      <td>Call2_vod__c</td>
      <td>기본-Detail(호출)</td>
    </tr>
    <tr>
      <td>호출 키 메시지</td>
      <td>카테고리</td>
      <td>메시지의 메시지 카테고리를 기록합니다. 주로 보고에 사용됩니다.</td>
      <td>Category_vod__c</td>
      <td>선택 목록</td>
    </tr>
    <tr>
      <td>호출 키 메시지</td>
      <td>CLM 프레젠테이션 이름</td>
      <td>CLM 프레젠테이션 이름 표시</td>
      <td>Clm_Presentation_Name_vod__c</td>
      <td>텍스트(80)</td>
    </tr>
    <tr>
      <td>호출 키 메시지</td>
      <td>키 메시지 이름</td>
      <td>타임스탬프가 지정된 키 메시지 이름</td>
      <td>Key_Message_Name_vod__c</td>
      <td>텍스트(80)</td>
    </tr>
    <tr>
      <td>호출 키 메시지</td>
      <td>제품 이름</td>
      <td> </td>
      <td>Product_Name__c</td>
      <td>공식(텍스트)</td>
    </tr>
    <tr>
      <td>호출 키 메시지</td>
      <td>반응</a>
      </td>
      <td>메시지에 대한 반응 목록을 선택합니다. 선택 목록을 편집하여 반응 값을 변경합니다.</td>
      <td>Response_vod__c</td>
      <td>선택 목록</td>
    </tr>
  </tbody>
</table>
