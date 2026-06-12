---
title: XEHBot Privacy Policy
description: Privacy policy explaining how XEHBot handles data in the Xbox Emulation Hub Discord server.
---

# XEHBot Privacy Policy

**Effective Date: June 12, 2026**

This privacy policy explains how XEHBot ("the Bot") handles, processes, and stores data within Discord. We are committed to protecting the privacy of our users and maintaining transparency about what data we interact with.

## 1. Data We Process

### A. Data Stored in Our Database
We only store the minimum configuration and moderation data necessary for the Bot's features:
* **Server Settings:** Channel IDs for welcome messages, logs, and the honeypot.
* **Autoresponder Rules:** Custom keywords and their corresponding reply messages configured by server administrators.
* **Moderation Records:** Warning records, strikes, mutes, kicks, and bans. This includes Discord User IDs, Moderator IDs, timestamps, case numbers, and reasons.
* **Active Mutes:** A list of currently muted Discord User IDs and their expiration times so the Bot knows when to automatically unmute them.

### B. Data Processed in Memory (Not Stored)
* **Message Content:** The Bot processes the text of messages to check for custom keywords that trigger autoresponder replies and to detect spam or malicious links in the honeypot channel. This text is processed entirely in memory, is never logged, saved, or stored, and is discarded immediately after processing.
* **Member Join/Leave Events:** The Bot processes member events to log welcome/leave activity and to manage active mutes (re-applying mutes if a user leaves and rejoins).

---

## 2. How We Use the Data
We use the collected information solely to provide, operate, and maintain the Bot's features, specifically:
* Running moderation tools and enforcing server rules.
* Triggering automated keyword responses.

---

## 3. Data Retention & Security

* **Moderation Records:** Retention of moderation history is at the discretion of the server administrators to maintain safety.
* **Active Mutes:** Active mute data is automatically deleted from our database as soon as the mute duration expires and the user is unmuted.
* **Security:** All stored data is kept in a secure, private database (`redb`) hosted on our private server. Access to the database is restricted strictly to the Bot's hosting administrators and developers.

---

## 4. Third-Party Sharing and AI Training

* **No Third-Party Sharing:** We do not sell, trade, rent, or share any user data with third-party services or external entities.
* **No AI/ML Training:** Message content and user data are never used to train machine learning models, artificial intelligence (AI), or large language models (LLMs).

---

## 5. Data Deletion & User Rights

Users have the right to request the deletion of any data associated with them.
* **Server-Specific Deletion:** Server administrators can remove or reset the Bot's settings and moderation logs at any time.
* **Global Deletion Requests:** If you want your moderation history or any other stored data permanently deleted from the Bot's database, you can contact the Bot Owner/Developer directly.

---

## 6. Contact Information

If you have questions about this policy or wish to submit a data deletion request, you can contact:
* **Bot Developer / Owner:** Discord: `.stern.` (or via the Xbox Emulation Hub Discord server)
* **Support / Inquiries:** Please contact the server staff.
