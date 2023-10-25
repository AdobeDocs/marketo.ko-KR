---
description: 기본 Dynamics 필드 매핑 - Marketo 문서 - 제품 설명서
title: 기본 동적 필드 매핑
exl-id: 5f39bd0c-202e-4aa1-a0ac-49ac2554aa1e
feature: Microsoft Dynamics
source-git-commit: 2403ae0f1fdca3b8238f3f59e2a3b94129deb301
workflow-type: tm+mt
source-wordcount: '830'
ht-degree: 18%

---

# 기본 동적 필드 매핑 {#default-dynamics-field-mapping}

처음에 Marketo Engage 계정을 Microsoft과 동기화하면 Marketo에서 기본 제공 Dynamics와 Marketo 필드 간에 이러한 연결을 자동으로 수행합니다.  Marketo은 리드, 계정, 기회 및 연락처에서 사용자 정의 필드도 동기화합니다.

## 리드 필드 {#lead-fields}

<table>
  <colgroup>
    <col>
    <col>
    <col>
  </colgroup>
  <tbody>
    <tr>
      <th>Marketo 필드</th>
      <th>MS Dynamics 필드</th>
      <th>MS Dynamics API 이름</th>
    </tr>
    <tr>
      <td>Microsoft 생성 날짜</td>
      <td>만든 일자</td>
      <td>createdon</td>
    </tr>
    <tr>
      <td>인사말</td>
      <td>인사말</td>
      <td>인사말</td>
    </tr>
    <tr>
      <td>첫 번째</td>
      <td>이름</td>
      <td>이름</td>
    </tr>
    <tr>
      <td>가운데</td>
      <td>중간 이름</td>
      <td>middlename</td>
    </tr>
    <tr>
      <td>마지막</td>
      <td>성</td>
      <td>성</td>
    </tr>
    <tr>
      <td>이메일</td>
      <td>이메일</td>
      <td>emailaddress1</td>
    </tr>
    <tr>
      <td>직위</td>
      <td>직위</td>
      <td>직함</td>
    </tr>
    <tr>
      <td>전화</td>
      <td>회사 전화</td>
      <td>telephone1</td>
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
      <td>도로 1</td>
      <td>address1_line1</td>
    </tr>
    <tr>
      <td>도시</td>
      <td>도시</td>
      <td>address1_city</td>
    </tr>
    <tr>
      <td>주</td>
      <td>시/도</td>
      <td>address1_stateorprovince</td>
    </tr>
    <tr>
      <td>국가</td>
      <td>국가/지역</td>
      <td>address1_country</td>
    </tr>
    <tr>
      <td>우편 번호</td>
      <td>Zip/우편 번호</td>
      <td>address1_postalcode</td>
    </tr>
    <tr>
      <td>개인 소스</td>
      <td>잠재 고객 소스</td>
      <td>리드소스 코드</td>
    </tr>
    <tr>
      <td>개인 상태</td>
      <td>상태</td>
      <td>statecode</td>
    </tr>
    <tr>
      <td>상태 사유</td>
      <td>상태 사유</td>
      <td>statuscode</td>
    </tr>
    <tr>
      <td>개인 메모</td>
      <td>설명</td>
      <td>설명</td>
    </tr>
    <tr>
      <td>두 낫 콜</td>
      <td>전화 통화 허용 안 함</td>
      <td>donotphone</td>
    </tr>
    <tr>
      <td>주소 삭제</td>
      <td>이메일 대량 수신 안 함</td>
      <td>donotbulkemail</td>
    </tr>
    <tr>
      <td>개인 등급</td>
      <td>등급</td>
      <td>잠재 고객 코드</td>
    </tr>
    <tr>
      <td>Microsoft 주소 2</td>
      <td>도로 2</td>
      <td>address1_line2</td>
    </tr>
    <tr>
      <td>Microsoft 주소 3</td>
      <td>도로 3</td>
      <td>address1_line3</td>
    </tr>
    <tr>
      <td>Microsoft에게 이메일을 보내지 않음</td>
      <td>이메일 허용 안 함</td>
      <td>donotemail</td>
    </tr>
    <tr>
      <td>Microsoft 팩스 사용 안 함</td>
      <td>팩스 허용 안 함</td>
      <td>donot팩스</td>
    </tr>
    <tr>
      <td>Microsoft에서 마케팅 자료를 보내지 않음</td>
      <td>마케팅 자료</td>
      <td>donotsendmm</td>
    </tr>
    <tr>
      <td>Microsoft 홈 전화</td>
      <td>집전화</td>
      <td>telephone2</td>
    </tr>
    <tr>
      <td>Microsoft 기본 연락 방법</td>
      <td>기본 연락 방법</td>
      <td>preferredcontactmethodcode</td>
    </tr>
    <tr>
      <td>Microsoft 주제</td>
      <td>주제</td>
      <td>제목</td>
    </tr>
    <tr>
      <td>마지막 관심 순간 날짜</td>
      <td>마지막 관심 순간 날짜</td>
      <td>mkt_lastinterestingmomentdate</td>
    </tr>
    <tr>
      <td>마지막 관심 순간 설명</td>
      <td>마지막 관심 순간 설명</td>
      <td>mkt_lastinterestingmomentdesc</td>
    </tr>
    <tr>
      <td>마지막 관심 순간 소스</td>
      <td>마지막 관심 순간 소스</td>
      <td>mkt_leadinterrestingmomentsource</td>
    </tr>
    <tr>
      <td>마지막 관심 순간 유형</td>
      <td>마지막 관심 순간 유형</td>
      <td>mkt_lastinterestingmomenttype</td>
    </tr>
    <tr>
      <td>회사</td>
      <td>회사 이름</td>
      <td>companyname</td>
    </tr>
    <tr>
      <td>상대 스코어</td>
      <td>상대 스코어</td>
      <td>mkt_relativescore</td>
    </tr>
    <tr>
      <td>우선 순위</td>
      <td>우선 순위</td>
      <td>mkt_priority</td>
    </tr>
    <tr>
      <td>상대 긴급도</td>
      <td>긴급도</td>
      <td>mkt_urgency</td>
    </tr>
    <tr>
      <td>제목</td>
      <td>주제</td>
      <td>제목</td>
    </tr>
    <tr>
      <td>연간 수익</td>
      <td>연간 수익</td>
      <td>매출</td>
    </tr>
  </tbody>
</table>

아래 잠재 고객 필드는 내부 사용을 위해 동기화됩니다.

<table>
  <colgroup>
    <col/>
    <col/>
  </colgroup>
  <tbody>
    <tr>
      <th>MS Dynamics 필드</th>
      <th>MS Dynamics API 이름</th>
    </tr>
    <tr>
      <td>소유자</td>
      <td>소유자 ID</td>
    </tr>
    <tr>
      <td>만든 날짜</td>
      <td>createdon</td>
    </tr>
  </tbody>
</table>

## 연락처 필드 {#contact-fields}

<table>
  <colgroup>
    <col/>
    <col/>
    <col/>
  </colgroup>
  <tbody>
    <tr>
      <th>Marketo 필드</th>
      <th>MS Dynamics 필드</th>
      <th>MS Dynamics API 이름</th>
    </tr>
    <tr>
      <td>Microsoft 생성 날짜</td>
      <td>만든 일자</td>
      <td>createdon</td>
    </tr>
    <tr>
      <td>인사말</td>
      <td>인사말</td>
      <td>인사말</td>
    </tr>
    <tr>
      <td>첫 번째</td>
      <td>이름</td>
      <td>이름</td>
    </tr>
    <tr>
      <td>가운데</td>
      <td>중간 이름</td>
      <td>middlename</td>
    </tr>
    <tr>
      <td>마지막</td>
      <td>성</td>
      <td>성</td>
    </tr>
    <tr>
      <td>이메일</td>
      <td>이메일</td>
      <td>emailaddress1</td>
    </tr>
    <tr>
      <td>직위</td>
      <td>직위</td>
      <td>직함</td>
    </tr>
    <tr>
      <td>전화</td>
      <td>회사 전화</td>
      <td>telephone1</td>
    </tr>
    <tr>
      <td>모바일</td>
      <td>휴대폰</td>
      <td>mobilephone</td>
    </tr>
    <tr>
      <td>주소</td>
      <td>주소 1: 상세 주소 1</td>
      <td>address1_line1</td>
    </tr>
    <tr>
      <td>도시</td>
      <td>주소 1: 시</td>
      <td>address1_city</td>
    </tr>
    <tr>
      <td>주</td>
      <td>주소 1: 시/도</td>
      <td>address1_stateorprovince</td>
    </tr>
    <tr>
      <td>국가</td>
      <td>주소 1: 국가/지역</td>
      <td>address1_country</td>
    </tr>
    <tr>
      <td>우편 번호</td>
      <td>주소 1: 우편 번호</td>
      <td>address1_postalcode</td>
    </tr>
    <tr>
      <td>개인 상태</td>
      <td>상태</td>
      <td>statecode</td>
    </tr>
    <tr>
      <td>상태 사유</td>
      <td>상태 사유</td>
      <td>statuscode</td>
    </tr>
    <tr>
      <td>두 낫 콜</td>
      <td>전화 통화 허용 안 함</td>
      <td>donotphone</td>
    </tr>
    <tr>
      <td>주소 삭제</td>
      <td>이메일 대량 수신 안 함</td>
      <td>donotbulkemail</td>
    </tr>
    <tr>
      <td>Microsoft 주소 2</td>
      <td>주소 1: 상세 주소 2</td>
      <td>address1_line2</td>
    </tr>
    <tr>
      <td>Microsoft 주소 3</td>
      <td>주소 1: 도로 3</td>
      <td>address1_line3</td>
    </tr>
    <tr>
      <td>Microsoft에게 이메일을 보내지 않음</td>
      <td>이메일 허용 안 함</td>
      <td>donotemail</td>
    </tr>
    <tr>
      <td>Microsoft 홈 전화</td>
      <td>집전화</td>
      <td>telephone2</td>
    </tr>
    <tr>
      <td>Microsoft 기본 연락 방법</td>
      <td>선호하는 연락 방법</td>
      <td>preferredcontactmethodcode</td>
    </tr>
    <tr>
      <td>마지막 관심 순간 날짜</td>
      <td>마지막 관심 순간 날짜</td>
      <td>mkt_lastinterestingmomentdate</td>
    </tr>
    <tr>
      <td>마지막 관심 순간 유형</td>
      <td>마지막 관심 순간 유형</td>
      <td>mkt_lastinterestingmomenttype</td>
    </tr>
    <tr>
      <td>마지막 관심 순간 소스</td>
      <td>마지막 관심 순간 소스</td>
      <td>mkt_leadinterrestingmomentsource</td>
    </tr>
    <tr>
      <td>마지막 관심 순간 설명</td>
      <td>마지막 관심 순간 설명</td>
      <td>mkt_lastinterestingmomentdesc</td>
    </tr>
    <tr>
      <td>Microsoft에서 마케팅 자료를 보내지 않음</td>
      <td>마케팅 자료</td>
      <td>donotsendmm</td>
    </tr>
    <tr>
      <td>Microsoft 팩스 사용 안 함</td>
      <td>Microsoft 팩스 사용 안 함</td>
      <td>donot팩스</td>
    </tr>
    <tr>
      <td>우선 순위</td>
      <td>우선 순위</td>
      <td>mkt_priority</td>
    </tr>
    <tr>
      <td>상대 긴급도</td>
      <td>긴급도</td>
      <td>mkt_urgency</td>
    </tr>
    <tr>
      <td>상대 스코어</td>
      <td>상대 스코어</td>
      <td>mkt_relativescore</td>
    </tr>
    <tr>
      <td>개인 메모</td>
      <td>설명</td>
      <td>설명</td>
    </tr>
    <tr>
      <td>개인 스코어</td>
      <td>잠재 고객 점수</td>
      <td>mkt_leadscore</td>
    </tr>
    <tr>
      <td>개인 메모</td>
      <td>설명</td>
      <td>설명</td>
    </tr>
  </tbody>
</table>

아래 연락처 필드는 내부 사용을 위해 동기화됩니다.

<table>
  <colgroup>
    <col/>
    <col/>
  </colgroup>
  <tbody>
    <tr>
      <th>MS Dynamics 필드</th>
      <th>MS Dynamics API 이름</th>
    </tr>
    <tr>
      <td>소유자</td>
      <td>소유자 ID</td>
    </tr>
    <tr>
      <td>만든 날짜</td>
      <td>createdon</td>
    </tr>
    <tr>
      <td>parentcustomerid</td>
      <td>회사 이름</td>
    </tr>
  </tbody>
</table>

## 계정 필드 {#account-fields}

<table>
  <colgroup>
    <col/>
    <col/>
    <col/>
  </colgroup>
  <tbody>
    <tr>
      <th>Marketo 필드</th>
      <th>MS Dynamics 필드</th>
      <th>MS Dynamics API 이름</th>
    </tr>
    <tr>
      <td>계정 (a)</td>
      <td>계정</td>
      <td>accountid</td>
    </tr>
    <tr>
      <td>청구지 주소</td>
      <td>주소 1: 상세 주소 1</td>
      <td>address1_line1</td>
    </tr>
    <tr>
      <td>청구지 시</td>
      <td>주소 1: 시</td>
      <td>address1_city</td>
    </tr>
    <tr>
      <td>청구지 국가</td>
      <td>주소 1: 국가/지역</td>
      <td>address1_country</td>
    </tr>
    <tr>
      <td>청구지 우편번호</td>
      <td>주소 1: 우편 번호</td>
      <td>address1_postalcode</td>
    </tr>
    <tr>
      <td>Microsoft 청구 주소 2</td>
      <td>주소 1: 상세 주소 2</td>
      <td>address1_line2</td>
    </tr>
    <tr>
      <td>Microsoft 청구 주소 3</td>
      <td>주소 1: 도로 3</td>
      <td>address1_line3</td>
    </tr>
    <tr>
      <td>주요 전화</td>
      <td>주요 전화</td>
      <td>telephone1</td>
    </tr>
    <tr>
      <td>비즈니스 유형</td>
      <td>비즈니스 유형</td>
      <td>businesstypecode</td>
    </tr>
    <tr>
      <td>Microsoft 계정 번호</td>
      <td>계정 번호</td>
      <td>accountnumber</td>
    </tr>
    <tr>
      <td>Microsoft 회사 상태</td>
      <td>상태</td>
      <td>statecode</td>
    </tr>
    <tr>
      <td>연간 수익</td>
      <td>연간 수익</td>
      <td>매출</td>
    </tr>
    <tr>
      <td>회사 메모</td>
      <td>설명</td>
      <td>설명</td>
    </tr>
    <tr>
      <td>산업</td>
      <td>산업</td>
      <td>산업 코드</td>
    </tr>
    <tr>
      <td>SIC 코드</td>
      <td>SIC 코드</td>
      <td>sic</td>
    </tr>
    <tr>
      <td>웹 사이트</td>
      <td>웹 사이트</td>
      <td>웹 사이트</td>
    </tr>
    <tr>
      <td>직원 수</td>
      <td>직원 수</td>
      <td>직원 수</td>
    </tr>
    <tr>
      <td>SIC 코드</td>
      <td>SIC 코드</td>
      <td>sic</td>
    </tr>
    <tr>
      <td>회사</td>
      <td>계정 이름</td>
      <td>이름</td>
    </tr>
    <tr>
      <td>직원 수</td>
      <td>직원 수</td>
      <td>직원 수</td>
    </tr>
  </tbody>
</table>

아래 계정 필드는 내부 사용을 위해 동기화됩니다.

<table>
  <colgroup>
    <col/>
    <col/>
  </colgroup>
  <tbody>
    <tr>
      <th>MS Dynamics 필드</th>
      <th>MS Dynamics API 이름</th>
    </tr>
    <tr>
      <td>소유자</td>
      <td>소유자 ID</td>
    </tr>
    <tr>
      <td>만든 날짜</td>
      <td>createdon</td>
    </tr>
  </tbody>
</table>

## 영업 기회 필드 {#opportunity-fields}

<table>
  <colgroup>
    <col/>
    <col/>
    <col/>
  </colgroup>
  <tbody>
    <tr>
      <th>Marketo 필드</th>
      <th>MS Dynamics 필드</th>
      <th>MS Dynamics API 이름</th>
    </tr>
    <tr>
      <td>근접확률</td>
      <td>가능성</td>
      <td>근접확률</td>
    </tr>
    <tr>
      <td>단계</td>
      <td>상태</td>
      <td>statecode</td>
    </tr>
    <tr>
      <td>실제 종료 일자</td>
      <td>실제 종료 일자</td>
      <td>actualclosedate</td>
    </tr>
    <tr>
      <td>이름</td>
      <td>주제</td>
      <td>이름</td>
    </tr>
    <tr>
      <td>예상 값</td>
      <td>예상. 매출</td>
      <td>estimatedValue</td>
    </tr>
    <tr>
      <td>설명</td>
      <td>설명</td>
      <td>설명</td>
    </tr>
  </tbody>
</table>

아래 계정 필드는 내부 사용을 위해 동기화됩니다.

<table>
  <colgroup>
    <col/>
    <col/>
  </colgroup>
  <tbody>
    <tr>
      <th>MS Dynamics 필드</th>
      <th>MS Dynamics API 이름</th>
    </tr>
    <tr>
      <td>소유자</td>
      <td>소유자 ID</td>
    </tr>
    <tr>
      <td>기회</td>
      <td>opportunityId</td>
    </tr>
    <tr>
      <td>잠재 고객</td>
      <td>customerId</td>
    </tr>
  </tbody>
</table>

## Marketo의 Microsoft 관련 시스템 필드(읽기 전용) {#microsoft-related-system-fields}

아래 필드는 Marketo에서 만들어졌지만 사용자가 조정할 수 없습니다.

<table>
  <colgroup>
    <col/>
    <col/>
  </colgroup>
  <tbody>
    <tr>
      <th>Marketo 필드</th>
      <th>설명</th>
    </tr>
    <tr>
      <td>Microsoft 유형</td>
      <td>리드 또는 연락처. 비어 있는 경우 잠재 고객은 Marketo의 사용자로만 존재합니다</td>
    </tr>
    <tr>
      <td>Microsoft 생성 날짜</td>
      <td>MS Dynamics에서 만든 날짜(Marketo에서 만든 날짜와 다를 수 있음)</td>
    </tr>
    <tr>
      <td>Microsoft이 삭제되었습니다.</td>
      <td>이전에 Microsoft에 있었으나 삭제되었습니다. 이제 Marketo에서만 살게 되었습니다.</td>
    </tr>
  </tbody>
</table>
