---
description: 기본 [!DNL Veeva] 필드 매핑 - Marketo 문서 - 제품 설명서
title: 기본 [!DNL Veeva] 필드 매핑
exl-id: 3bf36d50-daea-431f-9537-b3007ad75945
feature: Veeva CRM
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '253'
ht-degree: 36%

---

# 기본 [!DNL Veeva] 필드 매핑 {#default-veeva-field-mapping}

Marketo Engage 계정을 [!DNL Veeva]과(와) 처음 동기화할 때 Marketo은 기본 제공 [!DNL Veeva]과(와) Marketo 필드 간에 이러한 연결을 자동으로 만듭니다. Marketo은 계정 및 연락처의 사용자 정의 필드도 동기화합니다.

## 연락처 필드 {#contact-fields}

<table>
  <colgroup>
    <col/>
    <col/>
  </colgroup>
  <thead>
    <tr>
      <th>SFDC 필드</th>
      <th>Marketo 필드</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>생일</td>
      <td>생년월일</td>
    </tr>
    <tr>
      <td>만든 날짜</td>
      <td>SFDC 생성일</td>
    </tr>
    <tr>
      <td>연락처 설명</td>
      <td>개인 메모</td>
    </tr>
    <tr>
      <td>이메일</td>
      <td>이메일 주소</td>
    </tr>
    <tr>
      <td>회사 팩스</td>
      <td>팩스 번호</td>
    </tr>
    <tr>
      <td>이름</td>
      <td>이름</td>
    </tr>
    <tr>
      <td>이메일 옵트아웃</td>
      <td>주소 삭제</td>
    </tr>
    <tr>
      <td>삭제됨</td>
      <td>SFDC 삭제됨</td>
    </tr>
    <tr>
      <td>성</td>
      <td>성</td>
    </tr>
    <tr>
      <td>잠재 고객 소스</td>
      <td>소스</td>
    </tr>
    <tr>
      <td>잠재 고객 점수</td>
      <td>점수</td>
    </tr>
    <tr>
      <td>메일링 시티</td>
      <td>구/군/시</td>
    </tr>
    <tr>
      <td>MailingCountry</td>
      <td>국가</td>
    </tr>
    <tr>
      <td>메일링 우편 번호</td>
      <td>우편번호</td>
    </tr>
    <tr>
      <td>메일링 상태</td>
      <td>주/도</td>
    </tr>
    <tr>
      <td>메일링 스트리트</td>
      <td>주소</td>
    </tr>
    <tr>
      <td>휴대폰</td>
      <td>휴대폰 번호</td>
    </tr>
    <tr>
      <td>회사 전화</td>
      <td>전화번호</td>
    </tr>
    <tr>
      <td>인사말</td>
      <td>인사말</td>
    </tr>
    <tr>
      <td>제목</td>
      <td>직위</td>
    </tr>
  </tbody>
</table>

## 계정 필드 {#account-fields}

<table>
  <colgroup>
    <col/>
    <col/>
  </colgroup>
  <thead>
    <tr>
      <th>SFDC 필드</th>
      <th>Marketo 필드</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>연간 수익</td>
      <td>연간 수익</td>
    </tr>
    <tr>
      <td>청구지 시</td>
      <td>청구지 시</td>
    </tr>
    <tr>
      <td>청구지 국가</td>
      <td>청구지 국가</td>
    </tr>
    <tr>
      <td>청구 Zip/우편 번호</td>
      <td>청구지 우편번호</td>
    </tr>
    <tr>
      <td>청구 시/도</td>
      <td>청구지 주</td>
    </tr>
    <tr>
      <td>청구지</td>
      <td>청구지 주소</td>
    </tr>
    <tr>
      <td>계정 설명</td>
      <td>회사 메모</td>
    </tr>
    <tr>
      <td>업종</td>
      <td>업종</td>
    </tr>
    <tr>
      <td>삭제됨</td>
      <td>SFDC 삭제됨</td>
    </tr>
    <tr>
      <td>계정 이름</td>
      <td>회사 이름</td>
    </tr>
    <tr>
      <td>직원</td>
      <td>직원 수</td>
    </tr>
    <tr>
      <td>계정 전화</td>
      <td>주요 전화</td>
    </tr>
    <tr>
      <td>SIC 코드</td>
      <td>SIC 코드</td>
    </tr>
    <tr>
      <td>계정 사이트</td>
      <td>위치</td>
    </tr>
    <tr>
      <td>계정 유형</td>
      <td>SFDC 유형</td>
    </tr>
    <tr>
      <td>웹 사이트</td>
      <td>웹 사이트</td>
    </tr>
  </tbody>
</table>

## Marketo의 [!DNL Veeva] 관련 시스템 필드(읽기 전용) {#veeva-related-system-fields-in-marketo}

이러한 필드는 Marketo에서 생성되지만 고객이 조정할 수 없습니다.

<table>
  <colgroup>
    <col/>
    <col/>
  </colgroup>
  <thead>
    <tr>
      <th>필드</th>
      <th>설명</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>[!DNL Veeva] ID</td>
      <td>18자 [!DNL Salesforce] ID</td>
    </tr>
    <tr>
      <td>[!DNL Veeva] 유형</td>
      <td>연락처. 비어 있는 경우 잠재 고객은 Marketo의 사용자로만 존재합니다</td>
    </tr>
    <tr>
      <td>[!DNL Veeva] 만든 날짜</td>
      <td>SFDC에서 만든 날짜 (Marketo에서 만든 날짜와 다를 수 있음)</td>
    </tr>
    <tr>
      <td>[!DNL Veeva] 삭제됨</td>
      <td>이전에 SFDC에 있었으나 삭제되었습니다. 이제 Marketo에서만 살게 되었습니다.</td>
    </tr>
  </tbody>
</table>
