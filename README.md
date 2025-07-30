
# phase3-identity-access-security
OpenLDAP + RBAC + MFA + PAM Policies + Insider Threat Detection
=======
# 🛡️ Phase 3: Identity and Access Security Implementation

This repository documents the work completed for **Phase 3** of my cybersecurity internship, focused on **Identity and Access Management (IAM)**. It demonstrates practical implementations of centralized authentication, role-based access, multi-factor authentication, and access control policies within a controlled lab environment.

---

## ✅ Objectives

- 🔐 **OpenLDAP Configuration**  
  Centralized user authentication across Linux systems using OpenLDAP.

- 👥 **Role-Based Access Control (RBAC)**  
  Group-based permissions for privileged and non-privileged users.

- 🔒 **Multi-Factor Authentication (MFA)**  
  Integrated Google Authenticator to enforce MFA via PAM for SSH sessions.

- ⚙️ **Privileged Access Management (PAM) Policies**  
  Customized PAM configurations to enforce access control and auditing.

- 🕵️ **Insider Threat Detection**  
  Monitored and logged user access attempts to identify suspicious behavior.

---

## 🧪 Lab Environment

| Component          | Configuration                       |
|-------------------|--------------------------------------|
| **Host OS**       | Kali Linux                          |
| **LDAP Server**   | OpenLDAP on kali linux              |
| **Client OS**     | Ubuntu 22.04                        |
| **Access Tools**  | OpenSSH, Google Authenticator       |
| **Monitoring**    | Syslog, PAM logs, Auth logs         |

---

## 📂 Project Structure

```bash
phase3-identity-access-security/
├── README.md
├── screenshots/                 # Visuals of setup and tests
├── configs/                    # PAM, sshd_config, LDAP ldif files
├── mfa_test_results/           # MFA login attempt logs
└── report.pdf                  # Internship report (optional)

📸 Highlights

    Successfully authenticated users via OpenLDAP from Ubuntu client.

    Enforced 2FA using OTP-based MFA for SSH.

    Restricted sudo access based on group roles.

    Logged and reviewed unauthorized SSH attempts.

📌 Key Takeaways

This phase provided hands-on experience with real-world identity and access security concepts, improving my understanding of:

    Centralized authentication in enterprise environments.

    Secure SSH and PAM hardening techniques.

    Monitoring for access anomalies and potential insider threats.

🧠 Skills Demonstrated

    LDAP configuration and LDIF management

    MFA integration using PAM

    Linux server hardening

    SSH security best practices

    Log review and basic incident detection

📫 Connect with Me

Rulane Hlongwani
📍 Cybersecurity Intern | Aspiring Security Analyst
🔗 LinkedIn 
💼 GitHub: github.com/rlinemavuyangwa

    “Security is not a product, but a process.” – Bruce Schneier


---

### ✅ How to Use It:

1. Run:
   ```bash
   nano ~/phase3-identity-access-security/README.md


