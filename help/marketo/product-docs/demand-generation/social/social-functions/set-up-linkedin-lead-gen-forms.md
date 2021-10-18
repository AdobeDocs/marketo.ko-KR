---
unique-page-id: 12976798
description: LinkedIn Lead Gen Forms 설정 - Marketo 문서 - 제품 설명서
title: LinkedIn Lead Gen Forms 설정
exl-id: 554a546c-adeb-4132-830d-ff15ba5cf9a1
source-git-commit: 41d8762203786bac9aea03ac978daa0549ac8e93
workflow-type: tm+mt
source-wordcount: '433'
ht-degree: 0%

---

# LinkedIn Lead Gen Forms 설정 {#set-up-linkedin-lead-gen-forms}

LinkedIn Lead Gen Forms 를 사용하여 LinkedIn에서 광고 캠페인을 실행하고 Marketo에 대한 리드를 생성할 수 있습니다.

>[!NOTE]
>
>**관리 권한 필요**

1. Marketo으로 이동 **관리**.

   ![](assets/image2016-11-29-10-3a50-3a29.png)

1. 이동 **LaunchPoint**&#x200B;를 클릭하고 **새로 만들기** 을(를) 선택합니다. **새 서비스**.

   ![](assets/image2016-11-29-10-3a51-3a11.png)

1. 을(를) 입력합니다. **표시 이름** 서비스에 대해, **linkedIn 리드 세대** 드롭다운에서 서비스를 선택하고 **다음**.

   ![](assets/linkedin-lead-gen.png)

1. Marketo에서는 같은 브라우저에서 새 탭을 열어 [linkedin.com](https://www.linkedin.com). 통합에 사용할 계정을 사용하여 LinkedIn에 로그인합니다.

   >[!NOTE]
   >
   >LinkedIn 계정에는 스폰서 캠페인을 만들 모든 LinkedIn 비즈니스 계정에 액세스해야 합니다.

   ![](assets/linkedin-login.png)

1. LinkedIn에 로그인하고 Marketo으로 돌아가서 를 클릭합니다 **권한 부여**.

   ![](assets/linkedin-lead-gen-authorize.png)

1. 메시지가 표시되면 을 클릭합니다 **허용** LinkedIn에 Marketo 앱 설치를 수락하려면 다음을 수행하십시오.

   ![](assets/linkedin-marketo-allow.png)

1. 당신은 이제 권한이 있음을 알 것입니다. 클릭 **다음**.

   ![](assets/image2017-9-28-7-3a55-3a14.png)

   >[!CAUTION]
   >
   >이 서비스는 승인 후 1년 후에 자동으로 만료됩니다. 액세스를 다시 가져오려면 **재인증**. 브라우저 설정에 따라 LinkedIn 암호를 다시 입력해야 할 수 있습니다.

1. LinkedIn Lead Gen이 Marketo으로 들어올 계정을 선택하고 를 클릭합니다. **다음**.

   >[!TIP]
   >
   >필요한 비즈니스 계정이 표시되지 않는 경우 인증되는 사용자의 LinkedIn 계정에 LinkedIn의 비즈니스 계정에 대한 Lead Gen Form Manager 권한이 있는지 확인하십시오.

   ![](assets/linkedin-pages-to-capture.png)

1. Marketo에 대한 기본 LinkedIn 필드 매핑을 적용하려면 **만들기**. 기본 필드 매핑을 변경하거나 필드 매핑을 제거하거나 새 필드 매핑을 추가하려면 아래 모달을 통해 필드별로 이 작업을 수행할 수 있습니다.

   >[!CAUTION]
   >
   >Marketo에서는 두 LinkedIn 필드를 단일 Marketo 필드에 매핑하는 것을 지원합니다. **오직** 두 LinkedIn 필드가 동일한 형식이 아닙니다. 동일한 LinkedIn 양식의 두 필드를 단일 Marketo 필드에 매핑하면 사람들이 Marketo 데이터베이스를 입력하지 못할 수 있습니다.

   ![](assets/linkedin-lead-gen-mapping.png)

   >[!NOTE]
   >
   >에 이미 저장된 LinkedIn 필드만 [양식 템플릿](https://www.linkedin.com/help/lms/answer/79634) LinkedIn Campaign Manager는 Marketo 필드에 매핑할 수 있는 LinkedIn 필드로 표시됩니다.

   ![](assets/linkedin-installed-services.png)

잘했어요! LinkedIn Lead Gen Forms를 제출하는 사람은 LinkedIn 측에서 성공적인 캠페인을 실행할 때 Marketo으로 유입됩니다.

>[!NOTE]
>
>단일 LinkedIn 사용자 계정만 인증할 수 있습니다. Marketo에 연결할 비즈니스 계정이 여러 개 있는 경우, 권한이 있는 사용자의 LinkedIn 계정에 LinkedIn의 비즈니스 계정에 대한 Lead Gen Form Manager 권한이 있는지 확인하십시오.

>[!MORELIKETHIS]
>
>[스마트 캠페인에서 LinkedIn 리드 세대 양식 필터 및 트리거 사용](/help/marketo/product-docs/demand-generation/social/social-functions/use-linkedin-lead-gen-form-filters-and-triggers-in-a-smart-campaign.md)
