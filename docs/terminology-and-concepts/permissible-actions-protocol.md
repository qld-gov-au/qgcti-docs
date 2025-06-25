# Permissible Actions Protocol (PAP)
## Overview
The Permissible Actions Protocol (PAP) was designed to indicate how received information can be actioned within a recipient's environment. 

Similar to the [Traffic Light Protocol](./traffic-light-protocol.md) it is categorised into a colour coded system. While TLP is for *sharing* information, PAP is for *actioning* information. 

## Levels
| Level | Usage |
|-------|-------|
| <span class="terminology-levels levels-clear">PAP:CLEAR</span> | No restrictions in using this information |
| <span class="terminology-levels levels-green">PAP:GREEN</span> | Active actions allowed. Recipients may use PAP:GREEN information to ping the target, block incoming/outgoing traffic from/to the target, or specifically configure honeypots to interact with the target. |
| <span class="terminology-levels levels-amber">PAP:AMBER</span> | Passive cross check. Recipients may use PAP:AMBER information for conducting online checks, like using services provided by third parties (e.g. VirusTotal), or set up a monitoring honeypot. |
| <span class="terminology-levels levels-red">PAP:RED</span> | Non-detectable actions only. Recipients may not use PAP:RED information on the network. Only passive actions on logs, that are not detectable from the outside. |

## Further Information
For more information on PAP, visit:

- [MISP Taxonomies and Classification as Machine Tags](https://www.misp-project.org/taxonomies.html#_pap) 
