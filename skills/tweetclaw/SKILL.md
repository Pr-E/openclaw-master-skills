---
name: tweetclaw
description: "Install and use the @xquik/tweetclaw OpenClaw plugin for X/Twitter search, posting, follower export, media workflows, monitors, webhooks, direct messages, and giveaway draws via Xquik."
homepage: https://github.com/Xquik-dev/tweetclaw
metadata: {"openclaw":{"emoji":"🐦","skillKey":"tweetclaw","primaryEnv":"XQUIK_API_KEY","requires":{"bins":["openclaw"],"env":[]},"install":[{"id":"openclaw-plugin","kind":"openclaw-plugin","package":"@xquik/tweetclaw","label":"Install TweetClaw from npm"}],"tags":["twitter","x","tweets","openclaw-plugin","xquik","automation","monitoring","giveaway"]}}
---

# TweetClaw

Use TweetClaw when an OpenClaw agent needs structured X/Twitter automation through Xquik.

## Install

```bash
openclaw plugins install @xquik/tweetclaw
```

TweetClaw installs before credentials are configured. The free `explore` tool can show available endpoints without making live API calls.

## Configure

For account-backed reads, writes, extraction jobs, monitors, webhooks, media workflows, direct messages, and giveaway draws, configure an Xquik API key in OpenClaw plugin config.

```bash
openclaw config set plugins.entries.tweetclaw.config.apiKey "$XQUIK_API_KEY"
```

Keep API keys out of chats, docs, logs, screenshots, and shell history. Prefer environment variables so OpenClaw stores the secret locally without exposing it to the agent session.

MPP mode is optional and read-only. Use it only for supported pay-per-use read endpoints.

## Use Cases

- Search tweets and search tweet replies.
- Post tweets and post tweet replies after explicit user approval.
- Export followers and look up users.
- Upload media, download authenticated tweet media, and create gallery links.
- Send direct messages after explicit user approval.
- Monitor tweets and deliver webhook events.
- Run giveaway draws from tweet replies or engagement data.
- Explore Xquik API routes from OpenClaw without exposing credentials.

## Safety Rules

Confirm before any visible, state-changing, paid, private, or recurring action. Show the account, target, action, text, media list, and requested limits before sending.

Do not use TweetClaw for spam, harassment, deceptive engagement, credential collection, impersonation, platform evasion, or bulk unsolicited direct messages.

When only MPP mode is configured, do not attempt writes, direct messages, monitors, webhooks, uploads, media downloads, extraction jobs, draws, or private account reads.

## Verify

```bash
openclaw plugins inspect tweetclaw --runtime
openclaw skills info tweetclaw
```

## Links

- GitHub: https://github.com/Xquik-dev/tweetclaw
- npm: https://www.npmjs.com/package/@xquik/tweetclaw
- ClawHub: https://clawhub.ai/plugins/@xquik/tweetclaw
- Xquik: https://xquik.com
