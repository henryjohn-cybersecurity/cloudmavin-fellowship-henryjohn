# Task 1.3 Report

## Reconnaissance Baseline

### Executive Summary

This task involved completing the Linux Fundamentals and Networking Fundamentals modules on TryHackMe, followed by the Hack The Box Starting Point machines **Meow (Tier 0)** and **Fawn (Tier 1)**. The objective was to build foundational knowledge in Linux, networking, and reconnaissance while documenting all commands, observations, and evidence. The practical exercises strengthened my understanding of Linux command-line operations, network communication, DNS resolution, remote service interaction, and network scanning using industry-standard tools.

---

### Objectives

* Develop practical Linux command-line skills.
* Understand Linux file system navigation and file management.
* Learn fundamental networking concepts and protocols.
* Understand the OSI and TCP/IP network models.
* Perform DNS lookups and basic network reconnaissance.
* Scan hosts for open ports using Nmap.
* Complete the TryHackMe Linux Fundamentals and Networking modules.
* Complete the Hack The Box Meow and Fawn machines.
* Document all commands, observations, and evidence.

---

### Methodology

The practical exercises were completed using a Kali Linux virtual machine connected to the internet.

The following learning platforms were used:

* TryHackMe – Linux Fundamentals
* TryHackMe – Networking Fundamentals
* Hack The Box – Starting Point (Meow)
* Hack The Box – Starting Point (Fawn)

During each exercise, commands were executed within the Linux terminal, observations were recorded in Obsidian, screenshots were captured, and all activities were documented for reporting purposes.

---

### Technical Report

#### Part A – Linux Fundamentals

The Linux Fundamentals module introduced essential Linux commands used for system navigation, file management, text searching, and terminal operations.

Topics covered included:

* Linux terminal navigation
* Directory structure
* File management
* User identification
* Searching files
* Reading files
* Redirecting output
* Appending text to files
* Command operators

The practical exercises demonstrated how Linux commands interact with files and directories and how terminal operators improve command efficiency.

---

#### Part B – Networking Fundamentals

The Networking Fundamentals module introduced the basic principles of computer networking.

Topics studied included:

* Network communication
* OSI Model
* TCP/IP Model
* IP Addresses
* MAC Addresses
* DNS
* Common network ports
* Network protocols
* DNS resolution
* Remote server communication

Practical exercises involved resolving domain names, identifying IP addresses, communicating with remote servers, and understanding the purpose of commonly used ports.

---

#### Part C – Hack The Box

Two Starting Point machines were completed:

### Meow (Tier 0)

Skills demonstrated:

* Host discovery
* Connectivity testing
* Port scanning
* Remote login
* Basic reconnaissance

---

### Fawn (Tier 1)

Skills demonstrated:

* FTP enumeration
* Anonymous FTP login
* File discovery
* Downloading files
* Basic information gathering

These exercises reinforced the reconnaissance techniques introduced during the networking modules.

---

### Commands Used

#### Linux Commands

| Command | Purpose                                 |
| ------- | --------------------------------------- |
| whoami  | Displays the currently logged-in user   |
| pwd     | Displays the current working directory  |
| ls      | Lists files and directories             |
| cd      | Changes the current directory           |
| cat     | Displays the contents of a file         |
| echo    | Prints text to the terminal or a file   |
| find    | Searches for files and directories      |
| grep    | Searches for specific text inside files |

---

#### Linux Operators

| Operator | Purpose                                                        |
| -------- | -------------------------------------------------------------- |
| >        | Redirects output and overwrites a file                         |
| >>       | Appends output to an existing file                             |
| &        | Runs a process in the background                               |
| &&       | Executes the second command only if the first command succeeds |

---

#### Networking Commands

| Command              | Purpose                                                                            |
| -------------------- | ---------------------------------------------------------------------------------- |
| nslookup example.com | Retrieves the IP address associated with a domain name                             |
| host example.com     | Displays DNS records for a domain                                                  |
| ping <IP Address>    | Tests connectivity to a remote host                                                |
| telnet <IP Address>  | Connects to a remote service running on a specified port                           |
| GET / HTTP/1.1       | Sends a simple HTTP request after establishing a Telnet connection to a web server |
| nmap <IP Address>    | Scans a host to discover open ports and services                                   |

---

### Practical Activities Completed

#### Linux Fundamentals

Successfully executed:

* whoami
* pwd
* ls
* cd
* cat
* echo
* find
* grep

Observed outputs included:

* Current user identified as **TryHackMe**
* Directory listing showing Folder1, Folder2, Folder3 and Folder4
* Navigation into Folder1
* Discovery of **password.txt** and **access.log**
* Reading the contents of **password.txt**, revealing **password123**
* Searching **access.log** using **grep** to locate the required THM flag
* Using **echo**, **>**, and **>>** to create, overwrite, and append text to files

---

#### Networking Fundamentals

Successfully learned and demonstrated:

* OSI Model layers
* TCP/IP Model
* MAC Addressing
* IPv4 addressing
* DNS resolution
* Common network ports
* HTTP communication
* Basic remote server interaction
* Valid and invalid IP address ranges

---

#### Hack The Box

Successfully completed:

* Meow (Tier 0)
* Fawn (Tier 1)

Activities performed included:

* Host connectivity testing
* Network reconnaissance
* Open-port discovery using Nmap
* FTP enumeration
* Remote service interaction

---

### Screenshots & Evidence

The following evidence was collected during the practical exercises:

* Linux Fundamentals room completion
* Networking Fundamentals room completion
* Hack The Box Meow completion
* Hack The Box Fawn completion
* Linux terminal commands
* Nmap scan results
* DNS lookup results
* FTP connection screenshots
* Completion badges

---

### Findings

The practical exercises demonstrated that Linux proficiency is essential for cybersecurity professionals.

Understanding Linux commands enables efficient system navigation, file management, log analysis, and automation.

Networking knowledge provides the foundation for understanding how devices communicate, how services operate, and how attackers identify potential targets.

Reconnaissance techniques such as DNS lookups, host discovery, and port scanning are fundamental skills used by penetration testers and security analysts during information gathering.

---

### Risk Rating

**Medium**

Reason:

Poor understanding of Linux systems and networking can lead to configuration errors, ineffective incident response, and an inability to identify security vulnerabilities during reconnaissance activities.

---

### Recommendations

* Continue practicing Linux terminal commands daily.
* Develop greater proficiency with Nmap scanning techniques.
* Study additional networking protocols and services.
* Complete more TryHackMe and Hack The Box rooms to strengthen practical skills.
* Document all future practical exercises using the established documentation standard.
* Review Linux commands regularly to improve speed and confidence.

---

### Lessons Learned

This practical exercise significantly improved my confidence in using the Linux command line and reinforced my understanding of networking fundamentals.

I gained hands-on experience with system navigation, file management, text searching, DNS resolution, remote service interaction, and network reconnaissance. Completing the Hack The Box machines also demonstrated how these foundational skills are applied during real-world cybersecurity assessments.

---

### References

* TryHackMe – Pre Security Learning Path
* Hack The Box – Starting Point (Meow)
* Hack The Box – Starting Point (Fawn)
* Kali Linux Documentation
* Nmap Official Documentation
* Linux Manual Pages (man pages)

---

### AI Usage Declaration

Artificial Intelligence (ChatGPT by OpenAI) was used as a learning assistant to explain Linux concepts, networking principles, report organization, and documentation best practices. All practical exercises, commands, screenshots, analysis, observations, and conclusions were personally completed, verified, and understood by the student before submission.
