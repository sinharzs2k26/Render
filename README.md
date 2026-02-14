# 🌐 Render Management Bot

A powerful, multi-user Telegram bot designed to manage [Render.com](https://render.com) services on the go. This bot acts as a mobile command center, allowing developers to trigger deploys, manage environment variables, and monitor service status through a secure, per-user API key system.

Bot link: `t.me/RenderTelegram_bot`

---

## 🚀 Key Features

### 📋 Service Management
* **List Services:** Get a quick overview of all your web services, static sites, and databases.
* **Service Info:** View deep-dive technical details including build commands, start commands, and regions.
* **Control Power:** Suspend or Resume services instantly to manage costs and resources.
* **Safe Deletion:** Delete services with a built-in confirmation safety check.

### 📦 Deployment Control
* **Manual Deploy:** Trigger a fresh deployment of your latest code with one tap.
* **Status Monitoring:** Check the live status and commit messages of the latest deployment.
* **Cancel Deploys:** Stop an accidental or stuck in-progress deployment before it finishes.

### 🔑 Environment Variable (Env Var) Management
* **View Keys:** List all current environment variables for any service.
* **Quick Update:** Add or update a single variable using the `KEY = VALUE` format.
* **Bulk Sync:** Replace the entire environment configuration at once for complex updates.
* **Delete Vars:** Remove specific variables by name.

### 🔐 Multi-User Security
* **Session-Based Auth:** Users provide their own Render API key via a secure prompt.
* **Privacy First:** API keys are stored in volatile session memory—they are never hardcoded and are cleared on logout.
* **Logout Control:** Users can clear their credentials at any time using the `/logout` command.

---

## 🛠 Commands at a Glance

| Command | Action |
| :--- | :--- |
| `/start` | Welcome and introduction |
| `/login` | Securely connect your Render API Key |
| `/services` | List all active/suspended services |
| `/deploy` | Trigger a new service deployment |
| `/updatenv` | Add or edit an environment variable |
| `/logout` | Clear your session and API key |

---

## 📝 Setup Requirements

To use this bot, you will need:
1. A **Telegram Bot Token** (from [@BotFather](https://t.me/botfather)).
2. Your **Render API Key** (Generated in your Render Dashboard under *Account Settings* > *API Keys*).

---
*Disclaimer: This bot is an independent tool and is not officially affiliated with Render.com.*