---
title: "HTTP"
heading: "Admin's Guide to HTTP Apps"
description: "TODO"
weight: 100
---

External service providers can offer "remote" apps already deployed as HTTP
services.

Internal organization-specific apps can also be developed and run as HTTP
services on the existing hosting infrastructure, for example, using `systemd`.
It's important that your internal apps are only reachable by the Mattermost
server, and not from the public internet.

To install an HTTP app use `/apps install http {URL-to-manifest.json}` command in
Mattermost.
