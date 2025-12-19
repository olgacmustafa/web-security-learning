# Methodology

The SSTI exploitation process followed three main phases:

## 1. Detection
User input points were identified within the application.
Template expressions were injected to test whether they were evaluated
server-side.

## 2. Identification
Different template engines evaluate expressions differently.
By observing output behavior, the underlying engine was fingerprinted.

## 3. Exploitation
Once confirmed, the vulnerability was escalated from expression
evaluation to arbitrary command execution.
