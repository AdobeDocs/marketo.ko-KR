---
unique-page-id: 1147108
description: 프로그램 가져오기 - Marketo 문서 - 제품 설명서
title: 프로그램 가져오기
exl-id: 15e23e38-a24b-45b3-89a9-ffec85649f4a
feature: Programs
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '536'
ht-degree: 2%

---

# 프로그램 가져오기 {#import-a-program}

한 Marketo Engage 구독에서 다른 구독으로 프로그램을 가져올 수 있습니다. 예를 들어 샌드박스에서 프로그램을 만든 다음 라이브 구독으로 가져올 수 있습니다. 또한 [Marketo 프로그램 라이브러리](/help/marketo/product-docs/core-marketo-concepts/programs/program-library/program-import-library-overview.md){target="_blank"}에서 미리 빌드된 프로그램을 가져올 수 있습니다.

>[!CAUTION]
>
>&quot;사용자 지정 개체가 업데이트됨&quot; 트리거가 포함된 스마트 목록이 있는 프로그램은 가져오기에 실패합니다. 아래 설명된 단계를 수행하기 전에 모든 스마트 목록에서 이 트리거를 제거하십시오.

## 프로그램 가져오기 {#importing-a-program}

1. **[!UICONTROL Marketing Activities]**(으)로 이동합니다.

   ![](assets/import-a-program-1.png)

1. **[!UICONTROL New]** 드롭다운을 클릭하고 **[!UICONTROL Import Program]**&#x200B;를 선택합니다.

   ![](assets/import-a-program-2.png)

   >[!NOTE]
   >
   >* 프로그램 가져오기는 프로그램 가져오기 권한이 활성화된 역할이 있는 사용자만 사용할 수 있습니다. [사용자 역할 및 권한 관리](/help/marketo/product-docs/administration/users-and-roles/managing-user-roles-and-permissions.md){target="_blank"}에 대해 자세히 알아보세요.
   >
   >* 샌드박스 계정을 실시간 구독에 연결하려면 [Marketo 지원](https://nation.marketo.com/t5/Support/ct-p/Support){target="_blank"}에 문의하세요.

1. 가져올 Marketo **[!UICONTROL Subscription]** 및 프로그램을 선택하십시오. **[!UICONTROL Next]**&#x200B;를 클릭합니다.

   ![](assets/import-a-program-3.png)

1. 가져온 프로그램에 대해 **[!UICONTROL Campaign Folder]**&#x200B;을(를) 지정하십시오. **[!UICONTROL Next]**&#x200B;를 클릭합니다.

   ![](assets/import-a-program-4.png)

   >[!NOTE]
   >
   >**[!UICONTROL Use default conflict]** 규칙이 선택되어 있는지 확인하십시오. 동일한 이름의 자산을 가진 인스턴스로 프로그램을 가져올 때 충돌 규칙이 필요합니다.

1. 원하는 충돌 세부 정보를 선택하고 **[!UICONTROL Next]**&#x200B;을(를) 클릭합니다.

   ![](assets/import-a-program-5.png)

   >[!NOTE]
   >
   >사용자 지정 흐름 단계를 사용하는 프로그램 또는 흐름 단계 서비스에서 파생된 스마트 목록 규칙을 호환되는 서비스 공급자가 두 개 이상 있는 대상 인스턴스로 가져오면 가져오는 사용자에게 대상 인스턴스의 올바른 서비스 공급자에 단계 또는 규칙을 할당하라는 메시지가 표시됩니다.

1. 세부 정보를 미리 보고 프로그램을 **[!UICONTROL Import]**&#x200B;합니다.

   ![](assets/import-a-program-6.png)

가져오기가 완료되면 확인 이메일을 받게 됩니다.

>[!NOTE]
>
>가져온 배치 캠페인의 일정을 조정하고 트리거 캠페인을 활성화해야 합니다. 가져온 프로그램에서 캠페인 일정을 자동으로 비활성화하고 캠페인을 트리거합니다.

## 프로그램 가져오기 중 외부 Assets에 미치는 영향 {#impact-on-external-assets-during-program-imports}

프로그램은 이메일 템플릿, 랜딩 페이지 템플릿, 이미지, 양식, 토큰 및 프로그램 태그와 같은 외부 자산을 사용합니다. 랜딩 페이지 템플릿과 프로그램 태그를 처리하는 방법을 구성할 수 있으며, Marketo에서 나머지 부분을 자동으로 관리합니다.

**전자 메일/랜딩 페이지 템플릿:** 전자 메일/랜딩 페이지 템플릿을 Design Studio로 가져옵니다. 충돌 규칙을 사용하여 이름이 같은 템플릿이 있는 경우 동작을 구성할 수 있습니다. 기본 규칙을 사용하면 동일한 이름의 템플릿이 있는 경우 템플릿에 숫자가 추가됩니다. 예를 들어 &quot;표준 템플릿&quot;이라는 이름의 템플릿이 이미 있는 경우 새 템플릿의 이름은 &quot;표준 템플릿 - 1&quot;로 지정됩니다.

**랜딩 페이지/Forms:** Design Studio에 이름이 같은 폼이나 랜딩 페이지가 있으면 가져오지만 이름에 숫자가 추가됩니다(예: 랜딩 페이지 - 1).

같은 이름의 이미지가 없는 경우 랜딩 페이지에서 사용하는 **이미지:** 이미지를 디자인 스튜디오로 가져옵니다.

프로그램 외부에 있는 **토큰:** 토큰은 가져오는 동안 로컬 토큰으로 변환됩니다.

>[!CAUTION]
>
>이미지 유형 내 토큰은 프로그램 가져오기에 지원되지 않습니다. 내 토큰의 이미지 형식이 있는 프로그램을 가져오는 경우 _no_ 토큰이 전달됩니다.

**프로그램 태그:** 충돌 규칙을 사용하여 대상 계정에 없는 프로그램 태그가 처리되는 방식을 제어할 수 있습니다. 기본 규칙을 사용하면 프로그램 태그가 만들어지거나 태그를 무시하도록 선택할 수 있습니다.

>[!CAUTION]
>
>프로그램을 가져올 때 [동적 콘텐츠](/help/marketo/product-docs/personalization/segmentation-and-snippets/segmentation/understanding-dynamic-content.md){target="_blank"}가 포함된 이메일/랜딩 페이지를 건너뜁니다.
