---
unique-page-id: 14352514
description: Sales Connect에서 이메일 중복 제거 처리 방법 - Marketing To Docs - 제품 설명서
title: Sales Connect에서 이메일 중복 제거 처리 방법
translation-type: tm+mt
source-git-commit: 47b2fee7d146c3dc558d4bbb10070683f4cdfd3d
workflow-type: tm+mt
source-wordcount: '104'
ht-degree: 0%

---


# Sales Connect에서 {#how-sales-connect-handles-email-de-duping} 이메일 중복 제거 처리 방법

[CSV](http://docs.marketo.com/x/VADb) 파일을 Sales Connect에 업로드하는 경우 가져오기가 발생하기 전에 CSV의 모든 유사 연락처를 병합합니다.

이메일 주소 같은 것을 기반으로 합니다. 따라서 동일한 이메일 주소가 2개 있으면 하나의 연락처로 병합합니다.

나중에 동일한 연락처를 수동으로 추가/업로드하려고 하면 병합하지 않습니다.

데이터베이스에 이미 있는 연락처를 추가하려고 하면 추가하지 못하게 됩니다.

