---
unique-page-id: 10095307
description: 이메일 주소에 대한 사용자 지정 동기화 필터 규칙 - Marketo 문서 - 제품 설명서
title: 이메일 주소에 대한 사용자 지정 동기화 필터 규칙
exl-id: d1d51310-0c59-447c-818c-b25aa281c15c
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '202'
ht-degree: 0%

---

# 이메일 주소에 대한 사용자 지정 동기화 필터 규칙 {#custom-sync-filter-rules-for-an-email-address}

이메일 주소가 없는 레코드가 동기화되지 않도록 하려면 다음 규칙을 따르십시오.

* 리드가 생성되거나 리드의 이메일 주소 필드가 업데이트될 때 리드에 이메일 주소가 있는지 확인하고 이메일 주소가 있는 경우 Mkto로 동기화를 로 변경합니다. **True**. 그렇지 않으면 **False**

* 연락처가 만들어지거나 연락처의 이메일 주소 필드가 업데이트되면 연락처에 전자 메일 주소가 있는지 확인하고 연락처에 대한 동기화를 Mkto로 변경합니다. **True** mkto에 대한 동기화를 다음으로 변경합니다. **True** 계정 레코드 그렇지 않으면 로 변경합니다. **False**

* 연락처의 회사 이름(parentcustomerid) 필드가 업데이트되면 연락처의 Mkto 동기화 필드가 true인지 확인합니다. 있는 경우 계정의 Mkto에 동기화를 다음으로 변경합니다. **True** 또한
* 기회의 잠재적 고객(customerid) 필드 또는 연락처(parentcontactid)가 업데이트되면 계정의 Mkto 동기화 필드가 true인지 또는 연락처의 Sync to 필드가 참인지 확인합니다. 그런 경우 영업 기회에 대한 Mkto로 동기화를 다음으로 변경합니다. **True** 또한
