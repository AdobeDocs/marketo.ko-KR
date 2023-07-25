---
description: 사용자 및 라이선스 관리 - Marketo 문서 - 제품 설명서
title: 사용자 및 라이선스 관리
exl-id: 1fee628b-e9f3-46ab-b993-f2d09fe5e183
feature: Interactive Webinars
source-git-commit: 02b2e39580c5eac63de4b4b7fdaf2a835fdd4ba5
workflow-type: tm+mt
source-wordcount: '414'
ht-degree: 0%

---

# 사용자 및 라이선스 관리 {#user-and-license-management}

사용자를 추가 및 제거하고 현재 라이선스를 보는 방법에 대해 알아봅니다.

## 사용자 추가 {#add-a-user}

1. 로 이동 **관리자** 영역입니다.

   ![](assets/user-and-license-management-1.png)

1. 클릭 **대화형 웨비나**.

   ![](assets/user-and-license-management-2.png)

1. 클릭 **사용자 추가/제거**.

   ![](assets/user-and-license-management-3.png)

1. 사용 가능한 사용자 드롭다운을 클릭하고, 추가하려는 사용자를 선택한 다음 를 클릭합니다. **확인**.

   ![](assets/user-and-license-management-4.png)

## 사용자 제거 {#remove-a-user}

1. 로 이동 **관리자** 영역입니다.

   ![](assets/user-and-license-management-5.png)

1. 클릭 **대화형 웨비나**.

   ![](assets/user-and-license-management-6.png)

1. 클릭 **사용자 추가/제거**.

   ![](assets/user-and-license-management-7.png)

1. 제거할 사용자를 강조 표시하고 키보드에서 Delete 키를 누릅니다. 클릭 **확인** 완료 시.

   ![](assets/user-and-license-management-8.png)

## 라이선스 사용 {#license-usage}

대화형 웨비나는 Adobe Connect에서 제공하는 이벤트를 만들기 위한 특정 라이선스를 제공합니다. 라이센스가 추가될 때마다 새 라이센스 사용 상자가 나타납니다. Marketo 관리자는 아래 단계에 따라 라이센스를 볼 수 있습니다(편집할 수 없음). 추가 라이선스를 얻으려면 Adobe 계정 팀(계정 관리자)에 문의하십시오.

1. 로 이동 **관리자** 영역입니다.

   ![](assets/user-and-license-management-9.png)

1. 클릭 **대화형 웨비나**.

   ![](assets/user-and-license-management-10.png)

1. 라이센스 사용 카드로 스크롤합니다.

   ![](assets/user-and-license-management-11.png)

<table> 
  <tr> 
   <td><b>시작 일자</b></td>
   <td>라이센스 시작 날짜.</td>
  </tr>
  <tr> 
   <td><b>만료일</b></td>
   <td>라이센스가 만료되는 날짜입니다.</td>
  </tr>
  <tr> 
   <td><b>유형</b></td>
   <td>구매한 라이선스 유형. 사용 가능한 유형은 공유 이벤트 라이선스, 공유 룸 라이선스, 추가 저장소 라이선스 세 가지입니다.</td>
  </tr>
  <tr> 
   <td><b>이벤트 용량</b></td>
   <td>이벤트에 수용할 수 있는 최대 참가자 수입니다.</td>
  </tr>
  <tr> 
   <td><b>총 이벤트 수</b></td>
   <td>이 라이선스로 프로비저닝된 총 이벤트 수입니다.</td>
  </tr>
  <tr> 
   <td><b>사용된 이벤트</b></td>
   <td>완료된 총 이벤트 수입니다.</td>
  </tr>
  <tr> 
   <td><b>스토리지 용량</b></td>
   <td>기록, 자료, hero images, 문서 및 기타 자산을 저장하는 데 사용할 수 있는 스토리지 용량입니다.</td>
  </tr>
  </tbody>
</table>

**참고할 사항**

* &quot;추가 스토리지 라이센스&quot; 유형은 스토리지를 제공하므로 모든 필드의 값이 _외에_ 스토리지 용량은 단순히 &quot;-&quot;로 표시됩니다.

* &quot;Shared Room License&quot; 유형은 무제한 이벤트를 포함하며 &quot;Additional Storage License&quot;는 스토리지를 제공하므로 이러한 라이센스의 총 이벤트 필드는 간단히 &quot;-&quot;로 표시됩니다.

* 이벤트가 생성될 때마다 해당 라이선스에서 &quot;소비됨&quot;으로 계산됩니다(Shared Room 라이선스가 아닌 경우). 동일한 용량의 &quot;공유 이벤트 라이선스&quot;와 &quot;공유 룸 라이선스&quot;가 모두 있는 경우 &quot;공유 이벤트 라이선스&quot;에 대한 기본 설정이 제공됩니다. 이벤트가 게재되지 않았고 예약된 시간 전에 이벤트 프로그램 이 삭제되면 소비된 이벤트에서 이벤트를 빼서 이벤트 수를 보충합니다.

* 라이선스가 소진되면 해당 타일은 관리 섹션의 대화형 웨비나 화면에 유지되며 &quot;총 이벤트 수&quot; 및 &quot;사용된 이벤트 수&quot;는 동일한 값을 갖습니다. 라이선스가 만료될 때만 화면에서 제거됩니다.
