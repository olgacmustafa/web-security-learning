# Overview

Venomous is a web security lab focusing on file-based vulnerabilities.

The application improperly handles file inclusion parameters,
allowing attackers to traverse directories and include arbitrary
files from the server filesystem.

Combined with insecure logging practices, this leads to
remote command execution.
