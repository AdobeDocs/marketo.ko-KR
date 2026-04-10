---
solution: Marketo Engage
product: marketo
title: 고급 HTML 편집기를 사용하여 이메일 템플릿 편집
description: 보호, 액세스 단계 및 주요 제한 사항을 포함하여 Marketo Engage Email Designer에서 원시 HTML 소스 코드를 보고 편집하는 방법에 대해 알아봅니다.
level: Intermediate
feature: Email Designer
exl-id: b030e56a-de70-4b0d-9788-04a01235cffb
source-git-commit: 2b638c3945d6b28379655596d2c5c878d842e60e
workflow-type: tm+mt
source-wordcount: '367'
ht-degree: 0%

---

# 고급 HTML 편집기를 사용하여 이메일 템플릿 편집 {#advanced-html-mode}

고급 HTML 모드를 사용하면 [!DNL Marketo Engage] 이메일 Designer 인터페이스에서 직접 이메일 템플릿의 원시 소스 코드를 보고 편집할 수 있습니다.

이 기능을 사용하면 고급 표현식을 소스에 바로 삽입할 수 있습니다. 시각적(데스크톱) 보기로 다시 전환하면 컨텐츠가 다시 렌더링되므로 어떻게 표시되는지 확인하고 두 보기 중 하나에서 편집을 계속할 수 있습니다.

## 가드레일 {#guardrails}

고급 HTML 편집기를 사용하는 경우 다음 가드레일은 콘텐츠 호환성을 보호하고 기대를 설정합니다.

* 고급 HTML 편집기 **이(가) 코드를 확인**&#x200B;하지 않습니다. 구문 오류나 끊어진 레이아웃은 확인하지 않습니다. 저장하기 전에 콘텐츠를 주의 깊게 검토하십시오.

* 향후 시스템 업데이트로 기본 마크업에 대한 변경 사항을 덮어쓸 수 있습니다. **변경 내용이 유지되지 않을 수 있습니다**.

* [!DNL Adobe] 지원 **사용자 지정 코드 및 수동 변경으로 인한** 문제를 해결하거나 해결할 수 없습니다. 되돌리기가 필요할 경우를 대비하여 콘텐츠를 백업하십시오.

* 고급 HTML 보기에서는 콘텐츠를 시뮬레이션할 수 없습니다. 콘텐츠를 미리 보려면 데스크톱 보기로 전환하십시오.

* 콘텐츠 호환성을 위해 고급 HTML 보기에서 **저장할 수 없습니다**. 변경 내용을 저장할 준비가 되면 다시 데스크톱 보기로 전환합니다.

## 고급 HTML 모드 액세스 {#access-html-mode}

고급 HTML 편집기를 열고 템플릿 소스를 편집하려면 다음 단계를 따르십시오.

1. 이메일 Designer에서 [이메일 템플릿을 열거나 ](/help/marketo/product-docs/email-marketing/email-designer/email-template-authoring.md#create-an-email-template)하세요.

1. _전자 메일 템플릿 편집_ 화면에서 오른쪽 상단의 HTML 단추를 클릭합니다.

   ![](assets/advanced-html-mode-1.png){width="800" zoomable="yes"}

1. 고급 HTML 편집기를 처음 열면 경고 메시지가 표시됩니다. 검토를 마치면 **[!UICONTROL OK]**&#x200B;을(를) 클릭합니다.

   ![](assets/advanced-html-mode-2.png)

   >[!NOTE]
   >
   >이 경고는 고급 HTML 편집기를 처음 열 때 표시되며 매월 재설정됩니다.

1. 고급 HTML 편집기가 표시됩니다.

   ![](assets/advanced-html-mode-3.png){width="800" zoomable="yes"}

1. 이메일 콘텐츠에 원하는 변경 사항을 추가합니다.

   >[!WARNING]
   >
   >구문 유효성 검사 프로세스가 없으며 Adobe 지원에서 HTML 편집을 지원할 수 없으므로 올바른 HTML 및 CSS 코드를 입력해야 합니다.

1. 호환성의 이유로 고급 HTML 보기에서는 콘텐츠 시뮬레이션 및 저장을 사용할 수 없습니다. 데스크탑 보기로 다시 전환하여 콘텐츠를 미리 보고 변경 사항을 저장합니다.

   ![](assets/advanced-html-mode-4.png){width="800" zoomable="yes"}

   >[!NOTE]
   >
   >보기를 전환하면 편집 내용이 유지됩니다.
