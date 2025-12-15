## Methodology

The assessment began with network reconnaissance to identify
open ports and running services.

Following service detection, directory enumeration was performed
against the web server to discover hidden paths.

After identifying a web-based file management application,
publicly available documentation was reviewed to understand
its authentication mechanism.

Once a valid system user was identified, a brute-force approach
was applied to the SSH service using a controlled and limited
credential list.

The methodology focused on understanding system behavior
rather than blindly attacking services.
