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

* 잠재 고객이 생성되거나 잠재 고객의 이메일 주소 필드가 업데이트될 때 잠재 고객에게 이메일 주소가 있는지 확인하고 이메일 주소가 있는 경우 Mkto에 동기화 를 로 변경합니다. **[!UICONTROL True]**. 그렇지 않으면 다음으로 변경 **[!UICONTROL False]**.

* 연락처가 만들어지거나 연락처의 전자 메일 주소 필드가 업데이트되면 연락처에 전자 메일 주소가 있는지 확인하고 업데이트되면 Mkto에 동기화 를 다음으로 변경합니다. **[!UICONTROL True]** mkto에 동기화 변경 **[!UICONTROL True]** 계정 레코드에서. 그렇지 않으면 다음으로 변경 **[!UICONTROL False]**.

* 연락처의 회사 이름(parentcustomerid) 필드가 업데이트되면 연락처의 Mkto 동기화 필드가 true인지 확인합니다. 있는 경우 계정에서 Mkto로 동기화를 다음으로 변경 **[!UICONTROL True]** 또한.

* 영업 기회의 잠재 고객(customerid) 필드 또는 연락처(parentcontactid)가 업데이트되면 계정의 Mkto에 동기화 필드가 true인지 또는 연락처의 Mkto에 동기화 필드가 true인지 확인합니다. 있는 경우 다음에 대한 기회에서 Sync to Mkto를 변경합니다. **[!UICONTROL True]** 또한.
