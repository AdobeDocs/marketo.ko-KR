---
unique-page-id: 10095307
description: 이메일 주소에 대한 사용자 지정 동기화 필터 규칙 - Marketing To Docs - 제품 설명서
title: 이메일 주소에 대한 사용자 지정 동기화 필터 규칙
translation-type: tm+mt
source-git-commit: 47b2fee7d146c3dc558d4bbb10070683f4cdfd3d
workflow-type: tm+mt
source-wordcount: '202'
ht-degree: 0%

---


# 이메일 주소에 대한 사용자 지정 동기화 필터 규칙 {#custom-sync-filter-rules-for-an-email-address}

이메일 주소가 없는 레코드 동기화를 방지하려면 다음 규칙을 따르십시오.

* 리드가 생성될 때 OR의 이메일 주소 필드가 업데이트될 때 리드에 이메일 주소가 있는지 확인하고 있다면 동기화에서 **True로 변경합니다**. 그렇지 않은 경우 **False로 변경**

* 연락처를 만든 경우 또는 연락처의 이메일 주소 필드가 업데이트되면 연락처에 이메일 주소가 있는지 확인하고 연락처가 **Mkto로** 동기화하고 계정 레코드의 Mkto **로** 동기화를 True로 변경합니다. 그렇지 않은 경우 **False로 변경**

* 연락처의 회사 이름(parentcustomerid) 필드가 업데이트되면 연락처의 Mkto 동기화 필드가 사실인지 확인하십시오. 그렇다면 계정의 Mkto로 동기화를 **True로** 변경합니다
* 기회의 잠재적 고객(사용자 지정) 필드 또는 연락처(상위 연락처)가 업데이트되면 계정의 동기화 필드가 참인지 또는 연락처의 동기화 대상 필드가 참인지 확인하십시오. 그렇다면 Mkto로 동기화를 True로 **변경합니다**

