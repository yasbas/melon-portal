# 0001: License

Date: 2026-11-23

## Decision

AGPL-3.0

## Why

I want anyone to be able to use the portal, change it and self-host it, also commercially.

But I may offer a hosted version later. With AGPL, if someone changes the code and runs it as a service for other people, they have to publish their changes too. So nobody can take it and sell a closed SaaS version of it.

WordPress plugins that check licenses through the portal's API are separate programs, so they are not affected. If I later write a client library that goes inside the plugins, it gets its own MIT or GPL license.

## What I gave up

MIT would get more casual adoption. Some companies don't allow AGPL software at all.
