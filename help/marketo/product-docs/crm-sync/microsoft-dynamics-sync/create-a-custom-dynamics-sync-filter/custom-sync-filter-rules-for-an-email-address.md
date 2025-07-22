---
unique-page-id: 10095307
description: 이메일 주소에 대한 사용자 정의 동기화 필터 규칙 - Marketo 문서 - 제품 설명서
title: 이메일 주소에 대한 사용자 정의 동기화 필터 규칙
exl-id: d1d51310-0c59-447c-818c-b25aa281c15c
feature: Microsoft Dynamics
source-git-commit: 0d37fbdb7d08901458c1744dc68893e155176327
workflow-type: tm+mt
source-wordcount: '195'
ht-degree: 0%

---

# 이메일 주소에 대한 사용자 정의 동기화 필터 규칙 {#custom-sync-filter-rules-for-an-email-address}

전자 메일 주소가 없는 레코드가 동기화되지 않도록 하려면 다음 규칙을 따르십시오.

* 잠재 고객이 생성되거나 잠재 고객의 이메일 주소 필드가 업데이트될 때 잠재 고객에게 이메일 주소가 있는지 확인하고 이메일 주소가 있는 경우 Mkto에 동기화 를 **[!UICONTROL True]**(으)로 변경하십시오. 그렇지 않으면 **[!UICONTROL False]**(으)로 변경합니다.

* 연락처를 만들거나 연락처 전자 메일 주소 필드를 업데이트할 때 연락처에 전자 메일 주소가 있는지 확인하고 전자 메일 주소가 있는 경우 Mkto에 동기화를 **[!UICONTROL True]**(으)로 변경하고 계정 레코드에서 Mkto에 동기화를 **[!UICONTROL True]**(으)로 변경하십시오. 그렇지 않으면 **[!UICONTROL False]**(으)로 변경합니다.

* 연락처의 회사 이름(parentcustomerid) 필드가 업데이트되면 연락처의 Mkto 동기화 필드가 true인지 확인합니다. 이 경우 계정의 Mkto에 대한 동기화 도 **[!UICONTROL True]**(으)로 변경하십시오.
* 영업 기회의 잠재 고객(customerid) 필드 또는 연락처(parentcontactid)가 업데이트되면 계정의 Mkto에 동기화 필드가 true인지 또는 연락처의 Mkto에 동기화 필드가 true인지 확인합니다. 이 경우 **[!UICONTROL True]**(으)로도 Sync를 Mkto로 변경합니다.
