---
description: 흐름 단계 서비스 - Marketo 문서 - 제품 설명서
title: 흐름 단계 서비스
hide: true
hidefromtoc: true
exl-id: 81367562-8b27-4ec5-8a9b-b02083a2e999
source-git-commit: 99ad4c68b8ab635f6eb6f7f0f53cb67ee3efc51c
workflow-type: tm+mt
source-wordcount: '1325'
ht-degree: 0%

---

# 흐름 단계 서비스 {#flow-step-service}

>[!NOTE]
>
>이 사전 릴리스 기능은 현재 셀프 서비스 흐름 단계 베타 프로그램에 등록된 계정에만 사용할 수 있습니다.

셀프 서비스 흐름 단계는 웹 서비스를 Adobe Marketo Engage Smart Campaign에 작성, 게시 및 통합하는 프레임워크 및 기능 세트입니다. 이 안내서는 이미 작성 및 게시된 서비스를 설치 및 사용하려는 Marketo Engage 최종 사용자를 위한 것입니다. 자체 서비스를 제작 및 게시하는 방법에 대한 자세한 내용은 [서비스 공급자 인터페이스의 GitHub 리포지토리](https://github.com/adobe/Marketo-SSFS-Service-Provider-Interface). 개념 증명 조회 테이블 구현을 찾을 수 있습니다 [여기](https://github.com/adobe/mkto-flow-lookup).

## 사전 릴리스 제한 및 경고 {#pre-release-restrictions-and-warnings}

이 기능은 현재 베타 버전으로, 사용에 일부 제한 사항이 있습니다.

* 이 기능은 Marketo Engage의 샌드박스 인스턴스에서만 사용할 수 있습니다
* 사용자 지정 및 타사 흐름 단계는 2021년 4분기 릴리스부터 실행 가능한 캠페인과 호환되지 않습니다. 2022년 2사분기에 수정될 예정입니다.
* Marketo Sky UI는 이 기능이 활성화된 인스턴스에서 모두 사용해서는 안 됩니다

## 온보딩 및 관리 서비스 {#onboarding-and-managing-services}

사용자 지정 흐름 단계를 설치하려면 Marketo(**Webhooks 관리** 1월 21일 릴리스에서 3월 11일 릴리스의 변경) 설치 URL 외에도, 서비스 공급자 그리드에서 서비스 세부 사항 화면으로 드릴다운하여 초기 온보딩을 완료한 후 서비스 요소의 다른 모든 측면을 편집할 수 있습니다.

## 설치 URL {#installation-url}

설치를 시작하려면 먼저 서비스를 정의하는 OpenAPI 문서의 URL을 가져와야 합니다. 서비스 공급자가 이 정보를 제공할 수 있어야 하며, 일반적으로 다음으로 끝나는 URL이 있습니다. `/openapi.json`. 전체 URL은 다음과 같이 표시됩니다 `https://www.example.com/OpenAPI.json`. 이 URL이 있으면 관리 섹션의 서비스 공급자 메뉴로 이동합니다.

클릭 **다음** 서비스 인증서 입력 섹션으로 이동합니다.

![](assets/flow-step-service-1.png)

## 서비스 자격 증명 입력 {#enter-service-credentials}

설치 중인 서비스에 액세스하려면 Marketo에 유효한 API 자격 증명이 있어야 합니다. 서비스 공급자가 이러한 자격 증명을 제공해야 합니다. 서비스에는 세 가지 서로 다른 인증 옵션이 있으므로 자격 증명에 대한 세 가지 프롬프트 중 하나가 표시될 수 있습니다. **API 키** 입력 필드가 하나만 있는 경우 **기본 인증** 사용자 이름과 암호가 필요하고 Realm이라는 필드가 필요할 수도 있습니다. **OAuth2** 사용 _클라이언트 자격 증명_ 그랜트, _클라이언트 ID_ 및 _클라이언트 암호_.

>[!NOTE]
>
>OAuth2는 3월 11일 릴리스까지 사용할 수 없습니다.

자격 증명을 저장하면 Marketo은 서비스의 상태 엔드포인트를 호출하여 해당 끝점이 유효한지 확인합니다. 제공된 자격 증명이 올바르지 않으면 이를 나타내는 오류가 표시됩니다.

## 온보딩 안내서(선택 사항) {#onboarding-guide}

일부 서비스 제공업체는 선택적 온보딩 안내서 단계를 포함할 것입니다. 이 단계에는 해당 서비스와 관련된 서비스 온보딩을 완료하기 위한 추가 지침이 포함됩니다.

## 필드 매핑 {#field-mapping}

특정 리드 필드에서 데이터를 받거나 반환하려면 해당 필드를 매핑해야 합니다. 매핑은 온보딩 중에 필요한 단계이지만, 항상 나중에 다시 매핑을 변경하도록 돌아갈 수 있습니다. 별도의 화면에서 구성된 두 가지 유형의 매핑이 있습니다. **보내는 필드**: Marketo이 흐름 단계를 호출할 때 서비스에 전송됩니다. **수신 필드** 는 Marketo으로 데이터를 반환할 때 서비스에서 데이터를 받을 수 있는 필드입니다.

>[!NOTE]
>
>나가는 필드를 매핑하면, Marketo에 관련 서비스에서 처리한 리드와 관련된 필드에서 데이터를 전송할 수 있는 권한을 제공합니다. 데이터 개인 정보 보호, 보호 및 임차인 법이 적용되는 개인 식별 정보가 이러한 필드에 포함될 수 있으므로, 이러한 데이터를 서비스 공급자에게 전송할 적절한 법적 권한과 권한이 있는지 확인하십시오.

서비스 중단 없이 선택적 필드 매핑을 사용하지 않도록 설정할 수 있지만 필수 매핑을 완전히 제거하거나 비활성화하지 못할 수 있습니다.

## 서비스 기반 매핑 {#service-driven-mappings}

이벤트 등록 흐름 단계와 같이 입력 및 출력 세트가 고정된 서비스에서는 **서비스 기반 매핑**. 이러한 유형의 매핑에 대해 서비스 공급자는 데이터 유형과 힌트를 모두 API 이름 형태로 제공합니다. 힌트가 기존 리드 필드의 API 이름과 일치하면 해당 필드가 매핑 섹션에서 자동으로 채워집니다. 일치하는 힌트가 없는 필드의 경우, 일치하는 데이터 유형을 사용하는 필드 목록에서 수동으로 매핑을 채워야 합니다. 온보딩 완료를 위해 필요한 매핑을 채워야 합니다.

![](assets/flow-step-service-2.png)

## 사용자 기반 매핑 {#user-driven-mappings}

날짜 서식 서비스와 같이 고정 입력 및 출력 세트가 없는 서비스는 **사용자 기반 매핑**. 즉, 관리자가 들어오는 각 및 나가는 필드를 구성해야 합니다.

![](assets/flow-step-service-3.png)

## 보내는 필드 {#outgoing-fields}

발신 필드는 스마트 캠페인에서 흐름 단계를 사용할 때 흐름 단계 서비스로 전송되는 필드입니다.

## 수신 필드 {#incoming-fields}

들어오는 필드는 흐름 단계 서비스에서에 데이터를 쓸 수 있는 필드입니다.

## 구성 옵션(선택 사항) {#configuration-options}

일부 서비스에는 선택 사항이나 필수 글로벌 구성 옵션이 있습니다. 옵션이 필요한 경우 온보딩을 저장하거나 완료하기 전에 필요한 모든 옵션에 대한 값을 설정해야 합니다. 이름이 이탤릭체 인 매개 변수는 호출된 서비스에 헤더로 전송됩니다.

![](assets/flow-step-service-4.png)

## 서비스 사용 중단 {#retiring-a-service}

활성 사용을 중단하지 않고 새로운 또는 대체 버전의 서비스로 간편하게 전환하기 위해 서비스 공급자 메뉴에서 서비스를 중단할 수 있습니다. **서비스 사용 중단** 스마트 캠페인 흐름 팔레트에서 해당 흐름 단계를 제거하므로 새 사용을 만들 수 없습니다. 대부분의 경우, 서비스 사용 중지를 선택할 때 기존 서비스를 교체할 수 있는 교체 서비스가 있어야 합니다.

## 서비스 사용 중단 {#service-deprecation}

경우에 따라 서비스 공급업체는 소프트웨어 수명 주기의 일반적인 일부로서 흐름 단계 서비스를 사용하지 않아야 합니다. 서비스 공급자가 이 내용을 발표하면 서비스 공급자 그리드 보기에서 사용 중단 날짜 및 메시지가 채워집니다. 더 이상 사용되지 않는 서비스를 계속 사용하면 예상한 방식으로 더 이상 응답하지 않거나 Marketo Smart Campaign의 요청 수락을 중지하는 경우 서비스 중단이 발생할 수 있으므로, 수신한 서비스 사용 중단 알림에 유의하고 아직 사용 중인 서비스의 모든 단계를 중단하거나 교체하기 위한 적절한 단계를 수행해야 합니다.

## 타사 및 사용자 지정 흐름 단계 사용 {#using-third-party-and-custom-flow-steps}

설치된 흐름 단계는 표준 흐름 단계와 거의 동일한 방식으로 사용할 수 있습니다. 서비스에 정의된 모든 흐름 매개 변수가 최종 사용자에게 표시됩니다.

## 선택 목록 새로 고침 {#refreshing-picklists}

Marketo은 매일 밤 서비스의 선택 항목 목록을 새로 고칩니다. 그러나 캠페인 만들기와 같은 새로운 선택 사항이 필요한 경우가 있습니다. 새로 고침 단추를 사용하거나 관리 > 서비스 공급자 메뉴로 이동한 후 선택 목록 새로 고침 을 클릭하여 흐름 단계의 모든 인스턴스에서 쉽게 새로 고칠 수 있습니다.

## 수신 필드 확인 {#checking-incoming-fields}

해당 도구 설명 아이콘 위로 마우스를 가져간 후 주어진 흐름 단계에 대해 구성된 수신 필드를 확인할 수 있습니다. 이 방법은 리드가 이동하는 경우 변경될 수 있는 필드를 결정하는 데 유용하며, 따라서 이러한 필드를 사용하여 후속 단계에서 선택 사항을 구성할 수 있습니다.

![](assets/flow-step-service-5.png)

## 수신 필드 및 데이터 값 변경 {#incoming-fields-and-data-value-changes}

대부분의 다른 흐름 단계와 달리 SSFS 프레임워크를 사용하여 구현된 단계는 관리자가 매핑한 리드 필드에 데이터를 다시 쓰고 이러한 변경 사항을 데이터 값 변경 활동으로 기록할 수 있습니다.  흐름 단계에서 이러한 방식으로 데이터를 기록하면 Smart Campaign이 후속 단계로 이동하기 전에 이러한 모든 변경 사항이 완료되므로 기록된 모든 데이터가 후속 흐름 단계 선택 사항에 의존할 수 있습니다.

## 서비스 로그 및 통계 {#service-logs-and-statistics}

각 흐름 단계 서비스에는 상태를 모니터링하고 통합과 관련된 문제를 해결하는 데 도움이 되도록 몇 가지 유형의 로깅이 연결되어 있습니다.

## 서비스 통계 {#service-statistics}

서비스 통계 로그는 각 서비스에 대한 호출 및 콜백의 결과를 집계합니다. 시간, 수준(청크 또는 레코드) 및 코드별로 그룹화되고 수신된 각 코드에 대해 카운트와 최신 로그 메시지를 제공합니다. 이 대시보드는 주로 서비스 상태 모니터링에 도움이 되도록 설계되었습니다.