# Overview

Leaf is a beginner-level web security lab designed to introduce
**Server-Side Template Injection (SSTI)** vulnerabilities.

The application uses a server-side template engine to dynamically
render user-controlled input. Due to insufficient input validation,
template expressions provided by the user are evaluated on the server.

This vulnerability allows attackers to:
- Execute template expressions
- Identify the underlying template engine
- Achieve remote code execution in advanced scenarios

The goal of this lab is to understand how SSTI vulnerabilities work
and how they can lead to full system compromise.
