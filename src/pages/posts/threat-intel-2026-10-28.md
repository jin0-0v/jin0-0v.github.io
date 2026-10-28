---
layout: ../../layouts/post.astro
title: "Daily Threat Intel Report - 2026-10-28 "
pubDate: 2026-10-28
author: "AI Summary"
isPinned: false
image:
  src:
  alt:
tags: ["security", "threat-intel", "daily-report"]
---

## Cisco Talos Blog

오늘 신규 게시물 없음 / No new posts today (가장 최근 글 / Latest: From federal SOCs to Talos: Ryan Fetterman on practical security research, October 27, 2026)

---

## Talos Vulnerability Reports

오늘 날짜(2026-10-28)로 게시된 취약점 보고서는 총 2건입니다.

---

**Microsoft Windows Cloud Files Mini Filter Driver CldiStreamCompleteRequest use-after-free vulnerability**
- 링크: https://talosintelligence.com/vulnerability_reports/TALOS-2026-2426
- 요약(한글):
  - Microsoft Windows의 Cloud Files Mini Filter 드라이버 내 `CldiStreamCompleteRequest` 함수에서 발생하는 Use-After-Free(UAF) 취약점입니다 (CVE-2026-58613).
  - 해당 취약점은 CVSS 8.8의 높은 심각도를 가지며, 메모리 손상을 유발할 수 있습니다.
  - 공격자가 이를 악용할 경우 시스템 권한 상승이나 임의 코드 실행으로 이어질 수 있습니다.
- Summary (English):
  - Cisco Talos disclosed a high-severity Use-After-Free flaw (CVE-2026-58613, CVSS 8.8) in Microsoft Windows Cloud Files Mini Filter Driver.
  - The vulnerability specifically resides within the `CldiStreamCompleteRequest` routine, leading to memory corruption under certain conditions.
  - An attacker could potentially leverage this flaw to execute arbitrary code or escalate privileges on the target Windows system.

---

**Microsoft Windows Cloud Files Mini Filter Driver CldiStreamPrepareRequestForMoreProcessing Type Confusion vulnerability**
- 링크: https://talosintelligence.com/vulnerability_reports/TALOS-2026-2445
- 요약(한글):
  - Microsoft Windows Cloud Files Mini Filter 드라이버의 `CldiStreamPrepareRequestForMoreProcessing` 함수에서 타입 혼동(Type Confusion) 취약점이 발견되었습니다 (CVE-2026-80093).
  - CVSS 점수 8.8로 평가된 고위험군 취약점으로 보고되었습니다.
  - 악용 시 드라이버 컨텍스트 내에서 비정상적인 메모리 접근을 유발하여 권한 상승 등을 시도할 수 있습니다.
- Summary (English):
  - A Type Confusion vulnerability (CVE-2026-80093) has been identified in the `CldiStreamPrepareRequestForMoreProcessing` function of Windows Cloud Files Mini Filter Driver.
  - Assigned a CVSS score of 8.8, this flaw allows attackers to trigger improper memory handling within kernel-mode drivers.
  - Successful exploitation can destabilize the operating system and potentially result in elevated privilege execution.

---

