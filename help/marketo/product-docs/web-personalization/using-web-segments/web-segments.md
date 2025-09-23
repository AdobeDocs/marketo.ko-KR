---
unique-page-id: 4719093
description: 웹 세그먼트 - Marketo 문서 - 제품 설명서
title: 웹 세그먼트
exl-id: ec62c1ae-579a-4753-9b2d-18c7c2fa1ff5
feature: Web Personalization
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '1980'
ht-degree: 0%

---

# 웹 세그먼트 {#web-segments}

## 세그먼트 보기 {#view-segment}

![](assets/image2014-11-11-20-3a24-3a5.png)

세그먼트 탭에는 다양한 속성을 기반으로 설정한 사용자 정의 세그먼트가 모두 표시됩니다.  **세그먼트는 &#39;세그먼트 설정&#39; 페이지에 정의된 지정된 조건을 충족하는 방문자 컬렉션입니다.** 세그먼트는 특정 업계, 위치 또는 방문자의 현장 활동을 기반으로 한 방문자일 수 있습니다.

[!DNL Web Personalizatio]에서 방문자는 두 개 이상의 세그먼트를 일치시킬 수 있습니다. 예를 들어 미국 방문자에 대한 세그먼트와 금융 회사에 대한 세그먼트가 있는 경우 Bank of America의 웹 방문자는 미국 방문자에 대한 세그먼트와 금융 회사에 대한 세그먼트를 **모두**&#x200B;일치하게 됩니다.

**그래프:** 세그먼트 페이지에는 세그먼트의 방문자 수(y축)와 세그먼트 이름(x축)에 따라 선택한 세그먼트의 막대 차트 그래프가 표시됩니다.

<table>
 <thead>
  <tr>
   <th colspan="1" rowspan="1">이름</th>
   <th colspan="1" rowspan="1">설명</th>
  </tr>
 </thead>
 <tbody>
  <tr>
   <td colspan="1" rowspan="1"><strong>이름</strong></td>
   <td colspan="1" rowspan="1">세그먼트 제목</td>
  </tr>
  <tr>
   <td colspan="1" rowspan="1"><p><strong>일치</strong></p></td>
   <td colspan="1" rowspan="1">세그먼트의 사용자 지정 정의된 기준을 충족하는 방문자의 수입니다</td>
  </tr>
  <tr>
   <td colspan="1" rowspan="1"><strong>캠페인 설정</strong></td>
   <td colspan="1" rowspan="1">선택한 검색어와 연결된 Campaign CTA을 설정할 수 있습니다.</td>
  </tr>
  <tr>
   <td colspan="1"><strong>방문자</strong></td>
   <td colspan="1">선택한 검색어와 연관된 방문자 테이블의 미리보기</td>
  </tr>
  <tr>
   <td colspan="1" rowspan="1"><strong>클릭스트림</strong></td>
   <td colspan="1" rowspan="1">방문자가 사이트에서 보낸 활동 및 URL 경로와 각 페이지를 방문한 시간을 표로 표시합니다 </td>
  </tr>
 </tbody>
</table>

[세그먼트 레이블을 만들고 보는 방법](/help/marketo/product-docs/web-personalization/using-web-segments/label-your-segment.md) 보기

**세그먼트 - 오른쪽 패널**

![](assets/image2014-11-12-10-3a46-3a32.png)

표에서 세그먼트를 선택하면 오른쪽 패널에 세그먼트에 대한 추가 세부 정보가 표시됩니다.

이러한 세부 사항은 다음과 같습니다.

* 세그먼트 이름
* 세그먼트의 만든 날짜
* 세그먼트와 함께 작동하는 캠페인을 보여 주는 연결된 캠페인. 반응 수를 클릭하면 세그먼트에 대한 캠페인 CTA(Call to action)를 표시하는 캠페인 페이지로 이동합니다
* 세그먼트에 대한 일치(세그먼트 기준을 충족한 방문자 수) 및 세그먼트와 일치하는 고유(고유) 방문자 수입니다. 고유 방문자 링크를 클릭하면 세그먼트 결과를 표시하는 방문자의 페이지로 이동합니다
* 세그먼트의 소유자/사용자 생성자
* 세그먼트와 연계된 도메인 사이트
* 선택한 세그먼트 기준에 대한 간략한 요약

## 세그먼트 활성화 또는 비활성화 {#enable-or-disable-a-segment}

![](assets/image2014-11-12-10-3a48-3a9.png)

세그먼트를 활성화하거나 비활성화하려면 테이블에서 해당 세그먼트의 확인란을 선택하고 테이블 하단에 있는 &quot;[!UICONTROL Choose Action]&quot; 드롭다운 상자에서 &quot;[!UICONTROL Enable]&quot; 또는 &quot;[!UICONTROL Disable]&quot; 작업을 선택합니다. 세그먼트를 사용하지 않도록 설정하면 [!UICONTROL State] 열 아래에 &quot;사용 안 함&quot;이라는 단어가 표시됩니다.

## 세그먼트 만들기 {#create-segments}

만든 세그먼트는 **[!UICONTROL Set Segment]** 페이지에서 정의한 특정 기준을 충족합니다. 기준의 조합을 기반으로 세그먼트를 사용자 정의하여 캠페인의 특정 대상을 타깃팅할 수도 있습니다.

새 세그먼트를 만들려면

**[!UICONTROL Segments]** 페이지에서 그래프 아래의 **[!UICONTROL Create New]**&#x200B;을(를) 클릭합니다. 다음 화면이 나타납니다.

![](assets/four.png)

세그먼트에 일반 매개 변수를 정의합니다.

* **이름:** 세그먼트 이름을 지정합니다.
* **설명:** 세그먼트 기준에 대한 자세한 설명을 제공합니다.
* **도메인:** 세그먼트에 포함할 도메인을 선택합니다.
* **세그먼트 규칙 논리:** AND/OR 논리를 선택하여 각 세그멘테이션 특성을 빌드합니다.
* **타이밍:** 캠페인에 원하는 방문자 참여 수준을 정의합니다.

   * **시작 시**: 방문자가 웹 사이트에 도착하는 경우 참여
   * **첫 번째 - 9번째 클릭**: 웹 사이트에서 특정 클릭 수를 선택한 후 방문자와 연결합니다.

>[!TIP]
>
>**세그먼트 규칙 논리**
>
>세 가지 필터 옵션이 있습니다.
>
>1. 모든 필터 사용(1, 2 및 3...)
>1. 모든 필터 사용(1 또는 2 또는 3...)
>1. 고급 필터(및/또는 표현식 사용)
>
>    고급 필터를 사용하면 세그먼트 조건을 제어할 수 있습니다. &quot;and&quot; 및 &quot;or&quot;로 구분된 필터 번호를 입력합니다.
>
>    * 1과 2 그리고 3
>    * 1 또는 2 또는 3
>
>    &quot;and&quot;와 &quot;or&quot;를 혼합하려면 논리 의도를 명확하게 하기 위한 괄호가 필요합니다. 예: &quot;1 또는 2 및 3&quot;은 다음 중 하나로 작성해야 합니다.
>
>    * 1 및 (2 또는 3)
>    * (1 및 2) 또는 3
>
>    중첩된 괄호는 보다 복잡한 논리에 사용할 수 있습니다. 예:
>
>    * (1, 2) 또는 (3, 4)
>    * 1 및 (2 또는 (3 및 4))
>
>    삽입, 삭제 또는 순서 변경 후 논리를 확인합니다.

오른쪽 열의 세그먼트 속성을 왼쪽의 세그먼트 편집기로 드래그하여 놓습니다.

![](assets/five.png)

### Firmgraphics {#firmographics}

**위치**

**[!UICONTROL Location]**&#x200B;을(를) 세그먼트 편집기로 끌어서 놓습니다.

* 다음 매개 변수 중에서 선택합니다.

   * **[!UICONTROL Include]** - 캠페인에 위치를 포함할지 또는 제외할지 여부를 선택합니다.
   * **[!UICONTROL Select country to add]** - 드롭다운 상자에서 세그먼트에 포함할 국가를 선택합니다. 국가 이름이 오른쪽에 나타납니다. 여러 국가를 선택할 수 있습니다.

국가가 추가되면 세그먼트의 주, 도시 및 우편번호도 지정할 수 있습니다.

* **[!UICONTROL Select State or Province to add]** - 드롭다운 상자에서 포함하려는 미국 주 또는 캐나다 주를 선택합니다. 여러 항목을 선택할 수 있습니다.
* **[!UICONTROL Zip Code]** - 세그먼트에 포함할 우편 번호를 입력합니다.
* **[!UICONTROL Cities]** - 포함할 도시를 입력하세요. 도시 사이에 세미콜론을 사용하십시오.

>[!TIP]
>
>**어떤 세그먼트 조건을 선택해야 합니까? &#39;AND&#39; 또는 &#39;OR&#39;?** OR은 각 필드 내에서 추가 옵션으로 작동합니다. 잠재 고객이 해당 세그먼트에 대한 자격을 얻으려면 각 필드 내에서 선택한 여러 기준 중 하나의 기준만 충족하면 됩니다. (예를 들어 잠재 고객은 미국 *또는 국방 산업의*&#x200B;일 수 있습니다.) AND는 이 세그먼트에 대해 충족해야 하는 추가 필수 매개 변수로 작동합니다. (예를 들어, 잠재 고객은 모두 미국 및 국방 산업이어야 합니다.) 각 세그멘테이션 프로필 내에서 각 개별 필드는 선택한 세그먼트 조건에 따라 &quot;AND&quot; 또는 &quot;OR&quot; 중 하나로 기능할 수 있습니다.

**업종** **[!UICONTROL Profile Segmentation]** 섹션에서 **[!UICONTROL Industry]** 옆에 있는 상자를 선택합니다.

* 다음 매개 변수 중에서 선택합니다.

   * **[!UICONTROL Includes]** - 세그먼트에 산업을 포함할지 또는 제외할지 여부를 선택합니다.
   * **[!UICONTROL Select Industries to add]** - 세그먼트에 포함할 산업을 선택합니다. 산업은 드롭다운 상자 아래에 나타납니다. 여러 업종을 선택할 수 있습니다.

**조직 그룹**

**[!UICONTROL Profile Segmentation]** 섹션 아래에서 **[!UICONTROL Organization Group].** 옆에 있는 상자를 선택합니다.

* 드롭다운 상자에서 다음 선택 사항 중에서 선택합니다.

   * Fortune 500 - Fortune 500 기업만 이 세그먼트에 포함
   * Fortune 1000 - Fortune 1000대 기업만 이 세그먼트에 포함
   * Global 2000 - 이 세그먼트에 Global 2000 회사 포함
   * 엔터프라이즈 - 1,000명 이상의 직원과 2억 5,000만 달러 이상의 매출을 보유한 조직 포함
   * SMB - 이 세그먼트에 중소, 중견, 성장 기업만 포함

**명명된 계정-**

**조직**

* **이 회사(특정 이름)의 사용자임**

   * &#39;추가할 회사 선택&#39; 드롭다운에서 타깃팅할 회사를 선택합니다.
   * 타깃팅하려는 정확한 조직 이름을 입력할 수 있습니다. *이름을 수동으로 입력하는 대신 이름이 지정된 계정 목록을 사용하는 것이 좋습니다(*항상*)(아래 참조).

**명명된 계정 목록**

[명명된 계정 목록](/help/marketo/product-docs/web-personalization/account-based-web-marketing/create-a-new-account-list.md)에서 선택하여 주요 대상 계정을 세그먼트화합니다.

![](assets/image2015-5-27-17-3a14-3a8.png)

>[!NOTE]
>
>명명된 계정 목록 이름 옆에 있는 대괄호 안의 숫자는 웹 Personalization [API 읽기](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/javascriptapi/web-personalization)에 대한 목록에 대한 인덱스 참조로 사용됩니다.

**ISP 제외**

세그먼트에서 인터넷 서비스 공급자(ISP)를 제외합니다.

### 알려진 사람 {#known-people}

**[!UICONTROL Database]**

[!DNL Web Personalization]은(는) Marketo 데이터베이스와 통합되어 알려진 사용자 특성 및 데이터별로 캠페인을 세그먼트화하고 개인화할 수 있습니다.

데이터베이스를 선택하고 드롭다운에서 개인 데이터 필드를 선택합니다. 드롭다운에서 필드를 추가하려면 **+**&#x200B;을(를) 선택하십시오.

![](assets/seven.png)

계정 설정 > 데이터베이스에서 개인 데이터 필드를 추가하거나 제거할 수 있습니다

>[!TIP]
>
>직함, 점수, 역할 등과 같은 Marketo 직원의 모든 개인 데이터 필드에 따라 세그먼트 기준을 만듭니다.
>
>예: &quot;직함이 CMO와 같음&quot; 및 &quot;점수가 50점 이하임&quot;

**[!UICONTROL Marketo Email Campaign]** 방문자가 Marketo 이메일을 클릭하고 사이트에 도달하여 이메일 소개를 통해 캠페인을 세그먼트화하고 개인화합니다. Marketo 프로그램 이름 또는 캠페인 이름으로 세그먼트화하고 이메일에서 웹으로 대화를 계속합니다. 드롭다운에서 필드를 추가하려면 +를 선택합니다.

![](assets/image2015-5-27-17-3a20-3a34.png)

**[!UICONTROL Status]**

잠재 고객의 상태에 따라 세그먼트를 정의합니다(알려짐 또는 익명화).

* 알려짐 - 알려진 방문자에 대해 드롭다운 상자에서 이 옵션을 선택합니다. 방문자가 웹 사이트에서 양식을 제출하고 [!DNL Web Personalization] [!UICONTROL People] 페이지에 나타나는 경우 알 수 있습니다.
* 익명 - 익명 방문자에 대한 드롭다운 상자에서 이 옵션을 선택합니다.

![](assets/image2015-5-27-17-3a23-3a2.png)

### 동작 {#behavioral}

**[!UICONTROL Visits]-** 방문자 동작 또는 식별에 따라 세그먼트를 정의합니다.

* 방문 횟수 - 웹 사이트의 잠재 고객에 대한 방문 횟수를 지정하려면 드롭다운 상자에서 이 옵션을 선택합니다.

   * 드롭다운 상자에서 같음, 같음 또는 보다 큼 또는 같음 또는 보다 작음을 선택합니다.

* 특정 방문 횟수 - 드롭다운 상자에서 이 옵션을 선택하여 특정 방문자를 지정합니다.

   * 오른쪽 텍스트 상자에 추적할 방문자 번호를 입력합니다. 고유 [!DNL Web Personalization] 방문자 식별 번호는 방문자 페이지에서 방문자를 클릭하고 오른쪽 패널의 캠페인 설정을 클릭할 때 찾을 수 있습니다. 방문자 ID는 고급 설정 섹션에 있습니다. 방문자 ID는 URL에서도 찾을 수 있습니다(예: VISITOR=JZZJIFJNUI60PZ8Y97BHTY9BL8PKWS).

**검색어** - 잠재 고객의 검색어에 따라 세그먼트를 정의합니다.

* 방문자가 검색한 검색어 - 드롭다운 목록에서 방문자 검색에서 추적할 용어를 선택하거나 직접 검색어를 추가합니다. (검색어를 포함하는 구문을 포함하도록 기본값으로 설정되므로 검색어에 &#42; 와일드카드가 필요하지 않습니다.)

**[!UICONTROL Referrals]** - 방문자가 참조한 URL을 추가합니다.

* 추가할 참조 선택 - 드롭다운 목록에서 추적하려는 참조 사이트를 선택하거나 자신의 참조를 추가합니다. 선택하면 아래 상자에 추천이 표시됩니다. (와일드카드로 &#42;을(를) 사용할 수 있음)

**[!UICONTROL Include Pages]** - 웹 사이트에서 방문한 특정 페이지 잠재 고객을 추적합니다.

* URL 일치 - 추적하려는 특정 웹 페이지의 URL을 추가합니다. 여러 URL은 세미콜론으로 구분하여 추가할 수 있습니다. (와일드카드로 &#42;을(를) 사용할 수 있습니다.)

**[!UICONTROL Exclude Pages]** - 세그먼트에서 일치하지 않을 특정 페이지를 제외합니다. (와일드카드로 &#42;을(를) 사용할 수 있습니다.)

* URL이 일치하지 않음 - 추적에서 제외할 특정 웹 페이지의 URL을 추가합니다. 여러 URL을 세미콜론으로 구분하여 추가할 수 있습니다

![](assets/segment-extra.png)

### 장치/브라우저 {#device-browser}

**[!UICONTROL Mobile OS]**

[!UICONTROL Mobile OS]을(를) 세그먼트 편집기로 끌어다 놓기

![](assets/image2015-5-27-17-3a45-3a3.png)

* **방문자 유형**<br />
  **[!UICONTROL Mobile OS]** - 드롭다운 상자에서 나열된 하나 이상의 모바일 OS에서 선택합니다. 선택한 모바일 OS가 아래에 나타납니다.

   * 방문자가 모바일 장치를 사용하고 있습니다
   * 방문자가 이 특정 장치/OS를 사용하고 있습니다.
   * 방문자가 모바일 장치를 사용하고 있지 않습니다

* **[!UICONTROL Device]** - 드롭다운 목록에서 하나 이상의 장치(Apple, Samsung, LG, HTC, Nexus, Blackberry 등)를 선택합니다. 선택한 장치가 아래에 나타납니다.

**브라우저**

특정 브라우저 유형 및/또는 버전을 사용하는 타겟 방문자입니다.

* 브라우저 유형 - 드롭다운 상자에서, 하나 이상의 인터넷 브라우저 를 선택합니다. 선택한 브라우저가 아래에 표시됩니다.
* 브라우저 버전 - 세그먼트에 추가할 브라우저 버전을 입력합니다. 각 버전을 쉼표로 구분하여 여러 버전을 선택할 수 있습니다. (와일드카드로 &#42;을(를) 사용할 수 있습니다.)

### API {#api}

**데이터 이벤트** - 특정 사용자 지정 데이터 이벤트를 트리거하는 세그먼트 방문자

타깃팅할 이벤트 값을 추가합니다. 예: 서드파티 데이터 소스.

**사용자 컨텍스트 API**

웹 Personalization API 호출 [자세한 내용은 여기를 참조하십시오.](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/javascriptapi/web-personalization)

>[!TIP]
>
>**와일드카드 사용 -** 검색어 또는 그 안에 포함된 URL(예: &quot;[google.com](https://google.com)&quot; 또는 &quot;검색어 제품&quot;)을 포함하려는 경우 와일드카드라고 부르며 각 끝에 별표로 입력해야 합니다. 이 작은 사람&#42; 따라서 [google.com](https://google.com)에서 오는 모든 정보는 &#42; [google.com](https://google.com)&#42;(으)로 입력해야 합니다.

## [!UICONTROL Segments] 편집 {#edit-segments}

생성된 세그먼트를 편집할 수 있습니다.

1. 세그먼트를 편집하려면 **[!UICONTROL Segments]**(으)로 이동하십시오.

   ![](assets/image2014-11-12-11-3a38-3a22.png)

1. **[!UICONTROL Segments]** 테이블에서 편집할 세그먼트의 편집 아이콘(![](assets/segment-edit.png))을 클릭합니다. 선택한 세그먼트로 **[!UICONTROL Set Segment]** 페이지가 열립니다.
1. 세그먼트에 적용할 편집 또는 변경 사항을 적용합니다.
1. **[!UICONTROL Save]**&#x200B;를 클릭합니다.

## 세그먼트 삭제 {#delete-segments}

만든 세그먼트를 삭제할 수 있습니다.

1. 위의 **[!UICONTROL Segments]** 페이지에서 세그먼트를 선택합니다.
1. 삭제할 세그먼트의 삭제 아이콘(![](assets/segment-delete.png) )을 클릭합니다.
1. 확인 메시지가 표시되어 **세그먼트**&#x200B;을(를) 삭제하려고 함을 확인합니다.

>[!NOTE]
>
>캠페인과 연결된 세그먼트는 삭제할 수 없습니다. 먼저 캠페인을 삭제한 다음 세그먼트를 삭제해야 합니다.

잘됐네! 세그먼트 섹션을 이해했으므로 이제 캠페인에 대해 알아보겠습니다.

>[!MORELIKETHIS]
>
>* [기본 웹 세그먼트 만들기](/help/marketo/product-docs/web-personalization/using-web-segments/create-a-basic-web-segment.md)
>* [새 대화 상자 웹 캠페인 만들기](/help/marketo/product-docs/web-personalization/working-with-web-campaigns/create-a-new-dialog-web-campaign.md)
>* [영역 웹 캠페인에 새 항목 만들기](/help/marketo/product-docs/web-personalization/working-with-web-campaigns/create-a-new-in-zone-web-campaign.md)
>* [새 위젯 웹 캠페인 만들기](/help/marketo/product-docs/web-personalization/working-with-web-campaigns/create-a-new-widget-web-campaign.md)
