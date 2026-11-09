---
layout: ../../layouts/post.astro
title: "Daily Threat Intel Report - 2026-11-09 "
pubDate: 2026-11-09
author: "AI Summary"
isPinned: false
image:
  src:
  alt:
tags: ["security", "threat-intel", "daily-report"]
---

## Talos Vulnerability Reports

오늘 날짜(2026-11-09)로 게시된 취약점 보고서는 총 2건입니다.

---

**[Microsoft Windows Cloud Files Mini Filter Driver CldiStreamCompleteRequest use-after-free vulnerability]**
- 링크: https://talosintelligence.com/vulnerability_reports/TALOS-2026-2426
- 요약(한글):
  - Microsoft Windows 클라우드 파일 미니필터 드라이버(Cloud Files Mini Filter Driver)의 `CldiStreamCompleteRequest` 함수에서 UAF(Use-After-Free) 취약점이 발견되었습니다.
  - 해당 결함은 CVE-2026-58613으로 지정되었으며, CVSS 점수는 8.8(High)입니다.
  - 공격자가 이를 악용할 경우 시스템 권한 상승이나 임의 코드 실행 등의 심각한 보안 위협을 초래할 수 있습니다.
- Summary (English):
  - A use-after-free vulnerability exists within the `CldiStreamCompleteRequest` function of the Microsoft Windows Cloud Files Mini Filter Driver.
  - Tracked as CVE-2026-58613, this high-severity flaw carries a CVSS score of 8.8.
  - Successful exploitation could allow an attacker to execute arbitrary code or escalate privileges within the affected Windows system.

---

**[Microsoft Windows Cloud Files Mini Filter Driver CldiStreamPrepareRequestForMoreProcessing Type Confusion vulnerability]**
- 링크: https://talosintelligence.com/vulnerability_reports/TALOS-2026-2445
- 요약(한글):
  - Microsoft Windows 클라우드 파일 미니필터 드라이버의 `CldiStreamPrepareRequestForMoreProcessing` 함수에서 타입 혼동(Type Confusion) 취약점이 확인되었습니다.
  - 이 취약점은 CVE-2026-80093으로 할당되었으며, CVSS 점수 8.8(High)을 기록했습니다.
  - 조작된 입력을 통해 드라이버가 객체 타입을 잘못 해석하도록 유도함으로써 시스템 보안 경계를 침해할 수 있습니다.
- Summary (English):
  - A type confusion flaw was identified in the `CldiStreamPrepareRequestForMoreProcessing` function of the Microsoft Windows Cloud Files Mini Filter Driver.
  - Registered as CVE-2026-80093, this security vulnerability holds a CVSS score of 8.8.
  - Exploitation may enable threat actors to break type safety in kernel-level routines, potentially leading to privilege escalation.

---

