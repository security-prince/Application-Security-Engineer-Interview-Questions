# Application-Security-Engineer-Interview-Questions  
##### Some of the questions/topics which i was asked when i was giving interviews for Application/Product Security Engineering roles. I am sure this is not an exhaustive list but i felt these questions were important to be asked and some were challenging to answer. I tried to include the reference resource for some of the questions/topics, feel free to reach out to me on [twitter](https://twitter.com/security_prince) for any feedback/suggestions/discussions.


* ###### Which architecture is more secure? 2 tier or 3 tier
* ###### Explain SSL Handshake   
  * ###### https://www.youtube.com/watch?v=ubHZQrECeew  
  * ###### https://www.cloudflare.com/learning/ssl/how-does-ssl-work/  
  * ###### https://www.cloudflare.com/learning/ssl/what-happens-in-a-tls-handshake/  
* ###### Recommend XXE mitigation for application which requires external entities to be called because of business requirement  
* ###### Explain CORS and SOP  
  * ###### https://developer.mozilla.org/en-US/docs/Web/HTTP/CORS  
  * ###### https://portswigger.net/web-security/cors  
  * ###### https://developer.mozilla.org/en-US/docs/Web/Security/Same-origin_policy  
  * ###### https://www.bedefended.com/papers/cors-security-guide  
* ###### Does SOP mitigate CSRF attacks?  
  * ###### https://security.stackexchange.com/questions/157061/how-does-csrf-correlate-with-same-origin-policy

* ###### Exploiting SSRF attacks  
  * ###### https://portswigger.net/web-security/ssrf  
  * ###### https://www.hackerone.com/blog-How-To-Server-Side-Request-Forgery-SSRF  
  * ###### https://blog.appsecco.com/an-ssrf-privileged-aws-keys-and-the-capital-one-breach-4c3c2cded3af
* ###### What is web cache deception?  
  * ###### https://blog.cloudflare.com/understanding-our-cache-and-the-web-cache-deception-attack/  
  * ###### http://omergil.blogspot.com/2017/02/web-cache-deception-attack.html  
  * ###### https://portswigger.net/research/practical-web-cache-poisoning  
* ###### What is HTTP request smuggling?  
  * ###### http://projects.webappsec.org/w/page/13246928/HTTP%20Request%20Smuggling  
  * ###### https://portswigger.net/web-security/request-smuggling  
* ###### Explain DOM XSS. Can DOM XSS be stored? Can CSP header mitigate dom based XSS  
  * ###### https://www.html5rocks.com/en/tutorials/internals/howbrowserswork/  
  * ###### https://html.spec.whatwg.org/multipage/parsing.html  
  * ###### https://portswigger.net/web-security/cross-site-scripting/dom-based  
  * ###### https://brutelogic.com.br/blog/dom-based-xss-the-3-sinks/  
  * ###### https://www.scip.ch/en/?labs.20171214  
* ###### What will be your testcase for a file upload functionality?  
  * ###### https://medium.com/@satboy.fb/art-of-unrestricted-file-upload-exploitation-92ed28796d0  
  * ###### https://resources.infosecinstitute.com/file-upload-vulnerabilities/#gref  
  * ###### https://pentestlab.blog/2012/11/19/abusing-file-upload/  
  * ###### https://pentestlab.blog/2012/11/29/bypassing-file-upload-restrictions/  
* ###### What is HSTS?  
  * ###### https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Strict-Transport-Security  
* ###### Explain SSL Stripping  
  * ###### https://blog.cloudflare.com/performing-preventing-ssl-stripping-a-plain-english-primer/  
* ###### If you have API calls which need to fetch credentials, what will be the secure way to store secrets and making them available for API calls?  
* ###### How does file compression work?  
* ###### Which method is secure? Compress First and then Encrypt the data or Encrypt First then Compress  
* ###### You have found a vulnerability a product/infrastructure, how will you investigate if this was not exploited already by an attacker  
* ###### What is SPF, DKIM and DMARC?  
  * ###### https://www.smartertools.com/blog/2019/04/09-understanding-spf-dkim-dmarc  
  * ###### https://www.endpoint.com/blog/2014/04/15/spf-dkim-and-dmarc-brief-explanation  
  * ###### https://www.reddit.com/r/sysadmin/comments/aph6ee/lets_talk_about_email_spoofing_and_prevention_alt/
* ###### Explain DNS Exfiltration  
* ###### Explain Log Poisoning using LFI/RFI  
  * ###### https://www.hackingarticles.in/apache-log-poisoning-through-lfi/  
  * ###### https://www.hackingarticles.in/rce-with-lfi-and-ssh-log-poisoning/  
  * ###### https://highon.coffee/blog/lfi-cheat-sheet/  
* ###### Do the HttpOnly cookie and X-XSS-Protection header mitigate cross-site scripting attacks?  
* ###### How do you exploit XSS in a post request?  
  * ###### https://portswigger.net/blog/exploiting-xss-in-post-requests  
* ###### Difference: IDOR, Missing function level access control and privilege escalation  
* ###### How does burp suite work with HTTPs requests?  
  * ###### https://www.quora.com/How-is-it-possible-that-a-proxy-tool-like-Burp-Suite-is-able-to-decrypt-HTTPS-communication-like-plain-text-credentials  
  * ###### https://portswigger.net/burp/documentation/desktop/tools/proxy/using 
* ###### Is the DNS service's communication encrypted?
* ###### Security implications in DNS
* ###### DNS over HTTPs  
  * ###### https://hacks.mozilla.org/2018/05/a-cartoon-intro-to-dns-over-https/  
  * ###### https://www.chromium.org/developers/dns-over-https  
* ###### How does ssh authentication work?  
  * ###### https://www.digitalocean.com/community/tutorials/understanding-the-ssh-encryption-and-connection-process  
  * ###### https://gravitational.com/blog/ssh-handshake-explained/  
* ###### How to create and implement an SSL certificate?  
* ###### How to verify if a database is encrypted?  
* ###### If you want a script to use credentials from the system, where will you store the credentials?
* ###### Explain SDLC
* ###### In which phase of SDLC should security be integrated?
* ###### Explain encryption in Wifi network communication.
* ###### What are stateless and stateful requests?  
  * ###### https://www.geeksforgeeks.org/difference-between-stateless-and-stateful-protocol/  
* ###### How is the state of a request saved in HTTP?  
* ###### What data does the shadow file contains?  
  * ###### https://www.cyberciti.biz/faq/understanding-etcshadow-file/  
* ###### What is salt in cryptography?  
* ###### What is Double-Submit Cookie?  
* ###### What is Preflight request?  
  * ###### https://developer.mozilla.org/en-US/docs/Glossary/Preflight_request  
* ###### What are Certificate Transparency Logs?  
* ###### What is your favourite vulnerability and why?  
* ###### Talk about any latest/interesting vulnerability or breach you learnt about.

### Further Readings and references:
* ##### [Resources-for-Application-Security](https://github.com/security-prince/Resources-for-Application-Security)  
* ##### [How to prepare for a security engineer interview](https://medium.com/@eraymitrani/how-to-prepare-for-a-security-engineer-interview-6cf1d84de22f) by [Eray Mitrani](https://twitter.com/ErayMitrani)  
* ##### [Security_Engineer_Interview_Questions](https://github.com/tadwhitaker/Security_Engineer_Interview_Questions/blob/master/security-interview-questions) by [Tad Whitaker](https://twitter.com/theporkskewer)  
* ##### [Security Engineer - Interview Questions](https://gist.github.com/namishelex01/b5555edbdcdf5597174ddce5c86d3192) by [Namish](https://twitter.com/namishsir)  
* #####[60 Cybersecurity Interview Questions [2019 Update](https://danielmiessler.com/study/infosec_interview_questions/) by[Daniel Miessler](https://twitter.com/danielmiessler)
