---
unique-page-id: 1147356
description: 이메일 이벤트 로깅 이해 - Marketo 문서 - 제품 설명서
title: 이메일 이벤트 로깅 이해
exl-id: 107d7f4a-ad38-44e4-95d8-760539aacede
feature: Email Editor
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: tm+mt
source-wordcount: '305'
ht-degree: 1%

---

# 이메일 이벤트 로깅 이해 {#understanding-email-event-logging}

이메일을 보낼 때 Marketo은 개인의 활동 로그에 다양한 데이터 포인트를 기록합니다. 여기 기본 메뉴가 있습니다

| 이벤트 | 설명 |
|---|---|
| 보냄 | 실제로 전달되었는지 여부에 관계없이 Marketo 서버에서 이메일이 전송될 때마다 기록됩니다. 반송된 이메일은 여전히 &quot;전송됨&quot;으로 기록됩니다. |
| 게재됨 | 수신자 메일 서버가 이메일을 수락할 때마다 기록됩니다. 스팸 필터를 사용하지 않는 것은 아닙니다. 보낸 각 이메일에는 게재가 1개만 있을 수 있습니다. |
| 하드 바운스 | 일부 하드 바운스는 스팸 차단의 결과이므로 캠페인에서 24시간 동안 해당 사용자에게 이메일을 보내려고 하지 않습니다. 존재하지 않는 받은 편지함과 같은 다른 하드 바운스는 영구적이며, 우리는 어떤 캠페인에서든 그 사람에게 다시 이메일을 보내지 않을 것입니다. |
| 소프트 바운스 | 서버 응답이 불분명하거나 사서함이 가득 찼거나 일반적인 서버 문제가 있는 경우 기록됩니다. 향후 배달을 위해 이 직원들에게 24~36시간 동안 재시도 로직을 적용합니다. 이로 인해 해당 사용자가 다른 메일링으로부터 자격을 박탈당하지는 않습니다. |
| 열림 | 수신자가 차단되지 않은 이미지가 있는 이메일을 볼 때 기록됩니다. 이메일, 사용자, 스마트 캠페인당 하나의 열린 이벤트만 기록됩니다. 받은 편지함에서 동일한 이메일을 두 번 열면 두 번 이상 기록되지 않습니다. |
| 클릭됨 | 이메일의 장식된 URL이 브라우저에 로드될 때마다 기록됩니다(링크를 클릭한 결과). 일반적으로 클릭하는 수신자이지만 잘라내기/붙여넣기일 수도 있습니다. |
| 주소 삭제 | 사용자가 이메일의 구독 취소 링크를 클릭하고 구독 취소 양식을 제출하면 기록됩니다. |

>[!CAUTION]
>
>동일한 캠페인에서 동일한 사람에게 동일한 이메일을 두 번 보내는 경우 **열림** 이벤트가 최대 1번 기록됩니다.
