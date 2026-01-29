# Vulnerability Scanning with Nikto

## Objective
To perform a vulnerability scan on a web server using Nikto and identify possible security issues.

## Tool Used
- Nikto (Web Vulnerability Scanner)

## Target
- Localhost web server / testphp.vulnweb.com

## Procedure
1. Installed Nikto using apt package manager.
2. Executed Nikto scan on the target web server.
3. Saved scan output into nikto_scan_results.txt.
4. Analyzed the results to identify vulnerabilities.

## Observations
- Server information was disclosed.
- Missing security headers were detected.
- Potentially unsafe files and configurations were identified.

## Conclusion
Nikto successfully detected multiple vulnerabilities and misconfigurations, proving its effectiveness as a basic web vulnerability scanning tool.