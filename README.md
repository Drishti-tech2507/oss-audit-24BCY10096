# Open Source Audit Project

**Name:** Drishti Chopra  
**Registration Number:** 24BCY10096  
**Chosen Software:** LibreOffice  

---

## Project Overview

This project is an open source audit of LibreOffice, examining its origin, license, ethics, Linux footprint, and ecosystem. The project also includes five shell scripts that demonstrate Linux system administration and automation skills.

---

## Scripts Included

| Script | Purpose |
|--------|---------|
| `system_info.sh` | Displays system identity including OS, kernel, user, uptime |
| `package_check.sh` | Checks if LibreOffice is installed and displays license philosophy |
| `disk_audit.sh` | Audits system directories for size and permissions |
| `log_analyzer.sh` | Analyzes log files for error keywords |
| `manifesto.sh` | Generates a personalized open source philosophy statement |

---

## How to Run the Scripts

1. Make all scripts executable:
   ```bash
   chmod +x *.sh
   ```

2. Run each script:
   ```bash
   ./system_info.sh
   ./package_check.sh
   ./disk_audit.sh
   ./log_analyzer.sh /var/log/syslog error
   ./manifesto.sh
   ```

---

## Dependencies

- Linux distribution (Ubuntu/Fedora/Debian)
- Bash shell
- LibreOffice installed (for Script 2)
- Read access to log files (may require sudo for some logs)

---

## Script Details

### Script 1: system_info.sh
Displays system information including distribution name, kernel version, logged-in user, home directory, uptime, and current date.

### Script 2: package_check.sh
Checks if LibreOffice is installed on the system and displays package details along with a philosophy note about the software.

### Script 3: disk_audit.sh
Loops through important system directories and reports their disk usage, permissions, and ownership.

### Script 4: log_analyzer.sh
Reads a log file line by line, counts occurrences of a specified keyword (default: "error"), and displays the last 5 matching lines.

### Script 5: manifesto.sh
An interactive script that asks the user three questions and generates a personalized open source philosophy statement saved as a text file.

---

## Repository Structure

```
oss-audit-24BCY10096/
├── README.md
├── system_info.sh
├── package_check.sh
├── disk_audit.sh
├── log_analyzer.sh
└── manifesto.sh
```

---

## Report

The full report (12-16 pages) covers:
- Origin story of LibreOffice and the OpenOffice.org fork
- License analysis (MPL 2.0) and the four freedoms
- Ethical reflection on corporate control vs community governance
- Linux footprint with installation details and screenshots
- Ecosystem mapping of dependencies and community
- Comparison with Microsoft Office

---

## References

- [The Document Foundation](https://www.documentfoundation.org/)
- [Mozilla Public License 2.0](https://www.mozilla.org/en-US/MPL/2.0/)
- [GNU Philosophy](https://www.gnu.org/philosophy/)
- [LibreOffice Official Site](https://www.libreoffice.org/)

---

## Submitted By

**Drishti Chopra**  
**Registration Number:** 24BCY10096  
