\# Threat Hunting Report – Valid Accounts (T1078)



\## Objective

Conduct a proactive threat hunt to identify potential misuse of valid Windows accounts mapped to MITRE ATT\&CK technique T1078 (Valid Accounts).



\## Methodology

Windows authentication events were analyzed using Wazuh. Event IDs 4624 (successful logons), 4625 (failed logons), and 4672 (privileged logon) were reviewed.



\## Findings

Normal authentication activity was observed. No privileged logon events were detected.



\## Conclusion

No evidence of account misuse or privilege escalation was identified. Continuous monitoring is recommended.



