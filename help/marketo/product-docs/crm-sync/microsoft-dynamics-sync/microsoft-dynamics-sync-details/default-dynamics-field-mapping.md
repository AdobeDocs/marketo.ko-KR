---
description: 기본 Dynamics 필드 매핑 - Marketo 문서 - 제품 설명서
title: 기본 Dynamics 필드 매핑
exl-id: 5f39bd0c-202e-4aa1-a0ac-49ac2554aa1e
feature: Microsoft Dynamics
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '332'
ht-degree: 4%

---

# 기본 Dynamics 필드 매핑 {#default-dynamics-field-mapping}

Marketo Engage 계정을 Microsoft과 처음 동기화할 때 Marketo은 내장된 Dynamics와 Marketo 필드 간에 이러한 연결을 자동으로 만듭니다.  Marketo은 리드, 계정, 기회 및 연락처에서 사용자 정의 필드도 동기화합니다.

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
      <td>[!UICONTROL Microsoft Created Date]</td>
      <td>[!UICONTROL Created On]</td>
      <td>createdon</td>
    </tr>
    <tr>
      <td>[!UICONTROL Salutation]</td>
      <td>[!UICONTROL Salutation]</td>
      <td>인사말</td>
    </tr>
    <tr>
      <td>[!UICONTROL First]</td>
      <td>[!UICONTROL First Name]</td>
      <td>이름</td>
    </tr>
    <tr>
      <td>[!UICONTROL Middle]</td>
      <td>[!UICONTROL Middle Name]</td>
      <td>middlename</td>
    </tr>
    <tr>
      <td>[!UICONTROL Last]</td>
      <td>[!UICONTROL Last Name]</td>
      <td>성</td>
    </tr>
    <tr>
      <td>[!UICONTROL Email]</td>
      <td>[!UICONTROL Email]</td>
      <td>emailaddress1</td>
    </tr>
    <tr>
      <td>[!UICONTROL Job Title]</td>
      <td>[!UICONTROL Job title]</td>
      <td>직함</td>
    </tr>
    <tr>
      <td>[!UICONTROL Phone]</td>
      <td>[!UICONTROL Business Phone]</td>
      <td>전화 번호1</td>
    </tr>
    <tr>
      <td>[!UICONTROL Mobile]</td>
      <td>[!UICONTROL Mobile Phone]</td>
      <td>mobilephone</td>
    </tr>
    <tr>
      <td>[!UICONTROL Fax]</td>
      <td>[!UICONTROL Fax]</td>
      <td>팩스</td>
    </tr>
    <tr>
      <td>[!UICONTROL Address]</td>
      <td>[!UICONTROL Street 1]</td>
      <td>address1_line1</td>
    </tr>
    <tr>
      <td>[!UICONTROL City]</td>
      <td>[!UICONTROL City]</td>
      <td>address1_city</td>
    </tr>
    <tr>
      <td>[!UICONTROL State]</td>
      <td>[!UICONTROL State/Province]</td>
      <td>address1_stateorprovince</td>
    </tr>
    <tr>
      <td>[!UICONTROL Country]</td>
      <td>[!UICONTROL Country/Region]</td>
      <td>address1_country</td>
    </tr>
    <tr>
      <td>[!UICONTROL Postal Code]</td>
      <td>[!UICONTROL Zip/Postal Code]</td>
      <td>address1_postalcode</td>
    </tr>
    <tr>
      <td>[!UICONTROL Person Source]</td>
      <td>[!UICONTROL Lead Source]</td>
      <td>리드소스 코드</td>
    </tr>
    <tr>
      <td>[!UICONTROL Person Status]</td>
      <td>[!UICONTROL Status]</td>
      <td>statecode</td>
    </tr>
    <tr>
      <td>[!UICONTROL Status Reason]</td>
      <td>[!UICONTROL Status Reason]</td>
      <td>statuscode</td>
    </tr>
    <tr>
      <td>[!UICONTROL Person Notes]</td>
      <td>[!UICONTROL Description]</td>
      <td>설명</td>
    </tr>
    <tr>
      <td>[!UICONTROL Do Not Call]</td>
      <td>[!UICONTROL Do Not Allow Phone Calls]</td>
      <td>donotphone</td>
    </tr>
    <tr>
      <td>[!UICONTROL Unsubscribed]</td>
      <td>[!UICONTROL Do not bulk email]</td>
      <td>donotbulkemail</td>
    </tr>
    <tr>
      <td>[!UICONTROL Person Rating]</td>
      <td>[!UICONTROL Rating]</td>
      <td>잠재 고객 코드</td>
    </tr>
    <tr>
      <td>[!UICONTROL Microsoft Address 2]</td>
      <td>[!UICONTROL Street 2]</td>
      <td>address1_line2</td>
    </tr>
    <tr>
      <td>[!UICONTROL Microsoft Address 3]</td>
      <td>[!UICONTROL Street 3]</td>
      <td>address1_line3</td>
    </tr>
    <tr>
      <td>[!UICONTROL Microsoft Do Not Email]</td>
      <td>[!UICONTROL Do Not Allow Emails]</td>
      <td>donotemail</td>
    </tr>
    <tr>
      <td>[!UICONTROL Microsoft Do Not Fax]</td>
      <td>[!UICONTROL Do Not Allow Faxes]</td>
      <td>donot팩스</td>
    </tr>
    <tr>
      <td>[!UICONTROL Microsoft Do Not Send Marketing Material]</td>
      <td>[!UICONTROL Marketing Material]</td>
      <td>donotsendmm</td>
    </tr>
    <tr>
      <td>[!UICONTROL Microsoft Home Phone]</td>
      <td>[!UICONTROL Home Phone]</td>
      <td>전화 번호2</td>
    </tr>
    <tr>
      <td>[!UICONTROL Microsoft Preferred Method Of Contact]</td>
      <td>[!UICONTROL Preferred Method of Contact]</td>
      <td>preferredcontactmethodcode</td>
    </tr>
    <tr>
      <td>[!UICONTROL Microsoft Topic]</td>
      <td>[!UICONTROL Topic]</td>
      <td>제목</td>
    </tr>
    <tr>
      <td>[!UICONTROL Last interesting moment date]</td>
      <td>[!UICONTROL Last interesting moment date]</td>
      <td>mkt_lastinterestingmomentdate</td>
    </tr>
    <tr>
      <td>[!UICONTROL Last Interesting moment desc]</td>
      <td>[!UICONTROL Last Interesting moment desc]</td>
      <td>mkt_lastinterestingmomentdesc</td>
    </tr>
    <tr>
      <td>[!UICONTROL Last Interesting moment source]</td>
      <td>[!UICONTROL Last Interesting moment source]</td>
      <td>mkt_leadinterrestingmomentsource</td>
    </tr>
    <tr>
      <td>[!UICONTROL Last interesting moment type]</td>
      <td>[!UICONTROL Last interesting moment type]</td>
      <td>mkt_lastinterestingmomenttype</td>
    </tr>
    <tr>
      <td>[!UICONTROL Company]</td>
      <td>[!UICONTROL Company Name]</td>
      <td>companyname</td>
    </tr>
    <tr>
      <td>[!UICONTROL Relative Score]</td>
      <td>[!UICONTROL Relative Score]</td>
      <td>mkt_relativescore</td>
    </tr>
    <tr>
      <td>[!UICONTROL Priority]</td>
      <td>[!UICONTROL Priority]</td>
      <td>mkt_priority</td>
    </tr>
    <tr>
      <td>[!UICONTROL Relative Urgency]</td>
      <td>[!UICONTROL Urgency]</td>
      <td>mkt_urgency</td>
    </tr>
    <tr>
      <td>[!UICONTROL Subject]</td>
      <td>[!UICONTROL Topic]</td>
      <td>제목</td>
    </tr>
    <tr>
      <td>[!UICONTROL Annual Revenue]</td>
      <td>[!UICONTROL Annual Revenue]</td>
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
      <td>[!UICONTROL Owner] </td>
      <td>소유자 ID</td>
    </tr>
    <tr>
      <td>[!UICONTROL Created On]</td>
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
      <td>[!UICONTROL Microsoft Created Date]</td>
      <td>[!UICONTROL Created On]</td>
      <td>createdon</td>
    </tr>
    <tr>
      <td>[!UICONTROL Salutation]</td>
      <td>[!UICONTROL Salutation]</td>
      <td>인사말</td>
    </tr>
    <tr>
      <td>[!UICONTROL First]</td>
      <td>[!UICONTROL First Name]</td>
      <td>이름</td>
    </tr>
    <tr>
      <td>[!UICONTROL Middle]</td>
      <td>[!UICONTROL Middle Name]</td>
      <td>middlename</td>
    </tr>
    <tr>
      <td>[!UICONTROL Last]</td>
      <td>[!UICONTROL Last Name]</td>
      <td>성</td>
    </tr>
    <tr>
      <td>[!UICONTROL Email]</td>
      <td>[!UICONTROL Email]</td>
      <td>emailaddress1</td>
    </tr>
    <tr>
      <td>[!UICONTROL Job Title]</td>
      <td>[!UICONTROL Job Title]</td>
      <td>직함</td>
    </tr>
    <tr>
      <td>[!UICONTROL Phone]</td>
      <td>[!UICONTROL Business Phone]</td>
      <td>전화 번호1</td>
    </tr>
    <tr>
      <td>[!UICONTROL Mobile]</td>
      <td>[!UICONTROL Mobile Phone]</td>
      <td>mobilephone</td>
    </tr>
    <tr>
      <td>[!UICONTROL Address]</td>
      <td>[!UICONTROL Address 1: Street 1]</td>
      <td>address1_line1</td>
    </tr>
    <tr>
      <td>[!UICONTROL City]</td>
      <td>[!UICONTROL Address 1: City]</td>
      <td>address1_city</td>
    </tr>
    <tr>
      <td>[!UICONTROL State]</td>
      <td>[!UICONTROL Address 1: State/Province]</td>
      <td>address1_stateorprovince</td>
    </tr>
    <tr>
      <td>[!UICONTROL Country]</td>
      <td>[!UICONTROL Address 1: Country/Region]</td>
      <td>address1_country</td>
    </tr>
    <tr>
      <td>[!UICONTROL Postal Code]</td>
      <td>[!UICONTROL Address 1: Zip/Postal Code]</td>
      <td>address1_postalcode</td>
    </tr>
    <tr>
      <td>[!UICONTROL Person Status]</td>
      <td>[!UICONTROL Status]</td>
      <td>statecode</td>
    </tr>
    <tr>
      <td>[!UICONTROL Status Reason]</td>
      <td>[!UICONTROL Status Reason]</td>
      <td>statuscode</td>
    </tr>
    <tr>
      <td>[!UICONTROL Do Not Call]</td>
      <td>[!UICONTROL Do Not Allow Phone Calls]</td>
      <td>donotphone</td>
    </tr>
    <tr>
      <td>[!UICONTROL Unsubscribed]</td>
      <td>[!UICONTROL Do not bulk email]</td>
      <td>donotbulkemail</td>
    </tr>
    <tr>
      <td>[!UICONTROL Microsoft Address 2]</td>
      <td>[!UICONTROL Address 1: Street 2]</td>
      <td>address1_line2</td>
    </tr>
    <tr>
      <td>[!UICONTROL Microsoft Address 3]</td>
      <td>[!UICONTROL Address 1: Street 3]</td>
      <td>address1_line3</td>
    </tr>
    <tr>
      <td>[!UICONTROL Microsoft Do Not Email]</td>
      <td>[!UICONTROL Do Not Allow Emails]</td>
      <td>donotemail</td>
    </tr>
    <tr>
      <td>[!UICONTROL Microsoft Home Phone]</td>
      <td>[!UICONTROL Home Phone]</td>
      <td>전화 번호2</td>
    </tr>
    <tr>
      <td>[!UICONTROL Microsoft Preferred Method Of Contact]</td>
      <td>[!UICONTROL Preferred Method Of Contact]</td>
      <td>preferredcontactmethodcode</td>
    </tr>
    <tr>
      <td>[!UICONTROL Last interesting moment date]</td>
      <td>[!UICONTROL Last interesting moment date]</td>
      <td>mkt_lastinterestingmomentdate</td>
    </tr>
    <tr>
      <td>[!UICONTROL Last interesting moment type]</td>
      <td>[!UICONTROL Last interesting moment type]</td>
      <td>mkt_lastinterestingmomenttype</td>
    </tr>
    <tr>
      <td>[!UICONTROL Last Interesting moment source]</td>
      <td>[!UICONTROL Last Interesting moment source]</td>
      <td>mkt_leadinterrestingmomentsource</td>
    </tr>
    <tr>
      <td>[!UICONTROL Last Interesting moment desc]</td>
      <td>[!UICONTROL Last Interesting moment desc]</td>
      <td>mkt_lastinterestingmomentdesc</td>
    </tr>
    <tr>
      <td>[!UICONTROL Microsoft Do Not Send Marketing Material]</td>
      <td>[!UICONTROL Marketing Material]</td>
      <td>donotsendmm</td>
    </tr>
    <tr>
      <td>[!UICONTROL Microsoft Do Not Fax]</td>
      <td>[!UICONTROL Microsoft Do Not Fax]</td>
      <td>donot팩스</td>
    </tr>
    <tr>
      <td>[!UICONTROL Priority]</td>
      <td>[!UICONTROL Priority]</td>
      <td>mkt_priority</td>
    </tr>
    <tr>
      <td>[!UICONTROL Relative Urgency]</td>
      <td>[!UICONTROL Urgency]</td>
      <td>mkt_urgency</td>
    </tr>
    <tr>
      <td>[!UICONTROL Relative Score]</td>
      <td>[!UICONTROL Relative Score]</td>
      <td>mkt_relativescore</td>
    </tr>
    <tr>
      <td>[!UICONTROL Person Notes]</td>
      <td>[!UICONTROL Description]</td>
      <td>설명 </td>
    </tr>
    <tr>
      <td>[!UICONTROL Person Score]</td>
      <td>[!UICONTROL Lead Score]</td>
      <td>mkt_leadscore</td>
    </tr>
    <tr>
      <td>[!UICONTROL Person Notes]</td>
      <td>[!UICONTROL Description]</td>
      <td>설명 </td>
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
      <td>[!UICONTROL Owner] </td>
      <td>소유자 ID</td>
    </tr>
    <tr>
      <td>[!UICONTROL Created On]</td>
      <td>createdon</td>
    </tr>
    <tr>
      <td>[!UICONTROL Company Name]</td>
      <td>parentcustomerid</td>
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
      <td>[!UICONTROL Account (a)]</td>
      <td>[!UICONTROL Account]</td>
      <td>accountid</td>
    </tr>
    <tr>
      <td>[!UICONTROL Billing Address]</td>
      <td>[!UICONTROL Address 1: Street 1]</td>
      <td>address1_line1</td>
    </tr>
    <tr>
      <td>[!UICONTROL Billing City]</td>
      <td>[!UICONTROL Address 1: City]</td>
      <td>address1_city</td>
    </tr>
    <tr>
      <td>[!UICONTROL Billing Country]</td>
      <td>[!UICONTROL Address 1: Country/Region]</td>
      <td>address1_country</td>
    </tr>
    <tr>
      <td>[!UICONTROL Billing Postal Code]</td>
      <td>[!UICONTROL Address 1: Zip/Postal Code]</td>
      <td>address1_postalcode</td>
    </tr>
    <tr>
      <td>[!UICONTROL Microsoft Billing Address 2]</td>
      <td>[!UICONTROL Address 1: Street 2]</td>
      <td>address1_line2</td>
    </tr>
    <tr>
      <td>[!UICONTROL Microsoft Billing Address 3]</td>
      <td>[!UICONTROL Address 1: Street 3]</td>
      <td>address1_line3</td>
    </tr>
    <tr>
      <td>[!UICONTROL Main Phone]</td>
      <td>[!UICONTROL Main Phone]</td>
      <td>전화 번호1</td>
    </tr>
    <tr>
      <td>[!UICONTROL Business Type]</td>
      <td>[!UICONTROL Business Type]</td>
      <td>businesstypecode</td>
    </tr>
    <tr>
      <td>[!UICONTROL Microsoft Account Number]</td>
      <td>[!UICONTROL Account Number]</td>
      <td>accountnumber</td>
    </tr>
    <tr>
      <td>[!UICONTROL Microsoft Company Status]</td>
      <td>[!UICONTROL Status]</td>
      <td>statecode</td>
    </tr>
    <tr>
      <td>[!UICONTROL Annual Revenue]</td>
      <td>[!UICONTROL Annual Revenue]</td>
      <td>매출</td>
    </tr>
    <tr>
      <td>[!UICONTROL Company Notes]</td>
      <td>[!UICONTROL Description]</td>
      <td>설명</td>
    </tr>
    <tr>
      <td>[!UICONTROL Industry]</td>
      <td>[!UICONTROL Industry]</td>
      <td>산업 코드</td>
    </tr>
    <tr>
      <td>[!UICONTROL SIC Code]</td>
      <td>[!UICONTROL SIC Code]</td>
      <td>sic</td>
    </tr>
    <tr>
      <td>[!UICONTROL Website]</td>
      <td>[!UICONTROL Website]</td>
      <td>웹 사이트</td>
    </tr>
    <tr>
      <td>[!UICONTROL Num Employees]</td>
      <td>[!UICONTROL Number of Employees]</td>
      <td>직원 수</td>
    </tr>
    <tr>
      <td>[!UICONTROL SIC Code]</td>
      <td>[!UICONTROL SIC Code]</td>
      <td>sic</td>
    </tr>
    <tr>
      <td>[!UICONTROL Company]</td>
      <td>[!UICONTROL Account Name]</td>
      <td>이름</td>
    </tr>
    <tr>
      <td>[!UICONTROL Num Employees]</td>
      <td>[!UICONTROL Number of Employees]</td>
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
      <td>[!UICONTROL Owner] </td>
      <td>소유자 ID</td>
    </tr>
    <tr>
      <td>[!UICONTROL Created On]</td>
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
      <td>[!UICONTROL Close Probability]</td>
      <td>[!UICONTROL Probabliity]</td>
      <td>근접확률</td>
    </tr>
    <tr>
      <td>[!UICONTROL Stage]</td>
      <td>[!UICONTROL Status]</td>
      <td>statecode</td>
    </tr>
    <tr>
      <td>[!UICONTROL Actual Close Date]</td>
      <td>[!UICONTROL Actual Close Date]</td>
      <td>actualclosedate</td>
    </tr>
    <tr>
      <td>[!UICONTROL Name]</td>
      <td>[!UICONTROL Topic]</td>
      <td>이름</td>
    </tr>
    <tr>
      <td>[!UICONTROL Estimated Value]</td>
      <td>[!UICONTROL Est. Revenue]</td>
      <td>estimatedValue</td>
    </tr>
    <tr>
      <td>[!UICONTROL Description]</td>
      <td>[!UICONTROL Description]</td>
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
      <td>[!UICONTROL Owner] </td>
      <td>소유자 ID</td>
    </tr>
    <tr>
      <td>[!UICONTROL Opportunity]</td>
      <td>opportunityId</td>
    </tr>
    <tr>
      <td>[!UICONTROL Potential Customer]</td>
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
      <td>[!UICONTROL Microsoft Type]</td>
      <td>리드 또는 연락처. 비어 있는 경우 잠재 고객은 Marketo의 사용자로만 존재합니다</td>
    </tr>
    <tr>
      <td>[!UICONTROL Microsoft Created Date]</td>
      <td>[!DNL MS Dynamics]에 만든 날짜(Marketo에서 만든 날짜와 다를 수 있음)</td>
    </tr>
    <tr>
      <td>[!UICONTROL Microsoft is Deleted]</td>
      <td>이전에 Microsoft에 있었으나 삭제되었습니다. 이제 Marketo에서만 살게 되었습니다.</td>
    </tr>
  </tbody>
</table>
