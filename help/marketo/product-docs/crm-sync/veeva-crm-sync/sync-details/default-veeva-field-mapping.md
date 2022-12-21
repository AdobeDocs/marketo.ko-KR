---
description: 기본 Veva 필드 매핑 - Marketo 문서 - 제품 설명서
title: 기본 경험 필드 매핑
exl-id: 3bf36d50-daea-431f-9537-b3007ad75945
source-git-commit: 2ce44b7c44517a6fdb3f616a3d69b25158ea4ec9
workflow-type: tm+mt
source-wordcount: '263'
ht-degree: 31%

---

# 기본 경험 필드 매핑 {#default-veeva-field-mapping}

처음에 Marketo Engage 계정을 Veva와 동기화할 때 Marketo은 기본 제공 Vevar 필드와 Marketo 필드 간에 이러한 연결을 자동으로 만듭니다. Marketo은 또한 계정 및 연락처의 사용자 지정 필드를 동기화합니다.

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
      <td>출생일</td>
    </tr>
    <tr>
      <td>작성일</td>
      <td>SFDC 생성 날짜</td>
    </tr>
    <tr>
      <td>연락처 설명</td>
      <td>개인 정보</td>
    </tr>
    <tr>
      <td>이메일</td>
      <td>이메일 주소</td>
    </tr>
    <tr>
      <td>비즈니스 팩스</td>
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
      <td>삭제된 항목</td>
      <td>SFDC가 삭제됨</td>
    </tr>
    <tr>
      <td>성</td>
      <td>성</td>
    </tr>
    <tr>
      <td>잠재 고객 소스</td>
      <td>원문</td>
    </tr>
    <tr>
      <td>잠재 고객 점수</td>
      <td>스코어</td>
    </tr>
    <tr>
      <td>메일링 시티</td>
      <td>시</td>
    </tr>
    <tr>
      <td>메일링 컨트리</td>
      <td>국가</td>
    </tr>
    <tr>
      <td>MailingPostalCode</td>
      <td>우편 번호</td>
    </tr>
    <tr>
      <td>메일링 상태</td>
      <td>주</td>
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
      <td>비즈니스 전화</td>
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
      <td>청구 우편 번호</td>
      <td>청구지 우편번호</td>
    </tr>
    <tr>
      <td>청구 주/도</td>
      <td>청구지 주</td>
    </tr>
    <tr>
      <td>청구 거리</td>
      <td>청구지 주소</td>
    </tr>
    <tr>
      <td>계정 설명</td>
      <td>회사 노트</td>
    </tr>
    <tr>
      <td>산업</td>
      <td>산업</td>
    </tr>
    <tr>
      <td>삭제된 항목</td>
      <td>SFDC가 삭제됨</td>
    </tr>
    <tr>
      <td>계정 이름</td>
      <td>회사명</td>
    </tr>
    <tr>
      <td>직원</td>
      <td>직원 수</td>
    </tr>
    <tr>
      <td>계정 전화</td>
      <td>메인 전화</td>
    </tr>
    <tr>
      <td>SIC 코드</td>
      <td>SIC 코드</td>
    </tr>
    <tr>
      <td>계정 사이트</td>
      <td>사이트</td>
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

## Marketo의 veva 관련 시스템 필드(읽기 전용) {#veeva-related-system-fields-in-marketo}

이러한 필드는 Marketo에서 만들어지지만 고객이 조정할 수 없습니다.

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
      <td>Veva Id</td>
      <td>18자 Salesforce Id</td>
    </tr>
    <tr>
      <td>Vevar 유형</td>
      <td>연락. 비어 있는 경우, 리드는 Marketo에 개인으로만 존재합니다</td>
    </tr>
    <tr>
      <td>Veva 작성일</td>
      <td>SFDC에서 만든 날짜(Marketo에서 만든 날짜와 다를 수 있음)</td>
    </tr>
    <tr>
      <td>vevar가 삭제됨</td>
      <td>SFDC에 있었지만 삭제되었으며 현재 Marketo에서만 살고 있습니다</td>
    </tr>
  </tbody>
</table>
