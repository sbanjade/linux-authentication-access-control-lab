# Linux Authentication & Access Control Security Lab

## Objective
This project demonstrates how weak authentication mechanisms and improper access control can lead to unauthorized access and privilege escalation in Linux systems. The lab focuses on understanding authentication vs authorization and applying secure configuration best practices.

## Lab Environment
- Conducted in a controlled Linux virtual machine
- Performed as part of an academic cybersecurity course
- All actions were authorized and executed for educational and defensive security testing purposes
- No external systems or real-world networks were accessed

## Tools Used
- Linux (Ubuntu-based VM)
- SSH
- Hydra
- sudo
- chmod
- Standard Linux permission auditing tools

## Attack Simulation (Authorized)
- Attempted unauthorized access to a restricted directory as a standard user
- Performed controlled password-strength testing to demonstrate the risks of weak credentials
- Verified that authentication alone does not guarantee authorization
- Demonstrated how improper permission management can expose sensitive data

## Security Findings
- Weak passwords significantly increase the risk of credential compromise
- Authentication success does not imply authorization to access protected resources
- Overly permissive file permissions can bypass intended access controls
- Root-level access must be tightly controlled to prevent privilege abuse

## Hardening Recommendations
- Enforce strong password length and complexity policies
- Disable SSH password authentication and use key-based authentication
- Disable direct root login via SSH
- Apply the principle of least privilege for users and files
- Use group-based permissions or ACLs instead of broad permission changes
- Perform regular permission and access audits

## Key Learnings
This project strengthened my understanding of Linux authentication, authorization, and privilege escalation risks, and reinforced the importance of secure system configuration to protect sensitive data in real-world environments.
