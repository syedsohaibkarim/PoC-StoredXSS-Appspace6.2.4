# PoC-StoredXSS-Appspace6.2.4
Stored XSS throughout the portal.

Description. Stored Cross-site Scripting (XSS) vulnerability is one of OWASP Top-10 and it happens when the payload is saved with accepting special characters. It is identified that application is accepting special characters throughout the application and in forms. Even after escalating to Administrative Console, the application is showing the reflection as well.

Severity. High

For POC, selected Vulnerable Parameter. 'Application'  Reflection can be seen at <URL>/medianet/sgcontentset.aspx (Application Tab --> Application Content Set)
