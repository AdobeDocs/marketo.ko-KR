---
unique-page-id: 5472678
description: 라틴 문자 목록 가져오기 - Marketing Docs - 제품 설명서
title: 라틴 문자 목록 가져오기
translation-type: tm+mt
source-git-commit: 47b2fee7d146c3dc558d4bbb10070683f4cdfd3d
workflow-type: tm+mt
source-wordcount: '307'
ht-degree: 0%

---


# 라틴 문자 목록 가져오기 {#import-a-non-latin-characters-list}

영어가 아닌 파일을 가져오려고 하십니까? Excel에서 열면 목록이 완벽해 보입니다.

![](assets/image2015-2-10-9-3a34-3a57.png)

그러나 Marketing To로 가져오면 영어가 아닌 문자가 올바르게 선택되지 않은 것을 볼 수 있습니다.

![](assets/image2015-2-10-9-3a35-3a49.png)

Marketing to가 라틴 문자가 아닌 모든 문자를 인식할 수 있도록 파일이 제대로 저장되지 않기 때문입니다. 좋은 소식은 몇 가지 간단한 단계를 통해 수정할 수 있다는 것입니다.

1. Excel **의 파일** **메뉴에서 다른 이름으로** 저장..을 선택합니다.

   ![](assets/image2015-2-10-9-3a46-3a44.png)

1. [형식] 옵션으로 **UTF-16 유니코드 텍스트(.txt)** 를 **선택합니다** . 이렇게 하면 파일이 Marketing Cloud에서 표시하는 방식으로 인코딩됩니다.

   ![](assets/image2015-2-10-9-3a48-3a7.png)

   >[!NOTE]
   >
   >Marketing은 UTF-8, Shift-JIS 또는 EUC-JP도 지원합니다.

1. Excel에서는 새 파일을 확장자가 .txt인 텍스트 파일로 저장합니다. 또한 파일에 있는 모든 쉼표를 탭으로 변환합니다. 다시 바꿔야 합니다.

   >[!TIP]
   >
   >Mac을 사용하는 경우 Windows 또는 **TextEdit을** 사용하는 경우 메모장을 사용하여 텍스트 파일 **을** 열 수 있습니다.

   ![](assets/image2015-2-10-9-3a51-3a41.png)

1. 문서에서 탭을 선택하고 복사합니다.

   ![](assets/image2015-2-10-9-3a55-3a53.png)

1. 편집 **메뉴에서 찾기 및 바꾸기..** .를 **선택합니다** .

   ![](assets/image2015-2-10-9-3a59-3a8.png)

   >[!TIP]
   >
   >Windows 사용자를 위한 동일한 작업: **편집 > 바꾸기..**

1. 4단계에서 복사한 탭을 첫 번째(바꿀 내용) 상자에 붙여 넣고 두 번째(바꿀 내용) 상자에 쉼표를 입력합니다. 모두 **를 클릭합니다**.

   ![](assets/image2015-2-10-10-3a8-3a53.png)

1. 자, 모든 쉼표가 돌아오고 우리는 곧 시작할 준비가 되었습니다.

   ![](assets/image2015-2-10-10-3a14-3a45.png)

1. 새 파일을 Marketing To로 가져오면 정보가 올바르게 표시됩니다.

   ![](assets/image2015-2-10-10-3a16-3a9.png)

   >[!NOTE]
   >
   >가져오는 모든 날짜/시간 필드는 중부 시간으로 처리됩니다. 날짜/시간 필드가 다른 시간대에 있는 경우 Excel 공식을 사용하여 이것을 중부 시간(미국/시카고)으로 변환할 수 있습니다.

이상하다는 건 알지만 효과가 있어요 가져오기 완료!