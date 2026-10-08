# Awesome Muse [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![Discord](https://img.shields.io/badge/Discord-join-5865F2?logo=discord&logoColor=white)](https://discord.gg/sxjhCPdEG6)

> A curated list of the best guides, use cases, tools, and news for Muse, Meta's personal AI agent.

[![Last commit](https://img.shields.io/github/last-commit/cszach/awesome-muse?style=flat-square)](https://github.com/cszach/awesome-muse/commits/main)
[![Link check](https://img.shields.io/github/actions/workflow/status/cszach/awesome-muse/links.yml?label=links&style=flat-square)](https://github.com/cszach/awesome-muse/actions/workflows/links.yml)
[![Submit a resource](https://img.shields.io/badge/submit-a%20resource-blue?style=flat-square)](https://github.com/cszach/awesome-muse/issues/new/choose)

Muse takes goals in plain language and gets them done across your apps and the web: it books, buys, schedules, emails, and fills out forms, and asks for your approval before anything sensitive. This list collects the resources that help you get the most out of it. It is hand-picked, not exhaustive.

**Legend:** 🎖️ Official resource from Meta.

> [!NOTE]
> This is an unofficial, community-maintained list. It is not affiliated with or endorsed by Meta.

## Contents

- [About Muse](#about-muse)
- [Getting Started](#getting-started)
- [Community](#community)
- [Use Cases and Inspiration](#use-cases-and-inspiration)
- [Tips and Best Practices](#tips-and-best-practices)
- [Connectors and Integrations](#connectors-and-integrations)
- [Community Tools](#community-tools)
- [Community Builds](#community-builds)
- [Where to Use Muse](#where-to-use-muse)
- [Privacy, Safety, and Security](#privacy-safety-and-security)
- [Reviews and Hands-On](#reviews-and-hands-on)
- [News and Analysis](#news-and-analysis)
- [Videos and Podcasts](#videos-and-podcasts)

## About Muse

As of September 2026:

Muse is a personal AI agent that acts on goals you describe in plain language, using a browser and your connected apps, and keeps working after you leave the app. Read-only and low-risk steps run on their own; actions that send, buy, or share information stop and wait for your approval. Each user's tasks run in an isolated cloud computer, powered by Meta's Muse Spark models.

It is available in the United States and Canada to people 18 and older with a Meta account, on mobile and Mac, with a free tier and paid Power and Maximum plans.

## Getting Started

- [Muse](https://ai.meta.com/muse/) 🎖️ - Official product page with features and plans.
- [Download Muse](https://ai.meta.com/muse/download/) 🎖️ - Official download page for Mac and mobile.
- [Muse for Android](https://play.google.com/store/apps/details?id=com.facebook.aura) 🎖️ - Google Play listing.
- [Muse for iOS](https://apps.apple.com/us/app/muse-from-meta/id6760173601) 🎖️ - App Store listing.
- [Introducing Muse](https://about.fb.com/news/2026/09/introducing-muse-personal-ai-agent/) 🎖️ - Launch announcement from Meta's newsroom.
- [How to Get Started with Muse](https://www.engadget.com/2256577/how-to-get-started-with-meta-s-new-ai-agent-muse/) - Engadget's walkthrough of setup and first tasks.

## Community

- [Muse Discord](https://discord.com/invite/sxjhCPdEG6) - Independent community server for Muse users: get help, share use cases, and discuss what's new.

## Use Cases and Inspiration

- [50 Real Ways to Use Meta Muse](https://sidsaladi.substack.com/p/meta-muse-use-cases-50-real-ways) - Fifty use cases for everyday errands, work, and family life.
- [Musecases](https://musecases.netlify.app/) - 150+ real Muse use cases collected from X.
- [What People Are Actually Doing with Meta Muse](https://learnaiwithmariah.com/guides/meta-muse-use-cases/) - Roundup of what early users are doing with Muse.
- [Ship with Muse](https://shipwithmuse.live/) - Curated catalog of 1,078+ real builds made with Meta Muse, each linked to its public source.
- [Cal AI Alternative: Turn Meta Muse Into Your Calorie Tracker](https://sidsaladi.substack.com/p/cal-ai-alternative-turn-meta-muse) - A 15-day experiment using Muse as a free calorie logger with one setup prompt, pitched as a real alternative to a paid tracking app.

## Tips and Best Practices

> [!TIP]
> **Give context:** say who the task is for, what it is for, and what a good result looks like. **Name the format:** a table, a list, a PDF, or a short text. **Set boundaries:** for example, "Only search my email, not my messages." **Start small:** begin with low-risk tasks and read-only access, then grant more as you build trust.

- [How Muse Handles Your Privacy, Safety, and Security](https://www.meta.com/help/artificial-intelligence/1047255454427887/) 🎖️ - Help Center article on data access, approvals, and controls.
- [Meta Muse Features and Privacy Guide](https://www.digitalapplied.com/blog/meta-muse-personal-ai-agent-guide) - Overview of capabilities alongside the privacy settings worth changing.
- [How to Make Muse Run Your Money While You Sleep](https://x.com/ian_finlay/status/2103206219599274464) - Eight copy-paste finance automations with scheduling and safety setup.
- [The Unofficial Muse Handbook](https://omnilenscodex.substack.com/p/the-unofficial-muse-handbook) - Evidence-labeled handbook on what jobs fit Muse, where the evidence is strongest, and where it still fails.
- [Automating Real Work with Muse: Connectors + Scheduled Tasks](https://dev.to/ying_liao_0a481102ff971b4/automating-real-work-with-muse-connectors-scheduled-tasks-58co) - Hands-on guide to Muse's two automation primitives: structuring connectors and scheduled tasks around outcomes, not steps.

## Connectors and Integrations

Connectors give Muse access to your services, such as email, calendar, shopping, and smart home.

- [Meta AI Connectors](https://dev.meta.ai/products/connectors) 🎖️ - Developer platform for building connectors that Muse can use.
- [What the Muse Connector Application Asks For](https://stacktr.ee/blog/muse-connector-platform) - Walkthrough of the connector platform's application form.
- [dowser](https://github.com/harris-ryder/dowser) - Read-only MCP connector that finds the money hiding in your life; works with Muse and other agents.
- [muse-linkedin-connector](https://github.com/gops22/muse-linkedin-connector) - Custom connector linking Muse to LinkedIn.
- [muse-atlassian-skill](https://github.com/RobertDeRose/muse-atlassian-skill) - Workspace skills giving Muse Jira and Confluence access: search, read, create, and update from chat.

## Community Tools

Open-source projects built for Muse. Review the code and the permissions a tool asks for before you connect it.

- [Muse Mac Connector](https://github.com/dkm90x/muse-mac-connector) - macOS app that lets Muse perform actions on your Mac that you approve.
- [Muse Proxy](https://github.com/NeedsChloesure/muse-proxy) - Scoped API-key gateway that lets Muse reach self-hosted CalDAV and CardDAV servers without storing passwords.
- [PIL](https://github.com/pjpoulose/PIL) - Muse skill that turns your saved Instagram posts into a private, searchable knowledge base.
- [Agent Connector Launch Kit](https://github.com/camirian/agent-connector-launch-kit) - Starter kit for building OpenAPI-based connectors for Muse, with test tooling and notes from a real submission.
- [burner](https://github.com/useburner/burner) - Skill and command-line tool that lets Muse use the apps on a spare Android phone.
- [Muse Gadget SDK](https://github.com/facebookincubator/muse-gadget-sdk) - Meta's open-source ESP32 firmware and Linux SDK for building your own Muse hardware: displays, buttons, sensors, and actuators.
- [Muse Pocket](https://github.com/viticci/muse-pocket) - E-paper Muse companion for the Xteink X4 Pro e-reader, showing your Muse's character and live status, built on the Gadget SDK.
- [Muse-Chat-MCP](https://github.com/duclm1x1/Muse-Chat-MCP) - MCP server plus OpenAI-compatible shim that drives your own logged-in Chrome for muse.ai. Browser-automation approach; review what it can touch before connecting.
- [muse-plex-skill](https://github.com/RobertBergman/muse-plex-skill) - Gadget skill that plays music from your Plex server on a Bluetooth speaker attached to the Muse device.

Find more on the [`meta-muse` topic](https://github.com/topics/meta-muse).

## Community Builds

What people are building with Muse and the Gadget SDK: hardware ports, demos, and real projects. Early days, expect rough edges.

- [musechan](https://github.com/Tjtelenda/musechan) - Muse on a StackChan: the Gadget SDK ported to the M5Stack StackChan (CoreS3), with head servos, live face control, and pet reactions.
- [muse-gadget-xiaozhi](https://github.com/moerdowo/muse-gadget-xiaozhi) - Muse's gadget UI (pixel character, push-to-talk, captions) running on xiaozhi.me voice-AI hardware (ESP32-S3).
- [muse-gadget-psp](https://github.com/wobsoriano/muse-gadget-psp) - Muse running natively on a Sony PSP: hold R to talk, replies on screen and out loud, built on a C port of the Gadget SDK (needs PSP-3000 + custom firmware).
- [muse-ai-passport](https://github.com/timzenxia/muse-ai-passport) - Unofficial port of the Gadget SDK firmware to the FoloToy AI Passport (ESP32-C3) with push-to-talk.
- [homeassistant-addon-muse-gadget](https://github.com/Josh-Archer/homeassistant-addon-muse-gadget) - Home Assistant add-on that bridges Meta Muse via the Gadget SDK.
- [muse-gadget-c6-n16](https://github.com/assix/muse-gadget-c6-n16) - Gadget SDK bring-up on a generic ESP32-C6-N16 (no PSRAM), with board overlay and notes.
- [muse-arr](https://github.com/vocino/muse-arr) - Talk to your Sonarr, Radarr, and Jellyfin media stack from Muse: a Linux gadget on your home LAN that lets your phone's Muse agent queue movies and shows without SSH.
- [muse-r1](https://github.com/cameronapak/muse-r1) - Resurrect a Rabbit r1 as a push-to-talk Muse gadget: native Android Home app running on LineageOS 21, with full build docs, limitations, and rollback notes.
- [waveshare-muse-gadget-sdk](https://github.com/wupsbr/waveshare-muse-gadget-sdk) - Gadget SDK on three Waveshare ESP32-S3 boards (LCD 1.85C, AMOLED 1.43C and 1.8) with spoken replies via ElevenLabs, unsolicited pushes, touch volume, and battery level.
- [muse-gadget-everywhere](https://github.com/hypery11/muse-gadget-everywhere) - Open-source Android runtime that turns phones, tablets, and TVs into programmable Muse gadgets: display, media, voice, camera, and local automation.
- [Muse-charm-mosaico](https://github.com/samyeei/Muse-charm-mosaico) - Voice AI companion on ESP-Mosaico hardware with push-to-talk, eight animated character states, and Muse-generated personas.
- [luci-muse-gadget](https://github.com/burndown/luci-muse-gadget) - Runs the Gadget SDK Linux client on OpenWrt routers with a LuCI page, so your router shows up as a Muse gadget.
- [muse-gadget-macos](https://github.com/rjohnt/muse-gadget-macos) - CoreBluetooth adapter that pairs a Mac with the Muse app as a display gadget, with a live browser preview.

## Where to Use Muse

- [Everything We Announced at Meta Connect 2026](https://www.meta.com/blog/meta-connect-2026-everything-we-announced/) 🎖️ - Includes Muse on AI glasses and new connectors.
- [Muse Charm](https://www.meta.com/muse-charm/) 🎖️ - Keychain-sized companion device for Muse, announced at Connect 2026.
- [Muse Is Coming to Meta's AI Glasses](https://www.engadget.com/2267210/meta-muse-ai-agent-smart-glasses/) - Engadget on using Muse hands-free.
- [Meta's Muse launches on iPad just a month after its mobile debut](https://techcrunch.com/2026/10/07/metas-muse-launches-on-ipad-just-a-month-after-its-mobile-debut/) - TechCrunch on Muse's dedicated iPad app and the new connectors it shipped with, including Notion, Granola, and a small-business suite.

## Privacy, Safety, and Security

- [How We Built Safety into Muse](https://research.meta.ai/blog/security-and-safety-for-ai-agents-our-approach-with-muse) 🎖️ - Meta's write-up on how Muse is secured.
- [Meta Patched Muse's Zero-Day, but Security Teams Still Lack Visibility](https://venturebeat.com/security/meta-patched-muses-zero-day-but-security-teams-still-lack-visibility-into-what-the-agent-can-access) - VentureBeat on what the agent can access at work.
- [Meta's Muse AI Assistant Has a Zero-Day](https://www.malwarebytes.com/blog/bugs/2026/09/metas-muse-ai-assistant-has-a-zero-day-that-can-turn-it-into-a-mac-backdoor) - Malwarebytes on the Mac vulnerability that Meta patched within a day.
- [Meta's New Muse AI Agent Read My Private Messages](https://www.inc.com/jason-aten/metas-new-muse-ai-agent-read-my-private-messages-i-never-asked-it-to/91408202) - Inc. on how broad permissions play out in practice.
- [Meta Muse Privacy Review](https://www.neoteo.com/en/a-meta-muse-hands-on-review-found-task-help-and-data-prompts) - Multi-day test focused on how often Muse asks for sensitive data.
- [Should You Let Muse Manage Your Money?](https://finance.yahoo.com/personal-finance/banking/article/metas-muse-says-it-can-manage-your-money-should-you-let-it-141040045.html) - Yahoo Finance on the risks of connecting financial accounts.

- [I Asked Meta's Muse for Its Filesystem and It Sent Me 6.8 GB](https://www.reddit.com/r/BetterOffline/comments/1wpdpnr/i_asked_metas_muse_for_its_filesystem_and_it_sent/) - Hands-on experiment showing Muse handing over its filesystem, with active community discussion.
- [Before You Connect Your Inbox to Meta Muse](https://x.com/ronyspark/status/2104077587647492523) - Clause-by-clause analysis of Muse's privacy policy and ToS for connecting your inbox.
- [Muse Plaid Bank Linking: What It Can Actually See](https://www.explainx.ai/blog/meta-muse-plaid-bank-account-linking-2026) - Independent breakdown of Muse's Plaid bank linking: read-only balances and transactions, not a payment rail.
- [Meta's Muse Sent a Stranger to a User's Door](https://memeburn.com/metas-muse-sent-a-stranger-to-a-users-door-its-permission-settings-explain-why/) - The Marketplace address leak, a three-week timeline of Muse privacy incidents, and the approval-model weakness behind them, with settings to tighten.
- [AI personal agents are having a moment. Are they safe to use?](https://www.usatoday.com/story/tech/2026/10/01/ai-personal-agent-security/91992649007/) - USA Today: a reviewer's Muse gave away his home address, accepted a lowball Marketplace offer, and claimed he was at a pickup spot; Meta's explanation, reviewed transcripts, and Forter/Visa data.
- [Meta Muse: Personal Agent + Sentinel VM Security](https://www.explainx.ai/blog/meta-muse-personal-agent-launch-sentinel-vm-security-2026) - A teardown by explainx.ai of the Secure VM and Sentinel architecture: where credentials live, the five anti-prompt-injection layers, and the public bug bounty.
- [Dox for Me, O Muse](https://newsletter.hntrbrk.com/p/dox-for-me-o-muse-metas-new-ai-agent) - Hunterbrook investigation: Muse compiled lists of real Facebook and Instagram accounts in vulnerable groups on plain-language request, with safeguards easily evaded; Meta asked for details, no comment.
- [Meta Rushed to Fix Muse 'VM Escape' Vulnerability Soon Before Launch](https://www.404media.co/meta-rushed-to-fix-muse-vm-escape-vulnerability-immediately-before-launch/) - 404 Media on the pre-launch scramble to fix KVM escape flaws that could have let a Muse user reach Meta's internal databases, and the engineers who still call that boundary risky.
- [Muse Creates Detailed Profiles of All Your Friends and Family](https://www.wired.com/story/muse-creates-detailed-profiles-of-all-your-friends-and-family/) - Wired on the internal instructions a researcher pulled from Muse: an hourly process that keeps a page on every person in a user's life, including people who never installed Muse.

## Reviews and Hands-On

- [Meta Says Its Muse AI Agent Can Do Things for You. I Put It to the Test](https://www.cnn.com/2026/09/23/tech/meta-muse-ai-agent) - CNN's hands-on with real errands.
- [I Put Meta's Muse AI Agent to Work](https://www.barrons.com/articles/meta-muse-ai-review-29077e2f) - Barron's test by a non-power user: canceling subscriptions and finding a doctor, including what it got wrong.
- [I Tried Meta's Muse AI Agent. It's Helpful and Scary at the Same Time.](https://www.wsj.com/tech/personal-tech/meta-muse-ai-agent-review-ab956101) - WSJ's Nicole Nguyen spends a week on real errands with Muse, then weighs the privacy tradeoffs.

## News and Analysis

- [Meta wants your next gadget to be Muse-infused](https://techcrunch.com/2026/10/02/meta-wants-you-to-build-your-own-muse-gadget/) - TechCrunch on the open-source Muse Gadgets launch, the free Home Link dongle giveaway, and Meta's pitch to hardware hackers.
- [Don't Let the Adorable AI Agents Fool You](https://www.engadget.com/2275148/dont-let-the-adorable-ai-agents-fool-you/) - Karissa Bell argues Muse's cute Jolly avatar hides the real risk of broad account access, and gets the backstory on the viral Marketplace address mix-up (an "allow always" misunderstanding).
- [Musing About Meta's Muse](https://paulkedrosky.com/musing-about-metas-muse/) - Paul Kedrosky, after a couple of weeks on email and calendar scanning, argues Muse's real shift is its ambient invisibility, not the chatbot.
- [Everything New Coming to Muse](https://techcrunch.com/2026/09/23/everything-new-coming-to-metas-ai-agent-muse/) - TechCrunch's roundup of the Connect 2026 announcements.
- [Meta Debuts Its Muse AI Agent. Will Consumers Trust It?](https://techcrunch.com/2026/09/08/meta-debuts-its-muse-ai-agent-will-consumers-trust-it/) - TechCrunch's launch coverage.
- [Meta Is Putting Its Muscle Behind Muse](https://techcrunch.com/2026/09/25/meta-is-putting-its-muscle-behind-muse-as-the-ai-app-takes-off/) - TechCrunch on Muse's early growth.
- [Personal AI Agents Face a Public Reckoning](https://www.cnbc.com/2026/09/08/meta-personal-ai-agents-public-reckoning-privacy-safety.html) - CNBC on the privacy and safety debate around Muse.
- [Stratechery on Muse](https://stratechery.com/topic/digital-assistants/muse/) - Ben Thompson's ongoing strategic analysis.
- [Meta's New AI Agent Is an Instant Hit](https://www.wsj.com/tech/ai/meta-ai-agent-muse-reactions-5bf236af) - WSJ on Muse's first two weeks: the Amazon block, trust surveys, and revenue projections.
- [Spotify Is First Music Service to Connect to Meta Muse](https://musically.com/2026/09/24/spotify-is-first-music-service-to-connect-to-meta-muse-ai-agent/) - Music Ally on Spotify's Muse connector: playback, playlists, and podcast controls by conversation.
- [Meta expands Muse AI agent for small businesses](https://www.reuters.com/business/media-telecom/meta-expands-muse-ai-agent-small-businesses-2026-09-29/) - Reuters on Muse for Small Business: connectors for Shopify, QuickBooks, Slack, and more.

## Videos and Podcasts

- [Mark Zuckerberg on Muse](https://sources.news/p/mark-zuckerberg-meta-muse-ai-podcast-interview) - Sources podcast interview about the vision behind Muse.
- [Mark Zuckerberg Interview at Connect](https://www.nbcnews.com/tech/tech-news/mark-zuckerberg-interview-connect-audio-glasses-muse-ai-killing-us-rcna599257) - NBC News on Muse, glasses, and Meta's AI plans.
- [Meta Muse Review: Can It Actually Run Your Life?](https://www.youtube.com/watch?v=wJC_SQJ7msc) - Seven-day test of ten real errands, scored: five done right, two done wrong, two stalled.
- [Muse Just Stole the AI Spotlight](https://techcrunch.com/podcast/metas-muse-just-stole-the-ai-spotlight-from-openai-and-anthropic/) - Equity episode on Muse outpacing ChatGPT's early numbers and what it means for startups building on agents.
- [Muse Is Why Meta Has No Business Building the Agentic Web](https://www.youtube.com/watch?v=ybCF89NP4KE) - Critical walkthrough sorting Zuckerberg's Muse privacy and security claims by what exists today versus what is promised.

- [Meta Muse Tips & Tricks | 6 Features You Should Be Using](https://www.youtube.com/watch?v=jbGYcOWvCZI) - Hands-on walkthrough of price tracking, Instagram integration, the credential store, and Muse Wallet.

## Contributing

Found something great? Read the [contribution guidelines](contributing.md), then submit it. We add fewer things than we are sent, on purpose.
