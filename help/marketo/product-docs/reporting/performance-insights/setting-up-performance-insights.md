---
unique-page-id: 12981145
description: 성능 인사이트 설정 - Marketo 문서 - 제품 설명서
title: 성능 인사이트 설정
exl-id: f87bbaba-c2c1-4b83-9e07-f8a5d1f1738b
feature: Reporting
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '307'
ht-degree: 0%

---

# 성능 인사이트 설정 {#setting-up-performance-insights}

MPI를 설정하려면 아래 단계를 따르십시오.

## 영업 기회 설정 {#opportunity-setup}

1. 클릭 **관리자**.

   ![](assets/admin.png)

1. 클릭 **수익 주기 분석**.

   ![](assets/two-2.png)

   >[!NOTE]
   >
   >RCA가 없는 경우 다음을 선택해야 합니다 **프로그램 분석** 2단계.

1. 기여도 분석에서 **편집**.

   ![](assets/three-1.png)

1. 속성 설정 이 표시됩니다.

   ![](assets/four-2.png)

   속성이 명시적인 경우 Opportunity Contact Role 이 입력되었는지(Opportunity Role 엔드포인트 또는 CRM 통합을 통해) 확인합니다.

   Attribution이 암시적인 경우 리드/연락처의 회사 필드가 영업 기회의 계정 이름과 같은지 확인합니다.

   >[!NOTE]
   >
   >모든 기회에 적절한 필드가 채워져 있는지 확인합니다.
   >
   >* 영업 기회 금액
   >* 닫힘
   >* 성공
   >* 만든 날짜(사용자의 경우 설정되지 않을 수 있음)
   >* 마감일(사용자의 경우 설정되지 않을 수 있음)
   >* 영업 기회 유형

## 프로그램 설정 {#program-setup}

최소 12개월 동안 프로그램 비용을 업데이트합니다. 수동으로 또는 프로그램 API를 사용하여 이 작업을 수행할 수 있습니다. 이 예제에서는 수동으로 수행합니다.

1. 클릭 **마케팅 활동**.

   ![](assets/ma.png)

1. 프로그램을 찾아 선택합니다.

   ![](assets/select-program.png)

1. 다음을 클릭합니다. **설정** 탭.

   ![](assets/setup-tab.png)

1. 드래그 **기간 비용** 을 캔버스에 추가합니다.

   ![](assets/period-cost.png)

1. 최소 12개월 전에 프로그램 월 을 설정하고 **확인**.

   ![](assets/set-period.png)

1. 기간 비용을 설정하고 다음을 클릭합니다. **저장**.

   ![](assets/set-cost.png)

다음으로, 분석 비헤이비어를 검토하여 특정 채널이 분석에 포함되어야 하는지 여부를 나타냅니다. Analytics 동작(일반, 포함, 작동)을 설정합니다.

1. 클릭 **관리자**.

   ![](assets/admin.png)

1. 클릭 **태그**.

   ![](assets/tags.png)

1. 다음을 클릭합니다. **+** 을 클릭하여 채널 목록을 확장합니다.

   ![](assets/channel.png)

1. 원하는 채널을 두 번 클릭합니다.

   ![](assets/channel-click.png)

1. 다음을 클릭합니다. **Analytics 동작** 드롭다운을 클릭하고 원하는 비헤이비어를 선택합니다.

   ![](assets/edit-channel.png)

1. 성공 기준을 설정합니다.

   ![](assets/success.png)

1. 클릭 **저장**.

   ![](assets/save.png)

## 개인에게 프로그램 연결 {#tie-the-program-to-the-person}

1. 첫 번째 터치 속성이 작동하려면 데이터베이스의 각 사용자에 대해 획득 프로그램 및 획득 날짜가 설정되어 있는지 확인하십시오.
1. 프로그램에서 사용자의 성공 상태를 설정하는지 확인합니다.

>[!NOTE]
>
>변경 사항이 즉시 적용되지 않습니다. 변경 사항이 적용되기 전에 야간 기간이 필요합니다.
