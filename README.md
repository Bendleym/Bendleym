# 🔐 IAM Conditional Access Automation Lab (Entra ID + Graph API)

## 🔍 Overview
This lab simulates an identity security workflow in Microsoft Entra ID focused on Conditional Access enforcement and automated response actions. The project demonstrates how identity teams detect risky sign-in behavior, validate access context, and take automated steps to reduce account compromise risk while maintaining audit evidence.

## 🎯 Lab Goals
- Implement Conditional Access policies in Entra ID
- Detect impossible travel style sign-in risk using sign-in telemetry and IP context
- Automate verification and temporary account disablement using Graph API and Logic Apps style workflows
- Document identity response playbooks for auditability and repeatable execution

## 🧰 Tools Used
Microsoft Entra ID, Microsoft Graph API, Logic Apps style workflows, PowerShell, Active Directory (supporting identity concepts)

## ⚙️ Identity Detection and Response Workflow
- Implemented Conditional Access policy controls for sign-in risk scenarios
- Reviewed sign-in telemetry patterns and IP context to identify suspicious access
- Automated verification steps and temporary account disablement actions
- Documented response playbooks for token revocation, MFA escalation, and evidence tracking

## 📌 Playbooks Documented
- Risky sign-in triage and verification checklist
- Temporary disablement and re-enable criteria
- Token revocation and session control workflow
- MFA escalation and enforcement steps
- Audit evidence capture and case note structure

## 📌 Key Outcomes
- Demonstrated identity focused security controls and response workflows
- Practiced automation concepts using Graph API driven actions
- Strengthened understanding of Conditional Access, sign-in telemetry, and identity governance
- Built documentation aligned to repeatable analyst execution and audit readiness

## 📸 Screenshots

### 🖼️ OU Structure  
<img width="764" height="541" alt="Capture2" src="https://github.com/user-attachments/assets/799d3271-db90-45cb-aa5b-0f21a554c2e3" />

### 🖼️ User Examples  
<img width="742" height="538" alt="Capture3" src="https://github.com/user-attachments/assets/f8ebf3bc-58cd-4c96-acf9-633b681c2318" />

### 🖼️ Domain Admin Membership  
<img width="423" height="548" alt="Capture4" src="https://github.com/user-attachments/assets/184e5254-9780-4326-b240-29ae1932326c" />

### 🖼️ PowerShell Privilege Audit  
<img width="966" height="516" alt="Capture6" src="https://github.com/user-attachments/assets/aa50ef6f-15a8-4335-838b-1e39411b0251" />
