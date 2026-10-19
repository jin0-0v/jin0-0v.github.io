---
layout: ../../layouts/post.astro
title: "Daily Threat Intel Report - 2026-10-19 "
pubDate: 2026-10-19
author: "AI Summary"
isPinned: false
image:
  src:
  alt:
tags: ["security", "threat-intel", "daily-report"]
---

## Talos Vulnerability Reports

**Microsoft Windows Cloud Files Mini Filter Driver CldiStreamCompleteRequest use-after-free vulnerability**
- 링크: https://talosintelligence.com/vulnerability_reports/TALOS-2026-2426
- 요약(한글):
  - Microsoft Windows의 클라우드 파일 미니 필터 드라이버(`cldflt.sys`)에서 Use-After-Free(UAF) 취약점(CVE-2026-58613, CVSS 8.8)이 발견되었습니다.
  - `CldiStreamCompleteRequest` 함수 내부에서 메모리 해제 후 참조 문제가 발생하여 시스템 무결성에 영향을 줄 수 있습니다.
  - 공격자가 이를 악용할 경우 커널 권한 탈취 또는 시스템 충돌을 유발할 수 있어 주의가 요구됩니다.
- Summary (English):
  - A use-after-free vulnerability (CVE-2026-58613, CVSS 8.8) has been identified in the Microsoft Windows Cloud Files Mini Filter Driver.
  - The flaw stems from improper handling of memory objects within the `CldiStreamCompleteRequest` function.
  - A local attacker could leverage this vulnerability to execute arbitrary code with elevated kernel privileges or cause a denial of service.

---

**Microsoft Windows Cloud Files Mini Filter Driver CldiStreamPrepareRequestForMoreProcessing Type Confusion vulnerability**
- 링크: https://talosintelligence.com/vulnerability_reports/TALOS-2026-2445
- 요약(한글):
  - Microsoft Windows 클라우드 파일 미니 필터 드라이버에서 타입 혼동(Type Confusion) 취약점(CVE-2026-80093, CVSS 8.8)이 공개되었습니다.
  - `CldiStreamPrepareRequestForMoreProcessing` 루틴 처리 중 데이터 형식을 잘못 해석하여 발생하는 결함입니다.
  - 조작된 입력을 통해 권한 상승이나 예기치 않은 커널 수준의 메모리 손상을 유발할 위험이 있습니다.
- Summary (English):
  - A high-severity type confusion vulnerability (CVE-2026-80093, CVSS 8.8) exists in the Windows Cloud Files Mini Filter Driver.
  - The issue resides in the `CldiStreamPrepareRequestForMoreProcessing` routine due to improper validation of object types before processing.
  - An attacker could exploit this condition to corrupt kernel memory and potentially escalate privileges on the target system.

---

