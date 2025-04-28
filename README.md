# Firewall Audit & Optimization Project

## 📄 Project Overview
This project simulates a professional firewall audit and optimization exercise. I analyzed firewall rulesets to identify unused, redundant, and risky configurations, and recommended optimizations based on security best practices and AlgoSec-style methodology.

## 🛠️ Tools & Skills Used
- Cisco ASA Simulated Ruleset (Sample)
- Firewall Management Best Practices
- Rule Analysis and Risk Assessment
- AlgoSec-style Logic and Reasoning
- Visual Inspection Techniques

## 🎯 Project Objectives
- Analyze firewall configurations for security gaps
- Identify and remove unused rules
- Simplify complex rule sets to improve performance
- Improve security posture without impacting network operations

## 🧠 Key Activities
- **Audit Process:** Reviewed all ACL entries and firewall object groups
- **Optimization:** Documented unnecessary or overly permissive rules
- **Recommendations:** Provided security hardening suggestions
- **Documentation:** Created a Before vs After Ruleset Table

## 🔍 Notes
- This project uses a sample ruleset based on real-world scenarios.
- A full firewall optimization guide was followed to ensure compliance with security best practices.

---

| Rule ID | Issue Found | Recommendation |
|:-------|:------------|:----------------|
| 100 | Unused rule allowing ANY to DB Server | Remove |
| 110 | Overlapping object groups | Consolidate objects |
| 120 | Source IP overly permissive | Restrict to authorized IPs |
