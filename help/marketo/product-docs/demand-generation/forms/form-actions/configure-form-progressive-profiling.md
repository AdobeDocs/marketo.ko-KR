---
unique-page-id: 2359646
description: 양식 점진적 프로파일링 구성 - Marketo 문서 - 제품 설명서
title: 양식 점진적 프로파일링 구성
exl-id: 72afe3dc-0688-45ec-ab70-4dc9accf4fc8
feature: Forms
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '307'
ht-degree: 3%

---

# 양식 점진적 프로파일링 구성 {#configure-form-progressive-profiling}

짧은 양식도 좋아요 다른 사용자가 양식으로 돌아가면 새 필드를 제공하고 방문자의 프로필을 점진적으로 채울 수 있습니다. 방법은 다음과 같습니다.

>[!NOTE]
>
>이 기능이 제대로 작동하려면 표시되는 필드에 대해 양식 미리 채우기가 활성화되어 있는지, 숨겨진 필드에 대해 [비활성화됨](/help/marketo/product-docs/demand-generation/forms/form-fields/disable-pre-fill-for-a-form-field.md)이 설정되어 있는지 확인하십시오.

1. **[!UICONTROL Marketing Activities]**(으)로 이동합니다.

   ![](assets/ma-1.png)

1. 양식을 선택하고 **[!UICONTROL Edit Form]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2014-9-15-12-3a31-3a20.png)

1. **[!UICONTROL Form Settings]**&#x200B;에서 **[!UICONTROL Settings]**&#x200B;을(를) 클릭합니다.

   ![](assets/image2014-9-15-12-3a31-3a29.png)

1. **[!UICONTROL Progressive Profiling]**&#x200B;을(를) **[!UICONTROL Enabled]**(으)로 설정합니다.

   ![](assets/image2014-9-15-12-3a31-3a47.png)

1. 이제 구성해 보겠습니다. **[!UICONTROL Field Details]**(으)로 이동합니다.

   ![](assets/image2014-9-15-12-3a31-3a55.png)

1. 점진적 프로필 집합에 속하는 모든 필드를 끌어서 놓습니다.

   ![](assets/image2014-9-15-12-3a32-3a3.png)

1. 모든 필드를 이동하면 다음과 같이 표시됩니다.

   ![](assets/image2014-9-15-12-3a32-3a12.png)

   >[!NOTE]
   >
   >**[!UICONTROL Progressive Profiling]** 상자 외부의 필드는 채워져 있더라도 항상 폼에 표시됩니다.

1. **[!UICONTROL Progressive Profiling]** 상자를 선택합니다.

   ![](assets/image2014-9-15-12-3a32-3a19.png)

   >[!CAUTION]
   >
   >[!UICONTROL Progressive Profiling]에서 필수 필드를 사용할 때는 주의하십시오. 다른 필드에 대한 데이터를 이전에 제출한 후, 최신 양식에서는 표시되지 않기 때문에 방문자가 새 이메일 주소(새 사용자를 만들 수 있음)를 입력하면 이러한 필드는 계속 비어 있을 수 있습니다.

1. 이제 제공된 시간에 **점진적 프로파일링** 상자에서 사람들이 볼 빈 필드 수를 선택하십시오.

   ![](assets/image2014-9-15-12-3a32-3a26.png)

   >[!NOTE]
   >
   >**[!UICONTROL Number of Blank Fields]**&#x200B;을(를) 1로 선택하면 방문자가 이 양식을 처음 볼 때 다음이 표시됩니다.
   >
   >* 이름(비어 있음)
   >* 성(비어 있음)
   >* 이메일 주소(비어 있음)
   >* 전화 번호(비어 있음)
   >
   >모든 필드를 작성한다고 가정할 때 두 번째로 방문하면 다음이 표시됩니다.
   >
   >* 이름(사전 입력되어 있음)
   >* 성(사전 입력되어 있음)
   >* 이메일 주소(미리 입력됨)
   >* 휴대폰 번호(비어 있음)
   >
   >휴대폰 번호를 작성한다고 가정하면 세 번째 방문할 때 다음이 표시됩니다.
   >
   >* 이름(사전 입력되어 있음)
   >* 성(사전 입력되어 있음)
   >* 이메일 주소(미리 입력됨)
   >* 국가(비어 있음)

1. **[!UICONTROL Finish]**&#x200B;를 클릭합니다.

   ![](assets/image2014-9-15-12-3a33-3a35.png)

1. **[!UICONTROL Approve and Close]**&#x200B;를 클릭합니다.

   ![](assets/image2014-9-15-12-3a33-3a45.png)

잘했어! 네가 방금 한 일이 빛을 발할 것이다.

이 기능을 테스트하고 테스트하십시오. 고급이지만 이렇게 하면 양식을 매우 동적으로 만들 수 있습니다.
