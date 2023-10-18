---
unique-page-id: 1147108
description: 프로그램 가져오기 - Marketo 문서 - 제품 설명서
title: 프로그램 가져오기
exl-id: 15e23e38-a24b-45b3-89a9-ffec85649f4a
feature: Programs
source-git-commit: e49860ae611f2f77789bb491aeccbee46a911a2c
workflow-type: tm+mt
source-wordcount: '520'
ht-degree: 0%

---

# 프로그램 가져오기 {#import-a-program}

한 Marketo 구독에서 다른 구독으로 프로그램을 가져올 수 있습니다. 예를 들어 샌드박스에서 프로그램을 만든 다음 라이브 구독으로 가져올 수 있습니다. 또한 [Marketo 프로그램 라이브러리](/help/marketo/product-docs/core-marketo-concepts/programs/program-library/program-import-library-overview.md){target="_blank"}.

## 프로그램 가져오기 {#importing-a-program}

1. 다음으로 이동 **[!UICONTROL 마케팅 활동]**.

   ![](assets/import-a-program-1.png)

1. 다음을 클릭합니다. **[!UICONTROL 신규]** 드롭다운 및 선택 **[!UICONTROL 프로그램 가져오기]**.

   ![](assets/import-a-program-2.png)

   >[!NOTE]
   >
   >프로그램 가져오기는 프로그램 가져오기 권한이 활성화된 역할이 있는 사용자만 사용할 수 있습니다. 자세히 알아보기 [사용자 역할 및 권한 관리](/help/marketo/product-docs/administration/users-and-roles/managing-user-roles-and-permissions.md){target="_blank"}.
   >
   >샌드박스 계정을 라이브 구독에 연결하려면 다음으로 문의하십시오. [Marketo 지원](https://nation.marketo.com/t5/Support/ct-p/Support){target="_blank"}.

1. Marketo 선택 **[!UICONTROL 구독]** 가져올 프로그램. **[!UICONTROL 다음]**&#x200B;을 클릭합니다.

   ![](assets/import-a-program-3.png)

1. 지정 **[!UICONTROL 캠페인 폴더]** 가져온 프로그램의 경우. **[!UICONTROL 다음]**&#x200B;을 클릭합니다.

   ![](assets/import-a-program-4.png)

   >[!NOTE]
   >
   >다음을 확인하십시오. **[!UICONTROL 기본 충돌 사용]** 규칙이 선택됩니다. 동일한 이름의 자산을 가진 인스턴스로 프로그램을 가져올 때 충돌 규칙이 필요합니다.

1. 원하는 충돌 세부 정보를 선택하고 **[!UICONTROL 다음]**.

   ![](assets/import-a-program-5.png)

   >[!NOTE]
   >
   >사용자 지정 흐름 단계를 사용하는 프로그램 또는 흐름 단계 서비스에서 파생된 스마트 목록 규칙을 호환되는 서비스 공급자가 두 개 이상 있는 대상 인스턴스로 가져오면 가져오는 사용자에게 대상 인스턴스의 올바른 서비스 공급자에 단계 또는 규칙을 할당하라는 메시지가 표시됩니다.

1. 세부 정보 미리보기 및 **[!UICONTROL 가져오기]** 프로그램입니다.

   ![](assets/import-a-program-6.png)

가져오기가 완료되면 확인 이메일을 받게 됩니다.

>[!NOTE]
>
>가져온 배치 캠페인의 일정을 조정하고 트리거 캠페인을 활성화해야 합니다. 가져온 프로그램에서 캠페인 일정을 자동으로 비활성화하고 캠페인을 트리거합니다.

## 프로그램 가져오기 중 외부 자산에 미치는 영향 {#impact-on-external-assets-during-program-imports}

프로그램은 이메일 템플릿, 랜딩 페이지 템플릿, 이미지, 양식, 토큰 및 프로그램 태그와 같은 외부 자산을 사용합니다. 랜딩 페이지 템플릿과 프로그램 태그를 처리하는 방법을 구성할 수 있으며, Marketo에서 나머지 부분을 자동으로 관리합니다.

**이메일/랜딩 페이지 템플릿:** 이메일/랜딩 페이지 템플릿을 Design Studio로 가져옵니다. 충돌 규칙을 사용하여 이름이 같은 템플릿이 있는 경우 동작을 구성할 수 있습니다. 기본 규칙을 사용하면 동일한 이름의 템플릿이 있는 경우 템플릿에 숫자가 추가됩니다. 예를 들어 &quot;표준 템플릿&quot;이라는 이름의 템플릿이 이미 있는 경우 새 템플릿의 이름은 &quot;표준 템플릿 - 1&quot;로 지정됩니다.

**랜딩 페이지/Forms:** Design Studio에 이름이 같은 양식 또는 랜딩 페이지가 있는 경우 계속 가져오지만 이름에 숫자가 추가됩니다(예: 랜딩 페이지 - 1).

**이미지:** 같은 이름의 이미지가 없는 경우 랜딩 페이지에서 사용하는 이미지를 디자인 스튜디오로 가져옵니다.

**토큰:** 프로그램 외부에 있는 토큰은 가져오기 프로세스 중에 로컬 토큰으로 변환됩니다.

>[!CAUTION]
>
>이미지 유형 내 토큰은 프로그램 가져오기에 지원되지 않습니다. 내 토큰의 이미지 유형이 있는 프로그램을 가져오는 경우 _아니요_ 토큰이 통과됩니다.

**프로그램 태그:** 충돌 규칙을 사용하여 대상 계정에 존재하지 않는 프로그램 태그가 처리되는 방법을 제어할 수 있습니다. 기본 규칙을 사용하면 프로그램 태그가 만들어지거나 태그를 무시하도록 선택할 수 있습니다.

>[!CAUTION]
>
>프로그램을 가져올 때 포함된 이메일/랜딩 페이지 [다이내믹 콘텐츠](/help/marketo/product-docs/personalization/segmentation-and-snippets/segmentation/understanding-dynamic-content.md){target="_blank"} 건너뜁니다.
