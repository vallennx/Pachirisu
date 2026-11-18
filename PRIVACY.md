# Pachirisu Privacy Policy

**Effective date:** 18 November 2026  
**Operator:** We, Vallenn (vallenn.x), Tri (stark_17a), Strwbgrl (lannalovesss)  
**Contact:** aurelightthedawnkeeper@gmail.com · Support server: https://discord.gg/2zF7BaebnN

This policy explains what data the Pachirisu Discord bot handles, why, and what choices you have. Pachirisu helps run Pokétwo mass-incense events, and can also help set up your server's channels. We try to collect as little as possible.

## 1. What we collect and store

**Server (guild) configuration**, saved when a server uses the bot:
- Server ID, and IDs of channels and roles you configure (watch, blacklisted, paused, log, organizer, announcement channels, and so on).
- Settings you choose: auto-stop, auto-resume, prefixes of naming bots, premium tier, starboard and announcement templates, slot templates, list formats and image links you provide.

**Event data**, created while a server runs an event:
- Slot boards and their reservations, including Discord **user IDs** of members who claim slots or reserve Pokémon, and gifted-reserve recipients.
- Incense tracking per channel: spawns remaining, state (running / paused / bought), end time, and the user ID of the member who paused or bought.
- Donation records, reserve approvals, confirmed reserve lists, and saved sessions.

**User-level data (small):**
- User IDs of members who are incense-banned in a server, global-ban records (user ID, reason, who banned, when), and bot-staff records.
- Per-user notification preferences you set with the bot's AFK / catch-alert settings.

**Aggregate counters:** total sessions, pauses, resumes, and similar numbers, with no personal information.

**Operational logs:** timestamps, server and user IDs, command names, and error messages, kept on a rotating basis for about 7 days to fix problems.

**Support requests:** if you open a ticket or post in our support server, we keep the messages (and a transcript for tickets) to help you and to review support quality. You can ask us to delete them.

We do **not** store the text of ordinary chat messages, and we do not collect real names, email addresses, phone numbers, payment details, or IP addresses through the bot.

## 2. Why the bot needs certain Discord permissions

- **Message Content intent:** Pachirisu reads messages to run its `-` prefix commands, and to read **Pokétwo's own messages** (for example, "You purchased an Incense", spawns remaining, and catch announcements) so it can pause channels and post catch alerts. Messages are processed in memory to perform these actions. Message text is not saved, except content that an admin deliberately gives the bot to save (such as an announcement).
- **Server Members intent:** to resolve members, roles and permissions for organizer checks, reserves and slot ownership.
- **Manage Channels / Manage Messages / Manage Roles:** to pause and resume channels for Pokétwo, create, rename and delete channels and categories when you ask the bot to, remove commands sent in a paused channel, and manage optional features such as role gradients.
- **Ban Members:** to apply bans only when an organizer or developer uses the bot's ban or global-ban commands.

## 3. How we use data
- To provide the bot's features (pausing, slot boards, reserves, alerts, server setup, premium limits).
- To keep the service running, debug errors, and prevent abuse.
- We do **not** sell your data, use it for advertising, or build profiles of users.

## 4. Who data is shared with
- **Discord**, since the bot runs on Discord and everything it posts is subject to Discord's own terms and privacy policy.
- **Hatenna (optional):** if a server selects Hatenna as its naming bot, the bot sends the server ID, Pokémon names, and member user IDs for reserves to Hatenna's Organizer API, and reads reserves back. Hatenna's own policy (see <https://hatenna.xyz/>) governs its handling of that data. Pokétwo is a separate service with its own [Privacy Policy](https://poketwo.net/privacy); Pachirisu only reads Pokétwo's public messages in your server and does not receive anything from Pokétwo's systems.
- **Our hosting provider** bot-hosting.net, which stores the bot's files and database.
- **Ticket Tool bot** for ticket management in our support server.
- **Database backups:** copies of our database are periodically posted to a private Discord channel that only the developers can access. Discord stores these files.
- We may disclose information if required by law or to protect against abuse or harm.

## 5. Retention and deletion
- Server and event data is kept so your settings survive restarts and re-invites. Event-specific data (slot sessions, reserves, incense rows) is cleared when a session ends.
- **To delete your server's data**, or any data tied to your user ID, contact us (see above) with your server ID or user ID. We will delete it within **30 days**.
- Backups are overwritten over time and may retain deleted data for a short period before they expire.

## 6. Security
Secrets such as the bot token are kept outside the code in environment variables, and access to the database and backups is limited to the developers. No online service is perfectly secure, and we cannot guarantee absolute security.

## 7. Children
Pachirisu is for people who meet Discord's minimum age requirement (13, or higher where local law requires). We do not knowingly collect data from children under that age. If you believe we have, contact us and we will delete it.

## 8. Your rights
Depending on where you live, you may have rights to access, correct, delete, or restrict use of your personal data. Contact us to exercise them. Most data we hold is just Discord IDs and settings, which you can also change or remove yourself through the bot's commands.

## 9. Changes to this policy
We may update this policy. The "Effective date" above will change, and for material changes we will announce them in our support server. Continued use of the bot means you accept the updated policy.

## 10. Contact
aurelightthedawnkeeper@gmail.com · https://discord.gg/2zF7BaebnN
