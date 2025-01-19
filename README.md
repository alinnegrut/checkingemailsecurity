<h1>Checking the security of an e-mail account</h1>

<h2>Description</h2>
Within this project, I checked the security level of a personal e-mail account that I'm not using it for daily basis, where I approached the three principles of the CIA triad (Confidentiality, Integrity, Availability).<br />

<h2>Languages and Utilities Used</h2>

- <b>[Password Strength Meter](https://www.passwordmonster.com/)</b> 
- <b>[Yahoo Web services](https://www.yahoo.com/) </b>

<h2>Environments Used </h2>

- <b>Windows 11</b> (10.0.26100)

<h2>Project walk-through:</h2>

<p>
<b><h3>1. Confidentiality analysis:</h3></b>

- Assesing the email account password complexity and uniqueness using [Password Strength Meter](https://www.passwordmonster.com/).<br/>

  Here I introduced the account password in the empty box and generated the following asnwer:<br/>
  
![image](https://github.com/user-attachments/assets/43e488c8-9b41-49a9-84c2-927fb2cead3b)

- Verifying if two-factor authentication (2FA) is enabled to enhance the security of account access. <br/>

  While I checked if the 2FA authentication is enabled I found that is not.<br/>

![image](https://github.com/user-attachments/assets/b6fbe428-feac-44f3-85af-4cdbaa4e6d6b)
  
<b><h3>2. Integrity analysis:</h3></b>

Checking the following source https://help.yahoo.com, I found the next **info:** 

Yahoo Mail using several mechanisms and technologies to safeguard users from viruses, malicious attachments, and other cyberattacks. Below is a detailed evaluation of the key security measures implemented by Yahoo Mail to mitigate these threats:

  <b>- Automatic Attachment Scanning for Viruses</b>
    <p>Yahoo Mail utilizes antivirus software to detect and block malicious attachments before users open them. Whenever you receive or send an email with an attachment, it is automatically scanned for potential threats.</p>

  <b>- Phishing Protection</b>
    <p>Yahoo employs anti-phishing filters designed to identify suspicious emails that attempt to steal personal or financial information. These filters analyze the content and structure of messages to detect phishing indicators, such as suspicious links or deceptive texts.</p>

  <b>- Spam Protection</b>
    <p>Yahoo Mail leverages machine learning-based spam filters to analyze and classify messages as spam or legitimate. The system becomes more effective as it receives more data from users.</p>

  <b>- Email Encryption</b>
    <p>Yahoo uses TLS (Transport Layer Security) encryption to secure communications between servers and user devices, preventing attackers from intercepting data during email transmission.</p>

  <b>- Blocking Dangerous Attachments</b>
    <p>Yahoo Mail automatically blocks executable files (.exe) and other potentially dangerous file types. Restrictions are also applied to certain attachment types to enhance security.</p>

  <b>- Brute-Force Attack Prevention</b>
    <p>Yahoo detects and blocks fraudulent login attempts by limiting the number of failed attempts and monitoring the IP addresses of login attempts.</p>

  <b>- Security Notifications and Account Activity Monitoring</b>
    <p>Yahoo sends alerts when suspicious activity is detected, such as access from unfamiliar locations. Users can review recent activity and take prompt action if any unusual activity is noticed.</p>

- **Analyzing how the email service is protected against viruses and malicious attachments, assessing the level of protection against cyberattacks.**<br/>

![image](https://github.com/user-attachments/assets/06786e3a-aa1f-4ae9-99c4-3aff87766609)
![image](https://github.com/user-attachments/assets/f499b079-3206-4a7b-bbc8-0c3dd19d48d3)
![image](https://github.com/user-attachments/assets/9aa96b96-eccd-4a43-9e7c-842e5faa590d)

- **Evaluating how the email service identifies and blocks spam and phishing messages.**<br/>

![image](https://github.com/user-attachments/assets/3f95265e-a737-44f5-910a-777f9f92e3c8)
![image](https://github.com/user-attachments/assets/536909a7-5f40-40f9-8723-9b537468dca8)
![image](https://github.com/user-attachments/assets/7dde5079-9b92-4cd1-9af1-2e1e771b2d55)
![image](https://github.com/user-attachments/assets/c33be467-6fed-4a0e-9539-35d98564d9d1)
![image](https://github.com/user-attachments/assets/494f5efe-fd51-4194-b226-9ff962acc1d3)

<b><h3>3. Availability analysis:</h3></b>

- Verifying how the email service ensures the accessibility of the account and messages.

While using this email, direct login on the yahoo.com website is one of the access methods.
Other methods for accessing the account and messages include:
<ol>
  <li>Mobile app/smartphone</li>
  <li>Using app-specific passwords for third-party applications like Microsoft Outlook, Mozilla Thunderbird, which allows access to and storage of emails on a workstation.</li>
</ol>

![image](https://github.com/user-attachments/assets/f82fba2d-cc4b-4962-9a61-543511477372)

In case of loss of access to emails, it is possible to export emails by regularly backing them up to a third-party service, such as MailStore Home https://www.mailstore.com/en/products/mailstore-home/. Additionally, in case of loss of access to the email account, a recovery email address and phone number are assigned to the account for data recovery.
![image](https://github.com/user-attachments/assets/29d232d5-cae6-4eb2-b584-2c53c6b6c1a8)

<b><h3>3. Conclusions:</h3></b>

- Confidentiality can be improved by using a stronger password and implementing 2FA.</br>
- The integrity of messages is well protected by built-in scanning and filtering mechanisms, but additional measures, such as avoiding downloading suspicious attachments, are necessary.</br>
- The availability of data and messages can be ensured through regular backups and constant updates of recovery information, so users can access their account in case of emergency.</br>

**Identified weaknesses, such as a weak password, lack of two-step authentication, and manual backup, require improvements to protect the email account against cybersecurity risks.**
