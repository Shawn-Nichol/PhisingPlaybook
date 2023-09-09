# Email Analysis Playbook

Emails consist of two main parts: the header and the body. Analyzing both can reveal crucial information about the email's origin and potential threats.

## Email Header Analysis

The email header contains essential information about the email's journey:

### Key Elements to Examine in the Header

1. **From:** Check the sender's email address. Ensure it matches the expected sender.

2. **Subject:** Review the email subject line. Be cautious of suspicious or urgent subjects.

3. **Date:** Note the date when the email was sent. Anomalies in timestamps can be suspicious.

4. **To:** Verify the recipient's email address.

5. **Originating-IP:** Look for the IP address from which the email was sent. Cross-check with known IP addresses of legitimate senders.

6. **SMTP.maliform/header.form:** Examine the domain the email was sent from. Be cautious of irregular or misspelled domains.

7. **Reply-To:** Check if a different email address is specified for replies. This may indicate an attempt to divert responses.

### How to View Email Header Information

To access the header information, view the email in raw data format, [Here's a guide](https://mediatemple.zendesk.com/hc/en-us/articles/204644060-how-do-i-view-email-headers-for-a-message) on how to do it in various email platforms.

### Tools for Header Analysis

- [Google Messageheader Tool](https://toolbox.googleapps.com/apps/messageheader/analyzeheader)
- [Message Header Analyzer](https://mha.azurewebsites.net/)
- [Mailheader.org](https://mailheader.org/)

### IP and URL Analysis

- Use [ipinfo.io](https://ipinfo.io/) to gather information about IP addresses.
- [urlscan.io](https://urlscan.io/) helps scan URLs for potential threats.
- Tools like [CyberChef](https://gchq.github.io/CyberChef/) can be handy for URL extraction.

### URL Reputation Check

- [Talos Intelligence](https://talosintelligence.com/talos_file_reputation)
- [VirusTotal](https://www.virustotal.com/gui/home/upload)

### Attachment Analysis

- For attachment analysis, consider services like [Any.Run](https://app.any.run/) and [Joe Security](https://www.joesecurity.org/).



## Email Body Analysis

In the email body, focus on:

- **URL Links:** Check for suspicious or unexpected links within the email content.

- **Attachment Details:** Note the attachment's name and the attachment's hash value for further investigation.

  
## Automation

For efficient analysis, consider using automation tools like [PhishTool](https://www.phishtool.com/), which can streamline the process of header analysis, URL checking, and attachment examination.

Remember that phishing attacks often rely on social engineering tactics, so always exercise caution and verify the authenticity of emails, especially if they contain unexpected attachments or links.

By following these guidelines and using the provided tools, you can enhance your ability to identify and mitigate potential email threats effectively. Stay vigilant to protect yourself and your organization from email-based attacks.
