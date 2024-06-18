## Homework Description 
Analyze the code of a simple web application in JavaScript and HTML to identify and remediate common security vulnerabilities, following the OWASP Top Ten. 
 
### Vulnerabilities and Remediations 
1. **Insecure Storage of Credentials** 
   - **Solution:** Removed the use of localStorage for storing sensitive information. Implemented secure session handling on the server-side. 
 
2. **HTML Injection** 
   - **Solution:** Sanitized user inputs before rendering them in the DOM to prevent HTML injection attacks. 
