---
unique-page-id: 10095307
description: 이메일 주소에 대한 사용자 지정 동기화 필터 규칙 - 마케팅 문서 - 제품 설명서
title: 이메일 주소에 대한 사용자 지정 동기화 필터 규칙
translation-type: tm+mt
source-git-commit: 47b2fee7d146c3dc558d4bbb10070683f4cdfd3d
workflow-type: tm+mt
source-wordcount: '202'
ht-degree: 0%

---


# 이메일 주소 {#custom-sync-filter-rules-for-an-email-address}에 대한 사용자 지정 동기화 필터 규칙

이메일 주소가 없는 레코드 동기화를 방지하려면 다음 규칙을 따르십시오.

* 리드가 생성되거나 리드의 이메일 주소 필드가 업데이트될 때 리드에 이메일 주소가 있는지 확인하고 있다면 Mkto로 동기화를 **True**&#x200B;로 변경합니다. 그렇지 않은 경우 **False**&#x200B;로 변경합니다.

* 연락처를 만들 때 또는 연락처의 이메일 주소 필드가 업데이트될 때 연락처에 이메일 주소가 있는지 확인하고 있다면 Mkk로 동기화를 **True**&#x200B;로 변경하고 Mkto를 계정 레코드의 **True**&#x200B;로 변경합니다. 그렇지 않은 경우 **False**&#x200B;로 변경합니다.

* 연락처의 회사 이름(parentcustomerid) 필드가 업데이트되면 연락처의 Mkto 동기화 필드가 true인지 확인합니다. 그렇다면 계정의 Mkto에 동기화를 **True**&#x200B;로 변경하십시오.
* 기회의 [잠재적 고객](사용자 지정 고객) 필드 또는 [연락처](괄호로 묶음)가 업데이트되면 계정의 [mkto에 동기화] 필드가 true인지 또는 연락처의 [mkto에 동기화] 필드가 true인지 확인합니다. 이 경우 기회의 경우 Mkto로 동기화를 **True**&#x200B;로 변경합니다.

