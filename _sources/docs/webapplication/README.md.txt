# Web-applications

Unauthorised access to our data can occur due to a web application not properly protecting data. A lack of quality encryption and improper key generation is often cause. Luckily, this type of vulnerability is difficult to exploit.

* Strict data encryption with a proven encryption technique
* Protect websites with the HTTPS (SSL/TLS) protocol
* Weaknesses in password hashing algorithms can be used to steal sensitive information stored on a web or application server. Use cryptographic hash functions to implement password hashing.
* Use third-party pentesting. Even the best senior programmers are susceptible to making mistakes. Review the application for potential vulnerabilities. For best results, do it regularly.
* [FLoC](../browsing/FLoC.md) requires that a website provide an explicit HTTP response header if it wants to opt out of the program. Google is counting on webmasters to not be bothered with [this task](FloCed-sites.md).
* Although supposedly going extinct, [third party cookies](../browsing/Cookies.md) are still in use by, for example, many Wordpress (feature adding) plugins. Wordpress covers around 30% of the websites on the internet. [Make the WP GDPR compliant](Cookied-wps.md).
* A file upload vulnerability can have a crucial impact because code can be executed on the server or the client. The uploaded file can be misused to exploit other vulnerable components of an application or trigger vulnerabilities in defective libraries while the file exists on the same machine. Uploaded files that threat actors can use could contain Command and control (C&C) server information, directions for harassment or violence or steganographic materials.

