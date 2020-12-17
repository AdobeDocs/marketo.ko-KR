---
unique-page-id: 8783322
description: Microsoft Dynamics 동기화 유효성 검사 - Marketing To Docs - 제품 설명서
title: Microsoft Dynamics 동기화 유효성 검사
translation-type: tm+mt
source-git-commit: e149133a5383faaef5e9c9b7775ae36e633ed7b1
workflow-type: tm+mt
source-wordcount: '265'
ht-degree: 0%

---


# Microsoft Dynamics 동기화 유효성 검사 {#validate-microsoft-dynamics-sync}

>[!CAUTION]
>
>Dynamics Sync에 대해 MFA(Multi-Factor Authentication)가 활성화된 경우 Dynamics에서 Marketing To와 제대로 동기화하려면 MFA 인증을 비활성화해야 합니다. 자세한 내용은 [Marketing Support](http://nation.marketo.com/community/support_solutions)에 문의하십시오.

## Marketing에서 {#run-validate-sync-in-marketo}의 유효성 검사 동기화 실행

동기화 유효성 검사 도구를 실행하여 Microsoft Dynamics Sync와 Marketing Cloud 간의 최종 연결을 만들기 전에 올바르게 설정해야 합니다. 이 프로세스는 문제가 있는 위치를 정확히 파악하는 7가지 설정 단계의 검사 목록을 생성합니다. 이러한 작업이 제대로 수행되었는지 확인하는 것은 나중에 많은 시간을 절약할 수 있습니다.

1. **관리** 탭을 클릭한 다음 통합 영역에서 **Microsoft Dynamics** 링크를 클릭합니다.

   ![](assets/image2015-9-28-16-3a7-3a51.png)

1. **Microsoft**&#x200B;를 선택합니다.

   ![](assets/image2015-9-28-16-3a10-3a47.png)

1. **동기화 설정 유효성 검사** 탭을 클릭합니다.

   ![](assets/image2015-9-28-16-3a11-3a45.png)

1. 사용자 이름, 암호 및 URL을 입력합니다(클라이언트 ID와 클라이언트 암호는 선택 사항). 완료되면 **다음**&#x200B;을 클릭합니다.

   ![](assets/four-1.png)

   >[!NOTE]
   >
   >이전에 동기화한 경우 왼쪽 트리의 **CRM**&#x200B;에서 **Microsoft Dynamics**&#x200B;을 읽게 되고 위 양식의 데이터가 미리 채워질 수 있습니다.

1. 모든 것이 정상인 경우 동기화 유효성 검사에서는 녹색 확인 표시 ![—](assets/check.png)가 포함된 검사 목록을 생성합니다.

   ![](assets/image2015-9-22-15-3a58-3a12.png)

1. ![—](assets/delete.png)이 표시되면 해당 단계에 문제가 있는 것입니다. 문제를 식별하고 수정하려면 [Fix Dynamics 유효성 검사 동기화 문제](validate-microsoft-dynamics-sync/fix-dynamics-validation-sync-issues.md)를 참조하십시오. 그런 다음 위의 이미지와 같은 결과가 나타날 때까지 동기화 유효성 검사 단계를 다시 실행합니다.

   >[!CAUTION]
   >
   >현재 Marketing to Dynamics Sync에 대한 샌드박스 새로 고침을 지원하지 않습니다. Dynamics CRM 샌드박스를 새로 고쳐야 하는 경우 새로운 Marketing 샌드박스가 필요합니다. 자세한 내용은 고객 성공 관리자에게 문의하십시오.

>[!MORELIKETHIS]
>
>[Dynamics 유효성 검사 동기화 문제 수정](validate-microsoft-dynamics-sync/fix-dynamics-validation-sync-issues.md)

