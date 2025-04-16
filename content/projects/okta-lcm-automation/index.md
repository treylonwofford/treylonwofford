---
layout: page
permalink: "dartsnow"
title: "🔐Okta Lifecycle Management (LCM) Automation"
date: 2025-04-16
showAuthor: true
showDate: true
showReadingTime: true
---


This project automates user lifecycle operations (create, activate, assign to group, deactivate) using Okta's API.

## 📁 File Structure

```
okta-lcm-automation/
├── main.py
├── config.py
├── utils.py
├── README.md
```

## 📌 Features

- Create Okta user via API
- Activate user
- Assign user to group
- Deactivate user

## 🛠️ Setup

1. Clone the repo
2. Update `config.py` with your Okta domain and API token
3. Run:

```bash
pip install requests
python main.py
```
For further details: [github](https://github.com/treylonwofford/okta-lcm-automation)




