# Module 1: Advanced Exploitation ✅
**TryHackMe Blueprint Room** | Nmap + Python RCE

**Target**: 10.49.186.148
**Vulnerability**: Unrestricted File Upload (CWE-434)
**CVSS**: 9.8 Critical
**Outcome**: www-data shell via Python reverse shell

**Attack Chain**:
nmap → Port 80 → /upload RCE → shell.py → nc listener

**Files**:
- shell.py (Python reverse shell)
- EXPLOIT_LOG.json (CVSS 9.8)
- 3 screenshots (nmap, listener, shell)

**Status**: PRODUCTION READY
EOF