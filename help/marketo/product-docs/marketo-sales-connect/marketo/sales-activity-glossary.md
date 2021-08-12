---
description: 영업 활동 용어집 - Marketo 문서 - 제품 설명서
title: 영업 활동 용어집
hide: true
hidefromtoc: true
source-git-commit: 70f17106efe52ee742c8e31013e533fc36ce9835
workflow-type: tm+mt
source-wordcount: '275'
ht-degree: 3%

---

# 영업 활동 용어집 {#sales-activity-glossary}

Sales Connect에서 판매자가 영업 케이스에 리드를 추가하거나, 이메일을 보내거나, 활동을 호출하면 Marketo 활동 내역 아래에 기록됩니다. 또한 리드가 이메일, 열기, 클릭 및 회신을 참여하면 로그됩니다.

아래 활동은 Sales Connect에서 Marketo으로 기록됩니다.

>[!NOTE]
>
>이러한 활동 및 속성은 REST 및 벌크 API에서 사용할 수 있습니다.

## 활동 {#activities}

<table>
 <tr>
  <th>영업 활동</th>
  <th>속성</th>
 </tr>
 <tr>
  <th rowspan="3">영업 전자 메일 보내기</th>
  <td>보낸 사람</td>
 </tr>
 <tr>
  <td>원문</td>
 </tr>
 <tr>
  <td>템플릿 ID</td>
 </tr>
 <tr>
  <th rowspan="3">영업 전자 메일 열기</th>
  <td>보낸 사람</td>
 </tr>
 <tr>
  <td>원문</td>
 </tr>
 <tr>
  <td>템플릿 ID</td>
 </tr>
 <tr>
  <th rowspan="4">클릭한 영업 이메일</th>
  <td>링크</td>
 </tr>
 <tr>
  <td>보낸 사람</td>
 </tr>
 <tr>
  <td>원문</td>
 </tr>
 <tr>
  <td>템플릿 ID</td>
 </tr>
 <tr>
  <th rowspan="2">받은 영업 전자 메일</th>
  <td>받는 사람</td>
 </tr>
 <tr>
  <td>원문</td>
 </tr>
 <tr>
  <th rowspan="4">판매 이메일 바운스됨</th>
  <td>세부 사항</td>
 </tr>
 <tr>
  <td>템플릿 ID</td>
 </tr>
 <tr>
  <td>이메일</td>
 </tr>
 <tr>
  <td>보낸 사람</td>
 </tr>
 <tr>
  <th rowspan="7">수신한 영업 호출</th>
  <td>판매 호출</td>
 </tr>
 <tr>
  <td>영업 호출 상태</td>
 </tr>
 <tr>
  <td>영업 통화 제목</td>
 </tr>
 <tr>
  <td>영업 캠페인 이름</td>
 </tr>
 <tr>
  <td>영업 캠페인 URL</td>
 </tr>
 <tr>
  <td>전화 번호</td>
 </tr>
 <tr>
  <td>원문</td>
 </tr>
 <tr>
  <th rowspan="6">영업 캠페인에 추가</th>
  <td>영업 캠페인 이름</td>
 </tr>
 <tr>
  <td>영업 호출 상태</td>
 </tr>
 <tr>
  <td>영업 캠페인 URL</td>
 </tr>
 <tr>
  <td>보낸 사람</td>
 </tr>
 <tr>
  <td>원문</td>
 </tr>
 <tr>
  <td>영업 캠페인 ID</td>
 </tr>
 <tr>
  <th rowspan="6">영업 캠페인에서 제거</th>
  <td>영업 캠페인 이름</td>
 </tr>
 <tr>
  <td>영업 호출 상태</td>
 </tr>
 <tr>
  <td>영업 캠페인 URL</td>
 </tr>
 <tr>
  <td>보낸 사람</td>
 </tr>
 <tr>
  <td>원문</td>
 </tr>
 <tr>
  <td>영업 캠페인 ID</td>
 </tr>
</table>

## 설명 {#descriptions}

<table> 
 <tr>
  <th>속성</th>
  <th>설명</th>
 </tr>
 <tbody> 
  <tr> 
   <td><strong>보낸 사람</strong></td>
   <td>이메일을 보낸 사람의 이메일 주소입니다.</td> 
  </tr> 
  <tr> 
   <td><strong>원문</strong></td> 
   <td>활동의 소스. Sales Connect 활동에 대해 "Tout"으로 설정됩니다.</td> 
  </tr> 
  <tr> 
   <td><strong>템플릿 ID</strong></td> 
   <td>소스가 Tout이면 템플릿 ID는 Marketo Sales Connect 템플릿 ID입니다. 여러 템플릿에 있을 수 있는 제목 줄 대신 특정 템플릿을 타깃팅하려면 이 방법을 사용합니다.
</td> 
  </tr> 
  <tr> 
   <td><strong>받는 사람</strong></td> 
   <td>이메일을 보낸 사람의 이메일 주소입니다.</td> 
  </tr> 
  <tr> 
   <td><strong>세부 사항</strong></td> 
   <td>반송 오류 메시지 세부 정보입니다.</td> 
  </tr> 
  <tr> 
   <td><strong>이메일</strong></td> 
   <td>바운스된 이메일 주소입니다.</td> 
  </tr> 
 </tbody> 
</table>