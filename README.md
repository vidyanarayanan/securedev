# Secure development good practices 

# Vulnerabilities to watch out for
## Injections
### DB Query Injection
#### Mitigation:
 Prepared Statements
 Input Validation and Sanitization where Prepared Statements is not possible
 Escaping of characters
       
#### Lowering of impact:
   Enforce least privilege
   Error reporting should not reveal sql commands, product information/versions

### Cross-site Scripting (XSS)
Client-side attack. Type of injection where malicious scripts are injected into benign websites. An attacker uses web applications to send malicious code through browser-side scripts to the unsuspecting user - the end user's browser has no way to realize that the script should not be trusted. The browser therefore executes the script thinking that the script came from a trusted source. This malicious code can access cookies, session tokens, or other sensitive information.

#### Types or Cross-site scripting 
Stored XSS
Reflected XSS
DOM-based XSS
The above are all related. New classification by OWASP include the following:
Server XSS
Client XSS
