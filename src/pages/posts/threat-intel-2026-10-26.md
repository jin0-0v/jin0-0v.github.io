---
layout: ../../layouts/post.astro
title: "Daily Threat Intel Report - 2026-10-26 "
pubDate: 2026-10-26
author: "AI Summary"
isPinned: false
image:
  src:
  alt:
tags: ["security", "threat-intel", "daily-report"]
---

## Talos Vulnerability Reports

오늘 날짜(2026-10-26)로 게시된 취약점 보고서는 총 2건입니다. 요청하신 형식에 맞춰 정리해 드립니다.

---

**Microsoft Windows Cloud Files Mini Filter Driver CldiStreamCompleteRequest use-after-free vulnerability**
- 링크: https://talosintelligence.com/vulnerability_reports/TALOS-2026-2426
- 요약(한글):
  - Microsoft Windows의 클라우드 파일 미니 필터 드라이버(Cloud Files Mini Filter Driver)에서 Use-After-Free(UAF) 취약점이 발견되었습니다.
  - `CldiStreamCompleteRequest` 함수 내부의 메모리 관리 결함으로 인해 발생하며, CVSS 점수는 8.8(고위험)로 평가되었습니다.
  - 로컬 공격자가 이를 악용할 경우 시스템 권한을 획득하거나 커널 레벨에서 임의 코드를 실행할 위험이 있습니다.
- Summary (English):
  - A use-after-free vulnerability has been identified within the Microsoft Windows Cloud Files Mini Filter Driver.
  - The flaw stems from improper memory handling in the `CldiStreamCompleteRequest` routine, tracked under CVE-2026-58613 with a CVSS score of 8.8.
  - A local attacker could leverage this issue to trigger memory corruption and potentially achieve arbitrary code execution with elevated kernel privileges.

---

**Microsoft Windows Cloud Files Mini Filter Driver CldiStreamPrepareRequestForMoreProcessing Type Confusion vulnerability**
- 링크: https://talosintelligence.com/vulnerability_reports/TALOS-2026-2445
- 요약(한글):
  - Microsoft Windows 클라우드 파일 미니 필터 드라이버에서 타입 혼동(Type Confusion) 취약점이 확인되었습니다.
  - `CldiStreamPrepareRequestForMoreProcessing` 처리 루틴에 존재하며, CVE-2026-80093으로 할당되었고 CVSS 점수는 8.8입니다.
  - 공격자가 이를 악용하여 드라이버가 객체 타입을 잘못 참조하도록 유도함으로써 권한 상승 및 코드 실행 공격을 수행할 수 있습니다.
- Summary (English):
  - A type confusion vulnerability exists in the Microsoft Windows Cloud Files Mini Filter Driver.
  - Disclosed as TALOS-2026-2445 (CVE-2026-80093, CVSS 8.8), the flaw is located in the `CldiStreamPrepareRequestForMoreProcessing` function.
  - Exploitation allows an attacker to misinterpret object types in memory, potentially leading to local privilege escalation and system compromise.

---

