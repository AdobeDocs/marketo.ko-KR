---
unique-page-id: 12976798
description: linkedIn 리드 세대 Forms 설정 - Marketo 문서 - 제품 설명서
title: linkedIn Lead Gen Forms 설정
exl-id: 554a546c-adeb-4132-830d-ff15ba5cf9a1
feature: Social
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '433'
ht-degree: 0%

---

# linkedIn Lead Gen Forms 설정 {#set-up-linkedin-lead-gen-forms}

linkedIn 리드 세대 Forms을 사용하여 LinkedIn에서 광고 캠페인을 실행하고 Marketo에 대한 리드를 생성합니다.

>[!NOTE]
>
>**관리자 권한 필요**

1. Marketo으로 이동 **관리자**.

   ![](assets/image2016-11-29-10-3a50-3a29.png)

1. 다음으로 이동 **시작 지점**, 클릭 **신규** 및 선택 **새 서비스**.

   ![](assets/image2016-11-29-10-3a51-3a11.png)

1. 입력 **표시 이름** 서비스에 대해 **LinkedIn 리드 젠** 드롭다운에서 서비스를 참조하고 **다음**.

   ![](assets/linkedin-lead-gen.png)

1. Marketo은 동일한 브라우저에서 다음 위치에 새 탭을 엽니다. [linkedin.com](https://www.linkedin.com). 통합에 사용할 계정을 사용하여 LinkedIn에 로그인합니다.

   >[!NOTE]
   >
   >linkedIn 계정은 스폰서 캠페인을 만드는 데 사용할 모든 LinkedIn 비즈니스 계정에 액세스해야 합니다.

   ![](assets/linkedin-login.png)

1. linkedIn에 로그인한 후 Marketo으로 돌아가서 를 클릭합니다. **승인**.

   ![](assets/linkedin-lead-gen-authorize.png)

1. 메시지가 표시되면 **허용** Marketo 앱을 LinkedIn에 설치하는 것을 수락합니다.

   ![](assets/linkedin-marketo-allow.png)

1. 이제 권한이 부여되었음을 알 수 있습니다. 클릭 **다음**.

   ![](assets/image2017-9-28-7-3a55-3a14.png)

   >[!CAUTION]
   >
   >이 서비스는 승인 후 1년 후에 자동으로 만료됩니다. 다시 액세스하려면 다음을 클릭하십시오. **재인증**. 브라우저 설정에 따라 LinkedIn 암호를 다시 입력해야 할 수 있습니다.

1. linkedIn Lead Gen 리드를에서 Marketo으로 가져올 계정을 선택하고 을 클릭합니다. **다음**.

   >[!TIP]
   >
   >예상한 비즈니스 계정이 표시되지 않으면 권한이 부여된 사용자의 LinkedIn 계정에 LinkedIn의 비즈니스 계정에 대한 Lead Gen Form Manager 권한이 있는지 확인하십시오.

   ![](assets/linkedin-pages-to-capture.png)

1. 기본 LinkedIn에서 Marketo으로 필드 매핑을 허용하려면 **만들기**. 기본 필드 매핑을 변경하거나, 필드 매핑을 제거하거나, 새 필드 매핑을 추가하려면 아래 모달을 통해 필드별로 수행할 수 있습니다.

   >[!CAUTION]
   >
   >Marketo은 두 LinkedIn 필드를 단일 Marketo 필드에 매핑하는 것을 지원합니다. **그러나 다음과 같은 경우에만** 두 LinkedIn 필드의 양식이 동일하지 않습니다. 동일한 LinkedIn 양식의 두 필드를 단일 Marketo 필드에 매핑하면 사람들이 Marketo 데이터베이스를 입력하지 못할 수 있습니다.

   ![](assets/linkedin-lead-gen-mapping.png)

   >[!NOTE]
   >
   >이미 다음에 저장된 LinkedIn 필드만 해당 [양식 템플릿](https://www.linkedin.com/help/lms/answer/79634) linkedIn Campaign Manager에서 Marketo 필드에 매핑할 수 있는 LinkedIn 필드로 표시됩니다.

   ![](assets/linkedin-installed-services.png)

잘했어! linkedIn Lead Gen Forms를 제출하는 사람은 LinkedIn 측에서 성공적인 캠페인을 실행할 때 Marketo으로 유입되기 시작합니다.

>[!NOTE]
>
>단일 LinkedIn 사용자 계정만 승인할 수 있습니다. Marketo에 연결할 비즈니스 계정이 여러 개 있는 경우 권한이 부여된 사용자의 LinkedIn 계정에 LinkedIn의 비즈니스 계정에 대한 Lead Gen Form Manager 권한이 있는지 확인하십시오.

>[!MORELIKETHIS]
>
>[Smart Campaign에서 LinkedIn 리드 세대 양식 필터 및 트리거 사용](/help/marketo/product-docs/demand-generation/social/social-functions/use-linkedin-lead-gen-form-filters-and-triggers-in-a-smart-campaign.md)
