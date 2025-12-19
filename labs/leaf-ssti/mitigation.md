# Mitigation

The following security measures can be implemented to prevent
Server-Side Template Injection (SSTI) vulnerabilities:

## Input Handling
- Never render raw user input directly inside templates
- Apply strict input validation and output encoding
- Use allowlists for acceptable input values

## Template Engine Security
- Enable sandbox or restricted execution modes where supported
- Disable dangerous functions and filters such as `system`, `exec`, or similar
- Avoid exposing template engine errors to end users

## Application Hardening
- Separate application logic from template rendering
- Store sensitive information outside the web root
- Avoid hardcoding secrets inside configuration files

## Monitoring and Defense
- Implement logging and monitoring for abnormal template usage
- Perform regular security testing and code reviews

Applying these controls significantly reduces the risk of SSTI-related
remote code execution vulnerabilities.
