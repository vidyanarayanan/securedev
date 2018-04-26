# secure development good practices 

### DB Query Injection
#### Mitigation:
 Prepared Statements
 Input Validation and Sanitization where Prepared Statements is not possible
 Escaping of characters
       
#### Lowering of impact:
   Enforce least privilege
   Error reporting should not reveal sql commands, product information/versions

### Cross-site Scripting (XSS)
Client-side attack:  
