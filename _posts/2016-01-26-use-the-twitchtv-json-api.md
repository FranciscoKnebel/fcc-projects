---
layout: post
title: Use the Twitchtv JSON API
tags: [Zipline, Front End]
author: Francisco Knebel
codepen: MKVBxJ
github: https://github.com/FranciscoKnebel/fcc-Twitch
---

- User Story: I can see whether Free Code Camp is currently streaming on Twitch.tv.

- User Story: I can click the status output and be sent directly to the Free Code Camp's Twitch.tv channel.

- User Story: if a Twitch user is currently streaming, I can see additional details about what they are streaming.

- User Story: I will see a placeholder notification if a streamer has closed their Twitch account (or the account never existed). You can verify this works by adding brunofin and comster404 to your array of Twitch streamers.

UPDATE: Due to a change in conditions on API usage explained here Twitch.tv now requires an API key, but we've built a workaround. Use https://wind-bow.gomix.me/twitch-api instead of twitch's API base URL (i.e. https://api.twitch.tv/kraken ) and you'll still be able to get account information, without needing to sign up for an API key.
