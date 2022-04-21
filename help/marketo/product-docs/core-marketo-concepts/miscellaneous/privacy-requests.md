---
description: 개인 정보 보호 요청 - Marketo 문서 - 제품 설명서
title: 개인 정보 보호 요청
exl-id: ae61eabc-ad8f-4c7b-8097-838e89c1a3ec
source-git-commit: 12b82fdb24b20fde01082ddefe3d78429857f0bc
workflow-type: tm+mt
source-wordcount: '335'
ht-degree: 0%

---

# 개인 정보 보호 요청 {#privacy-requests}

이 문서에서는 Privacy Service UI 및 **Privacy Service API**.

>[!NOTE]
>
>Marketo Engage을 위해 Privacy Service UI 또는 API를 통해 제출된 개인 정보 보호 요청은 Marketo Engage + RT-CDP, B2B 및 B2P 버전을 가진 사용자만 적용됩니다.

다음 두 가지 방법으로 Marketo Engage에서 소비자 데이터에 액세스하거나 삭제하기 위한 개별 요청을 제출할 수 있습니다.

* 사용 [Privacy Service UI](https://privacyui.cloud.adobe.io/). 설명서를 참조하십시오 [여기](https://developer.adobe.com/experience-platform-apis/references/privacy-service/).
* 사용 **Privacy Service API**. 설명서를 참조하십시오 [여기](https://developer.adobe.com/experience-platform-apis/references/privacy-service/) 및 API 참조 [여기](https://www.adobe.io/apis/experiencecloud/gdpr/api-reference.html#!acpdr/swagger-specs/privacy-service.yaml).

다음 [Privacy Service](https://developer.adobe.com/experience-platform-apis/references/privacy-service/) 에서는 두 가지 유형의 요청을 지원합니다. 데이터 액세스 및 데이터 삭제

액세스 및 삭제 요청을 만드는 방법을 살펴보겠습니다.

## Marketo Engage 요청을 전송하기 위한 필수 설정 {#required-setup-to-send-requests-for-marketo-engage}

Marketo Engage에 대한 액세스 및 삭제 데이터를 요청하려면 다음을 수행해야 합니다.

1. 다음을 확인합니다.

   a. IMS 조직 ID<br/>
나. 작업을 수행하려는 사람의 이메일 주소

   IMS 조직 ID는 24자의 영숫자 문자열과 @AdobeOrg. 마케팅 팀이나 내부 Adobe 시스템 관리자가 조직의 IMS 조직 ID를 모르는 경우에는 Adobe 고객 지원 센터(gdprsupport@adobe.com)에 문의하십시오. 개인 정보 API에 요청을 제출하려면 IMS 조직 ID가 필요합니다.

1. Privacy Service에서 액세스 및 삭제 요청을 Marketo Engage에 제출하고 기존 요청의 상태를 확인할 수 있습니다.

## Marketo Engage JSON 요청의 필수 필드 값 {#required-field-values-in-marketo-engage-json-requests}

&quot;companyContexts&quot;:

* &quot;namespace&quot;: **imsOrgID**
* &quot;value&quot;: `<Your IMS Org ID Value>`

&quot;users&quot;:

* &quot;action&quot;: 둘 중 하나 **액세스** 또는 **delete**
* &quot;userIDs&quot;:
   * &quot;namespace&quot;: **이메일**
   * &quot;type&quot;: **standard**
   * &quot;value&quot;: `<Data Subject’s Email Address>`

&quot;include&quot;:

* **marketo** (요청에 적용되는 Adobe 제품)

&quot;regulation&quot;:

* **gdpr**, **ccpa**, **pdpa**, **lgpd_bra**, 또는 **nzpa_nzl**  (요청에 적용되는 개인정보 보호 규정)

## 예 1: GDPR 삭제 요청 {#gdpr-delete-request}

JSON 요청

```text
{
  "companyContexts": [
    {
      "namespace": "imsOrgID",
      "value": "1231659F56A68A8B7F000101@AdobeOrg"
    }
  ],
  "users": [
    {
      "action": [
        "delete"
      ],
      "userIDs": [
        {
          "namespace": "email",
          "type": "standard",
          "value": "john.doe@adobe.com"
        }
      ]
    }
  ],
  "include": [
    "marketo"
  ],
  "regulation": "gdpr",
}
```

JSON 응답

```text
{
  "requestId": "16331241037112570RX-245",
  "totalRecords": 1,
  "jobs": [
    {
      "jobId": "997b01e3-9568-402c-904b-b4e60a437875",
      "customer": {
        "user": {
          "action": [
            "delete"
          ],
          "userIDs": [
            {
              "namespace": "email",
              "value": "john.doe@adobe.com",
              "type": "standard",
              "namespaceId": 6,
              "isDeletedClientSide": false
            }
          ]
        }
      }
    }
  ]
}
```

## 예제 2: CCPA 액세스 요청 {#ccpa-access-request}

JSON 요청

```text
{
  "companyContexts": [
    {
      "namespace": "imsOrgID",
      "value": "1231659F56A68A8B7F000101@AdobeOrg"
    }
  ],
  "users": [
    {
      "action": [
        "access"
      ],
      "userIDs": [
        {
          "namespace": "email",
          "type": "standard",
          "value": "john.doe@adobe.com"
        }
      ]
    }
  ],
  "include": [
    "marketo"
  ],
  "regulation": "ccpa",
}
```

JSON 응답

```text
{
  "requestId": "16329573462631890RX-207",
  "totalRecords": 1,
  "jobs": [
    {
      "jobId": "3115e42d-011b-47ab-a2b0-ed4356af4d3e",
      "customer": {
        "user": {
          "action": [
            "access"
          ],
          "userIDs": [
            {
              "namespace": "email",
              "value": "john.doe@adobe.com",
              "type": "standard",
              "namespaceId": 6,
              "isDeletedClientSide": false
            }
          ]
        }
      }
    }
  ]
}
```

>[!MORELIKETHIS]
>
>[개인 정보 관리](/help/marketo/product-docs/core-marketo-concepts/miscellaneous/privacy-management.md)
