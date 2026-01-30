# wazuh-custom-rules

Repository ini berisi custom rules untuk deteksi serangan web (DVWA), FTP, dan File Integrity Monitoring.

## Daftar Rules
- **1002xx**: Web Attack Detection (SQLi, XSS, Path Traversal)
- **1003xx**: Suricata Integration
- **1004xx**: FTP Monitoring (Brute force detection)
- **1005xx**: FIM (Deteksi file PHP berbahaya)

## Cara Install
Copy file XML ke `/var/ossec/etc/rules/` dan restart wazuh-manager.
