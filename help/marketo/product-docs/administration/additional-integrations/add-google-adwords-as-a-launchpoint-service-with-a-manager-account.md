---
unique-page-id: 7504893
description: 관리자 계정을 사용하여 Google AdWords as a Launch Service 추가 - Marketo 문서 - 제품 설명서
title: 관리자 계정을 사용하여 Google AdWords를 Launchpoint 서비스로 추가
exl-id: aac106f4-6615-49d5-a561-0dd965c7b0ff
source-git-commit: ab8eb044b89c925accc3b6a4ac4def53e3927321
workflow-type: tm+mt
source-wordcount: '353'
ht-degree: 0%

---

# 관리자 계정을 사용하여 Google AdWords를 Launchpoint 서비스로 추가 {#add-google-adwords-as-a-launchpoint-service-with-a-manager-account}

Google AdWords 계정을 Marketo에 연결하여 Marketo에서 Google AdWords로 오프라인 전환 데이터를 자동으로 업로드합니다. 그런 다음 AdWords UI에서 자격 조건을 갖춘 리드, 기회 및 신규 고객(또는 추적하려는 모든 수익 단계)이 발생한 클릭을 손쉽게 확인할 수 있습니다  [사용자 지정 열 추가](https://support.google.com/adwords/answer/3073556) 참조하십시오. 이 정보는 Marketo UI에 표시되지 않습니다.

Google Adwords 계정이 여러 개 있는 경우 [Google AdWords Manager 계정](https://www.google.com/adwords/manager-accounts/) (이전의 My Client Center) 를 사용하여 Marketo과 통합했습니다.

추가 정보 [Google의 오프라인 전환 가져오기 기능](https://support.google.com/adwords/answer/2998031?hl=en).

>[!AVAILABILITY]
>
>모든 고객이 이 기능을 구입한 것은 아닙니다. 자세한 내용은 고객 성공 관리자에게 문의하십시오.

>[!NOTE]
>
>**관리 권한 필요**

>[!NOTE]
>
>을 통합할 수도 있습니다 [Launchpoint 서비스로서의 독립형 Google AdWords 계정](/help/marketo/product-docs/administration/additional-integrations/add-google-adwords-as-a-launchpoint-service.md).

1. 로 이동합니다. **관리** 섹션을 참조하십시오.

   ![](assets/login-admin-1.png)

1. 선택 **LaunchPoint**.

   ![](assets/image2014-12-5-14-3a35-3a27.png)

1. 선택 **새로 만들기** 및 **새 서비스**.

   ![](assets/image2015-2-23-14-3a54-3a50.png)

1. 표시 이름을 입력하고 을 선택합니다 **Google AdWords**.

   ![](assets/new-service-google-1.png)

1. 선택 **Marketo 권한 부여**.

   >[!NOTE]
   >
   >개인 Gmail 계정에서 로그아웃하고 팝업을 활성화해야 합니다.

   ![](assets/image2015-2-26-20-3a54-3a1.png)

1. 연결된 계정을 선택합니다 **Google AdWords**.

   ![](assets/image2015-2-23-15-3a31-3a16.png)

1. 선택 **수락**.

   ![](assets/image2015-2-23-16-3a32-3a45.png)

1. 상태가 **성공**. 선택 **다음**.

   ![](assets/image2015-2-26-20-3a55-3a21.png)

1. Marketo에서 Google AdWords로 오프라인 전환 업로드 **주별** 또는 **일별**.

   ![](assets/image2015-3-27-14-3a7-3a45.png)

1. 으로의 속성 전환 **첫 번째 클릭** 또는 **마지막 클릭**.

   | 유형 | 정의 |
   |---|---|
   | 첫 번째 클릭 | 오프라인 전환은 지난 90일 동안 사용자가 클릭한 첫 번째 AdWords에 귀속됩니다 |
   | 마지막 클릭 | 오프라인 전환은 사용자가 클릭한 마지막 AdWords에 귀속됩니다 |

   ![](assets/image2015-3-27-14-3a10-3a46.png)

   >[!NOTE]
   >
   >[자동 태깅](https://support.google.com/adwords/answer/1752125?hl=en) 이 기능을 사용하려면 선택해야 합니다. AdWords 내에서 활성화되어야 합니다.

1. 클릭 **다음**.

   ![](assets/image2015-3-27-14-3a11-3a31.png)

1. 업데이트하지 않으려는 계정의 선택을 취소합니다. 클릭 **만들기**.

   ![](assets/image2015-3-27-14-3a12-3a51.png)

   이제 매출 모델에서 AdWords 오프라인 전환을 매핑하는 방법에 대해서는 아래 관련 문서를 참조하십시오.

   >[!MORELIKETHIS]
   >
   >[관리자 계정을 사용하여 매출 모델에서 Google AdWords 전환 을 설정합니다](/help/marketo/product-docs/reporting/revenue-cycle-analytics/revenue-cycle-models/set-google-adwords-conversions-in-the-revenue-model-with-a-manager-account.md)
