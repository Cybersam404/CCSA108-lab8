# CCSA108 Practical Assignment: HTTPS Inspection

Report for CCSA108 HTTPS Inspection (Module 8), Check Point CCSA, ICDFA.

- **Student:** Jegede Samuel Aduragbemi
- **Report:** [CCSA108_Assignment_JegedeSamuel_C11_26_CCSA_17113.pdf](CCSA108_Assignment_JegedeSamuel_C11_26_CCSA_17113.pdf)

## What the report covers

**Part A: Practical tasks**
- Task 1: Planning, using the R82 Release Notes (HTTPS Inspection section).
- Task 2: HTTPS Inspection enabled on A-GW-Cluster with the outbound CA certificate and Full inspection mode. The certificate was exported.
- Task 3: Outbound HTTPS Inspection policy with two rules: Bypass Trusted Site (Financial Services category) and Inspect Outbound.
- Task 4: Policy published and install attempted.
- Task 5: Global Settings reviewed: Fail Mode, Categorization Mode and Server Validations.

**Part B: Theory questions** (multiple choice, short answers and a scenario).

## Environment limitation

Only the management server (A-SMS) was running. The gateway cluster A-GW-Cluster, its members and the log server were not running, and no Internal test host was available. Because of this:
- Installing the policy failed on the gateways, and the result is shown in the report.
- The certificate could not be installed on a test host.
- Tests T1 to T3 were not run. They are marked "Not run" in the report, with the expected results from the brief.

No result is recorded that was not seen.

## Notes
- My instructor named no trusted site, so the bypass rule uses the Financial Services category.
- Passwords and the CA private-key password are not shown anywhere in the report or this repository.

## AI assistance

I used Claude (Anthropic) to help me understand the module, find and check sources, and review the wording. I carried out the lab steps and took the screenshots myself.
