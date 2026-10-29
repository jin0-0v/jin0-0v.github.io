---
layout: ../../layouts/post.astro
title: "Daily Threat Intel Report - 2026-10-29 "
pubDate: 2026-10-29
author: "AI Summary"
isPinned: false
image:
  src:
  alt:
tags: ["security", "threat-intel", "daily-report"]
---

## Cisco Talos Blog

오늘 신규 게시물 없음 / No new posts today (가장 최근 글 / Latest: Inside KeyDrift: Analyzing historical UAT-11473 activity on Cisco SD-WAN, October 28, 2026)

---

## Talos Vulnerability Reports

2026년 10월 29일 자로 게시된 취약점 보고서는 총 5건입니다. 각 보고서의 정리 내용은 다음과 같습니다.

---

**Microsoft Windows Cloud Files Mini Filter Driver CldiStreamCompleteRequest use-after-free vulnerability**
- 링크: https://talosintelligence.com/vulnerability_reports/TALOS-2026-2426
- 요약(한글):
  - Microsoft Windows의 Cloud Files Mini Filter 드라이버 내 `CldiStreamCompleteRequest` 함수에서 UAF(Use-After-Free) 취약점이 발견되었습니다.
  - 공격자가 조작된 요청을 통해 해제된 메모리에 접근함으로써 임의 코드 실행이나 시스템 불안정을 유발할 수 있습니다.
  - 심각도 CVSS 점수는 8.8로 평가되었으며 관련 식별자는 CVE-2026-58613입니다.
- Summary (English):
  - A use-after-free vulnerability exists in the Microsoft Windows Cloud Files Mini Filter Driver via the `CldiStreamCompleteRequest` function.
  - An attacker could exploit this flaw by issuing crafted requests to access previously freed memory, potentially leading to privilege escalation or system crashes.
  - This vulnerability is tracked as CVE-2026-58613 with a CVSS score of 8.8.

---

**Microsoft Windows Cloud Files Mini Filter Driver CldiStreamPrepareRequestForMoreProcessing Type Confusion vulnerability**
- 링크: https://talosintelligence.com/vulnerability_reports/TALOS-2026-2445
- 요약(한글):
  - Windows Cloud Files Mini Filter 드라이버의 `CldiStreamPrepareRequestForMoreProcessing` 구성 요소에 타입 혼동(Type Confusion) 취약점이 존재합니다.
  - 부적절한 데이터 타입 처리로 인해 공격자가 메모리 무결성을 훼손하거나 권한 상승을 시도할 수 있습니다.
  - CVSS 8.8의 높은 위험도를 가지며 CVE-2026-80093으로 분류되었습니다.
- Summary (English):
  - A type confusion flaw was identified within the `CldiStreamPrepareRequestForMoreProcessing` routine of the Microsoft Windows Cloud Files Mini Filter Driver.
  - Improper handling of internal data structures allows attackers to trigger memory corruption, paving the way for potential local privilege escalation.
  - The security issue carries a CVSS score of 8.8 and is designated as CVE-2026-80093.

---

**frangoteam FUXA /api/runscript authorization bypass vulnerability**
- 링크: https://talosintelligence.com/vulnerability_reports/TALOS-2026-2417
- 요약(한글):
  - 웹 기반 SCADA/HMI 대시보드 플랫폼인 frangoteam FUXA의 `/api/runscript` 엔드포인트에서 권한 우회 취약점이 확인되었습니다.
  - 불충분한 접근 제어로 인해 비인가 사용자가 제한된 스크립트 실행 기능을 호출할 수 있습니다.
  - CVSS 점수는 5.6이며 CVE-2026-42949로 추적됩니다.
- Summary (English):
  - An authorization bypass vulnerability has been uncovered in frangoteam FUXA's `/api/runscript` API endpoint.
  - Due to inadequate access control checks, unauthorized users can invoke restricted script execution routines.
  - Tracked as CVE-2026-42949, this flaw holds a CVSS severity

---

