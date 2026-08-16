###### &#x20;**Phishing Email Investigation Report**



&#x20;**1. Executive Summary**



&#x09;A suspicious email was investigated to determine

&#x09;whether it represented a phishing attempt.



&#x20;**2. Email Details**



&#x09;- Subject: Your account will be suspended – Verify immediately

&#x09;- Sender: jonsnoww4545@gmail.com

&#x09;- Recipient: kan\*\*\*\*\*\*\*@gmail.com

&#x09;- Date:Sat, Aug 15, 2026 



&#x20;**3. Header Analysis**



&#x09;- SPF: pass

&#x09;- DKIM:pass

&#x09;- DMARC:pass 

&#x09;- Sender analysis:phishing.



&#x20;**4. URL Analysis**



&#x09;- URL: https://www.instogram.com/accounts/login/

&#x09;- Domain:instogram.com 

&#x09;- Findings: Domain is a typosquat of "instagram.com" ('a' replaced with 'o' — 

&#x20; 			"instogram.com"), a common phishing tactic to trick users. 

&#x20; 			Highly likely malicious/credential-harvesting page.



&#x20;**5. Attachment Analysis**



&#x09;- Attachment: download.pdf.exe

&#x09;- SHA256:  <6a0ca958784190e5ad097109b01adc41e289454a3f335ad8ef6416ef0d5b9411>

&#x09;- Findings:The file uses a double extension



&#x20;**6. Threat Intelligence**



&#x09;- VirusTotal result: - Detection Score: 17/92 security vendors flagged this URL as 

&#x20; 					malicious/phishing/suspicious.

&#x09;- Community Score: 92 (highly suspicious/confirmed malicious by community).

&#x09;- Status: URL and domain flagged as "suspicious" by multiple engines.

&#x09;- Notable detections:

&#x20; 	• Abusix – Phishing

&#x20; 	• ADMINUSLabs – Malicious

&#x20; 	• AlLabs (MONITORAPP) – Phishing

&#x20; 	• BitDefender – Phishing

&#x20; 	• BlockList – Malicious

&#x20; 	• Blueliv – Malicious

&#x20; 	• Chong Lua Dao – Malicious

&#x20; 	• CINS Army – Malicious

&#x09;- Resolved IP Address: 1\*\*.\*\*.\*\*.\*\*

&#x09;- URL auto-redirects from HTTP to HTTPS 

&#x20;	 (http://www.instogram.com → https://www.instogram.com/accounts/login/)



&#x09;- Other findings:- Multiple independent security vendors (across different categories — 

&#x20; 	phishing, malware, blocklist databases) have flagged this domain, 

&#x20; 	indicating high-confidence malicious classification, not a false positive.



**7. IOCs**



&#x09;- Sender:jonsnoww4545@gmail.com

&#x09;- Domain: instogram.com

&#x09;- URL: https://www.instogram.com/accounts/login/

&#x09;- IP: 1\*\*.\*\*.\*\*.\*\*

&#x09;- SHA256: <6a0ca958784190e5ad097109b01adc41e289454a3f335ad8ef6416ef0d5b9411>



&#x20;**8. Risk Assessment**

&#x09; Medium 



**9. Final Verdict**



&#x09;Phishing / Suspicious 

**10. Recommended Actions**



&#x09;1. Block suspicious URL/domain.

&#x09;2. Quarantine similar emails.

&#x09;3. Search for matching IOCs.

&#x09;4. Check whether users interacted with the URL.

&#x09;5. Reset credentials if credentials were submitted.

