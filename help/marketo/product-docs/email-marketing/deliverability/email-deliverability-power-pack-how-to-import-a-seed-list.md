---
unique-page-id: 10099077
description: 이메일 전달성 파워 팩 - 시드 목록을 가져오는 방법 - Marketo 문서 - 제품 설명서
title: 이메일 게재 기능 파워 팩 - 시드 목록을 가져오는 방법
exl-id: a4782611-2556-43bf-802b-afeb332eafcd
feature: Deliverability
source-git-commit: 3cb7e5ddef8ec05a7cf8d65dd9f3bafa5dcb7da1
workflow-type: tm+mt
source-wordcount: '332'
ht-degree: 0%

---

# 이메일 전달성 파워 팩: 시드 목록을 가져오는 방법 {#email-deliverability-power-pack-how-to-import-a-seed-list}

시드 목록은 Google 앱, Hotmail, Yahoo! 등을 비롯한 여러 사서함 공급자의 이메일 계정 목록으로, 스팸 폴더 전달률과 받은 편지함의 비율을 비교하는 데 사용됩니다. 다음은 Marketo 인스턴스로 해당 목록을 가져오는 방법입니다.

>[!IMPORTANT]
>
>이 기사는 현재 에베레스트 구독이 활발한 사람들을 위한 것이다. Bird(이전 MessageBird)별 받은 편지함 추적기를 사용하는 경우 자습서 [은(는) 여기에서 찾을 수 있음](/help/marketo/product-docs/email-marketing/deliverability/inbox-tracker/inbox-tracker-tutorials.md){target="_blank"}.

## 시드 목록 가져오기 {#import-a-seed-list}

1. 내 Marketo에서 **전달성 도구**.

   ![](assets/email-deliverability-power-pack-1.png)

1. 에베레스트 지원서가 공개될 것이다. 왼쪽 탐색 메뉴에서 **비행 중** 및 선택 **받은 편지함 배치**.

   ![](assets/email-deliverability-power-pack-2.png)

1. 다음을 클릭합니다. **시드 목록 관리** 탭.

   ![](assets/email-deliverability-power-pack-3.png)

1. 작업 드롭다운을 클릭하고 을 선택합니다. **한 줄에 한 개 다운로드**.

   ![](assets/email-deliverability-power-pack-4.png)

   >[!NOTE]
   >
   >Everest에서 목록을 최적화하도록 하려면 페이지 상단에 있는 시드 목록 최적화 도구 를 사용하십시오.

1. 내보내기가 끝나면 브라우저의 다운로드 폴더에 목록이 .txt 파일로 나타납니다. 검색 및 [가져오기](/help/marketo/getting-started/quick-wins/import-a-list-of-people.md) 정적 목록으로 Marketo 인스턴스에 통합합니다.

   ![](assets/email-deliverability-power-pack-5.png)

   >[!TIP]
   >
   >목록을 쉽게 찾을 수 있도록 이름을 지정하십시오.

   >[!CAUTION]
   >
   >이러한 받은 편지함 배치 캠페인은 한 달에 제한적으로 제공됩니다. 받는 사람 수를 보려면 에베레스트에서 계정 설정 > 구독 아래의 구독 섹션을 참조하십시오. 자세한 내용은 Marketo 영업 담당자에게 문의하십시오.

## 새 시드 목록 가져오기 {#acquiring-new-seedlists}

시드 목록은 한 달에 한 번씩 변경될 수 있습니다. 이메일 게재 기능 파워 팩에 정기적으로 로그인하여 시드 목록의 상태를 확인하는 것이 중요합니다. 새 주소가 추가되거나 업데이트가 필요한 경우 애플리케이션 왼쪽 하단에 있는 알림 아이콘을 통해 알림을 받게 됩니다.

Marketo의 정적 목록이 생성되면 해당 목록으로 보내어 이메일의 받은 편지함 배치를 테스트할 수 있습니다.
