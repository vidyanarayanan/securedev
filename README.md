# secure development good practices 

DB Query Injection
	Mitigation:
a.	Prepared Statements
b.	Input Validation and Sanitization where Prepared Statements is not possible
c.	Escaping of characters
       
	Lowering of impact:
1.	Enforce least privilege
2.	Error reporting should not reveal sql commands, product information/versions

Cross-site Scripting (XSS)
Client-side attack:  
