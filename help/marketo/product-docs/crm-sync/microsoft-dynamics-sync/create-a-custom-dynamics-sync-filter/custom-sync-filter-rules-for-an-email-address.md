---
unique-page-id: 10095307
description: 이메일 주소에 대한 사용자 정의 동기화 필터 규칙 - Marketo 문서 - 제품 설명서
title: 이메일 주소에 대한 사용자 정의 동기화 필터 규칙
exl-id: d1d51310-0c59-447c-818c-b25aa281c15c
feature: Microsoft Dynamics
source-git-commit: 2403ae0f1fdca3b8238f3f59e2a3b94129deb301
workflow-type: tm+mt
source-wordcount: '202'
ht-degree: 0%

---

# 이메일 주소에 대한 사용자 정의 동기화 필터 규칙 {#custom-sync-filter-rules-for-an-email-address}

전자 메일 주소가 없는 레코드가 동기화되지 않도록 하려면 다음 규칙을 따르십시오.

* 잠재 고객이 만들어지거나 잠재 고객의 전자 메일 주소 필드가 업데이트되면 잠재 고객에게 전자 메일 주소가 있는지 확인하고 업데이트되면 Mkto에 동기화 를 **[!UICONTROL True]**(으)로 변경합니다. 그렇지 않으면 **[!UICONTROL False]**(으)로 변경하십시오.

* 연락처가 만들어지거나 연락처의 전자 메일 주소 필드가 업데이트되면 연락처에 전자 메일 주소가 있는지 확인하고 있는 경우 Mkto에 대한 동기화를 **[!UICONTROL True]**(으)로 변경하고 계정 레코드에서 Mkto에 대한 동기화를 **[!UICONTROL True]**(으)로 변경하십시오. 그렇지 않으면 **[!UICONTROL False]**(으)로 변경하십시오.

* 연락처의 회사 이름(parentcustomerid) 필드가 업데이트되면 연락처의 Mkto 동기화 필드가 true인지 확인합니다. 이 경우 계정의 Mkto에 대한 동기화 도 **[!UICONTROL True]**(으)로 변경하십시오.

* 영업 기회의 잠재 고객(customerid) 필드 또는 연락처(parentcontactid)가 업데이트되면 계정의 Mkto에 동기화 필드가 true인지 또는 연락처의 Mkto에 동기화 필드가 true인지 확인합니다. 이 경우 Sync를 Mkto로 변경하여 **[!UICONTROL True]**(으)로도 전환할 수 있습니다.
