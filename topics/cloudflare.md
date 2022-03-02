Here you'll find non-exhaustive information on how Cloudflare works in our domains and services.

# What's Cloudflare?

Cloudflare is one of the biggest networks operating on the Internet. People use Cloudflare services for the purposes of increasing the security and performance of their web sites and services.

## How does Cloudflare help Filo?

Cloudflare helps Filo by protecting its website and API from malicious people.

# Cloudflare bans

It's essential that we protect our website from people with malicious intent, for this we are using bans on Cloudflare. Below you'll find information about these bans and how they can affect you.

## What's a Cloudflare ban?

A Cloudflare ban is a sanction that will deny you access to our website. The ban can be given by:
- Your IP address.
- Your ISP[^1].
- Your IP address range[^2].
- Your User-Agent.
- Your country.
- The type of browser [🕵️](https://www.torproject.org/) you use.

## How can I identify a Cloudflare ban?

You'll be able to quickly identify a Cloudflare ban, because you'll receive a 403 error followed by an error page titled "Access Denied".

<p align=center><img src="https://raw.githubusercontent.com/filobot/docs/main/resources/Cloudflare%20ban.png" alt="" /><br>

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
