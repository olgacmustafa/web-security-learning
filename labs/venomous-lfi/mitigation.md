# Mitigation

To prevent LFI and log poisoning attacks:

- Never include files directly from user input
- Use allowlists for file inclusion
- Validate and normalize paths using realpath()
- Restrict permissions on log files
- Prevent logs from being interpreted as executable code
- Disable unnecessary PHP execution features
