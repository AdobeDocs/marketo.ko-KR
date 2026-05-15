---
description: 이메일, 랜딩 페이지, 캠페인 등 모든 구성 요소에서 모범 사례를 감사하는 방법을 알아봅니다.
title: 프로그램 QA
badge: Beta
exl-id: 51d4b2d8-44b0-4b51-851f-7cb233baf2d6
source-git-commit: f552c0b0219aede39e0742466ab2473e8e924e55
workflow-type: tm+mt
source-wordcount: '195'
ht-degree: 0%

---

# 프로그램 QA {#program-qa}

이메일, 랜딩 페이지, 캠페인 등 모든 구성 요소에 대한 모범 사례를 살펴보려면 프로그램을 감사하십시오.

>[!PREREQUISITES]
>
>이 기능을 사용하려면 먼저 [Core Gen-AI 약관 및 추가 약관](https://www.adobe.com/legal/terms/enterprise-licensing/genai-ww.html){target="_blank"}에 동의해야 합니다. 자세한 내용은 Adobe 계정 팀(계정 관리자)에 문의하십시오.

>[!NOTE]
>
>이 기능은 비공개 베타 버전이며 현재 다음 몇 달에 걸쳐 단계적으로 롤아웃할 예정입니다. 내 Marketo 화면에서 _AI로 빌드_ 타일이 표시되면 구독이 활성화된 시기를 알 수 있습니다.

## 사용 방법 {#how-to-use}

1. 내 Marketo에서 **AI로 빌드** 타일을 클릭합니다.

   ![](assets/program-qa-1.png)

1. **프로그램 QA** 에이전트를 선택하십시오.

   ![](assets/program-qa-2.png)

   대화형 AI 화면으로 이동합니다.

1. 오른쪽 창에서 QA할 프로그램을 선택합니다.

   ![](assets/program-qa-3.png){width="800" zoomable="yes"}

   선택한 프로그램의 요약이 중앙 창에 나타납니다.

   ![](assets/program-qa-4.png){width="450" zoomable="yes"}

1. 프롬프트 창에서 &quot;QA 프로그램&quot;을 입력하고 **보내기**&#x200B;를 클릭합니다.

   ![](assets/program-qa-5.png)

   AI 도우미는 선택한 프로그램의 QA를 제공하며, 무엇이 통과했고 무엇이 실패했는지 보여 줍니다.

   ![](assets/program-qa-6.png)

<!--
   You have three validation paths to choose from:

   | Path | What You Provide | Verification Type | Best For |
   | --- | --- | --- | --- |
   | Rules Only | Nothing | Compliance checks | Org compliance & audits |
   | + Test Plan | Your team's test document | Rules + Custom checks | Team or channel-specific checks |
   | + Campaign Brief | Campaign brief document | Exact field matching | Pre-launch readiness |

1. To Upload a Test Plan, a Campaign Brief, or both, click the upload icon, add your files and click **Send**. To proceed with rules only, enter "Proceed with Rules Only" in the prompt window and click **Send**. In this example, we are proceeding with rules only.

PICC

1. To start validation, click **Run QA Validation**.

PICC

1. The report generates. To see the full report, click View Full Report.

PICC

1. The report appears in the center console. Scroll down to view. You can also download the report via .docx file.

PICC
-->
