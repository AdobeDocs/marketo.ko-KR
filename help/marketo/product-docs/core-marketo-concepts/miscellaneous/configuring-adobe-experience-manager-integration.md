---
unique-page-id: 30081815
description: Adobe Experience Manager 통합 구성 - Marketo 문서 - 제품 설명서
title: Adobe Experience Manager 통합 구성
hide: true
hidefromtoc: true
exl-id: 06b2c214-1afb-443f-ae01-0c00fed77dce
source-git-commit: 3105fb33fb457d4dfb63081b80d4d1def717ad34
workflow-type: tm+mt
source-wordcount: '235'
ht-degree: 0%

---

# Adobe Experience Manager 통합 구성 {#configuring-adobe-experience-manager-integration}

AEM 자산을 액세스, 선택 및 Marketo의 Design Studio로 가져올 수 있도록 AEM을 구성합니다.

>[!NOTE]
>
>**관리 권한 필요**

>[!IMPORTANT]
>
>* 이 통합은 AEM의 온-프레미스 구현에서만 작동하며 AEM Cloud Service 구현에는 지원되지 않습니다.
>
>* 현재 이 기능은 Firefox에서만 완전히 지원됩니다. Safari에서 지원되지 않으며, SameSite 쿠키 설정에 따라 최신 버전의 Chrome에서 작동하지 않을 수 있습니다.


1. Adobe Experience Manager으로 이동합니다(URL은 회사에만 해당됨).

   ![](assets/one.png)

1. Adobe으로 로그인하거나 로컬로 로그인할 수 있습니다. 이 예제에서는 로컬로 로그인합니다.

   ![](assets/two.png)

1. in **도구**&#x200B;를 클릭합니다. **작업** 을(를) 선택합니다. **웹 콘솔**.

   ![](assets/2a.png)

1. 브라우저에서 &quot;Granite Cross-Origin Resource Sharing Policy Adobe&quot;을(Windows의 경우 ctrl+f, Mac의 cmd+f)로 검색합니다.

   ![](assets/three.png)

1. 을(를) 클릭합니다. **+** 오른쪽에 서명하세요.

   ![](assets/four.png)

1. 에서 **허용된 원본(Regexp)** 텍스트 상자, 입력 `https://.*\.marketo\.com` 을(를) 클릭합니다. **저장**.

   ![](assets/five-psd.png)

1. 페이지 상단의 헤더에서 **웹 콘솔** 을(를) 선택합니다. **시스템 정보**.

   ![](assets/six.png)

1. 서버 정보에서 **다시 시작** 버튼을 클릭합니다.

   ![](assets/seven.png)

1. 클릭 **확인** 확인합니다.

   ![](assets/eight.png)

1. Marketo Classic에서 **관리**.

   ![](assets/nine.png)

1. 통합에서 을 선택합니다 **Adobe Experience Manager**.

   ![](assets/ten.png)

1. 클릭 **편집**.

   ![](assets/eleven.png)

1. AEM URL을 입력하고 을(를) 클릭합니다 **확인**.

   ![](assets/twelve.png)

   다 끝났어! 이제 다음을 수행할 수 있습니다 [Marketo Sky에서 Design Studio로 AEM 자산 가져오기](https://experienceleague.adobe.com/docs/marketo/sky/design-studio/importing-assets-with-adobe-experience-manager.html?lang=en#design-studio).
