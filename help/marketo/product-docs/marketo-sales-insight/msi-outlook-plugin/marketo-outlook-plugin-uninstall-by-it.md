---
unique-page-id: 11382829
description: IT에서 Marketo Outlook 플러그인 제거 - Marketo 문서 - 제품 설명서
title: IT에서 Marketo Outlook 플러그인 제거
exl-id: 678684da-3e99-462f-9950-504df1c1bb1e
feature: Marketo Sales Insights
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '128'
ht-degree: 0%

---

# IT에서 Marketo Outlook 플러그인 제거 {#marketo-outlook-plugin-uninstall-by-it}

다음은 IT가 원격으로 Marketo Outlook 플러그인을 제거하는 방법입니다.

다음 명령줄을 &#39;System&#39;으로 실행하거나 /x 스위치를 사용하여 관리 사용자 계정으로 실행하여 제거합니다.

`<pre>msiexec.exe /x [File Name] /qn </pre>`

>[!NOTE]
>
>**예**
>
>`<pre>msiexec.exe /x MarketoAddInSetup64.msi /qn </pre>`

문제 해결을 위해 로깅을 활성화하여 출력 로그 파일을 만들 수 있습니다.

`<pre>msiexec.exe /x [File Name] /qn /L*v MarketoAddinUninstall.log</pre>`

>[!NOTE]
>
>**예**
>
>`<pre>msiexec.exe /x MarketoAddInSetup64.msi /qn /L*v MarketoAddinUninstall.log</pre>`

로그 파일의 위치를 지정하려면 명령줄에서 파일 경로를 지정할 수 있습니다.

`<pre>msiexec.exe /x [File Name] /qn /L*v [File Path]MarketoAddinUninstall.log</pre>`

>[!NOTE]
>
>**예**
>
>`<pre>msiexec.exe /x MarketoAddInSetup64.msi /qn /L*v C:\temp\MarketoAddinUninstall.log</pre>`

>[!CAUTION]
>
>플러그인을 원격으로 제거하면 사용자의 컴퓨터에서 Outlook이 강제로 닫힙니다.

다음을 참조하십시오. [Microsoft의 전체 스위치 목록](https://support.microsoft.com/en-us/office/command-line-switches-for-microsoft-office-products-079164cd-4ef5-4178-b235-441737deb3a6) 다른 로깅 수준 또는 사용자 인터페이스 수준을 사용하려고 하는 경우.
