# PHP2Shell Resources
## Overview
On 22 October 2026, **CVE-2026-109618** (remote code execution via out-of-memory corruption) and **CVE-2026-109619** (remote code execution via stale global state), two critical vulnerabilities in PHP, were disclosed to the public. Queensland Government Cyber Threat Intelligence (QGCTI) is collating a list of resources to assist Queensland Government entities in their response efforts. 

For further information, guidance, and recommendations, please see the recent alert issued by QGCTI, AL26-023. 

This page will be updated as new resources are available.

## PHP Releases
- Security Advisory: [PHP Security Advisory](https://www.php.net/index.php)
- Fixed Releases: [PHP Downloads](https://www.php.net/downloads.php?source=Y)
- CVE-2026-109619 Technical Write-Up: [GHSA-w8hw-w9fx-j79w](https://github.com/php/php-src/security/advisories/GHSA-w8hw-w9fx-j79w)
- CVE-2026-109618 Technical Write-Up: [GHSA-6wmf-4rv5-p3rp](https://github.com/php/php-src/security/advisories/GHSA-6wmf-4rv5-p3rp)

## Initial Disclosure
- Dedicated Website: [PHP2Shell](https://www.php2shell.com/)
- Wiz: [PHP2Shell: AI uncovers critical RCE vulnerabilities affecting 70% of the Internet | Wiz Blog](https://www.wiz.io/blog/php2shell-php-rce)
- Calif: [php2shell by Calif Research](https://calif.io/php2shell/)
- OpenAI: [Patch the Planet: global response coordination as agents uncover critical vulnerabilities](https://openai.com/index/coordinated-disclosure-of-critical-vulnerabilities/)
- CrowdStrike: [CrowdStrike Protects Customers from Threats Delivered via PHP2Shell](https://www.crowdstrike.com/en-us/blog/crowdstrike-protects-customers-from-php-rce-zero-days/)

## Detections
- Talos Snort Rules:[Network Intrusion Detection & Prevention System](https://snort.org/advisories/talos-rules-2026-10-21)
- CoreLight Zeek and Suricata Detections: [php2shell: Zeek and Suricata Detections for PHP RCE](https://corelight.com/blog/php2shell-detection-before-disclosure)
- ikow php2shell-poc Detections: [php2shell-poc/detection at main · ikow/php2shell-poc](https://github.com/ikow/php2shell-poc/tree/main/detection)
- NCSC-NL: [php2shell/detection_mitigation at main · NCSC-NL/php2shell](https://github.com/NCSC-NL/php2shell/tree/main/detection_mitigation)
- Abstract Security Detection Guidance: [PHP2Shell: Critical PHP RCE Vulnerabilities CVE-2026-109618 and CVE-2026-109619](https://www.abstract.security/blog/php2shell-critical-php-rce-vulnerabilities-cve-2026-109618-and-cve-2026-109619)

## Vendor Advisories
- Cisco: [Cisco Security Advisory: Vulnerabilities in PHP Affecting Cisco Products: October 2026](https://sec.cloudapps.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-php-october26-Jj384Daq)
- F5: [K000163821: PHP vulnerabilities CVE-2026-109618 and CVE-2026-109619](https://my.f5.com/manage/s/article/K000163821)
- Palo Alto: [CVE-2026-109618 Impact of Critical Vulnerabilities in PHP (CVE-2026-109618, CVE-2026-109619) on Palo Alto Networks Products](https://security.paloaltonetworks.com/CVE-2026-109618)
- CloudFlare: [Cloudflare deploys protections against php2shell vulnerability](https://blog.cloudflare.com/php-vulnerabilities-waf-protection/#update-php-and-keep-the-protection-enabled)
- Imperva: [PHP2Shell: When PHP Runs Out of Memory at the Wrong Moment](https://www.imperva.com/blog/php2shell-vulnerability-updates/)
- AWS: [PHP web runtimes \(CVE-2026-109618 and CVE-2026-109619\)](https://aws.amazon.com/security/security-bulletins/2026-143-aws/)
- RedHat: [RHSB-2026-013 Request handling memory corruption - php \(CVE-2026-109618, CVE-2026-109619\) - "php2shell" | Red Hat Customer Portal](https://access.redhat.com/security/vulnerabilities/RHSB-2026-013)
- Ubuntu: [php2shell \(CVE-2026-109618 and CVE-2026-109619\) – PHP critical vulnerability fixes available](https://ubuntu.com/blog/php2shell-vulnerability-fixes-available)
- Debian: [[SECURITY] [DSA 6574-1] php8.4 security update](https://lists.debian.org/debian-security-announce/2026/msg00489.html?pow_referer=)
- CheckPoint: [CPAI-2026-15172](https://advisories.checkpoint.com/defense/advisories/public/2026/cpai-2026-15172.html)
- Sophos: [Advisory: PHP2Shell Vulnerabilities \(CVE-2026-109618, CVE-2026-109619\)](https://www.sophos.com/en-us/security-advisories/sophos-sa-20261021-php2shell)
- Microsoft: [Addressing PHP2Shell CVE-2026-109618 and CVE-2026-109619: upgrade guidance and Azure WAF mitigations | Microsoft Community Hub](https://techcommunity.microsoft.com/blog/azurenetworksecurityblog/addressing-php2shell-cve-2026-109618-and-cve-2026-109619-upgrade-guidance-and-az/4566623)
- cPanel: [138 Change Log | cPanel & WHM Documentation](https://docs.cpanel.net/changelogs/138-change-log/)
- Netgate (PfSense): [Critical PHP Security Update](https://forum.netgate.com/topic/201565/critical-php-security-update)
- OpnSense: [OPNsense \(@opnsense\) 312 likes · 16 replies](https://x.com/opnsense/status/2112985458514756087)
- Citrix: [Protecting NetScaler Management Access from PHP CVE-2026-109618 & CVE 2026-109619](https://community.citrix.com/techzone-blogs/110_security-updates/protecting-netscaler-management-access-from-php-cve-2026-109618-cve-2026-109619-r1640/)
- Rapid7: [CVE-2026-109618 and CVE-2026-109619: Critical Unauthenticated Remote Code Execution in PHP](https://www.rapid7.com/blog/post/etr-cve-2026-109618-and-cve-2026-109619-critical-unauthenticated-remote-code-execution-in-php/)
- Akamai: [Critical Remote Code Execution Vulnerabilities in PHP Core](https://www.akamai.com/blog/security-research/critical-remote-code-execution-vulnerabilities-php-core)
- Google Cloud: [Responding to core PHP vulnerabilities CVE-2026-109618 and CVE-2026-109619 | Google Cloud Blog](https://cloud.google.com/blog/products/identity-security/responding-to-core-php-vulnerabilities-cve-2026-109618-cve-2026-109619/)
- Fortinet: [FG-IR-26-186](https://fortiguard.fortinet.com/psirt/FG-IR-26-186#:~:text=Fortinet%20PSIRT%20is,Fortinet%20Products)
- ZScaler: [CVE-2026-109618 and CVE-2026-109619: PHP2Shell | ThreatLabz](https://www.zscaler.com/blogs/security-research/cve-2026-109618-and-cve-2026-109619-php-vulnerable-unauthenticated-rce)
- Qualys: [PHP2Shell: PHP Patches Two Critical RCE Vulnerabilities, Urges Immediate Updates](https://blog.qualys.com/vulnerabilities-threat-research/2026/10/20/php-announces-critical-security-release-for-two-vulnerabilities)
- Horizon3.ai: [CVE-2026-109618 / CVE-2026-109619](https://horizon3.ai/attack-research/vulnerabilities/cve-2026-109618-cve-2026-109619/)

## Government Advisories
- CCCS: [AL26-026 - Critical vulnerabilities impacting PHP - CVE-2026-109618 and CVE-2026-109619 - Canadian Centre for Cyber Security](https://www.cyber.gc.ca/en/alerts-advisories/al26-026-critical-vulnerabilities-impacting-php-cve-2026-109618-cve-2026-109619)
- ASD: [Critical vulnerabilities in PHP](https://www.cyber.gov.au/alert/critical-vulnerabilities-in-php?ref=search)
- NCSC: [Critical security issue affecting PHP](https://www.ncsc.gov.uk/news/critical-security-issue-affecting-php)
- CISA: [Critical Vulnerabilities in PHP Require Immediate Patching](https://www.cisa.gov/news-events/alerts/2026/10/21/critical-vulnerabilities-php-require-immediate-patching)
- CERT-EU: [Critical Vulnerabilities in PHP](https://cert.europa.eu/publications/security-advisories/2026-018/)
- CIRCL: [TR-102 Critical Remote Code Execution Vulnerabilities in PHP - CVE-2026-109618 and CVE-2026-109619](https://www.circl.lu/pub/tr-102/)

## Research
- Datadog: [PHP2Shell - Critical vulnerabilities in PHP (CVE-2026-109618, CVE-2026-109619): detection, analysis, and remediation](https://securitylabs.datadoghq.com/articles/php2shell-critical-vulnerabilities-in-php/)
- SANS ISC: [Critical PHP Vulnerability (CVE-2026-109618, CVE-2026-109619) [infocon yellow]](https://isc.sans.edu/diary/rss/33440)

## Proof of Concept Code
- ikon php2shell: [ikow/php2shell-poc: CVE-2026-109618/109619 PHP session.upload_progress Exploit Research — POC & Analysis](https://github.com/ikow/php2shell-poc/tree/main)
- blasty: [blasty/php-8.5.4-apache-uaf-poc: Private Dockerized PHP 8.5.4 Apache session upload-progress UAF research PoC](https://github.com/blasty/php-8.5.4-apache-uaf-poc)
- Zero061: [php2shell — PHP 8.4.26 session vulnerability reproduction](https://github.com/Zer061/CVE-2026-109618)

## Misc
- PHP Version Checker for Codex: [openai/php2shell-checker](https://github.com/openai/php2shell-checker)
- CVE-2026-109618: [CVE-2026-109618](https://www.cve.org/CVERecord?id=CVE-2026-109618)
- CVE-2026-109619: [CVE-2026-109619](https://www.cve.org/CVERecord?id=CVE-2026-109619)
- NCSC-NL Affected Software List: [NCSC-NL GitHub](https://github.com/NCSC-NL/php2shell/tree/main/software)
