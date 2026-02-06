# 🔍 Security Gap Analysis Guide — Windows & Linux

A beginner-friendly guide to performing Security Gap Analysis (Configuration Compliance Assessment) using official tools and baselines.

> **Purpose:** Compare current system configuration against recommended security baselines to identify gaps and vulnerabilities.

---

## 📂 Contents

- [Core Concept](Core%20Concept)
- [Windows - Policy Analyzer](Windows%20-%20Policy%20Analyzer)
- [Linux - OpenSCAP](Linux%20-%20OpenSCAP)
- [Windows vs Linux Comparison](Windows%20vs%20Linux%20Comparison)

---

## 🧠 What Is Gap Analysis?

Also called **hardening audit** or **compliance check**. It compares:

**Intended/Recommended** configuration → from official baselines (Microsoft SCT, CIS, STIG, NIST)

**Actual/Effective** configuration → what the live system really has right now

**Differences = security gaps** (weak passwords, no lockouts, insecure services, etc.)

---

## 🎯 Goal

- Detect configuration drift
- Prioritize fixes
- Harden systems
- Meet compliance requirements (CIS, NIST, DoD STIG, etc.)

---

## 🔑 Key Takeaways

- Always use the baseline that matches your **exact OS version and build**
- Security baselines are **general best practices** — tailor them to your organization
- After applying fixes → **re-scan** to confirm compliance
- This is a fundamental skill for security audits, system hardening, and regulatory compliance

---

## ⚖️ Legal Reminder

✅ Your own systems · ✅ Authorized company systems · ✅ Lab/test environments

❌ Unauthorized systems · ❌ Production without change management approval

---

## 🤝 Contributing

Found a mistake or want to add a tool? Open a PR!

## 📄 License

MIT License — feel free to use and share.
