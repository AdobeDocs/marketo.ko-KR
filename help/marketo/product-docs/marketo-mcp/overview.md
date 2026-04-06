---
description: 곧 출시 예정
title: MCP 개요 문서
hide: true
hidefromtoc: true
source-git-commit: 62f5166e6a77c8ef50e7c596754205e8f02c6dc7
workflow-type: tm+mt
source-wordcount: '254'
ht-degree: 0%

---

# MCP 개요 문서 {#overview}

다른 사람의 텍스트:

Marketo Engage 공개 MCP Server는 Marketo REST API가 AI 에이전트에 구조화된 도구로 액세스할 수 있도록 하는 클라우드 기반 서비스입니다. MCP(Model Context Protocol)를 기반으로 구축된 이 솔루션은 AI 시스템이 Marketo과 안전하고 효율적으로 상호 작용할 수 있도록 표준화된 스키마 기반 인터페이스를 제공합니다.

Marketo 종단점을 각 애플리케이션에 수동으로 통합하는 대신, MCP 서버는 MCP 호환 에이전트가 사용 가능한 작업을 검색하고 필요한 매개 변수를 이해하며 일관된 프로토콜을 통해 작업을 실행할 수 있는 단일 AI 기반 게이트웨이를 제공합니다.

공개 REST API와 내부 API로 구성된 일련의 도구를 사용할 수 있으며, 이 도구는 UI에서처럼 Marketo 핵심 기능을 수행하지만 API 호출을 수행합니다. 도구가 개발됨에 따라 더 많은 도구가 지속적으로 추가됩니다. &lt;----이 필요합니다.

MCP 서버는 셀프서비스로 제공되며 엔드포인트를 구축하고 연결을 인증함으로써 Adobe IO 프레임워크를 통해 설정할 수 있습니다. 자세한 내용 및 설정 세부 사항을 보려면 Adobe Developer 사이트(여기에 링크 추가)를 방문하십시오. 이거요? https://developer.adobe.com/marketo-apis/

SOAP API로 표시되는 캠페인 도구가 REST API로 변환되고 추가되었습니다.

구성하고 사용 가능한 도구 목록을 보려면 여기(하이퍼링크)의 지침을 따르십시오.

참고: 사용할 수 없는 도구는 &quot;캠페인 비활성화&quot; 및 &quot;정적 목록 삭제&quot;(TBD)입니다.

///////////////////////////////////////////////

## 설정 {#settings}

NAME을 Marketo Engage 계정에 연결하려면 아래 단계를 따르십시오.

1. 내 Marketo에서 **AI로 빌드** 타일을 클릭합니다.

스크린샷

1. 톱니바퀴 아이콘 클릭

인스턴스가 아직 연결되어 있지 않아야 함