---
description: 기본 Dynamics 필드 매핑 - 마케팅 문서 - 제품 설명서
title: 기본 Dynamics 필드 매핑
translation-type: tm+mt
source-git-commit: a7c90193e5c934119fa3b6bdf864d1458d1aad7c
workflow-type: tm+mt
source-wordcount: '528'
ht-degree: 1%

---


# 기본 동적 필드 매핑 {#default-dynamics-field-mapping}

처음 Marketing 계정을 Microsoft와 동기화할 때 Marketing은 내장된 Dynamics 및 Marketing 필드 간에 이러한 연결을 자동으로 만듭니다.  또한 Marketing Cloud는 리드, 계정, 기회 및 연락처에 있는 사용자 지정 필드를 동기화합니다.

## 리드 필드 {#lead-fields}

<table> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <th>마케팅 필드</th> 
   <th>MS Dynamics 필드</th> 
   <th>MS Dynamics API 이름</th> 
  </tr> 
  <tr> 
   <td>Microsoft 만든 날짜</td> 
   <td>만든 날짜</td> 
   <td>createdon</td> 
  </tr> 
  <tr> 
   <td>인사말</td> 
   <td>인사말</td> 
   <td>인사</td> 
  </tr> 
  <tr> 
   <td>첫 번째</td> 
   <td>이름</td> 
   <td>이름</td> 
  </tr> 
  <tr> 
   <td>중간</td> 
   <td>중간 이름</td> 
   <td>중간 이름</td> 
  </tr> 
  <tr> 
   <td>마지막</td> 
   <td>성</td> 
   <td>lastname</td> 
  </tr> 
  <tr> 
   <td>이메일</td> 
   <td>이메일</td> 
   <td>emailaddress1</td> 
  </tr> 
  <tr> 
   <td>직함</td> 
   <td>직함</td> 
   <td>작업 제목</td> 
  </tr> 
  <tr> 
   <td>전화</td> 
   <td>회사 전화</td> 
   <td>전화1</td> 
  </tr> 
  <tr> 
   <td>모바일</td> 
   <td>휴대폰</td> 
   <td>mobilephone</td> 
  </tr> 
  <tr> 
   <td>팩스</td> 
   <td>팩스</td> 
   <td>팩스</td> 
  </tr> 
  <tr> 
   <td>주소</td> 
   <td>거리 1</td> 
   <td>address1_line1</td> 
  </tr> 
  <tr> 
   <td>시</td> 
   <td>시</td> 
   <td>address1_city</td> 
  </tr> 
  <tr> 
   <td>주</td> 
   <td>시/도</td> 
   <td>address1_state_promination</td> 
  </tr> 
  <tr> 
   <td>국가</td> 
   <td>국가/지역</td> 
   <td>address1_country</td> 
  </tr> 
  <tr> 
   <td>우편 번호</td> 
   <td>우편 번호</td> 
   <td>address1_postalcode</td> 
  </tr> 
  <tr> 
   <td>개인 출처</td> 
   <td>리드 소스</td> 
   <td>leadsourcecode</td> 
  </tr> 
  <tr> 
   <td>개인 상태</td> 
   <td>상태</td> 
   <td>상태 코드</td> 
  </tr> 
  <tr> 
   <td>상태 이유</td> 
   <td>상태 이유</td> 
   <td>statuscode</td> 
  </tr> 
  <tr> 
   <td>개인 메모</td> 
   <td>설명</td> 
   <td>description</td> 
  </tr> 
  <tr> 
   <td>호출 안 함</td> 
   <td>전화 통화 허용 안 함</td> 
   <td>도노폰</td> 
  </tr> 
  <tr> 
   <td>구독 취소</td> 
   <td>전자 메일 일괄 처리 안 함</td> 
   <td>donobulkemail</td> 
  </tr> 
  <tr> 
   <td>개인 등급</td> 
   <td>등급</td> 
   <td>leadqualitycode</td> 
  </tr> 
  <tr> 
   <td>Microsoft 주소 2</td> 
   <td>거리 2</td> 
   <td>address1_line2</td> 
  </tr> 
  <tr> 
   <td>Microsoft 주소 3</td> 
   <td>거리 3</td> 
   <td>address1_line3</td> 
  </tr> 
  <tr> 
   <td>Microsoft 전자 메일 보내기 안 함</td> 
   <td>이메일 허용 안 함</td> 
   <td>도노테메일</td> 
  </tr> 
  <tr> 
   <td>Microsoft 팩스 전송 안 함</td> 
   <td>팩스 허용 안 함</td> 
   <td>donofax</td> 
  </tr> 
  <tr> 
   <td>Microsoft에서 마케팅 자료를 보내지 않음</td> 
   <td>마케팅 자료</td> 
   <td>donosendmm</td> 
  </tr> 
  <tr> 
   <td>Microsoft Home Phone</td> 
   <td>홈 전화</td> 
   <td>전화 2</td> 
  </tr> 
  <tr> 
   <td>Microsoft에서 선호하는 연락 방법</td> 
   <td>기본 연락 방법</td> 
   <td>preferredcontact메서드 코드</td> 
  </tr> 
  <tr> 
   <td>Microsoft 주제</td> 
   <td>주제</td> 
   <td>subject</td> 
  </tr> 
 </tbody> 
</table>

## 연락처 필드 {#contact-fields}

<table> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <th>마케팅 필드</th> 
   <th>MS Dynamics 필드</th> 
   <th>MS Dynamics API 이름</th> 
  </tr> 
  <tr> 
   <td>Microsoft 만든 날짜</td> 
   <td>만든 날짜</td> 
   <td>createdon</td> 
  </tr> 
  <tr> 
   <td>인사말</td> 
   <td>인사말</td> 
   <td>인사</td> 
  </tr> 
  <tr> 
   <td>첫 번째</td> 
   <td>이름</td> 
   <td>이름</td> 
  </tr> 
  <tr> 
   <td>중간</td> 
   <td>중간 이름</td> 
   <td>중간 이름</td> 
  </tr> 
  <tr> 
   <td>마지막</td> 
   <td>성</td> 
   <td>lastname</td> 
  </tr> 
  <tr> 
   <td>이메일</td> 
   <td>이메일</td> 
   <td>emailaddress1</td> 
  </tr> 
  <tr> 
   <td>직함</td> 
   <td>직함</td> 
   <td>작업 제목</td> 
  </tr> 
  <tr> 
   <td>전화</td> 
   <td>회사 전화</td> 
   <td>전화1</td> 
  </tr> 
  <tr> 
   <td>모바일</td> 
   <td>휴대폰</td> 
   <td>mobilephone</td> 
  </tr> 
  <tr> 
   <td>주소</td> 
   <td>주소 1:거리 1</td> 
   <td>address1_line1</td> 
   <tr> 
   <td>시</td> 
   <td>주소 1:시</td> 
   <td>address1_city</td> 
  </tr> 
  <tr> 
   <td>주</td> 
   <td>주소 1:시/도</td> 
   <td>address1_state_promination</td> 
  </tr> 
  <tr> 
   <td>국가</td> 
   <td>주소 1:국가/지역</td> 
   <td>address1_country</td> 
   <tr> 
   <td>우편 번호</td> 
   <td>주소 1:우편 번호</td> 
   <td>address1_postalcode</td> 
  </tr> 
  <tr> 
   <td>개인 상태</td> 
   <td>상태</td> 
   <td>상태 코드</td> 
  </tr> 
  <tr> 
   <td>상태 이유</td> 
   <td>상태 이유</td> 
   <td>statuscode</td> 
  </tr> 
   <tr> 
   <td>호출 안 함</td> 
   <td>전화 통화 허용 안 함</td> 
   <td>도노폰</td> 
  </tr> 
  <tr> 
   <td>구독 취소</td> 
   <td>전자 메일 일괄 처리 안 함</td> 
   <td>donobulkemail</td> 
  </tr> 
  <tr> 
   <td>Microsoft 주소 2</td> 
   <td>주소 1:거리 2</td> 
   <td>address1_line2</td> 
  </tr> 
   <tr> 
   <td>Microsoft 주소 3</td> 
   <td>주소 1:거리 3</td> 
   <td>address1_line3</td> 
  </tr> 
  <tr> 
   <td>Microsoft 전자 메일 보내기 안 함</td> 
   <td>이메일 허용 안 함</td> 
   <td>도노테메일</td> 
  </tr> 
  <tr> 
   <td>Microsoft Home Phone</td> 
   <td>홈 전화</td> 
   <td>전화 2</td> 
  </tr> 
  <tr> 
   <td>Microsoft에서 선호하는 연락 방법</td> 
   <td>기본 연락 방법</td> 
   <td>preferredcontact메서드 코드</td> 
  </tr> 
 </tbody> 
</table>

## 계정 필드 {#account-fields}

<table> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <th>마케팅 필드</th> 
   <th>MS Dynamics 필드</th> 
   <th>MS Dynamics API 이름</th> 
  </tr> 
  <tr> 
   <td>계정 (a)</td> 
   <td>계정</td> 
   <td>acid</td> 
  </tr> 
  <tr> 
   <td>청구 주소</td> 
   <td>주소 1:거리 1</td> 
   <td>address1_line1</td> 
  </tr> 
  <tr> 
   <td>청구 구/군/시</td> 
   <td>주소 1:시</td> 
   <td>address1_city</td> 
  </tr> 
  <tr> 
   <td>청구 국가</td> 
   <td>주소 1:국가/지역</td> 
   <td>address1_country</td> 
  </tr> 
  <tr> 
   <td>청구 우편 번호</td> 
   <td>주소 1:우편 번호</td> 
   <td>address1_postalcode</td> 
  </tr> 
  <tr> 
   <td>Microsoft 청구 주소 2</td> 
   <td>주소 1:거리 2</td> 
   <td>address1_line2</td> 
  </tr> 
  <tr> 
   <td>Microsoft 청구 주소 3</td> 
   <td>주소 1:거리 3</td> 
   <td>address1_line3</td> 
  </tr> 
  <tr> 
   <td>기본 전화</td> 
   <td>기본 전화</td> 
   <td>전화1</td> 
  </tr> 
  <tr> 
   <td>비즈니스 유형</td> 
   <td>비즈니스 유형</td> 
   <td>사업상 시간 코드</td> 
  </tr> 
  <tr> 
   <td>Microsoft 계정 번호</td> 
   <td>계정 번호</td> 
   <td>계정 번호</td> 
  </tr> 
  <tr> 
   <td>Microsoft 회사 상태</td> 
   <td>상태</td> 
   <td>상태 코드</td> 
  </tr> 
  <tr> 
   <td>연간 매출</td> 
   <td>연간 매출</td> 
   <td>매출액</td> 
  </tr> 
  <tr> 
   <td>회사 메모</td> 
   <td>설명</td> 
   <td>description</td> 
  </tr> 
  <tr> 
   <td>업계</td> 
   <td>업계</td> 
   <td>업계 코드</td> 
  </tr> 
  <tr> 
   <td>SIC 코드</td> 
   <td>SIC 코드</td> 
   <td>음악</td> 
  </tr> 
  <tr> 
   <td>웹 사이트</td> 
   <td>웹 사이트</td> 
   <td>웹 사이트</td> 
  </tr> 
 </tbody> 
</table>

## Marketing To의 Microsoft 관련 시스템 필드(읽기 전용) {#microsoft-related-system-fields-in-marketo}

이러한 필드는 Marketing To에서 만들어지지만 고객이 조정할 수 없습니다.

<table> 
 <colgroup> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <th>마케팅 필드</th> 
   <th>설명</th> 
  </tr> 
  <tr> 
   <td>Microsoft Type</td> 
   <td>리드 또는 담당자. 비어 있는 경우 리드는 Marketing To에 개인으로만 존재합니다.</td> 
  </tr> 
  <tr> 
   <td>Microsoft 만든 날짜</td> 
   <td>MS Dynamics에서 만든 날짜(마케팅에서 만든 날짜와 다를 수 있음)</td> 
  </tr> 
  <tr> 
   <td>Microsoft가 삭제됨</td> 
   <td>이전에 Microsoft에 있었지만 삭제되었으며 현재 Marketing To에서만 사용 중인 사람</td> 
  </tr> 
 </tbody> 
</table>
