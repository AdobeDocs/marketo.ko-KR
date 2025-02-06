---
title: Experience Manager 문서 연결
description: AEM 자산을 활용할 수 있도록 Adobe Experience Manager Cloud Service을 Adobe Marketo Engage에 연결하는 방법을 알아봅니다.
source-git-commit: 92404e10771920862cd147c09e2ada37484e6118
workflow-type: tm+mt
source-wordcount: '224'
ht-degree: 0%

---

# Adobe Experience Manager Cloud Service 연결 {#connect-adobe-experience-manager-cloud-services}

Marketo Engage 이메일 Designer에서 AEM Asset 저장소를 활용할 수 있도록 AEM Assets Cloud Service 계정을 Adobe Marketo Engage 인스턴스에 연결하는 방법을 알아봅니다.

>[!NOTE]
>
>**관리자 권한 필요**

1. Marketo Engage에서 **관리자** 영역으로 이동하여 왼쪽 탐색 트리에서 **Adobe Experience Manager**&#x200B;을(를) 선택하십시오.

   ![관리 섹션에서 Adobe Experience Manager 선택](assets/connect-adobe-experience-manager-cloud-services-1.png){width="800"}

1. _Adobe Experience Manager Cloud Service_ 옆에 있는 **편집**&#x200B;을 클릭합니다.

   ![편집 클릭](assets/connect-adobe-experience-manager-cloud-services-2.png){width="400"}

1. 저장소를 하나 이상 선택합니다.

   ![저장소 선택](assets/connect-adobe-experience-manager-cloud-services-3.png){width="800"}

   >[!NOTE]
   >
   >Marketo Engage 구독과 동일한 IMS 조직에 연결된 저장소만 나열됩니다.

1. 저장소를 구성하려면 [서비스 자격 증명 인증서](https://experienceleague.adobe.com/ko/docs/experience-manager-learn/getting-started-with-aem-headless/authentication/service-credentials)를 추가해야 합니다. **+ 인증서 추가** 단추를 클릭합니다.

   ![인증서 추가](assets/connect-adobe-experience-manager-cloud-services-4.png){width="800"}

1. 인증서를 드래그 앤 드롭하거나(JSON 파일만) 컴퓨터에서 선택합니다. 완료되면 **추가**&#x200B;를 클릭하세요.

   ![컴퓨터에서 인증서를 찾습니다](assets/connect-adobe-experience-manager-cloud-services-5.png){width="600"}

1. 구성된 저장소는 상태 및 만료와 함께 아래에 표시됩니다. 인증서를 보려면 줄임표 단추(**...**)를 클릭하십시오. 그렇지 않으면, 넌 끝이야.

   ![인증서가 추가되었습니다](assets/connect-adobe-experience-manager-cloud-services-5.png){width="600"}

이제 해당 저장소의 디지털 에셋 관리 라이브러리에 있는 모든 이미지는 Marketo Engage 이메일 Designer에서 액세스할 수 있습니다.

>[!MORELIKETHIS]
>
>[Experience Manager 자산 작업](/help/marketo/product-docs/email-marketing/email-designer/aem-assets.md)
