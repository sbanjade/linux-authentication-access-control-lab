# Security Takeaways

## Authentication vs Authorization
Authentication verifies a user's identity, while authorization determines what resources the user is allowed to access. This lab demonstrated that even with valid credentials, access can still be restricted through proper permission management.

## Risks of Weak Passwords
Short and simple passwords significantly reduce the effort required for credential compromise. Enforcing strong password policies is critical to preventing unauthorized access.

## Privilege Escalation Impact
Root access enables unrestricted control over the system. If obtained by an attacker, it can lead to complete system compromise, data exposure, or service disruption.

## Permission Management Best Practices
Using broad permission changes such as `chmod o+rx` can introduce security risks. In production systems, administrators should prefer group-based permissions, ownership management, or Access Control Lists (ACLs).

## Real-World Relevance
Misconfigured access controls and weak credentials are common causes of security incidents. Proper authentication, authorization, and least-privilege enforcement are foundational to securing Linux systems.
