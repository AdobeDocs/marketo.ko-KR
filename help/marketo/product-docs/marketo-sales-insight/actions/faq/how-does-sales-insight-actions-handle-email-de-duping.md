---
description: Sales Insight Action에서 이메일 중복 제거를 처리하는 방법 - Marketo 문서 - 제품 설명서
title: Sales Insight Action은 이메일 중복 제거를 어떻게 처리합니까?
exl-id: 40b01f7f-df50-4bd2-ac35-4c4e4f80915e
source-git-commit: d9b8b92ac5f051178b8eb9b450c4949b56d50b99
workflow-type: tm+mt
source-wordcount: '107'
ht-degree: 0%

---

# Sales Insight Action은 이메일 중복 제거를 어떻게 처리합니까? {#how-does-sales-insight-actions-handle-email-de-duping}

당신이 [csv 업로드](/help/marketo/product-docs/marketo-sales-insight/actions/people/managing-contacts/import-contacts-via-csv.md) 파일을 Sales Insight Actions에 삽입하면 가져오기가 수행되기 전에 CSV에서 같은 모든 연락처를 병합합니다.

이메일 주소 등을 기반으로 합니다. 따라서 동일한 두 개의 이메일 주소가 있는 경우 이를 하나의 연락처로 병합합니다.

나중에 동일한 연락처를 수동으로 추가/업로드하려고 하면 병합되지 않습니다.

데이터베이스에 이미 있는 연락처를 추가하려고 하면 추가하지 못하도록 합니다.
