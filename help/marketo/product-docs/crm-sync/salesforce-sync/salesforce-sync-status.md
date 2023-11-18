---
description: Salesforce 동기화 상태 - Marketo 문서 - 제품 설명서
title: Salesforce 동기화 상태
exl-id: 61197808-7812-4e0a-8ac6-4a60af0f7979
feature: Salesforce Integration
source-git-commit: 4045f262889d06304111288d30da893529396e81
workflow-type: tm+mt
source-wordcount: '554'
ht-degree: 4%

---

# Salesforce 동기화 상태 {#salesforce-sync-status}

동기화 상태 대시보드를 사용하여 동기화 단계 및 성공 상태의 일부로 동기화 상태를 봅니다.

동기화 단계는 객체 스키마 및 데이터 자체에 대한 각 객체 유형별 푸시 또는 풀 작업을 반영합니다. 통계는 동기화 중 새 레코드, 업데이트, 삭제 및 실패 수를 다룹니다. 사용자는 날짜, 작업 유형 또는 오브젝트 유형별로 필터링할 수 있습니다. 동기화 상태 대시보드에 지난 5일 동안의 동기화 주기 상태가 표시됩니다.

>[!NOTE]
>
>관리자 권한 필요

## 동기화 상태 보기 {#view-sync-status}

1. 클릭 **[!UICONTROL 관리자]**.

   ![](assets/salesforce-sync-status-1.png)

1. 아래 [!UICONTROL 통합], 클릭 **Salesforce**, 그런 다음 **[!UICONTROL 동기화 상태]** 탭.

   ![](assets/salesforce-sync-status-2.png)

기본적으로 통계는 가장 최근에 시작한 항목별로 정렬됩니다. 정렬 아이콘을 클릭하여 시작 날짜 또는 종료 날짜(가장 최근 날짜부터 가장 오래된 날짜까지)별로 정렬할 수 있습니다.

![](assets/salesforce-sync-status-3.png)

## 동기화 상태 필터링 {#filter-sync-status}

1. 데이터를 필터링하려면 페이지의 맨 오른쪽에 있는 필터 아이콘을 클릭합니다.

   ![](assets/salesforce-sync-status-4.png)

1. 날짜 및 시간 범위를 선택한 다음 필터링할 드롭다운을 클릭합니다 [!UICONTROL 오브젝트 유형], [!UICONTROL 작업 유형], 및/또는 [!UICONTROL 상태 유형].

   ![](assets/salesforce-sync-status-5.png)

1. 클릭 **[!UICONTROL 적용]**.

   ![](assets/salesforce-sync-status-6.png)

**선택적 단계**: 동기화 오류를 내보내려면 **[!UICONTROL 내보내기]**. 데이터는 CSV로 내보내집니다.

![](assets/salesforce-sync-status-7.png)

## 동기화 상태 필드 {#sync-status-fields}

<table> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <th>필드</th> 
   <th>설명</th> 
   <th>열거형 값</th> 
  </tr> 
  <tr> 
   <td colspan="1">시작 시간:</td> 
   <td colspan="1">동기화 주기 시작 날짜/시간(사용자의 시간대)</td> 
   <td colspan="1"></td> 
  </tr>  
  <tr> 
   <td colspan="1">종료 시간</td> 
   <td colspan="1">동기화 주기 종료 날짜/시간(사용자의 시간대)</td> 
   <td colspan="1"></td> 
  </tr> 
  <tr> 
   <td colspan="1">오브젝트</td> 
   <td colspan="1">오브젝트 유형</td> 
   <td colspan="1">연락처, 개인, 작업, 기회, 잠재 고객, 기타</td> 
  </tr>  
  <tr> 
   <td colspan="1">작업</td> 
   <td colspan="1">작업 유형</td> 
   <td colspan="1">아래와 같은 작업 유형</td> 
  </tr>  
  <tr> 
   <td colspan="1">상태</td> 
   <td colspan="1">배치 상태</td> 
   <td colspan="1">성공, 실패, 미완료, 진행 중, 정리됨*</td> 
  </tr>
  <tr> 
   <td colspan="1">신규</td> 
   <td colspan="1">새 레코드 수</td> 
   <td colspan="1"></td> 
  </tr>  
  <tr> 
   <td colspan="1">업데이트됨</td> 
   <td colspan="1">업데이트된 레코드 수</td> 
   <td colspan="1"></td> 
  </tr>  
  <tr> 
   <td colspan="1">삭제됨</td> 
   <td colspan="1">삭제된 레코드 수</td> 
   <td colspan="1"></td> 
  </tr> 
  <tr> 
   <td colspan="1">실패한 항목</td> 
   <td colspan="1">동기화가 실패한 레코드 수</td> 
   <td colspan="1"><br></td> 
  </tr>  
  <tr> 
   <td colspan="1">건너뜀</td> 
   <td colspan="1">동기화의 관심 필드에 대한 변경 사항이 없어 건너뛴 레코드 수</td> 
   <td colspan="1"></td> 
  </tr>  
 </tbody> 
</table>

&#42;동기화 단계 실패 후 데이터가 이전 무결성 상태로 되돌아갔습니다.

## 오브젝트 유형 {#object-type}

<table> 
 <colgroup> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <td colspan="1">계정</td> 
  </tr>  
  <tr> 
   <td colspan="1">계정 유형</td> 
  </tr> 
  <tr> 
   <td colspan="1">사용자 지정 개체</td> 
  </tr>  
  <tr> 
   <td colspan="1">Campaign</td> 
  </tr>  
  <tr> 
   <td colspan="1">캠페인 멤버 상태</td> 
  </tr>
  <tr> 
   <td colspan="1">연락처</td> 
  </tr>  
  <tr> 
   <td colspan="1">이메일 템플릿</td> 
  </tr>  
  <tr> 
   <td colspan="1">Event</td> 
  </tr> 
  <tr> 
   <td colspan="1">개인(잠재 고객)</td> 
  </tr>  
  <tr> 
   <td colspan="1">기회</td> 
  </tr>  
  <tr> 
   <td colspan="1">영업 기회 연락처 역할</td> 
  </tr>  
  <tr> 
   <td colspan="1">작업</td> 
  </tr>  
  <tr> 
   <td colspan="1">사용자</td> 
  </tr>  
 </tbody> 
</table>

## 작업 유형 {#operation-type}

<table> 
 <colgroup> 
  <col> 
  <col> 
  <col>
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <th>작업 유형</th> 
   <th>이 개체에 대해 발견됨</th> 
   <th>비고</th> 
   <th>작업 유형</th>
  </tr> 
  <tr> 
   <td colspan="1">프로그램에 대한 초기화 링크</td> 
   <td colspan="1">Campaign</td> 
   <td colspan="1">프로그램에 캠페인 연결</td> 
   <td colspan="1">업데이트</td>
  </tr>  
  <tr> 
   <td colspan="1">끌어오기 전환</td> 
   <td colspan="1">개인(잠재 고객)*</td> 
   <td colspan="1">SFDC에서 Marketo으로 전환 작업을 가져옵니다. Unit(number)는 연락처로 전환하는 리드입니다.</td> 
   <td colspan="1">업데이트, 실패한 항목 또는 건너뜀</td>
  </tr> 
  <tr> 
   <td colspan="1">삭제 가져오기</td> 
   <td colspan="1">연락처, 개인(잠재 고객), 영업 기회, 캠페인, 캠페인 멤버, 영업 기회 연락처, 사용자 정의 오브젝트, 캠페인, 캠페인 멤버 상태, 영업 기회 연락처 역할</td> 
   <td colspan="1">Marketo에 동기화 중인 SFDC의 삭제된 레코드</td> 
   <td colspan="1">삭제됨, 실패한 항목 또는 건너뜀</td>
  </tr>  
  <tr> 
   <td colspan="1">가져오기 업데이트</td> 
   <td colspan="1">작업, 개인(가망 고객), 개인(가망 고객) 대기열, 연락처, 이벤트, 기회, 계정, 계정 유형, 캠페인 멤버, 사용자 정의 객체, 캠페인, 캠페인 멤버 상태, 이벤트, 개인 상태, 기회, 기회 연락처 역할</td> 
   <td colspan="1">SFDC의 업데이트 또는 새 레코드가 Marketo에 동기화됨, 이벤트를 활동으로 가져오기</td> 
   <td colspan="1">새로 만들기, 업데이트됨, 실패한 항목 또는 건너뜀</td>
  </tr>  
  <tr> 
   <td colspan="1">새로 푸시</td> 
   <td colspan="1">작업, 이메일 템플릿</td> 
   <td colspan="1">푸시 작업(활동)</td> 
   <td colspan="1"></td>
  </tr>
  <tr> 
   <td colspan="1">푸시 업데이트</td> 
   <td colspan="1">작업, 이메일 템플릿, 개인, 연락처, 캠페인</td> 
   <td colspan="1">SFDC로 업데이트 푸시 및 삭제</td> 
   <td colspan="1">업데이트, 실패한 항목 또는 건너뜀</td>
  </tr>  
  <tr> 
   <td colspan="1">동기화 스키마</td> 
   <td colspan="1">캠페인 멤버, 사용자 정의 객체, 캠페인, 캠페인 멤버 상태, 작업, 개인, 기회, 기회 연락처 역할, 사용자</td> 
   <td colspan="1">다른 개체에 대한 메타데이터를 동기화하여 다음 주기에서 동기화할 새 필드를 결정합니다.</td> 
   <td colspan="1"></td>
  </tr>  
  <tr> 
   <td colspan="1">프로그램과 동기화</td> 
   <td colspan="1">캠페인</td> 
   <td colspan="1">Marketo 프로그램을 SFDC 캠페인과 동기화</td> 
   <td colspan="1">신규, 업데이트, 실패 또는 건너뜀</td>
  </tr> 
  <tr> 
   <td colspan="1">활동 업데이트</td> 
   <td colspan="1">Tasks</td> 
   <td colspan="1">Salesforce에서 활동 가져오기</td> 
   <td colspan="1"></td>
  </tr>  
  <tr> 
   <td colspan="1">FKS 업데이트</td> 
   <td colspan="1">전체</td> 
   <td colspan="1">모든 개체의 외래 키 업데이트</td> 
   <td colspan="1">해당 없음</td>
  </tr>  
 </tbody> 
</table>

&#42;구독 수준의 브랜딩 구성에 따라 보고서의 &quot;잠재 고객&quot; 또는 &quot;개인&quot;이라는 레이블이 결정됩니다.
