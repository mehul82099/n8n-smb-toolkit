<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:EA4B71,100:2575fc&height=200&section=header&text=n8n%20SMB%20Toolkit&fontSize=50&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=50%2B%20Ready-to-Use%20n8n%20Workflows%20for%20Indian%20SMBs&descAlignY=56&descSize=16&descColor=ffe0e9" width="100%"/>

[![Stars](https://img.shields.io/github/stars/mehul82099/n8n-smb-toolkit?style=for-the-badge&color=f7c948&labelColor=0d1117)](https://github.com/mehul82099/n8n-smb-toolkit/stargazers)
[![Forks](https://img.shields.io/github/forks/mehul82099/n8n-smb-toolkit?style=for-the-badge&color=2575fc&labelColor=0d1117)](https://github.com/mehul82099/n8n-smb-toolkit/network)
[![Issues](https://img.shields.io/github/issues/mehul82099/n8n-smb-toolkit?style=for-the-badge&color=EA4B71&labelColor=0d1117)](https://github.com/mehul82099/n8n-smb-toolkit/issues)
[![License](https://img.shields.io/github/license/mehul82099/n8n-smb-toolkit?style=for-the-badge&color=46E3B7&labelColor=0d1117)](LICENSE)

**The most practical n8n automation kit built specifically for Indian businesses.**

</div>

---

## 🌟 Why This Toolkit Exists

Every Indian SMB owner has the same problems:
- Manually copying orders from WhatsApp to spreadsheets
- Sending payment reminders one by one
- Missing leads because no one replied on time
- Paying someone to do data entry that a bot can do in 2 seconds

This toolkit gives you **copy-paste n8n workflows** that solve all of that. Import a JSON file, add your credentials, and you're live.

---

## 📦 What's Inside

### 💳 Payments & Finance
| Workflow | Description | File |
|----------|-------------|------|
| Razorpay Payment Alert | Telegram alert on every payment received | `workflows/razorpay-payment-alert.json` |
| UPI Webhook Handler | Auto-log UPI payments to Google Sheets | `workflows/upi-webhook-to-sheets.json` |
| Payment Failure Recovery | Auto-send retry link when payment fails | `workflows/payment-failure-recovery.json` |
| GST Invoice Generator | Auto-generate GST invoice PDF on order | `workflows/gst-invoice-generator.json` |

### 💬 WhatsApp & Telegram
| Workflow | Description | File |
|----------|-------------|------|
| WhatsApp Lead Capture | Capture leads from WA to CRM + Sheets | `workflows/whatsapp-lead-capture.json` |
| Telegram Order Bot | Full order management via Telegram | `workflows/telegram-order-bot.json` |
| WhatsApp Broadcast Scheduler | Schedule bulk WA messages to customers | `workflows/whatsapp-broadcast-scheduler.json` |
| Telegram Daily Report Bot | Auto daily sales/orders summary at 9pm | `workflows/telegram-daily-report.json` |

### 🤖 AI Automation
| Workflow | Description | File |
|----------|-------------|------|
| AI Customer Support Bot | Gemini AI replies to customer queries | `workflows/ai-customer-support.json` |
| AI Lead Qualifier | Auto-score leads using AI | `workflows/ai-lead-qualifier.json` |
| Product Description Generator | AI writes product descriptions in bulk | `workflows/ai-product-desc-generator.json` |
| AI Email Responder | Auto-draft email replies using GPT | `workflows/ai-email-responder.json` |

### 📊 CRM & Data
| Workflow | Description | File |
|----------|-------------|------|
| Google Sheets CRM Sync | Sync form submissions to Sheets CRM | `workflows/sheets-crm-sync.json` |
| E-commerce Inventory Alert | Alert when stock goes below threshold | `workflows/inventory-low-alert.json` |
| Order Confirmation SMS | Auto-send order confirmation via SMS | `workflows/order-confirmation-sms.json` |
| Customer Birthday Greeter | Auto wish customers on birthday | `workflows/birthday-greeter.json` |

---

## ⚡ Quick Start

### Prerequisites
- n8n installed (self-hosted or n8n.cloud)
- Credentials: Razorpay API, Telegram Bot Token, WhatsApp API, Google Sheets OAuth

### Import a Workflow

```bash
# 1. Copy the JSON content from any workflow file
# 2. Open n8n → Workflows → Import from JSON
# 3. Paste the JSON
# 4. Add your credentials
# 5. Activate — you're live!
```

### Self-host n8n in 1 minute (Render free tier)
```bash
# Deploy to Render (free)
# Use Docker image: n8nio/n8n
# Set env: N8N_BASIC_AUTH_ACTIVE=true
```

---

## 🛠️ Credential Setup Guides

| Service | Guide |
|---------|-------|
| Razorpay | [Setup Razorpay Webhook](docs/razorpay-setup.md) |
| Telegram Bot | [Create Telegram Bot](docs/telegram-setup.md) |
| WhatsApp API | [WhatsApp Business API](docs/whatsapp-setup.md) |
| Google Sheets | [OAuth Setup](docs/google-sheets-setup.md) |
| Gemini AI | [Gemini API Key](docs/gemini-setup.md) |

---

## 🇮🇳 Built for India

```
✅ Razorpay & UPI payment flows
✅ GST invoice generation
✅ Indian phone number formatting
✅ Hindi + English message templates
✅ Works with Juspay, CCAvenue, PayU
✅ MSME-scale, not enterprise bloat
```

---

## 📺 Video Tutorials

> Coming soon on YouTube — subscribe to [@mehul82099](https://github.com/mehul82099) for updates

---

## 🤝 Contributing

Got a workflow that saved your business time? Submit a PR!

```bash
git clone https://github.com/mehul82099/n8n-smb-toolkit
cd n8n-smb-toolkit
# Add your workflow JSON to /workflows
# Add docs to /docs
# Submit PR with description of what it does
```

---

## 💬 Support

- 🐛 [Open an Issue](https://github.com/mehul82099/n8n-smb-toolkit/issues)
- 📬 Email: mehuljhabak10@gmail.com
- 📢 Telegram: [@mehul82099](https://t.me/mehul82099)

---

## 📄 License

MIT License — free to use, modify, and distribute.

---

<div align="center">

**⭐ Star this repo if it saves you time — it helps more Indian SMBs discover it!**

[![Star History Chart](https://api.star-history.com/svg?repos=mehul82099/n8n-smb-toolkit&type=Date)](https://star-history.com/#mehul82099/n8n-smb-toolkit&Date)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2575fc,100:EA4B71&height=120&section=footer" width="100%"/>

</div>

<!-- Last updated: July 2026 -->
