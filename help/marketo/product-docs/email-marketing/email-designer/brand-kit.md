---
solution: Marketo Engage
product: marketo
title: 제목
description: 브랜드 지침을 만들고 관리하는 방법을 알아봅니다.
level: Beginner, Intermediate
feature: Email Designer
hide: true
hidefromtoc: true
source-git-commit: 25a218896c84a7145f05079fe8adcf3d657adcad
workflow-type: tm+mt
source-wordcount: '1178'
ht-degree: 9%

---

# 브랜드 만들기 및 관리 {#brands}

>[!AVAILABILITY]
>
>Adobe Marketo Engage에서 AI 도우미를 사용하려면 먼저 [사용자 동의](https://www.adobe.com/kr/legal/licenses-terms/adobe-dx-gen-ai-user-guidelines.html){target="_blank"}에 동의해야 합니다. 자세한 내용은 Adobe 계정 팀(계정 관리자)에 문의하십시오.

브랜드 지침은 브랜드의 시각적 및 언어적 정체성을 확립하는 상세한 규칙 및 표준 세트입니다. 모든 마케팅 및 커뮤니케이션 플랫폼에서 일관된 브랜드 표현을 유지하는 참조 역할을 합니다.

이제 [!DNL Marketo Engage]에서 브랜드 세부 정보를 수동으로 입력 및 구성하거나 자동 정보 추출을 위해 브랜드 지침 문서를 업로드할 수 있습니다.

## 브랜드 액세스 {#generative-access}

**[!UICONTROL Brands]**&#x200B;에서 [!DNL Adobe Marketo Engage] 메뉴에 액세스하려면 사용자에게 **[!UICONTROL Manage brand kit]** 또는 **[!UICONTROL Enable AI assistant]** 권한이 부여되어야 합니다. 추가 정보 링크

+++  브랜드 관련 권한을 할당하는 방법을 알아봅니다.

브랜드에 대한 권한을 할당하려면 다음 단계를 따르십시오.

1. **권한** 제품에서 **역할** 탭으로 이동하여 원하는 **역할**&#x200B;을 선택하십시오.

1. 권한을 수정하려면 **편집**&#x200B;을 클릭하십시오.

1. **AI Assistant** 리소스를 추가한 다음 드롭다운 메뉴에서 **브랜드 키트 관리** 또는 **[!UICONTROL Enable Ai assistant]**&#x200B;를 선택합니다.

   **[!UICONTROL Enable Ai assistant]** 권한은 **[!UICONTROL Brands]** 메뉴에 대한 읽기 전용 액세스를 제공합니다.

   스크린샷

1. 변경 내용을 적용하려면 **저장**&#x200B;을 클릭하십시오.

   이 역할에 이미 할당된 모든 사용자의 권한은 자동으로 업데이트됩니다.

1. 새 사용자에게 이 역할을 할당하려면 **역할** 대시보드의 **사용자** 탭으로 이동하여 **사용자 추가**&#x200B;를 클릭하십시오.

1. 사용자 이름, 이메일 주소를 입력하거나 목록에서 선택한 다음 **저장**&#x200B;을 클릭합니다.

1. 이전에 사용자를 생성하지 않은 경우 [이 설명서](https://experienceleague.adobe.com/ko/docs/experience-platform/access-control/abac/permissions-ui/users)를 참조하십시오.

+++

## 브랜드 만들기 및 관리 {#create-brand-kit}

브랜드 지침을 만들고 관리하기 위해 직접 세부 정보를 입력하거나 브랜드 지침 문서를 업로드하여 정보를 자동으로 추출할 수 있습니다.

1. **[!UICONTROL Brands]** 메뉴에서 **[!UICONTROL Create brand]**&#x200B;을(를) 클릭합니다.

   스크린샷

1. 내 브랜드의 **[!UICONTROL Name]**&#x200B;을(를) 입력하십시오.

1. 파일을 드래그 앤 드롭하거나 선택하여 브랜드 지침을 업로드하고 자동으로 관련 브랜드 정보를 추출합니다. **[!UICONTROL Create brand]**&#x200B;을(를) 클릭합니다.

   이제 정보 추출 프로세스가 시작됩니다. 완료하는 데 몇 분 정도 걸릴 수 있습니다.

   스크린샷

1. 이제 콘텐츠 및 시각적 만들기 표준이 자동으로 채워집니다. 다양한 탭을 탐색하여 필요에 따라 정보를 조정합니다. [자세히 알아보기](#personalize)

1. 각 섹션 또는 범주의 고급 메뉴에서 참조를 추가하여 관련 브랜드 정보를 자동으로 추출할 수 있습니다.

   기존 콘텐츠를 제거하려면 **[!UICONTROL Clear section]** 또는 **[!UICONTROL Clear category]** 옵션을 사용하십시오.

   스크린샷

1. 구성이 완료되면 **[!UICONTROL Save]**&#x200B;을(를) 클릭한 다음 **[!UICONTROL Publish]**&#x200B;을(를) 클릭하여 브랜드 지침을 AI Assistant에서 사용할 수 있도록 합니다.

1. 게시된 브랜드를 수정하려면 **[!UICONTROL Edit brand]**&#x200B;을(를) 클릭하십시오.

   >[!NOTE]
   >
   >이렇게 하면 편집 모드에 임시 복사본이 만들어지고 게시 후 라이브 버전이 대체됩니다.

   스크린샷

1. **[!UICONTROL Brands]** 대시보드에서 빈 아이콘을 클릭하여 고급 메뉴를 열어 다음 작업을 수행합니다.

   * 브랜드 보기
   * 편집
   * 복제
   * 게시
   * 게시 취소
   * 삭제

   스크린샷

이제 AI Assistant 메뉴의 **[!UICONTROL Brand]** 드롭다운에서 브랜드 지침에 액세스할 수 있으므로 사양에 맞게 정렬된 콘텐츠 및 에셋을 생성할 수 있습니다. AI Assistant에 대해 자세히 알아보기 - 링크

스크린샷

### 기본 브랜드 설정 {#default-brand}

캠페인 생성 중 콘텐츠를 생성하고 정렬 점수를 계산할 때 자동으로 적용할 기본 브랜드를 지정할 수 있습니다.

기본 브랜드를 설정하려면 **[!UICONTROL Brands]** 대시보드로 이동하십시오. 아이콘을 클릭하여 고급 메뉴를 열고 **[!UICONTROL Mark as default brand]**&#x200B;을(를) 선택합니다.

스크린샷

## 브랜드 개인화 {#personalize}

### 브랜드 정보 {#about-brand}

**[!UICONTROL About the brand]** 탭을 사용하여 브랜드의 목적, 성격, 태그 및 기타 정의 특성에 대한 개요를 포함하여 브랜드의 핵심 ID를 설정하십시오.

1. 먼저 **[!UICONTROL Key details]** 범주에 브랜드의 기본 정보를 입력하십시오.

   * **[!UICONTROL Brand Kit Name]**: 브랜드 키트 이름을 입력하십시오.

   * **[!UICONTROL When to Use]**: 이 브랜드 키트를 적용해야 하는 시나리오 또는 컨텍스트를 지정합니다.

   * **[!UICONTROL Brand Name]**: 공식 브랜드 이름을 입력하십시오.

   * **[!UICONTROL Brand Description]**: 이 브랜드가 나타내는 것에 대한 개요를 제공하십시오.

   * **[!UICONTROL Default Tagline]**: 브랜드와 연결된 기본 태그 추가

   스크린샷

1. **[!UICONTROL Guiding principles]** 카테고리에서 브랜드의 핵심 방향과 철학을 명확히 합니다.

   * **[!UICONTROL Mission]**: 브랜드의 용도를 자세히 설명합니다.

   * **[!UICONTROL Vision]**: 장기 목표 또는 원하는 향후 상태를 설명합니다.

   * **[!UICONTROL Market Positioning]**: 브랜드가 시장에서 어떻게 포지셔닝되고 있는지 설명합니다.

   스크린샷

1. **[!UICONTROL Core brand values]** 범주에서 &quot;추가 아이콘&quot;을 클릭하여 브랜드의 핵심 값을 추가하고 세부 정보를 입력합니다.

   * **[!UICONTROL Value]**: 핵심 브랜드 값에 이름을 지정합니다.

   * **[!UICONTROL Description]**: 이 값이 브랜드에 어떤 의미가 있는지 설명합니다.

   * **[!UICONTROL Behaviors]**: 실제로 이 값을 반영하는 작업 또는 태도에 대해 대략적으로 설명합니다.

   * **[!UICONTROL Manifestations]**: 실제 브랜딩에서 이 값이 표현되는 방식에 대한 예를 제공합니다.

   스크린샷

1. 필요한 경우 &quot;편집&quot; 아이콘을 클릭하여 핵심 브랜드 가치 중 하나를 업데이트하거나 삭제합니다.

   스크린샷

이제 브랜드를 추가로 개인화하거나 [브랜드를 게시](#create-brand-kit)할 수 있습니다.

### 작성 스타일 {#writing-style}

**[!UICONTROL Writing style]** 섹션에서는 모든 자료의 명확성, 일관성 및 일관성을 유지하기 위해 언어, 서식 및 구조를 사용해야 하는 방법에 대해 자세히 설명하는 콘텐츠 쓰기 표준을 간략하게 설명합니다.

+++ 사용 가능한 범주 및 예

<table>
  <thead>
    <tr>
      <th>카테고리</th>
      <th>하위 범주</th>
      <th>지침 예</th>
      <th>제외 예</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="4">콘텐츠 제작 표준</td>
      <td>브랜드 메시징 표준</td>
      <td>혁신과 고객 중심의 메시지를 강조하십시오.</td>
      <td>제품 기능을 너무 많이 약속하지 마십시오.</td>
    </tr>
    <tr>
      <td>태그 사용</td>
      <td>모든 디지털 마케팅 에셋의 로고 아래에 타깃을 놓습니다.</td>
      <td>타깃줄을 수정하거나 번역하지 마십시오.</td>
    </tr>
    <tr>
      <td>핵심 메시징</td>
      <td>생산성 향상과 같은 주요 이점 설명 강조</td>
      <td>관련 없는 값 제안을 사용하지 마십시오.</td>
    </tr>
    <tr>
      <td>이름 지정 표준</td>
      <td>"ProScheduler"와 같이 간단한 수사적 이름을 사용합니다.</td>
      <td>복잡한 용어나 특수 문자를 사용하지 마십시오.</td>
    </tr>
    <tr>
      <td rowspan="5">브랜드 커뮤니케이션 스타일</td>
      <td>브랜드 성격 트레이트</td>
      <td>친숙하고 접근하기 쉬워.</td>
      <td>패배주의자가 되지 마라.</td>
    </tr>
    <tr>
      <td>필기학</td>
      <td>문장을 짧고 굵게 유지하세요.</td>
      <td>과도한 전문 용어를 사용하지 마십시오.</td>
    </tr>
    <tr>
      <td>상황적 어조</td>
      <td>위기 커뮤니케이션에서 전문적 태도를 유지하십시오.</td>
      <td>지원 커뮤니케이션을 무시하지 마십시오.</td>
    </tr>
    <tr>
      <td>단어 선택 지침</td>
      <td>"혁신적", "현명한" 등의 단어를 사용하십시오.</td>
      <td>"싸다" 또는 "해킹"과 같은 단어를 피하십시오.</td>
    </tr>
    <tr>
      <td>언어 표준</td>
      <td>미국 영어 규칙을 따르십시오.</td>
      <td>영국 철자와 미국 철자를 혼합하지 마십시오.</td>
    </tr>
    <tr>
      <td rowspan="3">법적 규정 준수 표준</td>
      <td>상표 기준</td>
      <td>항상 ™ 또는 ® 기호를 사용하십시오.</td>
      <td>필요한 경우 법적 기호를 생략하지 마십시오.</td>
    </tr>
    <tr>
      <td>저작권 표준</td>
      <td>마케팅 자료에 대한 저작권 고지를 포함합니다.</td>
      <td>권한 없이 서드파티 콘텐츠를 사용하지 마십시오.</td>
    </tr>
    <tr>
      <td>면책조항 표준</td>
      <td>디지털 에셋에 고지 사항을 눈에 띄게 표시합니다.</td>
      <td>보이지 않는 영역에 면책조항을 숨기지 마십시오.</td>
    </tr>
</table>

+++

</br>

**[!UICONTROL Writing Style]**&#x200B;을(를) 개인화하려면:

1. **[!UICONTROL Writing Style]** 탭에서 이 아이콘을 클릭하여 지침, 예외 또는 제외를 추가합니다.

1. 지침, 예외 또는 제외를 입력하고 **[!UICONTROL Add]**&#x200B;을(를) 클릭합니다.

   스크린샷

1. 업데이트하거나 삭제할 지침 또는 제외 중 하나를 선택합니다.

1. 예를 편집하려면 &quot;편집&quot;을 클릭하고 삭제하려면 &quot;삭제&quot; 아이콘을 클릭하십시오.

   스크린샷

이제 브랜드를 추가로 개인화하거나 [브랜드를 게시](#create-brand-kit)할 수 있습니다.

### 시각적 콘텐츠 {#visual-content}

**[!UICONTROL Visual Content]** 섹션은 이미지 및 디자인에 대한 표준을 정의하며 통일되고 일관된 브랜드 디자인을 유지하는 데 필요한 사양을 자세히 설명합니다.

+++ 사용 가능한 범주 및 예

<table>
  <thead>
    <tr>
      <th>카테고리</th>
      <th>지침 예</th>
      <th>제외 예</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>사진 표준</td>
      <td>야외 촬영에는 자연 채광을 사용하십시오.</td>
      <td>지나치게 편집되거나 픽셀화된 이미지는 피하십시오.</td>
    </tr>
    <tr>
      <td>일러스트레이션 표준</td>
      <td>깔끔하고 미니멀한 스타일을 사용하세요.</td>
      <td>지나치게 복잡하지 않도록 합니다.</td>
    </tr>
    <tr>
      <td>아이콘 표준</td>
      <td>일관된 24px 격자 시스템을 사용합니다.</td>
      <td>아이콘 차원을 혼합하지 않거나, 일관성이 없는 획 가중치를 사용하거나, 격자 규칙을 벗어나지 않습니다.</td>
    </tr>
    <tr>
      <td>사용 지침</td>
      <td>전문 환경에서 제품을 사용하는 실제 고객을 반영하는 라이프스타일 이미지를 선택하십시오.</td>
      <td>브랜드 톤과 모순되거나 문맥에서 벗어난 이미지를 사용하지 마십시오.</td>
    </tr>
</table>

+++

</br>

**[!UICONTROL Visual content]**&#x200B;을(를) 개인화하려면:

1. **[!UICONTROL Visual content]** 탭에서 BLANK를 클릭하여 지침, 제외 또는 예를 추가합니다.

1. 지침, 제외 또는 예를 입력하고 **[!UICONTROL Add]**&#x200B;을(를) 클릭합니다.

   스크린샷

1. 올바른 사용을 보여 주는 이미지를 추가하려면 **[!UICONTROL Example]**&#x200B;을(를) 선택하고 **[!UICONTROL Select image]**&#x200B;을(를) 클릭합니다. 제외 예로서 잘못된 사용을 보여주는 이미지를 추가할 수도 있습니다.

   스크린샷

1. 업데이트하거나 삭제할 지침 또는 제외 중 하나를 선택합니다.

1. 지침 또는 제외 중 하나를 선택하여 업데이트합니다. 삭제하려면 &quot;삭제&quot; 아이콘을 클릭합니다.

   스크린샷

이제 브랜드를 추가로 개인화하거나 [브랜드를 게시](#create-brand-kit)할 수 있습니다.
