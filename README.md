# Zed Attack Proxy Cookbook

<a href="https://www.packtpub.com/product/zed-attack-proxy-cookbook/9781801817332?utm_source=github&utm_medium=repository&utm_campaign=9781801817332"><img src="https://static.packt-cdn.com/products/9781801817332/cover/smaller" alt="Zed Attack Proxy Cookbook" height="256px" align="right"></a>

This is the code repository for [Zed Attack Proxy Cookbook](https://www.packtpub.com/product/zed-attack-proxy-cookbook/9781801817332?utm_source=github&utm_medium=repository&utm_campaign=9781801817332), published by Packt.

**Hacking tactics, techniques, and procedures for testing web applications and APIs**

## What is this book about?
Security is an ever-changing, fast-paced discipline. Thankfully, there are free tools that you can use to protect your systems. OWASP Zed Attack Proxy (ZAP) is the most popular one: it allows you to test for vulnerabilities and exploits with the same functionality as a licensed tool! But how does it work?

This book covers the following exciting features:
* Install ZAP on different operating systems or environments
* Explore how to crawl, passively scan, and actively scan web apps
* Discover authentication and authorization exploits
* Conduct client-side testing by examining business logic flaws
* Use the BOAST server to conduct out-of-band attacks
* Understand the integration of ZAP into the final stages of a CI/CD pipeline

If you feel this book is for you, get your [copy](https://www.amazon.com/dp/1801817332) today!

<a href="https://www.packtpub.com/?utm_source=github&utm_medium=banner&utm_campaign=GitHubBanner"><img src="https://raw.githubusercontent.com/PacktPublishing/GitHub/master/GitHub.png" 
alt="https://www.packtpub.com/" border="5" /></a>

## Instructions and Navigations
All of the code is organized into folders. For example, Chapter11.

The code will look like the following:
```
pipeline { 
   agent any 
   parameters { 
          choice(name: "ZAP_SCAN", choices: ["zap-baseline.py", "zap-full-scan.py"], description: "Parameter to choose type of ZAP scan") 
          string(name: "ENTER_
```

**Following is what you need for this book:**
This book is for cybersecurity professionals, ethical hackers, application security engineers, DevSecOps engineers, students interested in web security, cybersecurity enthusiasts, and anyone from the open source cybersecurity community looking to gain expertise in ZAP. Familiarity with basic cybersecurity concepts will be helpful to get the most out of this book.

With the following software and hardware list you can run all code files present in the book (Chapter 1-11).
### Software and Hardware List
| Chapter | Software required | OS required |
| -------- | ------------------------------------ | ----------------------------------- |
| 1-11 | Java | Windows, macOS, or Linux |
| 1-11 | Docker Desktop/Docker Compose | Windows, macOS, or Linux |
| 1-11 | OWASP Juice-Shop | Windows, macOS, Linux, or Docker |
| 1-11 | Mutillidae II | Windows, macOS, or Linux |
| 1-11 | Jenkins | Windows, macOS, Linux, or Docker |

We also provide a PDF file that has color images of the screenshots/diagrams used in this book. [Click here to download it](https://packt.link/oBhpt).

### Related products
* The Ultimate Kali Linux Book, Second Edition [[Packt]](https://www.packtpub.com/product/the-ultimate-kali-linux-book-second-edition/9781801818933?utm_source=github&utm_medium=repository&utm_campaign=9781801818933) [[Amazon]](https://www.amazon.com/dp/1801818932)

* Nmap Network Exploration and Security Auditing Cookbook, Th ird Edition [[Packt]](https://www.packtpub.com/product/nmap-network-exploration-and-security-auditing-cookbook-third-edition/9781838649357?utm_source=github&utm_medium=repository&utm_campaign=9781838649357) [[Amazon]](https://www.amazon.com/dp/1838649352)


## Get to Know the Author
**Ryan Soper**
 is a lead penetration tester, senior application security engineer, and veteran of the US Coast Guard. His experience includes penetration testing, application security, and IT consulting, among more, throughout his career. He’s an active member and organizer of the DefCon813 chapter, a member of the OWASP Tampa chapter, and enjoys connecting with others throughout the community at conferences or other various networking events. He can be contacted at ryans.wapt@gmail.com or followed on Twitter at @soapszzz.
Ryan is an ambassador for the Innocent Lives Foundation (ILF), a group of hackers that work with law enforcement to protect children from online predators. Your support will help the team to continue their important work. I urge you to consider making a donation to the ILF at https://www.innocentlivesfoundation.org/donate/.

**Nestor N Torres**
 is a senior application security engineer and web application penetration tester. His experience includes application security, IT consulting, penetration testing, and mobile penetration testing. He is an active member and organizer of the DefCon813 chapter and OWASP Tampa chapter, who enjoys helping new colleagues interested in joining the cyber security field. You can find him at his local BSides in Orlando and Tampa and other conferences such as Defcon and OWASP events.
He can be contacted at nestor.wapt@gmail.com or followed on Twitter at @n3stortorres.

**Ahmed Almoailu**
 is a cyber security engineer with years of experience in vulnerability management, risk management, network security, cloud security, and endpoint security. He has a Master of Science in Cybersecurity and a Bachelor of Science in computer information systems from Saint Leo University and is currently working in healthcare. He is a member of the DefCon813 chapter and participates in security events in the community. Ahmed holds CASP+, Security+, Certified Ethical Hacker (CEH), eJPT, and AWS Cloud Practitioner certifications. Ahmed can be contacted at ahmed.wapt@gmail.com.
