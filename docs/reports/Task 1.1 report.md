# Task 1.1 Report

## Lab & Portfolio Bring-Up

## Executive Summary

A cybersecurity laboratory environment was successfully provisioned using Oracle VirtualBox and Kali Linux. A structured documentation workflow was established using Obsidian, while GitHub was configured to maintain version-controlled evidence and technical reports.

The environment is now ready for subsequent practical cybersecurity exercises.

---

## Objectives

- Provision Kali Linux virtual machine.
- Configure documentation environment.
- Create GitHub repository.
- Establish VM recovery snapshot.

---

## Lab Environment

| Component | Details |
|----------|---------|
| **Host Operating System** | Windows 11 |
| **Virtualization Platform** | Oracle VirtualBox |
| **Guest Operating System** | Kali Linux |
| **Memory** | 3072 MB |
| **Processor** | 2 CPU Cores |
| **Virtual Disk** | Approximately 90 GB |

---

## Methodology

1. Installed Oracle VirtualBox.
2. Created a Kali Linux virtual machine.
3. Installed Kali Linux.
4. Updated the operating system.
5. Created a VM snapshot.
6. Installed Obsidian.
7. Created a GitHub repository.
8. Created the documentation structure.

---

## Commands Used

```bash
sudo apt update
sudo apt full-upgrade -y
cat /etc/os-release
uname -r
whoami
```

---

## Findings

- The laboratory environment was successfully provisioned without critical issues.
- All required software components were installed and tested.
- Version control and documentation systems were successfully initialized.

---

## Risk Rating

**Low**

**Reason:**

The environment is isolated inside a virtual machine, reducing the risk of affecting the host operating system.

---

## Recommendations

- Maintain regular VM snapshots.
- Update Kali Linux weekly.
- Back up documentation regularly.
- Use Git commits frequently.

---

## Lessons Learned

During this task, I learned:

- Virtual machine deployment.
- Linux installation.
- Kali Linux system updates.
- GitHub repository initialization.
- Documentation best practices.

---

## References

- Oracle VirtualBox Documentation
- Kali Linux Documentation
- GitHub Documentation
- NIST Cybersecurity Framework (CSF) 2.0

---

## AI Usage Declaration

Artificial Intelligence (ChatGPT by OpenAI) was used strictly as a learning assistant and documentation guide.

All practical implementation was completed personally by the student.
