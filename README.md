                                                                                             Phishing Email Analysis – README
1. Obtained a Sample Phishing Email
I collected a phishing email pretending to be from Google Account Support, claiming unusual login activity and requesting account verification.

2. Examined Sender’s Email for Spoofing
I compared the sender address with official Google domains.
The address security-horeply@google-support-a… did not match Google’s legitimate domains, confirming spoofing.

3. Checked Email Headers
I used an online header analyzer (MxToolBox) and found:

Return-Path mismatch
SPF/DKIM/DMARC failures
Unknown routing servers
IP not owned by Google
These showed the email was not legitimately sent.

4. Identified Suspicious Links/Attachments
I inspected the link and attachment without opening them:
Fake link: https://google-security-check.com/verify-user
Suspicious PDF: Google_Security_Verification_Report.pdf
Both were malicious indicators.

5. Detected Urgent/Threatening Language
The email used pressure tactics like:
“Important: Action Required”
“24 hours to verify”
“Restricted access”

6. Found Mismatched URLs
By hovering over the link, I confirmed the displayed text did not match the real URL, which pointed to a fake domain.

7. Noticed Grammar/Spelling Errors
I found errors such as “compleete” and “Plaase,” which are common signs of phishing emails.

8. Summary of Phishing Traits
The email showed:
Spoofed sender
Failed authentication
Fake URLs and malicious attachment
Urgency tactics
Errors in language
Mismatched links

Conclusion

All evidence confirms the email was a phishing attempt designed to steal user credentials.
