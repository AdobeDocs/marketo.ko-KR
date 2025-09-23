---
unique-page-id: 11379928
description: 감사 추적의 변경 세부 정보 - Marketo 문서 - 제품 설명서
title: 감사 추적에서 세부 사항 변경
exl-id: 5583be62-46a6-42f9-b4b3-0df63a171b2d
feature: Audit Trail
source-git-commit: 09a656c3a0d0002edfa1a61b987bff4c1dff33cf
workflow-type: tm+mt
source-wordcount: '1902'
ht-degree: 12%

---

# 감사 추적에서 세부 사항 변경 {#change-details-in-audit-trail}

Audit Trail은 insight 구독에서 어떤 작업을 수행하는지 다양한 Marketo 기능을 제공합니다. 세부사항은 다음과 같습니다.

## 자산 감사 추적 {#asset-audit-trail}

<table>
 <colgroup>
  <col>
  <col>
  <col>
 </colgroup>
 <tbody>
  <tr>
   <th colspan="1">에셋/유형</th>
   <th colspan="1">액션</th>
   <th colspan="1">변경 세부 사항</th>
  </tr>
  <tr>
   <td rowspan="15"><strong>기본 프로그램</strong><br><br><br><br><br><br><br><br><br><br><br></td>
   <td>만들기</td>
   <td>"프로그램 이름"에서 "채널 유형"<br>또는<br>클론된 채널 유형</td>
  </tr>
  <tr>
   <td>이름 바꾸기</td>
   <td>새 이름 "새 이름", 이전 이름 "이전 이름"</td>
  </tr>
  <tr>
   <td>복제</td>
   <td>작업 영역 "작업 영역 이름" <br>위치 "캠페인 폴더" 또는 "참여 프로그램" <br>복제된 프로그램 이름 "새 이름"에 복제됨</td>
  </tr>
  <tr>
   <td>삭제</td>
   <td>N/A</td>
  </tr>
  <tr>
   <td>채널 편집</td>
   <td>새 채널 "새 채널 이름" 이전 채널 "이전 채널 이름" </td>
  </tr>
  <tr>
   <td>프로그램 토큰 수정</td>
   <td>토큰 "토큰 이름" 값 "토큰 값" 추가</td>
  </tr>
  <tr>
   <td>프로그램 토큰 수정</td>
   <td>토큰 "토큰 이름" 편집 새 값 "새 값" 이전 값 "이전 값"</td>
  </tr>
  <tr>
   <td>프로그램 토큰 수정</td>
   <td>토큰 "토큰 이름" 삭제</td>
  </tr>
  <tr>
   <td>프로그램 설정 수정</td>
   <td>Analytics 비헤이비어 "비헤이비어 이름" 추가</td>
  </tr>
  <tr>
   <td>프로그램 설정 수정</td>
   <td><p>Analytics 비헤이비어 "비헤이비어 이름" 편집</p><p>이전 비헤이비어 "비헤이비어 이름"</p></td>
  </tr>
  <tr>
   <td>프로그램 설정 수정</td>
   <td>분석 비헤이비어 "비헤이비어 이름" 삭제</td>
  </tr>
  <tr>
   <td colspan="1">프로그램 설정 수정</td>
   <td colspan="1">기간 비용 값 "#" 프로그램 월 "yyyy-mm" 추가</td>
  </tr>
  <tr>
   <td colspan="1">프로그램 설정 수정</td>
   <td colspan="1">기간 원가 편집 새 원가 값 "#", 새 프로그램 월 "yyyy-mm", 이전 원가 값 "#", 이전 프로그램 월 "yyyy-mm"</td>
  </tr>
  <tr>
   <td colspan="1">프로그램 설정 수정</td>
   <td colspan="1">기간 원가를 삭제합니다. 값 "#" 프로그램 월 "yyyy-mm"</td>
  </tr>
  <tr>
   <td>내보내기</td>
   <td>N/A</td>
  </tr>
  <tr>
   <td rowspan="19"><strong>이메일</strong><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br></td>
   <td>만들기</td>
   <td>템플릿 "템플릿 이름" <br> 또는 "에셋 이름"에서 복제된 <br>을(를) 사용하여 생성됨</td>
  </tr>
  <tr>
   <td>편집</td>
   <td>"이름에서"가 "이름에서 새"로 업데이트됨</td>
  </tr>
  <tr>
   <td>편집</td>
   <td>"From Email"이 "newemail@name.com"로 업데이트되었습니다.</td>
  </tr>
  <tr>
   <td>편집</td>
   <td>"회신 대상"이 "newreplytoemail@name.com"로 업데이트됨</td>
  </tr>
  <tr>
   <td>편집</td>
   <td>"제목"이 "새 제목 줄"로 업데이트됨</td>
  </tr>
  <tr>
   <td>편집</td>
   <td>세그멘테이션 "segmentation_name"이 추가됨</td>
  </tr>
  <tr>
   <td>편집</td>
   <td>세분화 제거됨</td>
  </tr>
  <tr>
   <td>편집</td>
   <td>코드 조각 "snippet_name" 추가됨</td>
  </tr>
  <tr>
   <td>편집</td>
   <td>코드 조각 제거됨</td>
  </tr>
  <tr>
   <td>편집</td>
   <td>템플릿 "template_name"에서 이메일을 편집했습니다(참고: 코드를 직접 편집한 경우 오늘 이 문제가 발생함).</td>
  </tr>
  <tr>
   <td>편집</td>
   <td>새 설명 "new description" 이전 설명 "old description"</td>
  </tr>
  <tr>
   <td>편집</td>
   <td><code>"&lt;module name&gt;" &lt;attribute&gt;</code> 모듈을 "value"로 편집</td>
  </tr>
  <tr>
   <td>삭제</td>
   <td>N/A</td>
  </tr>
  <tr>
   <td>이름 바꾸기</td>
   <td>새 이름 "새 이름", 이전 이름 "이전 이름"</td>
  </tr>
  <tr>
   <td>복제</td>
   <td>"Design studio"에 폴더 "foldername"으로 복제됨 <br>자산 이름 "name"<br>또는<br>프로그램 "program name"<br>자산 이름 "name"(으)로 복제됨</td>
  </tr>
  <tr>
   <td>이동</td>
   <td>"Design studio"로 폴더 "폴더 이름"<br>또는<br>프로그램 "프로그램 이름"으로 "마케팅 활동"으로 이동됨</td>
  </tr>
  <tr>
   <td>승인</td>
   <td>N/A</td>
  </tr>
  <tr>
   <td>승인 취소</td>
   <td>N/A</td>
  </tr>
  <tr>
   <td>초안</td>
   <td>코드 조각 "코드 조각 이름"이 승인되어 이메일이 작성되었습니다.<br>또는<br>템플릿 "템플릿 이름"이 승인되어 이메일이 작성되었습니다.</td>
  </tr>
   <td rowspan="17">이메일 프로그램</td>
   <td>만들기</td>
   <td>"프로그램 이름"에서 "채널 유형"<br>또는<br>클론된 채널 유형</td>
  </tr>
  <tr>
   <td colspan="1">이름 바꾸기</td>
   <td colspan="1">새 이름 "새 이름", 이전 이름 "이전 이름"</td>
  </tr>
  <tr>
   <td>복제</td>
   <td>작업 영역 "작업 영역 이름" <br>위치 "Campaign 폴더 또는 참여 프로그램" <br>복제된 프로그램 이름 "새 이름"에 복제됨</td>
  </tr>
  <tr>
   <td>삭제</td>
   <td>N/A</td>
  </tr>
  <tr>
   <td>중단</td>
   <td>N/A</td>
  </tr>
  <tr>
   <td>채널 편집</td>
   <td>새 채널 "새 채널" 이전 채널 "이전 채널"</td>
  </tr>
  <tr>
   <td>프로그램 토큰 수정</td>
   <td>토큰 "토큰 이름" 값 "토큰 값" 추가</td>
  </tr>
  <tr>
   <td>프로그램 토큰 수정</td>
   <td>토큰 "토큰 이름" 편집 새 값 "새 값" 이전 값 "이전 값"</td>
  </tr>
  <tr>
   <td>프로그램 토큰 수정</td>
   <td>토큰 "토큰 이름" 삭제</td>
  </tr>
  <tr>
   <td>프로그램 일정 수정</td>
   <td>일정을 "시작 날짜, 시작 시간"에 시작하여 "종료 날짜, 종료 시간"까지 종료하도록 설정</td>
  </tr>
  <tr>
   <td>프로그램 일정 수정</td>
   <td>일정을 "새 날짜, 새 시간"으로 변경함</td>
  </tr>
  <tr>
   <td>프로그램 설정 수정</td>
   <td>Analytics 비헤이비어 "비헤이비어 이름" 추가</td>
  </tr>
  <tr>
   <td>프로그램 설정 수정</td>
   <td>Analytics 동작 "동작 이름"<br>이전 동작 "동작 이름" 편집</td>
  </tr>
  <tr>
   <td>프로그램 설정 수정</td>
   <td>분석 비헤이비어 "비헤이비어 이름" 삭제</td>
  </tr>
  <tr>
   <td colspan="1">프로그램 설정 수정</td>
   <td colspan="1">기간 비용 값 "#" 프로그램 월 "yyyy-mm" 추가</td>
  </tr>
  <tr>
   <td colspan="1">프로그램 설정 수정</td>
   <td colspan="1">기간 원가 편집 새 원가 값 "#", 새 프로그램 월 "yyyy-mm", 이전 원가 값 "#", 이전 프로그램 월 "yyyy-mm"</td>
  </tr>
  <tr>
   <td colspan="1">프로그램 설정 수정</td>
   <td colspan="1">기간 원가를 삭제합니다. 값 "#" 프로그램 월 "yyyy-mm"</td>
  </tr>
  <tr>
   <td rowspan="8">이메일 템플릿</td>
   <td>만들기</td>
   <td>비어 있거나 "템플릿 이름"에서 복제됨</td>
  </tr>
  <tr>
   <td>편집</td>
   <td>새 설명 "새 설명", 이전 설명 "이전 설명"</td>
  </tr>
  <tr>
   <td>편집</td>
   <td>HTML 편집됨</td>
  </tr>
  <tr>
   <td>삭제</td>
   <td>N/A</td>
  </tr>
  <tr>
   <td>이름 바꾸기</td>
   <td>새 이름 "새 이름", 이전 이름 "이전 이름"</td>
  </tr>
  <tr>
   <td>복제</td>
   <td>"폴더 이름" <br> 복제된 자산 이름 "이름"으로 복제됨</td>
  </tr>
  <tr>
   <td>승인</td>
   <td>N/A</td>
  </tr>
  <tr>
   <td>승인 취소</td>
   <td>N/A</td>
  </tr>
  <tr>
   <td rowspan="23">참여 프로그램</td>
   <td>만들기</td>
   <td>"프로그램 이름"에서 복제된 채널 유형 "채널 유형"<br> 또는<br></td>
  </tr>
  <tr>
   <td>이름 바꾸기</td>
   <td>새 이름 "새 이름", 이전 이름 "이전 이름"</td>
  </tr>
  <tr>
   <td>복제</td>
   <td>작업 영역 "작업 영역 이름" <br>위치 "Campaign 폴더 또는 참여 프로그램" <br>복제된 프로그램 이름 "새 이름"에 복제됨</td>
  </tr>
  <tr>
   <td>삭제</td>
   <td>N/A</td>
  </tr>
  <tr>
   <td>채널 편집</td>
   <td>새 채널 "새 채널" 이전 채널 "이전 채널"</td>
  </tr>
  <tr>
   <td>프로그램 스트림 수정</td>
   <td><p>스트림 추가</p><p>이름 "name" 배치 "#"</p></td>
  </tr>
  <tr>
   <td>프로그램 스트림 수정</td>
   <td><p>스트림 편집</p><p>새 스트림 이름: "new name" 이전 스트림 이름: "old name"</p><p>새 배치: "new #" 이전 배치: "old #"</p></td>
  </tr>
  <tr>
   <td>프로그램 스트림 수정</td>
   <td>스트림 이름 "name" 삭제</td>
  </tr>
  <tr>
   <td>프로그램 스트림 수정</td>
   <td>콘텐츠 추가<br>Steam 이름 "stream name"<br>Type "Email" or "Program"<br>Name "email name" or "program name"<br>Smart Campaign "smart campaign name"</td>
  </tr>
  <tr>
   <td>프로그램 스트림 수정</td>
   <td>콘텐츠 활성화<br>스트림 이름 "스트림 이름"<br>콘텐츠 이름 "전자 메일 이름" 또는 "프로그램 이름"</td>
  </tr>
  <tr>
   <td>프로그램 스트림 수정</td>
   <td>콘텐츠 비활성화<br>스트림 이름 "스트림 이름"<br>콘텐츠 이름 "전자 메일 이름" 또는 "프로그램 이름"</td>
  </tr>
  <tr>
   <td>프로그램 스트림 수정</td>
   <td>콘텐츠 제거<br>스트림 이름 "스트림 이름"<br>콘텐츠 이름 "전자 메일 이름" 또는 "프로그램 이름"</td>
  </tr>
  <tr>
   <td>프로그램 토큰 수정</td>
   <td>토큰 "토큰 이름" 값 "토큰 값" 추가</td>
  </tr>
  <tr>
   <td>프로그램 토큰 수정</td>
   <td>토큰 "토큰 이름" 편집 새 값 "새 값" 이전 값 "이전 값"</td>
  </tr>
  <tr>
   <td>프로그램 토큰 수정</td>
   <td>토큰 "토큰 이름" 삭제</td>
  </tr>
  <tr>
   <td>프로그램 설정 수정</td>
   <td>Analytics 비헤이비어 "비헤이비어 이름" 추가</td>
  </tr>
  <tr>
   <td>프로그램 설정 수정</td>
   <td>Analytics 동작 "동작 이름"<br>이전 동작 "동작 이름" 편집</td>
  </tr>
  <tr>
   <td>프로그램 설정 수정</td>
   <td>분석 비헤이비어 "비헤이비어 이름" 삭제</td>
  </tr>
  <tr>
   <td>프로그램 설정 수정</td>
   <td>프로그램 상태를 변경합니다. 새 값 "on/off" 이전 값 "off/on"</td>
  </tr>
  <tr>
   <td colspan="1">프로그램 설정 수정</td>
   <td colspan="1">기간 비용 값 "#" 프로그램 월 "yyyy-mm" 추가</td>
  </tr>
  <tr>
   <td colspan="1">프로그램 설정 수정</td>
   <td colspan="1">기간 원가 편집 새 원가 값 "#", 새 프로그램 월 "yyyy-mm", 이전 원가 값 "#", 이전 프로그램 월 "yyyy-mm"</td>
  </tr>
  <tr>
   <td colspan="1">프로그램 설정 수정</td>
   <td colspan="1">기간 원가를 삭제합니다. 값 "#" 프로그램 월 "yyyy-mm"</td>
  </tr>
  <tr>
   <td>내보내기</td>
   <td>N/A</td>
  </tr>
  <tr>
   <td rowspan="18">이벤트 프로그램</td>
   <td>만들기</td>
   <td>"프로그램 이름"에서 "채널 유형"<br>또는<br>클론된 채널 유형</td>
  </tr>
  <tr>
   <td>이름 바꾸기</td>
   <td>새 이름 "새 이름", 이전 이름 "이전 이름"</td>
  </tr>
  <tr>
   <td>삭제</td>
   <td>N/A</td>
  </tr>
  <tr>
   <td>복제</td>
   <td>작업 영역 "작업 영역 이름" <br>위치 "캠페인 폴더" 또는 "참여 프로그램" <br>복제된 프로그램 이름 "새 이름"에 복제됨</td>
  </tr>
  <tr>
   <td>채널 편집</td>
   <td>새 채널 "새 채널" 이전 채널 "이전 채널" </td>
  </tr>
  <tr>
   <td>프로그램 토큰 수정</td>
   <td>토큰 "토큰 이름" 값 "토큰 값" 추가</td>
  </tr>
  <tr>
   <td>프로그램 토큰 수정</td>
   <td>토큰 "토큰 이름" 편집 새 값 "새 값" 이전 값 "이전 값"</td>
  </tr>
  <tr>
   <td>프로그램 토큰 수정</td>
   <td>토큰 "토큰 이름" 삭제</td>
  </tr>
  <tr>
   <td>프로그램 일정 수정</td>
   <td>일정을 "시작 날짜, 시작 시간"에 시작하여 "종료 날짜, 종료 시간"까지 종료하도록 설정</td>
  </tr>
  <tr>
   <td>프로그램 일정 수정</td>
   <td>일정을 "새 날짜, 새 시간"으로 변경함</td>
  </tr>
  <tr>
   <td>프로그램 설정 수정</td>
   <td>Analytics 비헤이비어 "비헤이비어 이름" 추가</td>
  </tr>
  <tr>
   <td>프로그램 설정 수정</td>
   <td>Analytics 동작 "동작 이름"<br>이전 동작 "동작 이름" 편집</td>
  </tr>
  <tr>
   <td>프로그램 설정 수정</td>
   <td>분석 비헤이비어 "비헤이비어 이름" 삭제</td>
  </tr>
  <tr>
   <td colspan="1">프로그램 설정 수정</td>
   <td colspan="1">기간 비용 값 "#" 프로그램 월 "yyyy-mm" 추가</td>
  </tr>
  <tr>
   <td colspan="1">프로그램 설정 수정</td>
   <td colspan="1">기간 원가 편집 새 원가 값 "#", 새 프로그램 월 "yyyy-mm", 이전 원가 값 "#", 이전 프로그램 월 "yyyy-mm"</td>
  </tr>
  <tr>
   <td colspan="1">프로그램 설정 수정</td>
   <td colspan="1">기간 원가를 삭제합니다. 값 "#" 프로그램 월 "yyyy-mm"</td>
  </tr>
  <tr>
   <td colspan="1">프로그램 설정 수정</td>
   <td colspan="1">이벤트 파트너 'partner_name'이(가) 추가되었습니다.</td>
  </tr>
  <tr>
   <td>내보내기</td>
   <td>N/A</td>
  </tr>
  <tr>
   <td rowspan="5">폴더</td>
   <td>만들기</td>
   <td>N/A</td>
  </tr>
  <tr>
   <td>삭제</td>
   <td>N/A</td>
  </tr>
  <tr>
   <td>편집</td>
   <td>토큰 "token_name", 값 "value"가 추가됨</td>
  </tr>
  <tr>
   <td>편집</td>
   <td>토큰 "token_name" 새 값 "token_value" 이전 값 "old_token_value"를 편집했습니다.</td>
  </tr>
  <tr>
   <td>편집</td>
   <td>토큰 "token_name" 삭제됨</td>
  </tr>
  <tr>
   <td rowspan="8">양식</td>
   <td>만들기</td>
   <td>곧 출시 예정 자세히 알아보기 또는 "양식 이름"에서 복제됨</td>
  </tr>
  <tr>
   <td>삭제</td>
   <td>N/A</td>
  </tr>
  <tr>
   <td>이름 바꾸기</td>
   <td>새 이름 "새 이름", 이전 이름 "이전 이름"</td>
  </tr>
  <tr>
   <td>편집</td>
   <td>새 설명 "new description" 이전 설명 "old description"</td>
  </tr>
  <tr>
   <td>편집</td>
   <td>편집된 양식 설정 </td>
  </tr>
  <tr>
   <td>편집</td>
   <td>편집된 필드 세부 정보</td>
  </tr>
  <tr>
   <td>복제</td>
   <td>"Design studio"에 폴더 "foldername"으로 복제됨 <br>자산 이름 "name"<br>또는<br>프로그램 "program name"<br>자산 이름 "name"(으)로 복제됨</td>
  </tr>
  <tr>
   <td>이동</td>
   <td>"Design studio"로 폴더 "폴더 이름"<br>또는<br>프로그램 "프로그램 이름"으로 "마케팅 활동"으로 이동됨</td>
  </tr>
  <tr>
   <td>양식</td>
   <td>승인</td>
   <td># 자산에서 사용됨 </td>
  </tr>
  <tr>
   <td rowspan="9">랜딩 페이지</td>
   <td>만들기</td>
   <td>템플릿 "템플릿 이름" <br> 또는 "에셋 이름"에서 복제된 <br>을(를) 사용하여 생성됨</td>
  </tr>
  <tr>
   <td>삭제</td>
   <td>N/A</td>
  </tr>
  <tr>
   <td>이름 바꾸기</td>
   <td>새 이름 "새 이름", 이전 이름 "이전 이름"</td>
  </tr>
  <tr>
   <td>편집</td>
   <td>새 설명 "새 설명" 이전 "이전 설명"</td>
  </tr>
  <tr>
   <td>편집</td>
   <td>추가된 "이미지", 제거된 "이미지", 편집된 이미지 구성 요소</td>
  </tr>
  <tr>
   <td>편집</td>
   <td>"리치 텍스트"가 추가되고, "리치 텍스트"가 제거되었으며, 리치 텍스트 구성 요소가 편집되었습니다.</td>
  </tr>
  <tr>
   <td>복제</td>
   <td>"Design studio"에 폴더 "foldername"<br>복제된 자산 이름 "name"<br>복제된 자산 URL "www.url.com"<br>또는<br>프로그램 "program name" <br>복제된 자산 이름 "name"<br>복제된 자산 URL "www.url.com"</td>
  </tr>
  <tr>
   <td>이동</td>
   <td>"Design studio"로 폴더 "폴더 이름"<br> 또는 <br>(으)로 이동됨 "마케팅 활동"으로 프로그램 "프로그램 이름"</td>
  </tr>
  <tr>
   <td>승인</td>
   <td>N/A</td>
  </tr>
  <tr>
   <td>초안</td>
   <td>템플릿 "템플릿 이름"이 승인되었으므로 랜딩 페이지가 작성되었습니다.</td>
  </tr>
  <tr>
   <td>승인 취소</td>
   <td>N/A</td>
  </tr>
  <tr>
   <td rowspan="8">랜딩 페이지 템플릿</td>
   <td>만들기</td>
   <td><p>"자산 이름"에서 빈<br>또는<br>복제됨</p></td>
  </tr>
  <tr>
   <td>삭제</td>
   <td>N/A</td>
  </tr>
  <tr>
   <td>이름 바꾸기</td>
   <td>새 이름 "새 이름", 이전 이름 "이전 이름"</td>
  </tr>
  <tr>
   <td>편집</td>
   <td>새 설명 "새 설명" 이전 설명 "이전 설명"</td>
  </tr>
  <tr>
   <td>복제</td>
   <td>"폴더 이름" <br>복제된 자산 이름 "이름"으로 복제됨</td>
  </tr>
  <tr>
   <td>내보내기</td>
   <td>N/A</td>
  </tr>
  <tr>
   <td>승인</td>
   <td># 자산에서 사용됨 </td>
  </tr>
  <tr>
   <td>승인 취소</td>
   <td>N/A</td>
  </tr>
  <tr>
   <td rowspan="5">목록(정적)</td>
   <td>만들기</td>
   <td>N/A</td>
  </tr>
  <tr>
   <td>내보내기</td>
   <td>N/A</td>
  </tr>
  <tr>
   <td>복제</td>
   <td>"Person Database"에 폴더 "foldername" <br>자산 이름 "name"<br>또는<br>프로그램 "프로그램 이름"에 "마케팅 활동"에 복제됨<br>자산 이름 "name" 복제됨</td>
  </tr>
  <tr>
   <td>삭제</td>
   <td>N/A</td>
  </tr>
  <tr>
   <td>이름 바꾸기</td>
   <td>새 이름 "새 이름", 이전 이름 "이전 이름"</td>
  </tr>
  <tr>
   <td rowspan="12">스마트 캠페인</td>
   <td>만들기</td>
   <td>N/A</td>
  </tr>
  <tr>
   <td>활성화</td>
   <td>N/A</td>
  </tr>
  <tr>
   <td>비활성화</td>
   <td>N/A</td>
  </tr>
  <tr>
   <td>중단</td>
   <td>N/A</td>
  </tr>
  <tr>
   <td>이동</td>
   <td>"프로그램"으로 "프로그램 이름"<br>또는<br>폴더로 "폴더"로 "폴더 이름" 폴더로 이동됨</td>
  </tr>
  <tr>
   <td>이름 바꾸기</td>
   <td>새 이름 "새 이름", 이전 이름 "이전 이름"</td>
  </tr>
  <tr>
   <td>편집</td>
   <td>새 설명 "새 설명" 이전 "이전 설명"</td>
  </tr>
  <tr>
   <td>삭제</td>
   <td>N/A</td>
  </tr>
  <tr>
   <td>복제</td>
   <td>"프로그램 이름" <br>자산 이름 "이름"<br>또는<br>폴더 "이름"<br>자산 이름 "이름"에 "폴더"로 복제됨프로그램 "프로그램"에 복제됨</td>
  </tr>
  <tr>
   <td>스마트 목록 설정 수정</td>
   <td>필터 및 트리거의 이름과 값을 포함하여 현재 상태의 스냅숏을 표시합니다.</td>
  </tr>
  <tr>
   <td>캠페인 일정 수정</td>
   <td>N/A</td>
  </tr>
  <tr>
   <td>플로우 단계 작업 수정</td>
   <td>각 흐름 단계의 이름과 값을 포함하여 현재 상태의 스냅숏을 표시합니다.</td>
  </tr>
  <tr>
   <td rowspan="7">스마트 목록</td>
   <td>만들기</td>
   <td>"스마트 목록 이름"에서 복제됨</td>
  </tr>
  <tr>
   <td>내보내기</td>
   <td>N/A</td>
  </tr>
  <tr>
   <td>이름 바꾸기</td>
   <td>새 이름 "새 이름", 이전 이름 "이전 이름"</td>
  </tr>
  <tr>
   <td>편집</td>
   <td>새 설명 "새 설명" 이전 "이전 설명"</td>
  </tr>
  <tr>
   <td>삭제</td>
   <td>N/A</td>
  </tr>
  <tr>
   <td>복제</td>
   <td>"Person Database"에 폴더 "foldername" <br>자산 이름 "name"<br>또는<br>프로그램 "프로그램 이름" <br>자산 이름 "name"(으)로 복제됨</td>
  </tr>
  <tr>
   <td>스마트 목록 설정 수정</td>
   <td>필터 및 트리거의 이름과 값을 포함하여 현재 상태의 스냅숏을 표시합니다. </td>
  </tr>
  <tr>
   <td rowspan="11">스니펫</td>
   <td>만들기</td>
   <td><p>"코드 조각 이름"에서 빈<br>or<br>복제됨</p></td>
  </tr>
  <tr>
   <td>편집</td>
   <td>세그멘테이션 "segmentation_name"이 추가됨</td>
  </tr>
  <tr>
   <td>편집</td>
   <td>세분화 제거됨</td>
  </tr>
  <tr>
   <td>편집</td>
   <td>편집됨</td>
  </tr>
  <tr>
   <td>삭제</td>
   <td>N/A</td>
  </tr>
  <tr>
   <td>이름 바꾸기</td>
   <td>새 이름 "새 이름", 이전 이름 "이전 이름"</td>
  </tr>
  <tr>
   <td>편집</td>
   <td>새 설명 "새 설명" 이전 "이전 설명"</td>
  </tr>
  <tr>
   <td>복제</td>
   <td>"폴더 이름" <br>복제된 코드 조각 이름 "name"에 복제됨</td>
  </tr>
  <tr>
   <td>승인</td>
   <td># 자산에서 사용됨</td>
  </tr>
  <tr>
   <td>초안 없이 승인</td>
   <td>N/A</td>
  </tr>
  <tr>
   <td>승인 취소</td>
   <td><p>N/A</p></td>
  </tr>
 </tbody>
</table>

## 관리자 감사 추적 {#admin-audit-trail}

<table>
 <colgroup>
  <col>
  <col>
  <col>
 </colgroup>
 <tbody>
  <tr>
   <th>관리 영역</th>
   <th>액션</th>
   <th>변경 세부 사항</th>
  </tr>
  <tr>
   <td>IP 제한 사항</td>
   <td>편집</td>
   <td>허용/차단된 "블록", IP 주소 "#", 비활성화된 IP 제한 ""에 대한 IP 제한 사항이 편집되었습니다.</td>
  </tr>
  <tr>
   <td rowspan="2">파티션</td>
   <td>만들기</td>
   <td>파티션 이름이 "partition name"인 파티션 생성됨</td>
  </tr>
  <tr>
   <td>삭제</td>
   <td>"partition name" 파티션 삭제됨</td>
  </tr>
  <tr>
   <td>암호 보안 수준</td>
   <td>편집</td>
   <td>암호 보안이 템플릿으로 변경됨: 표준 보안, 최소 길이: #, 소문자: #, 숫자: #, 혼합 사례: # , 만료 : #, 세션 시간 초과: #</td>
  </tr>
  <tr>
   <td rowspan="3">역할<br><br></td>
   <td>만들기</td>
   <td>역할 이름이 "역할 이름"으로 만들어진 역할(참고: 추가된 권한에 대한 세부 정보가 필요한 경우 지원 팀에 문의하십시오.) - <br>역할에 할당된 권한의 스냅숏을 표시합니다.</td>
  </tr>
  <tr>
   <td>삭제</td>
   <td>"역할 이름" 역할이 삭제되었습니다.</td>
  </tr>
  <tr>
   <td>편집</td>
   <td>역할이 "이전 이름"에서 "새 이름"으로 편집되었습니다(참고: 편집된 권한에 대한 세부 정보가 필요한 경우 지원팀에 문의하십시오). - <br>역할에 할당된 권한의 스냅숏을 표시합니다.<br></td>
  </tr>
  <tr>
   <td>Smartlist 보고서</td>
   <td>편집</td>
   <td>다운로드하기 위해 로그인하기 위해 편집된 SmarList: "true 또는 false"</td>
  </tr>
  <tr>
   <td rowspan="7">사용자<br><br><br><br></td>
   <td>만들기(초대)</td>
   <td>초대된 사용자: 이메일 "이메일 주소", 이름 "이름과 성", 액세스 만료 "비어 있거나 날짜가 있음", API 사용자 "참 또는 거짓" - <br>사용자에게 할당된 역할 및 작업 영역의 스냅숏을 표시합니다.</td>
  </tr>
  <tr>
   <td colspan="1">삭제</td>
   <td colspan="1">"user name" 사용자가 삭제됨</td>
  </tr>
  <tr>
   <td>편집</td>
   <td>사용자의 이름이 "이전 이름"에서 "새 이름"으로 변경되었습니다. 이메일: "email", apiUser: "true 또는 false" 액세스 만료: "blank 또는 date"</td>
  </tr>
  <tr>
   <td>편집</td>
   <td>사용자가 이메일: "email", apiUser: "true or false", 액세스 만료: "blank or with date"에 대해 편집되었습니다.</td>
  </tr>
  <tr>
   <td colspan="1">편집</td>
   <td colspan="1">사용자에게 할당된 역할 및 작업 영역을 포함하여 현재 상태의 스냅샷을 표시합니다.</td>
  </tr>
  <tr>
   <td>문제</td>
   <td>이메일: "사용자 이메일" 이름: "사용자 이름"에 발급된 캘린더 라이선스</td>
  </tr>
  <tr>
   <td>재설정</td>
   <td>이름 "name" 및 이메일 "email"에 대한 암호 재설정</td>
  </tr>
  <tr>
   <td rowspan="2">작업 영역</td>
   <td>만들기</td>
   <td>Workspace이 "workspace name"(으)로 생성됨</td>
  </tr>
  <tr>
   <td>삭제</td>
   <td>"workspace name" 작업 영역 삭제됨</td>
  </tr>
 </tbody>
</table>

>[!MORELIKETHIS]
>
>[감사 추적에서 필터링](/help/marketo/product-docs/administration/audit-trail/filtering-in-audit-trail.md)
