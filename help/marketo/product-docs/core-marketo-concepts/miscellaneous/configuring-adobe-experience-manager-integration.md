---
unique-page-id: 30081815
description: Adobe Experience Manager 통합 구성 - Marketing Docs - 제품 설명서
title: Adobe Experience Manager 통합 구성
translation-type: tm+mt
source-git-commit: 47b2fee7d146c3dc558d4bbb10070683f4cdfd3d
workflow-type: tm+mt
source-wordcount: '219'
ht-degree: 0%

---


# Adobe Experience Manager 통합 구성 {#configuring-adobe-experience-manager-integration}

AEM 에셋을 액세스, 선택 및 Marketing의 Design Studio로 가져올 수 있도록 AEM을 구성합니다.

>[!NOTE]
>
>**관리자 권한 필요**

>[!CAUTION]
>
>현재 이 기능은 Firefox에서만 완전히 지원됩니다. Safari에서는 지원되지 않으며 SameSite 쿠키 설정에 따라 최신 버전의 Chrome(v. 80)에서 작동하지 않을 수 있습니다.

1. Adobe Experience Manager으로 이동합니다(URL은 회사에만 해당).

   ![](assets/one.png)

1. Adobe으로 로그인하거나 로컬로 로그인할 수 있습니다. 이 예에서는 로컬로 로그인합니다.

   ![](assets/two.png)

1. **도구**&#x200B;에서 **작업**&#x200B;을 클릭하고 **웹 콘솔**&#x200B;을 선택합니다.

   ![](assets/2a.png)

1. 브라우저에서 &quot;Adobe Granite Cross-Origin Resource Sharing Policy&quot;를 검색합니다(Windows의 경우 ctrl+f, Mac의 cmd+f).

   ![](assets/three.png)

1. 오른쪽에 있는 **+** 기호를 클릭합니다.

   ![](assets/four.png)

1. **허용된 원본(등록)** 텍스트 상자에 &quot;https://&quot;을 입력합니다.*\.markto\.com&quot;(따옴표 없이)을 클릭하고 **저장**&#x200B;을 클릭합니다.

   ![](assets/five-psd.png)

1. 페이지 상단의 헤더에서 **웹 콘솔**&#x200B;을 클릭하고 **시스템 정보**&#x200B;를 선택합니다.

   ![](assets/six.png)

1. [서버 정보]에서 **다시 시작** 단추를 클릭합니다.

   ![](assets/seven.png)

1. **확인**&#x200B;을 클릭하여 확인합니다.

   ![](assets/eight.png)

1. Marketing Classic에서 **관리**&#x200B;를 클릭합니다.

   ![](assets/nine.png)

1. 통합에서 **Adobe Experience Manager**&#x200B;을 선택합니다.

   ![](assets/ten.png)

1. **편집**&#x200B;을 클릭합니다.

   ![](assets/eleven.png)

1. AEM URL을 입력하고 **확인**&#x200B;을 클릭합니다.

   ![](assets/twelve.png)

   다 준비됐어요! 이제 Marketo Sky[의 Design Studio에 AEM 에셋을 가져올 수 있습니다.](http://help.marketo.com/hc/en-us/articles/360036765993)

