---
title: 모델 상태 및 데이터 유효성
description: 모델 상태 및 데이터 유효성
exl-id: b14ec648-be1c-467b-b41d-2c53d74e25ea
source-git-commit: 41a51afde7942d6973a01636810bc5862d023e99
workflow-type: tm+mt
source-wordcount: '0'
ht-degree: 0%

---

# 모델 상태 및 데이터 유효성

모델의 성능은 입력 데이터의 품질과 완전성에 따라 다릅니다. 각 AI 모델에 대해 가장 큰 영향을 주는 요소를 참조하십시오. 이벤트 등록, 이벤트 참석 또는 가입 해지를 초래할 수 있는 최상위 요소를 참조하십시오.

>[!NOTE]
>
>(+)로 표시된 동작은 양의 예측에 영향을 줍니다(또는 그 반대의 경우).

여러분의 모델 건강을 평가하는 방법은 다음과 같습니다.

로 이동합니다 **[!UICONTROL Models and Data Health]** 섹션 **[!UICONTROL Predictive Audiences]** 에서 **[!UICONTROL Admin]** Marketo Classic 영역. 모든 모델과 상태를 확인할 수 있습니다.

![이미지 원](/help/sky/assets/predictive-audiences/model-health-and-data-validity/model-health-and-data-validity-1.png)

* **교육 상태**: 모델이 능동적으로 훈련되는지(예측 개선) 여부를 나타냅니다. 교육은 2주마다 자동으로 수행됩니다. 모든 모델 _처리 중_ 마치는 데 최대 24시간이 걸릴 수 있습니다 기타 _실패_ 모델, 연락처 [Marketo 지원](https://nation.marketo.com/t5/Support/ct-p/Support).
* **점수 상태**: 모델이 프로그램 멤버의 예측(가능성 백분율)을 능동적으로 계산하는지 여부를 나타냅니다.
* **성능**: 데이터 완전성 및 데이터 품질을 기반으로 모델 상태를 분류합니다(아래 참조).
* **데이터 완전성**: 존재/완료된 데이터 속성의 비율.
* **데이터 품질**: 사용 가능한 좋은 데이터를 포함하는 속성의 백분율입니다.
