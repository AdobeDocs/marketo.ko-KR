---
unique-page-id: 2952636
description: 사용자 정의 로직을 사용하여 중복 사용자 찾기 - Marketo 문서 - 제품 설명서
title: 사용자 지정 논리를 사용하여 중복 인물 찾기
exl-id: e268ca34-03a3-403a-8869-4e2b60bba05c
translation-type: tm+mt
source-git-commit: 72e1d29347bd5b77107da1e9c30169cb6490c432
workflow-type: tm+mt
source-wordcount: '137'
ht-degree: 5%

---

# 사용자 지정 논리 {#find-duplicate-people-with-custom-logic}을(를) 사용하여 중복 인물 찾기

Marketo에는 이메일 주소와 일치시켜 중복 사용자를 찾는 시스템 스마트 목록이 있습니다. 다른 필드를 사용하여 중복 항목을 찾으려면 다음 방법을 참조하십시오.

>[!PREREQUISITES]
>
>[스마트 목록 만들기](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/create-a-smart-list.md)

1. **마케팅 활동** 영역으로 이동합니다.

![](assets/ma-2.png)

1. 스마트 목록을 선택하고 **스마트 목록** 탭을 클릭합니다.

   ![](assets/two-4.png)

1. **중복 필드** 필터를 찾아 캔버스로 드래그합니다.

   ![](assets/three-4.png)

1. 사용 가능한 4가지 옵션 중 하나를 선택합니다.

   * 이메일 주소
   * 전체 이름
   * 성
   * 업데이트 날짜:

   >[!NOTE]
   >
   >이메일 주소를 제외한 모든 필드는 대/소문자를 구분합니다. 따라서 [전체 이름] 필드에 &quot;john doe&quot;를 사용하면 _not_ John Doe에 대한 결과가 반환됩니다.

   ![](assets/four-2.png)

   완료! 스마트 목록을 실행하여 이전에 선택한 필드에서 동일한 값을 가진 사람을 찾습니다.
