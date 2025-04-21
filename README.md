# 📬 Lenovo E-Mail Tool | DACH Support Edition

<div align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/0/06/Lenovo_Global_Corporate_Logo.png" width="200" alt="Lenovo Logo">
  <h3><i>Automated Email Generation System for Tier-1 DACH Technical Agents</i></h3>
  <img src="https://img.shields.io/badge/STATUS-LIVE-28a745?style=for-the-badge">
  <img src="https://img.shields.io/badge/USAGE-DAILY_OPERATIONAL-0073e6?style=for-the-badge">
</div>

---

## 🔧 Overview

This internal HTML tool empowers Lenovo support agents across the DACH region (Germany, Austria, Switzerland) to generate, customize, and copy precise, localized email templates in seconds. It streamlines outbound support communication, ensures legal and tonal compliance, and eliminates typing errors.

---

## 💼 Core Use Cases

| Context                        | Purpose                                                                       |
|-------------------------------|-------------------------------------------------------------------------------|
| 📞 Post-call follow-up        | Send recap emails with selected issue context and escalation steps           |
| 💬 Customer clarification     | Request additional images, data, or confirmations                            |
| 🔁 Redirection flow           | Forward clients to partners like Microsoft, Google, Nvidia, etc.             |
| ⚠️ 3-Strike protocol          | Automate warnings, final notices, and closure notices with consistent tone   |
| 💡 Troubleshooting & Repairs  | Guide customer through BIOS, drivers, OS resets, OneKey Recovery, diagnostics|

---

## 🎛️ Features Breakdown

- 🔀 **Dynamic dropdowns**: Generate precise responses by selecting context-specific templates
- 👤 **Personalization**: Input agent name, customer salutation, and case number
- 📋 **Clipboard Button**: Copy preformatted message with a single click
- 🔄 **Reset Button**: Clears all inputs instantly for next case
- 🧠 **Multilingual-optimized**: German formal tone, regionally accurate contact points

---

## 🧠 Agent Input Zones

| Input Type         | Description                                                      |
|--------------------|------------------------------------------------------------------|
| `Agent Name`       | Personalizes signature                                           |
| `Case Number`      | Fills in auto-referenced ticket number throughout message        |
| `Customer Title`   | Auto-formats intro: Herr, Frau, or neutral                       |
| `Customer Name`    | Directly inserted after greeting salutation                      |
| `MultiTemplate`    | Dropdown to pick troubleshooting, redirection, or update blocks |
| `Signature Option` | Controls whether to include surveys, APOS, disclaimers          |

---

## 📜 Sample Flow

```bash
1. Input: Agent = 'Max Mustermann', Case = 'DE9999'
2. Select: Customer = Herr Meier
3. Template: 'BIOS Reset' + Signature + Survey
4. Click: [Generate] → Preview shows full response
5. Click: [Copy Email] → Paste into CRM / Outlook
```

> No login, no backend, zero loading time.

---

## 🛠 Technical Stack

- 🧾 HTML5 + inline `<style>` and `<script>`
- 🧠 JS functions control field logic, DOM update, string templating
- 🔐 Operates fully offline; safe for internal desktop distribution
- 🎯 No libraries, zero dependencies – pure vanilla

---

## 🔮 Potential Expansions

- ☁️ Cloud sync w/ agent lookup for pre-filled data
- 📝 Markdown/HTML dual-render mode toggle
- 🌍 Multilingual toggle (EN, DE, FR)
- 📬 CRM API integration for push-to-email
- 📊 Logging usage analytics per dropdown or email copy click

---

## 📩 Contact / Troubleshooting

For updates, bug reports, or new template requests, contact:

**Internal Tool Maintainer**: `toolsupport@erzisolutions.local`

---

> Built to support those who support others.  
> ✉️ Lenovo DACH Mailer: simplify, standardize, scale.

---
