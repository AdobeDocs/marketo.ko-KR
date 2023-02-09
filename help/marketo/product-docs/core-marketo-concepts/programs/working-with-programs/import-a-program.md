---
unique-page-id: 1147108
description: 프로그램 가져오기 - Marketo 문서 - 제품 설명서
title: 프로그램 가져오기
exl-id: 15e23e38-a24b-45b3-89a9-ffec85649f4a
source-git-commit: adff42d54d7953c9ec72e4d736ce0153502be960
workflow-type: tm+mt
source-wordcount: '519'
ht-degree: 0%

---

# 프로그램 가져오기 {#import-a-program}

하나의 Marketo 구독에서 다른 프로그램으로 프로그램을 가져올 수 있습니다. 예를 들어 샌드박스에서 프로그램을 만든 다음 라이브 구독으로 가져올 수 있습니다. 또한 Marketo 프로그램 라이브러리에서 사전 빌드된 프로그램을 가져올 수도 있습니다.

## 프로그램 가져오기 {#importing-a-program}

1. 이동 **마케팅 활동.**

   ![](assets/import-a-program-1.png)

1. 클릭 **새로 만들기** 드롭다운 선택 **프로그램 가져오기**.

   ![](assets/import-a-program-2.png)

   >[!NOTE]
   >
   >프로그램 가져오기는 프로그램 가져오기 권한이 활성화된 역할이 있는 사용자만 사용할 수 있습니다. 추가 정보 [사용자 역할 및 권한 관리](/help/marketo/product-docs/administration/users-and-roles/managing-user-roles-and-permissions.md).
   >
   >샌드박스 계정을 라이브 구독에 연결하려면 [Marketo 지원](https://nation.marketo.com/t5/Support/ct-p/Support).

1. Marketo 선택 **구독** 가져올 프로그램과 클릭 **다음**.

   ![](assets/import-a-program-3.png)

1. 을(를) 지정합니다 **캠페인 폴더** 가져온 프로그램에 대해 설명합니다. 클릭 **다음.**

   ![](assets/import-a-program-4.png)

   >[!NOTE]
   >
   >확인 **기본 충돌 사용** 규칙이 선택되어 있습니다. 동일한 이름의 자산이 있는 인스턴스로 프로그램을 가져올 때는 충돌 규칙이 필요합니다.

1. 원하는 충돌 세부 정보를 선택하고 **다음**.

   ![](assets/import-a-program-5.png)

   >[!NOTE]
   >
   >Flow Step Service에서 파생된 사용자 정의 흐름 단계 또는 Smart List 규칙을 사용하는 프로그램을 둘 이상의 호환 서비스 공급자가 있는 대상 인스턴스로 가져오면 가져오는 사용자에게 대상 인스턴스의 올바른 서비스 공급자에 단계나 규칙을 할당하라는 메시지가 표시됩니다.

1. 세부 사항 및 미리 보기 **가져오기** 프로그램

   ![](assets/import-a-program-6.png)

가져오기가 완료되면 이메일 확인을 받게 됩니다.

>[!NOTE]
>
>가져온 배치 캠페인을 다시 예약하고 트리거 캠페인을 활성화해야 합니다. 시스템은 가져온 프로그램에서 캠페인 일정을 자동으로 비활성화하고 캠페인을 트리거합니다.

## 프로그램 가져오기 중 외부 자산에 미치는 영향 {#impact-on-external-assets-during-program-imports}

프로그램은 이메일 템플릿, 랜딩 페이지 템플릿, 이미지, 양식, 토큰 및 프로그램 태그와 같은 외부 자산을 사용합니다. 랜딩 페이지 템플릿과 프로그램 태그를 처리하는 방법을 구성하고 Marketo에서 나머지 태그를 자동으로 관리합니다.

**이메일/랜딩 페이지 템플릿:** 이메일/랜딩 페이지 템플릿을 Design Studio로 가져옵니다. 이름이 같은 템플릿이 있을 때 충돌 규칙을 사용하여 동작을 구성할 수 있습니다. 기본 규칙을 사용하면 동일한 이름의 템플릿이 있는 경우 템플릿에 숫자가 추가됩니다. 예를 들어 &quot;표준 템플릿&quot;이라는 이름의 템플릿이 이미 있으면 새 템플릿의 이름은 &quot;표준 템플릿 - 1&quot;으로 지정됩니다.

**랜딩 페이지/Forms:** 이름이 같은 양식 또는 랜딩 페이지가 Design Studio에 있으면 가져오지만 이름에 숫자가 추가됩니다(예: 랜딩 페이지 - 1).

**이미지:** 랜딩 페이지에서 사용하는 이미지는 동일한 이름의 이미지가 없는 한 디자인 스튜디오로 가져옵니다.

**토큰:** 프로그램 외부에 있는 토큰은 가져오기 프로세스 중에 로컬 토큰으로 변환됩니다.

>[!CAUTION]
>
>이미지 유형 내 토큰은 프로그램 가져오기에 대해 지원되지 않습니다. 이미지 유형이 있는 프로그램을 가져올 경우 **아니요** 토큰이 전달됩니다.

**프로그램 태그:** 충돌 규칙을 사용하여 대상 계정에 존재하지 않는 프로그램 태그가 처리되는 방식을 제어할 수 있습니다. 기본 규칙을 사용하면 프로그램 태그가 만들어지거나 태그를 무시하도록 선택할 수 있습니다.

>[!CAUTION]
>
>프로그램을 가져올 때 다음이 포함된 이메일/랜딩 페이지 [다이내믹 콘텐츠](/help/marketo/product-docs/personalization/segmentation-and-snippets/segmentation/understanding-dynamic-content.md) 를 건너뜁니다.
