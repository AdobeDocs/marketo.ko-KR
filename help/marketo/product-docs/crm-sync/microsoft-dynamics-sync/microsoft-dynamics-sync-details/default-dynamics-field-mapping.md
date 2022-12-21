---
description: 기본 Dynamics 필드 매핑 - Marketo 문서 - 제품 설명서
title: 기본 Dynamics 필드 매핑
exl-id: 5f39bd0c-202e-4aa1-a0ac-49ac2554aa1e
source-git-commit: d87809e12f153d025f8d013ea52e06c0b6530154
workflow-type: tm+mt
source-wordcount: '829'
ht-degree: 17%

---

# 기본 Dynamics 필드 매핑 {#default-dynamics-field-mapping}

처음에 Marketo 계정을 Microsoft과 동기화할 때 Marketo은 내장된 Dynamics 및 Marketo 필드 간에 이러한 연결을 자동으로 만듭니다.  Marketo은 또한 리드, 계정, 기회 및 연락처에 사용자 지정 필드를 동기화합니다.

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
      <td>중간</td>
      <td>중간 이름</td>
      <td>미들네임</td>
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
      <td>직위</td>
      <td>직위</td>
      <td>jobtitle</td>
    </tr>
    <tr>
      <td>휴대폰</td>
      <td>비즈니스 전화</td>
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
      <td>Street 1</td>
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
      <td>address1_stateorstate</td>
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
      <td>개인 소스</td>
      <td>잠재 고객 소스</td>
      <td>leadsourcecode</td>
    </tr>
    <tr>
      <td>개인 상태</td>
      <td>상태</td>
      <td>statecode</td>
    </tr>
    <tr>
      <td>상태 이유</td>
      <td>상태 이유</td>
      <td>statecode</td>
    </tr>
    <tr>
      <td>개인 정보</td>
      <td>설명</td>
      <td>설명</td>
    </tr>
    <tr>
      <td>두 낫 콜</td>
      <td>전화 통화 허용 안 함</td>
      <td>도노폰</td>
    </tr>
    <tr>
      <td>주소 삭제</td>
      <td>대량 이메일 안함</td>
      <td>donotbulkemail</td>
    </tr>
    <tr>
      <td>개인 등급</td>
      <td>등급</td>
      <td>leadqualitycode</td>
    </tr>
    <tr>
      <td>Microsoft 주소 2</td>
      <td>Street 2</td>
      <td>address1_line2</td>
    </tr>
    <tr>
      <td>Microsoft 주소 3</td>
      <td>Street 3</td>
      <td>address1_line3</td>
    </tr>
    <tr>
      <td>Microsoft Do Not Email</td>
      <td>이메일 허용 안 함</td>
      <td>도노테말</td>
    </tr>
    <tr>
      <td>Microsoft 팩스 보내기 안 함</td>
      <td>팩스 허용 안 함</td>
      <td>donotfax</td>
    </tr>
    <tr>
      <td>Microsoft 마케팅 자료를 보내지 않음</td>
      <td>마케팅 자료</td>
      <td>donotsendmm</td>
    </tr>
    <tr>
      <td>Microsoft 홈 전화</td>
      <td>집 전화</td>
      <td>telephone2</td>
    </tr>
    <tr>
      <td>Microsoft 기본 연락 방법</td>
      <td>선호하는 연락 방법</td>
      <td>preferredcontactmethod 코드</td>
    </tr>
    <tr>
      <td>Microsoft 항목</td>
      <td>주제</td>
      <td>주제</td>
    </tr>
    <tr>
      <td>마지막 흥미로운 순간 날짜</td>
      <td>마지막 흥미로운 순간 날짜</td>
      <td>mkt_lastinterest_momentdate</td>
    </tr>
    <tr>
      <td>마지막 흥미로운 모멘트 설명</td>
      <td>마지막 흥미로운 모멘트 설명</td>
      <td>mkt_lastinterestmomentdesc</td>
    </tr>
    <tr>
      <td>마지막 관심 영역 소스</td>
      <td>마지막 관심 영역 소스</td>
      <td>mkt_leadinterestmomentsource</td>
    </tr>
    <tr>
      <td>마지막 흥미로운 순간 유형</td>
      <td>마지막 흥미로운 순간 유형</td>
      <td>mkt_lastinterestmomenttype</td>
    </tr>
    <tr>
      <td>회사</td>
      <td>회사명</td>
      <td>companyname</td>
    </tr>
    <tr>
      <td>상대 점수</td>
      <td>상대 점수</td>
      <td>mkt_relativescore</td>
    </tr>
    <tr>
      <td>우선 순위</td>
      <td>우선 순위</td>
      <td>mkt_priority</td>
    </tr>
    <tr>
      <td>상대적인 긴급성</td>
      <td>긴급성</td>
      <td>mkt_긴급성</td>
    </tr>
    <tr>
      <td>제목</td>
      <td>주제</td>
      <td>주제</td>
    </tr>
    <tr>
      <td>연간 수익</td>
      <td>연간 수익</td>
      <td>매출</td>
    </tr>
  </tbody>
</table>

아래의 리드 필드는 내부 사용을 위해 동기화됩니다.

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
      <td>소유자 </td>
      <td>ownerid</td>
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
      <td>중간</td>
      <td>중간 이름</td>
      <td>미들네임</td>
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
      <td>직위</td>
      <td>직위</td>
      <td>jobtitle</td>
    </tr>
    <tr>
      <td>휴대폰</td>
      <td>비즈니스 전화</td>
      <td>telephone1</td>
    </tr>
    <tr>
      <td>모바일</td>
      <td>휴대폰</td>
      <td>mobilephone</td>
    </tr>
    <tr>
      <td>주소</td>
      <td>주소 1: Street 1</td>
      <td>address1_line1</td>
    </tr>
    <tr>
      <td>시</td>
      <td>주소 1: 구/군/시</td>
      <td>address1_city</td>
    </tr>
    <tr>
      <td>주</td>
      <td>주소 1: 시/도</td>
      <td>address1_stateorstate</td>
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
      <td>상태 이유</td>
      <td>상태 이유</td>
      <td>statecode</td>
    </tr>
    <tr>
      <td>두 낫 콜</td>
      <td>전화 통화 허용 안 함</td>
      <td>도노폰</td>
    </tr>
    <tr>
      <td>주소 삭제</td>
      <td>대량 이메일 안함</td>
      <td>donotbulkemail</td>
    </tr>
    <tr>
      <td>Microsoft 주소 2</td>
      <td>주소 1: Street 2</td>
      <td>address1_line2</td>
    </tr>
    <tr>
      <td>Microsoft 주소 3</td>
      <td>주소 1: Street 3</td>
      <td>address1_line3</td>
    </tr>
    <tr>
      <td>Microsoft Do Not Email</td>
      <td>이메일 허용 안 함</td>
      <td>도노테말</td>
    </tr>
    <tr>
      <td>Microsoft 홈 전화</td>
      <td>집 전화</td>
      <td>telephone2</td>
    </tr>
    <tr>
      <td>Microsoft 기본 연락 방법</td>
      <td>선호하는 연락 방법</td>
      <td>preferredcontactmethod 코드</td>
    </tr>
    <tr>
      <td>마지막 흥미로운 순간 날짜</td>
      <td>마지막 흥미로운 순간 날짜</td>
      <td>mkt_lastinterest_momentdate</td>
    </tr>
    <tr>
      <td>마지막 흥미로운 순간 유형</td>
      <td>마지막 흥미로운 순간 유형</td>
      <td>mkt_lastinterestmomenttype</td>
    </tr>
    <tr>
      <td>마지막 관심 영역 소스</td>
      <td>마지막 관심 영역 소스</td>
      <td>mkt_leadinterestmomentsource</td>
    </tr>
    <tr>
      <td>마지막 흥미로운 모멘트 설명</td>
      <td>마지막 흥미로운 모멘트 설명</td>
      <td>mkt_lastinterestmomentdesc</td>
    </tr>
    <tr>
      <td>Microsoft 마케팅 자료를 보내지 않음</td>
      <td>마케팅 자료</td>
      <td>donotsendmm</td>
    </tr>
    <tr>
      <td>Microsoft 팩스 보내기 안 함</td>
      <td>Microsoft 팩스 보내기 안 함</td>
      <td>donotfax</td>
    </tr>
    <tr>
      <td>우선 순위</td>
      <td>우선 순위</td>
      <td>mkt_priority</td>
    </tr>
    <tr>
      <td>상대적인 긴급성</td>
      <td>긴급성</td>
      <td>mkt_긴급성</td>
    </tr>
    <tr>
      <td>상대 점수</td>
      <td>상대 점수</td>
      <td>mkt_relativescore</td>
    </tr>
    <tr>
      <td>개인 정보</td>
      <td>설명</td>
      <td>설명 </td>
    </tr>
    <tr>
      <td>개인 점수</td>
      <td>잠재 고객 점수</td>
      <td>mkt_leadscore</td>
    </tr>
    <tr>
      <td>개인 정보</td>
      <td>설명</td>
      <td>설명 </td>
    </tr>
  </tbody>
</table>

아래의 연락처 필드는 내부 사용을 위해 동기화됩니다.

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
      <td>소유자 </td>
      <td>ownerid</td>
    </tr>
    <tr>
      <td>만든 날짜</td>
      <td>createdon</td>
    </tr>
    <tr>
      <td>parentcustomerid</td>
      <td>회사명</td>
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
      <td>계정(a)</td>
      <td>계정</td>
      <td>accountid</td>
    </tr>
    <tr>
      <td>청구지 주소</td>
      <td>주소 1: Street 1</td>
      <td>address1_line1</td>
    </tr>
    <tr>
      <td>청구지 시</td>
      <td>주소 1: 구/군/시</td>
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
      <td>주소 1: Street 2</td>
      <td>address1_line2</td>
    </tr>
    <tr>
      <td>Microsoft 청구 주소 3</td>
      <td>주소 1: Street 3</td>
      <td>address1_line3</td>
    </tr>
    <tr>
      <td>메인 전화</td>
      <td>메인 전화</td>
      <td>telephone1</td>
    </tr>
    <tr>
      <td>비즈니스 유형</td>
      <td>비즈니스 유형</td>
      <td>businessstypecode</td>
    </tr>
    <tr>
      <td>Microsoft 계정 번호</td>
      <td>계정 번호</td>
      <td>계정 번호</td>
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
      <td>회사 노트</td>
      <td>설명</td>
      <td>설명</td>
    </tr>
    <tr>
      <td>산업</td>
      <td>산업</td>
      <td>industrycode</td>
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
      <td>이름</td>
      <td>계정 이름</td>
    </tr>
    <tr>
      <td>직원 수</td>
      <td>직원 수</td>
      <td>직원 수</td>
    </tr>
  </tbody>
</table>

아래의 계정 필드는 내부 사용을 위해 동기화됩니다.

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
      <td>소유자 </td>
      <td>ownerid</td>
    </tr>
    <tr>
      <td>만든 날짜</td>
      <td>createdon</td>
    </tr>
  </tbody>
</table>

## 기회 필드 {#opportunity-fields}

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
      <td>확률 닫기</td>
      <td>확률</td>
      <td>닫힘 확률</td>
    </tr>
    <tr>
      <td>단계</td>
      <td>상태</td>
      <td>statecode</td>
    </tr>
    <tr>
      <td>실제 마감 날짜</td>
      <td>실제 마감 날짜</td>
      <td>actualclosedate</td>
    </tr>
    <tr>
      <td>이름</td>
      <td>주제</td>
      <td>이름</td>
    </tr>
    <tr>
      <td>예상 값</td>
      <td>설정. 매출</td>
      <td>estimatedValue</td>
    </tr>
    <tr>
      <td>설명</td>
      <td>설명</td>
      <td>설명</td>
    </tr>
  </tbody>
</table>

아래의 계정 필드는 내부 사용을 위해 동기화됩니다.

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
      <td>소유자 </td>
      <td>ownerid</td>
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

아래 필드는 Marketo에서 만들어지지만 사용자가 조정할 수 없습니다.

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
      <td>리드 또는 연락처. 비어 있는 경우, 리드는 Marketo에 개인으로만 존재합니다</td>
    </tr>
    <tr>
      <td>Microsoft 생성 날짜</td>
      <td>MS Dynamics에서 만든 날짜(Marketo에서 만든 날짜와 다를 수 있음)</td>
    </tr>
    <tr>
      <td>Microsoft 삭제</td>
      <td>Microsoft에 있었지만 삭제되어 현재 Marketo에만 있는 사람</td>
    </tr>
  </tbody>
</table>
