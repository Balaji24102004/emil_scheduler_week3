# Local Timed Email Marketing Campaign - Week 3 (Email Generation)

## 🚀 Project Overview

This project is a Python-based automated email marketing campaign system that:
- Uses **Google Gemini API** to dynamically generate email content.
- Sends emails via **SMTP (Gmail)**.
- Supports **local state tracking** to avoid resending.
- Sends emails in both **HTML and Plain Text formats**.

---

## 📅 **Week 3 Objectives (Completed):**

✅ Integrate **Google Gemini API** to generate:
- `subject`
- `body`
- `call-to-action (CTA)`

✅ Parse Gemini’s JSON response.

✅ Format and send both:
- **Plain Text Email**
- **HTML Email**  

✅ Track which emails are sent using **`campaign_state.json`**.

---

## 🏗️ **Project Structure**

| File | Description |
|------|-------------|
| `scheduled_email.py` | 🔥 Main script to generate & send emails (Week 3 core) |
| `campaign.json` | 🎯 Campaign data: product, audience, email series |
| `campaign_state.json` | 📝 Tracks which emails were sent (to avoid resending) |
| `campaign_parser.py` | 📦 Manages reading/writing state JSON |
| `campaign_state.py` | 📦 Loads campaign structure |
| `.env.example.txt` | 🔑 Sample environment file (without secrets) |
| `config.json` | ⚙️ Optional configuration |
| `test_gemini.py` | 🧪 Gemini API test script |

---

## 🔧 **Setup Instructions**

1. Clone the repo.
2. Install required packages:
```bash
pip install -r requirements.txt
# emil_scheduler_week3
week3
