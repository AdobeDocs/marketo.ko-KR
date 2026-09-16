---
description: 조직 규칙 이 어떻게 거버넌스 표준을 정의하는지 알아보고 프로그램 생성, 캠페인 계획 및 유효성 검사에 걸쳐 Marketo Engage 동료에게 안내합니다.
title: 조직 규칙
source-git-commit: c1581e2b692dd50bf472756e4e6222ff75ae091c
workflow-type: tm+mt
source-wordcount: '829'
ht-degree: 0%
---
# 조직 규칙 {#organizational-rules}

조직 규칙은 프로그램 생성, 캠페인 계획 및 유효성 검사 워크플로 전반에서 Marketo Engage용 Coworker를 안내하는 단일 문서로 마케팅 운영 표준 및 거버넌스 요구 사항을 정의합니다.

## 조직 규칙이란 무엇입니까? {#what-are-organizational-rules}

조직 규칙은 조직의 캠페인 표준을 캡처하는 Markdown 기반 구성 문서입니다.

* 프로그램, 이메일 및 스마트 캠페인에 대한 이름 지정 규칙
* 필요한 에셋 및 구조(폴더, 토큰, 보고서)
* 준수 요구 사항(구독 취소 링크, UTM 매개 변수, 제외 필터)
* 우수 사례(이메일 디자인, 스마트 목록 구성)

모든 Marketo Engage 환경에는 기본 조직 규칙이 포함되어 있습니다. 조직의 특정 거버넌스 요구 사항을 반영하도록 사용자 지정할 수 있습니다.

## 조직 규칙 사용 위치 {#where-organizational-rules-are-used}

조직 규칙은 다음 세 가지 기술에 대해 Marketo Engage용 동료에게 안내합니다.

| 스킬 | 규칙 적용 방법 |
| --- | --- |
| 프로그램 빌드 | 규칙은 프로그램 구조, 이름 지정 및 초기 설정을 작성하는 데 도움이 됩니다. Marketo Engage용 동료는 프로그램을 만들기 전에 개요 의 모든 준수 문제에 플래그를 지정합니다. |
| 플랜 캠페인 | 규칙은 Marketo Engage용 Coworker가 사용자 표준에 따라 스마트 캠페인, 필터 및 흐름 단계를 구성하는 방법을 알려줍니다. |
| 프로그램 유효성 검사 | 규칙은 활성화 전에 프로그램의 유효성을 검사할 때 Marketo Engage용 동료가 확인하는 내용을 정의합니다. |

## 조직 규칙에 액세스하고 사용자 지정하는 방법 {#how-to-access-and-customize-organizational-rules}

1. 내 Marketo에서 **Marketo Engage용 동료** 타일을 클릭합니다.
1. 톱니바퀴 아이콘을 클릭합니다.
1. **조직 규칙** 탭을 선택합니다.
1. 기본 규칙을 검토합니다(마케팅 작업 모범 사례로 미리 채워져 있음).
1. 조직의 와(과) 일치하도록 규칙을 편집합니다.

   * 이름 지정 규칙(프로그램, 이메일, 캠페인)
   * 필수 폴더 구조
   * 필수 토큰 및 필드
   * 준수 및 제외 표준

1. 변경할 때 버전 번호를 업데이트합니다.
1. 변경 내용을 저장합니다. Marketo Engage 스킬에 대한 모든 동료는 사용자 지정된 규칙을 즉시 사용하게 됩니다.

## 조직 규칙 구조 {#organizational-rules-structure}

조직 규칙은 YAML 프론트맨트로 Markdown으로 포맷됩니다.

```markdown
---
name: Your Organization Name - Marketo Campaign Governance
version: 1.0
enabled: true
customized: true
---

# Naming Conventions

## Programs
- Pattern: {{REGION}}_FY{{YEAR}}_{{QUARTER}}_{{TYPE}}_{{DATE}}_{{NAME}}
- Example: AMER_FY25_Q2_WBR_250315_Product_Launch_Webinar
- Region codes: AMER, EMEA, APAC, GLOBAL

## Emails
- Pattern: {{PROGRAM_NAME}}_{{SEQUENCE}}_{{PURPOSE}}
- Example: Product_Launch_01_Invitation

# Program Structure

## Required Local Folders
- 01 Emails
- 02 Smart Campaigns
- 03 Reports

## Required Tokens
- {{my.eventDate}}
- {{my.replyToEmail}}

# Email Compliance

## Required Elements
- Unsubscribe link in footer
- Company name and physical address
- All external links include UTM parameters

## Recommended Elements
- Alt text on all images
- Mobile-responsive design (600px max-width)
```

## 조직 규칙 모범 사례 {#best-practices-for-organizational-rules}

* **기본값으로 시작**: 사용자 지정하기 전에 기본 규칙을 검토하십시오. 마케팅 운영에 대한 업계 모범 사례를 반영합니다.
* **규칙 집중 유지**: 조직에 관련된 요구 사항만 포함합니다. 불필요한 규칙은 소음을 발생시키고 불필요하게 준수 점수를 줄입니다.
* **자동 및 수동 확인 사용**:

  * 자동 확인: 이름 지정 규칙, 필수 폴더, 토큰 사용(Marketo Engage용 Coworker가 확인할 수 있음)
  * 수동 확인: 이메일 시각적 디자인, 브랜드 준수, 캠페인 논리(Marketo Engage용 동료는 이를 수동 검토 단계로 플래그 지정)

* **엄격함과 유연성 간의 균형 조정**: 너무 엄격한 규칙은 프로그램 생성 속도를 저하시킬 수 있습니다. 너무 느슨한 규칙은 중요한 규정 준수 문제를 포착하지 못합니다.
* **규칙 버전**: 중요 변경 작업을 수행할 때 버전 번호를 업데이트하여 팀에서 거버넌스 표준이 업데이트되었음을 알 수 있도록 합니다.
* **변경 내용 전달**: 조직 규칙을 업데이트할 때 마케팅 운영 팀에 변경 내용과 이유를 알려 주십시오.

## Marketo Engage용 동료가 확인할 수 있는 사항 및 확인할 수 없는 사항 {#what-coworker-can-and-cannot-validate}

Marketo Engage용 Coworker CAN 유효성 검사(자동 검사):

* 명명 규칙은 패턴과 일치합니다
* 필수 폴더 구조가 있음
* 필요한 토큰이 준비되었습니다.
* 이메일에는 구독 취소 링크 및 필수 바닥글 요소가 있습니다.
* 외부 링크에는 UTM 매개 변수가 포함되어 있습니다
* 스마트 캠페인 이름은 규칙을 따릅니다.

Marketo Engage용 동료가 유효성을 검사할 수 없음(수동 검토 필요):

* 스마트 목록 필터 논리(API 제한: 필터를 수동으로 구성해야 함)
* 스마트 캠페인 흐름 단계 논리(API 제한 사항: 흐름을 수동으로 구성해야 함)
* 이메일 시각적 렌더링 및 응답성(시각적 검사 필요)
* 브랜드 준수 및 메시징 톤(사람의 판단 필요)
* 동적 콘텐츠 세분화 규칙(API 제한)

Marketo Engage용 Coworker에 확인할 수 없는 사항이 발생하면 워크플로의 수동 검토 단계로 플래그를 지정합니다.

## 규정 준수 점수 {#compliance-scoring}

프로그램 유효성 검사 를 사용하는 경우 Marketo Engage용 Coworker는 다음을 기반으로 규정 준수 점수를 계산합니다.

* **검사 통과**: Marketo Engage용 Coworker가 준수 여부를 확인했으며 문제를 찾지 못했습니다.
* **확인 실패**: Marketo Engage의 동료가 조직 규칙 위반을 발견했습니다.
* **수동 검토 단계**: 사람 확인이 필요한 항목(점수에 포함되지 않음)

프로그램은 100% 준수할 수 있으며 여전히 수동 검토 단계가 필요합니다. 점수 계산에서 제외됩니다.

## 조직 규칙 사용자 지정의 예 {#examples-of-organizational-rules-customization}

**예 1: 엄격한 명명 규칙**

```markdown
## Programs
Pattern: {{COUNTRY}}-{{BUSINESS_UNIT}}-{{CAMPAIGN_TYPE}}-FY{{YEAR}}-{{QUARTER}}-{{DATE}}
```

지역 및 비즈니스 단위 전반에 걸쳐 엄격한 거버넌스가 필요한 경우 사용합니다.

**예제 2: 필수 접두사를 사용하는 유연한 이름 지정**

```markdown
## Programs
Pattern: {{PREFIX}}_* (where PREFIX = EMEA, AMER, APAC, GLOBAL)
Example: AMER_Q2_Product_Launch_Webinar_2025
```

지역 코드에는 일관성을 유지하고 나머지는 유연성을 유지하려면 이 옵션을 사용합니다.

**예 3: 최소 규칙(준수 집중)**

```markdown
# Email Compliance - REQUIRED

- Unsubscribe link present
- CAN-SPAM physical address in footer
- Reply-to email configured
```

조직이 이름 지정/구조 일관성보다 규정 준수를 우선시하는 경우 사용합니다.

## 문제 해결 {#troubleshooting}

**Q: 조직 규칙을 업데이트했지만 Marketo Engage용 동료가 여전히 이전 규칙을 사용하고 있습니다.**

A: 새 프로그램 및 유효성 검사에 변경 사항이 즉시 적용됩니다. 기존 프로그램에서 작업 중인 경우 브라우저를 새로 고치거나 새 Marketo Engage 공동 작업자 워크플로를 시작하여 업데이트된 규칙을 보십시오.

**Q: 기본 규칙으로 되돌릴 수 있습니까?**

A: 예. **설정** > **조직 규칙**(으)로 이동한 다음 **기본값으로 재설정**&#x200B;을 클릭합니다. 사용자 지정 규칙이 기본 규칙으로 대체됩니다.

**Q: 프로그램이 좋아 보이는데도 내 준수 점수가 낮습니다.**

A: 실패한 검사를 확인합니다. 조직 규칙을 검토하여 현재 워크플로우에 대해 너무 엄격한지 확인하거나 표준에 맞게 프로그램을 조정해야 하는지 확인하십시오.
