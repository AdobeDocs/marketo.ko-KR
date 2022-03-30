---
unique-page-id: 10099077
description: 전자 메일 게재 기능 팩 - 설명서 목록을 가져오는 방법 - Marketo 문서 - 제품 설명서
title: 전자 메일 게재 기능 전원 팩 - 세부 목록을 가져오는 방법
exl-id: a4782611-2556-43bf-802b-afeb332eafcd
source-git-commit: 6ad418c8f4056b9a2fb31b0ac995692f0c618795
workflow-type: tm+mt
source-wordcount: '291'
ht-degree: 0%

---

# 전자 메일 게재 기능 팩: 시드 목록을 가져오는 방법 {#email-deliverability-power-pack-how-to-import-a-seedlist}

시드 목록은 Google 앱, Hotmail, Yahoo! 등을 포함하여 여러 사서함 공급자의 이메일 계정 목록이며 받은 편지함 비율과 스팸 폴더 게재 가능성을 대략적으로 계산하는 데 사용됩니다. 다음은 해당 목록을 Marketo 인스턴스로 가져오는 방법입니다.

>[!AVAILABILITY]
>
>모든 고객이 이 기능을 구입한 것은 아닙니다. 자세한 내용은 영업 담당자에게 문의하십시오.

## 묘목 목록 가져오기 {#import-a-seedlist}

1. 이동 **게재 기능 도구**.

   ![](assets/one-1.png)

1. 클릭 **받은 편지함 정보**.

   ![](assets/two-1.png)

1. 클릭 **시드 목록 가져오기**.

   ![](assets/three-1.png)

1. 클릭 **목록 내보내기**.

   ![](assets/four.png)

   >[!NOTE]
   >
   >선택 **목록 최적화** 250OK로 [목록 최적화](https://help.returnpath.com/hc/en-us/articles/360046746451-What-is-250ok-s-seedlist-optimizer-and-why-should-I-use-it-) 활성화해줄 수 있습니다. 선택 **목록 사용자 지정** 포함할 묘목 목록 영역을 선택하려면

1. 내보낸 후에 목록이 브라우저의 다운로드 폴더에 .txt 파일로 표시됩니다. 검색, [가져오기](/help/marketo/getting-started/quick-wins/import-a-list-of-people.md) 정적 목록으로 Marketo 인스턴스에 추가할 수 있습니다.

   ![](assets/five.png)

   >[!TIP]
   >
   >쉽게 찾을 수 있도록 목록에 이름을 지정하도록 하십시오.

   >[!CAUTION]
   >
   >매월 이러한 받은 편지함 정보 제공업체 캠페인의 양이 제한됩니다. 몇 명인지 보려면 250OK를 보세요 **계정 설정**. 자세한 내용은 Marketo 영업 담당자에게 문의하십시오.

## 새 시드 목록 가져오기 {#acquiring-new-seedlists}

묘목도 매월 자주 변경될 수 있습니다. 전자 메일 게재 기능 팩에 정기적으로 로그인하여 시드 목록의 상태를 확인하는 것이 중요합니다. 새 주소를 추가하거나 끝에 업데이트가 필요한 경우 Get Seedlist 페이지의 인터페이스를 통해 알림을 받게 됩니다.

Marketo에서 정적 목록을 만든 후 보내기를 시작하여 이메일의 받은 편지함 배치를 테스트할 수 있습니다.
