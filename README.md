# instagram-auto-dm-bot

The "instagram-auto-dm-bot" automates direct messaging on Instagram, enabling users to send bulk messages without manual effort. By streamlining this outreach process, this tool helps marketers, influencers, and businesses scale their engagement strategies on the platform.


<p align="center">
  <a href="https://Appilot.app" target="_blank"><img src="https://github.com/Instagram-Automations/Footer-test/blob/main/appilot-baner.png" alt="Appilot Banner" width="100%"></a>
</p>
<p align="center">
  <a href="https://t.me/devpilot1" target="_blank"><img src="https://img.shields.io/badge/Chat%20on-Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram"></a>
  <a href="mailto:support@appilot.app" target="_blank"><img src="https://img.shields.io/badge/Email-support@appilot.app-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"></a>
  <a href="https://Appilot.app" target="_blank"><img src="https://img.shields.io/badge/Visit-Website-007BFF?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Website"></a>
  <a href="https://discord.gg/wpfG4j84" target="_blank"><img src="https://img.shields.io/badge/Join-Appilot_Community-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Appilot Discord"></a>
</p>



## Introduction

This automation tool automates sending direct messages (DMs) to users on Instagram. It eliminates the need for repetitive manual tasks, enabling businesses and individuals to engage in outreach campaigns effortlessly. With this bot, you can target specific audiences and send personalized messages at scale, boosting user engagement without increasing manual workload.

### Key Benefits of instagram-auto-dm-bot
- Saves time by automating repetitive direct messaging tasks.
- Allows customization of outreach messages to improve response rates.
- Increases scalability of marketing efforts by targeting large numbers of users.
- Eliminates human error in messaging, ensuring consistent communication.
- Helps marketers and businesses increase brand visibility with minimal effort.

## Core Features
| Feature | Description |
|----------|-------------|
| Bulk DM Sending | Send personalized DMs to multiple users at once. |
| User Targeting | Filter users based on hashtags, location, or activity. |
| Message Personalization | Customize messages with user data for better engagement. |
| Auto Follow | Automatically follow users after sending a DM to increase engagement. |
| Scheduling | Set specific times for messages to be sent automatically. |
| Proxy Support | Use proxies to prevent account bans and manage multiple accounts. |
| Retry Logic | Automatic retries for failed messages to ensure delivery. |
| Activity Logging | Keep track of sent messages and interactions for reporting. |

---

## How It Works
1. **Input or Trigger**: Triggered by user inputs (target user list, message content).
2. **Core Logic**: The bot filters users based on criteria (e.g., hashtags, location) and sends DMs.
3. **Output or Action**: DMs are sent to users, and follow actions are completed based on settings.
4. **Other Functionalities**: The bot supports scheduling and retries for failed messages.
5. **Safety Controls**: Includes proxy support, rate limiting, and logging to ensure safe usage.

---

## Tech Stack
**Language:** Python
**Frameworks:** Flask, Celery
**Tools:** Selenium, Requests
**Infrastructure:** AWS EC2, Redis

---

## Directory Structure
    instagram-auto-dm-bot/
    ├── src/
    │   ├── main.py
    │   ├── automation/
    │   │   ├── tasks.py
    │   │   ├── scheduler.py
    │   │   └── utils/
    │   │       ├── logger.py
    │   │       ├── proxy_manager.py
    │   │       └── config_loader.py
    ├── config/
    │   ├── settings.yaml
    │   ├── credentials.env
    ├── logs/
    │   └── activity.log
    ├── output/
    │   ├── results.json
    │   └── report.csv
    ├── requirements.txt
    └── README.md

---

## Use Cases
- Digital marketers use it to automate direct messages to potential clients, so they can scale their outreach efforts efficiently.
- Influencers use it to send personalized welcome messages to new followers, so they can boost engagement and build relationships.
- Social media managers use it to promote campaigns to targeted audiences, so they can improve brand awareness.
- Event organizers use it to send invites to followers, so they can increase attendance at events.

---

## FAQs

**How do I configure this automation for multiple accounts?**
The bot allows for multiple account configurations by setting up separate credentials for each account and using isolated sessions for each profile.

**Does it support proxy rotation or anti-detection?**
Yes, the bot supports rotating proxies to avoid account bans and includes anti-detection mechanisms like randomized delays between messages.

**Can I schedule it to run periodically?**
Yes, you can configure a cron-like schedule to trigger DM sending at specific intervals or times.

**What about emulator vs real device parity?**
The bot works on both emulators and real devices with the same features, but real devices may offer better reliability for long-running tasks.

---

### Performance & Reliability Benchmarks
**Execution Speed:** 100-200 DMs per minute under typical conditions with AWS EC2 instances.
**Success Rate:** 93-95% across long-running jobs with retries.
**Scalability:** Supports scaling to manage hundreds of accounts via sharded queues and parallel workers.
**Resource Efficiency:** Targets 1-2 GB RAM per instance, optimizing CPU usage for multi-threaded tasks.
**Error Handling:** Includes auto-retries, backoff strategies, and structured logging for better monitoring and recovery.


<p align="center">
<a href="https://cal.com/app-pilot-m8i8oo/30min" target="_blank">
 <img src="https://img.shields.io/badge/Book%20a%20Call%20with%20Us-34A853?style=for-the-badge&logo=googlecalendar&logoColor=white" alt="Book a Call">
</a>
 <a href="https://www.youtube.com/@Appilot-app/videos" target="_blank">
  <img src="https://img.shields.io/badge/🎥%20Watch%20demos%20-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="Watch on YouTube">
 </a>
</p>
