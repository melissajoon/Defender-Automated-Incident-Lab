# 🛡️ Microsoft Defender for Endpoint – Automated Incident Response Lab

This project is a hands-on lab simulating automated incident response using Microsoft Defender for Endpoint, Microsoft Sentinel, and Logic Apps. The purpose is to demonstrate how security alerts can be detected, tagged, and responded to automatically using scalable and practical SOAR capabilities.

---

## 🔍 Lab Objectives

- Connect a virtual machine to Microsoft Defender for Endpoint.
- Simulate real-world attacks (e.g., failed logons, brute-force).
- Detect incidents using Microsoft Sentinel analytics rules.
- Trigger automated responses using Logic Apps and Automation Rules.
- Send formatted email alerts containing incident details.

---

## 🧰 Tools & Technologies Used

| Tool | Purpose |
|------|---------|
| **Microsoft Defender for Endpoint** | Endpoint protection & detection |
| **Microsoft Sentinel** | SIEM for detection & alert correlation |
| **Logic Apps** | Automated playbook to send email alerts |
| **Azure VM (Windows)** | Target system for simulating attacks |

---

## ⚙️ How It Works

1. **VM Onboarding**  
   A Windows VM was onboarded to Microsoft Defender for Endpoint using Microsoft security portal.

2. **Alert Simulation**  
   Simulated multiple failed logon attempts and brute-force behaviors to trigger alerts.

3. **Analytics Rules**  
   Custom scheduled rules were created in Microsoft Sentinel to detect:
   - Multiple failed logons
   - Brute force behavior

4. **Automation Rules**  
   Automation rules were defined to trigger Logic Apps when an alert or incident is created.

5. **Logic App (Playbook)**  
   The playbook sends an email containing:
   - Alert name  
   - Severity  
   - Description  
   - Alert timestamp  
   💡 Emails were formatted professionally using HTML.

---

## 📸 Screenshots

All screenshots from Logic App workflow, automation rule, Sentinel alerts, and sample email are stored in the structured folders above for clarity and traceability.

---

## 📁 Project Structure

```
Defender-Automated-Incident-Lab/
│
├── README.md
├── /Defender
│   ├── 3.Defender-Onboard.png
│   ├── 4.EICAR-Detection.png
│   └── 5.EICAR-Attack-Graph-Details.png
├── /Playbook
│   ├── 6.Logic-App-Design.png
│   ├── 7.logic-App-Run
│   ├── 8.Automation-Rule.png
│   ├── 9.Email-Alert
│   └── 10.Run-History.png
└── /Sentinel
    └── analytics-rule-queries.kql
```

---

## ✅ Outcomes

- Emails were successfully triggered for each simulated alert.
- Logic App executed within milliseconds.
- Demonstrated integration between Microsoft Sentinel and Defender for automated response.

---

## 📬 Contact

**Melissa Jahani**  
📧 [melissajahani@gmail.com](mailto:melissajahani@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/melissajahani)  
💻 [GitHub](https://github.com/melissajoon)

---

> ⭐ Star this repo if you found it helpful, and feel free to contribute ideas or improvements!
