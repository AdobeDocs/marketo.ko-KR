---
unique-page-id: 4719302
description: 영어가 아닌 사용자 지정 개체 동기화 활성화 - Marketo 문서 - 제품 설명서
title: 비영어 사용자 지정 개체 동기화 활성화
exl-id: 5d1c5b52-5323-4f68-847b-7d24e6acd6c4
feature: Salesforce Integration
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '157'
ht-degree: 0%

---

# 비영어 사용자 지정 개체 동기화 활성화 {#enable-non-english-custom-object-sync}

Marketo 동기화 사용자가 영어 이외의 언어로 설정된 경우 사용자 지정 개체 동기화를 활성화하려고 하면 오류가 발생할 수 있습니다.

## 오류 {#the-error}

![](assets/image2014-12-10-13-3a17-3a51.png)

## 둘러보기 {#getting-around-it}

1. Marketo 동기화 사용자를 사용하여 Salesforce에 로그인합니다.

   ![](assets/image2014-12-10-13-3a18-3a1.png)

1. 사용자 이름 아래에서 **설정**.

   ![](assets/image2014-12-10-13-3a18-3a11.png)

1. 아래 **개인 정보**, 클릭 **내 개인 정보**.

   ![](assets/image2014-12-10-13-3a18-3a22.png)

1. 클릭 **편집**.

   ![](assets/image2014-12-10-13-3a18-3a32.png)

1. 변경 **언어** 끝 **영어**.

   ![](assets/image2014-12-10-13-3a18-3a45.png)

1. 클릭 **저장**.

   ![](assets/image2014-12-10-13-3a18-3a55.png)

1. Marketo으로 돌아가서 **관리자 > Salesforce > 개체** 클릭 **스키마 새로 고침**.

   ![](assets/image2014-12-10-13-3a19-3a6.png)

1. 그러면 개체 목록이 영어로 당겨집니다. 이제 선택한 개체를 선택하고 **동기화 활성화**.

   ![](assets/image2014-12-10-13-3a19-3a16.png)

1. 이제 사용자 지정 개체가 활성화되고 동기화됩니다.

   ![](assets/image2014-12-10-13-3a19-3a26.png)

1. 이제 Salesforce로 돌아가서 위의 단계를 사용하여 동기화 사용자를 기본 언어로 다시 변경합니다.

>[!NOTE]
>
>마지막으로 스키마를 새로 고쳐 언어에서 개체를 다시 가져오는 것을 잊지 마십시오.
