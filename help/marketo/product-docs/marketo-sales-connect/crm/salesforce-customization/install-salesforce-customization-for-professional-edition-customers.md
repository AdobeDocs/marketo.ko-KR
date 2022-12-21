---
unique-page-id: 27656223
description: Professional Edition 고객을 위한 Salesforce Customization 설치 - Marketo 문서 - 제품 설명서
title: Professional Edition 고객을 위한 Salesforce 사용자 지정 설치
exl-id: dc004a28-b580-4449-9fde-e744681ac53a
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '272'
ht-degree: 0%

---

# Professional Edition 고객을 위한 Salesforce 사용자 지정 설치 {#install-salesforce-customization-for-professional-edition-customers}

Salesforce Professional Edition을 사용하는 고객은 사용자 지정을 설치하기 위해 다음 단계를 수행해야 합니다.

>[!PREREQUISITES]
>
>* Sales Connect 관리자는 Salesforce 및 Sales Connect 계정을 연결해야 합니다.
>* 사용된 Salesforce 인스턴스에는 13개의 사용자 지정 활동 필드를 설치할 공간이 있어야 합니다.


## 설치 {#installation}

1. Sales Connect에서 오른쪽 상단의 톱니바퀴 아이콘을 클릭하고 을 선택합니다 **설정**.

   ![](assets/one-4.png)

1. 관리자 설정에서 을 클릭합니다. **Salesforce**.

   ![](assets/two-4.png)

1. Salesforce 계정에 연결되어 있는지 확인합니다.

   >[!CAUTION]
   >
   >연결된 경우 녹색 &quot;설치&quot; 단추가 표시됩니다. **금지** 이 단추를 클릭하고 대신 4단계로 진행합니다.

1. 연결된 Salesforce 계정에 로그인한 다음 [이 링크](https://login.salesforce.com/packaging/installPackage.apexp?p0=04t0b000001oWEZ).
1. Sales Connect 설치 페이지로 전송됩니다.

   ![](assets/install-package.png)

1. 사용자 지정을 설치할 사용자를 선택합니다. 관리 전용, 모든 사용자 또는 특정 프로필.
1. 을(를) 클릭합니다. **설치** 사용자 지정 설치 단추입니다.
1. 성공적인 설치를 확인하려면 Salesforce 계정에 로그인합니다.
1. 클릭 **설정**&#x200B;를 클릭하고 검색 막대에서 &quot;Installed Packages&quot;를 검색한 다음 **설치된 패키지**.

   여기에 Marketo Sales Connect 사용자 지정 사항이 표시됩니다.

   Salesforce 인스턴스에서 Sales Connect를 구성하려면 Installation Guide의 7페이지에 있는 &quot;CONFIGURING THE SALES ENGAGE SALESFORCE PACKAGE&quot; 섹션에서 시작하는 단계를 따르십시오.

   >[!NOTE]
   >
   >Sales Engage 는 Sales Connect 의 이전 이름입니다.

## 안내서 {#guides}

[Salesforce Classic 설치 안내서](https://s3.amazonaws.com/tout-user-store/salesforce/assets/Marketo+Sales+Engage+For+Salesforce_+Installation+and+Success+Guide.pdf)

[Salesforce Lightning 설치 안내서](https://s3.amazonaws.com/tout-user-store/salesforce/assets/SF+Guide+for+Lightning.pdf)
