Here you'll find non-exhaustive information on how Cloudflare works in our domains and services.

# What's Cloudflare?

Cloudflare is one of the biggest networks operating on the Internet. People use Cloudflare services for the purposes of increasing the security and performance of their web sites and services.

## How does Cloudflare help us?

Cloudflare helps us keep our website safe from attackers with malicious intent and speeds up our website globally.

# About Cloudflare Bans

A very important task for Cloudflare is to protect us from DDoS attacks that could take our service offline, and to do this, we automate systems so that bans can be sent to attackers or devices victimized by the attacker.

> We take every ban we issue very seriously, and we won't hesitate to prioritize protecting ourselves in these types of situations.
> {.is-info}

## What's a Cloudflare ban?

There are two types of prohibitions that we make use of:
- **[Temporary bans]()**: Responded with the code 403 followed by the message "The owner of the website has banned your IP address.".
- **[Permanent bans]()**: Responded with The code 403 followed by the message "Access Denied. This website uses Cloudflare to protect itself from attacks.".

Objects that can be banned:
- Your IP address.
- Your ISP[^1].
- Your IP address range[^2].
- Your User-Agent.
- Your country.
- The type of browser [🕵️](https://www.torproject.org/) you use.

> When a ban is issued, you are prohibited from accessing any services or pages on our website while the ban is in effect.
> {.is-danger}

### Temporary bans

These are bans that typically expire after **1 hour** of being issued.

> These sanctions can't be appealed.
> {.is-danger}

### Permanent bans

These bans never expire once they are issued.

> If you think your ban is wrong, please **[contact us]()**.
> {.is-info}

> Making an appeal doesn't ensure you'll be unbanned, it only ensures that we'll thoroughly review your case.
> {.is-warning}

# What actions are banned from Cloudflare?

> Not all actions are listed here for security reasons.
> {.is-warning}

## Excess 429 errors[^3] in the API

The API has two types of rate limits:
- Individual or specific.
- Global or common.

The individual or specific rate limits are more restrictive, but, as a consequence, exceeding this limit won't result in a ban on Cloudflare. These limits are specific to each API endpoint.

Global or common rate limits are restrictive in the long term, that's, if you make a large number of requests per minute, you'll likely receive a global rate limit.

If you exceed 5 times the warning for exceeding the global request quota in less than 1 hour, your IP address will be temporarily banned for 1 hour.

## Excess 429 errors[^3] in the rest of the service

The rest of our website has only one type of ratelimits:
- Global or common.

Global or common rate limits are restrictive in the long term, that's, if you make a large number of requests per minute, you'll likely receive a global rate limit.

If you exceed 5 times the warning for exceeding the global request quota in less than 1 hour, your IP address will be temporarily banned for 1 hour

[^1]: Internet Service Provider: We refer to the company that provides you with the internet connection service.
[^2]: You can find out your IP address range by **[clicking here](https://www.calculator.net/ip-subnet-calculator.html)**.
[^3]: 429 errors tell browsers and applications making requests of any kind to our website that your rate limit is being exceeded.
