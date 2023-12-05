# Requirements
- The web API shall implement Distributed Denial of Service (DDoS) mitigation measures to maintain availability during an attack, with the ability to handle sustained traffic of up to 1 Gbps.
-  The web API shall maintain detailed access logs for all requests, including the user, timestamp, and actions performed, with log entries accessible only to authorized administrators.
- The web API shall implement digital signatures for critical transactions, providing non-repudiation for actions performed by users.
- The web API shall enforce strong password policies, requiring a minimum password length of 12 characters and incorporating complexity requirements (e.g., uppercase, lowercase, digits, symbols).
- Role-based access control (RBAC) shall be implemented, with users assigned the minimum necessary permissions based on their roles, achieving a minimum of 95% accuracy in permissions enforcement.
- Critical security patches shall be applied within 7 days of release, with regular vulnerability assessments conducted quarterly.
- The web API shall have an incident response plan with a target time of 2 hours for detecting and responding to security incidents.
- Developers shall follow secure coding practices, with a goal of reducing the number of high and critical security vulnerabilities to less than 5% of the total codebase.
- 

# # Reference(s)
- https://owasp.org/www-project-application-security-verification-standard/
- https://www.iso.org/standard/35733.html
- https://www.nist.gov/cyberframework