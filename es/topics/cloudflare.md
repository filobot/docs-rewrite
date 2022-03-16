Here you'll find non-exhaustive information on how Cloudflare works in our domains and services.

# What's Cloudflare?

Cloudflare is one of the biggest networks operating on the Internet. People use Cloudflare services for the purposes of increasing the security and performance of their web sites and services.

## How does Cloudflare help us?

Cloudflare helps us keep our website safe from attackers with malicious intent and speeds up our website globally.

# About Cloudflare bans

A very important task for Cloudflare is to protect us from DDoS attacks that could take our service offline, and to do this, we automate systems so that bans can be sent to attackers or devices victimized by the attacker.

> We take every ban we issue very seriously, and we won't hesitate to prioritize protecting ourselves in these types of situations.
  {.is-info}

There are two types of bans that we make use of:
- **Temporary bans**: Responded with the code 403 followed by the message "Access Denied".
- **Permanent bans**: Responded with The code 403 followed by the message "Access Denied".

\* The type of ban received will also be specified.

> In some situations, a [captcha](https://www.hcaptcha.com) may be required before accessing our website, as an alternative to Cloudflare bans.
  {.is-info}

Objects that can be banned:
- Your IP address.
- Your Internet Service Provider[^1].
- Your IP address range[^2].
- The User-Agent of your browser.
- Your country.
- The type of browser [🕵️](https://www.torproject.org/) you use.

\* Not all objects are mentioned here.

> When a ban is issued, you are banned from accessing any services or pages on our website while the ban is in effect.
  {.is-danger}

### Temporary bans

These are bans that typically expire after **1 hour** of being issued.

> These sanctions can't be appealed.
  {.is-danger}

### Permanent bans

These bans never expire once they are issued.

> If you think your ban is unfair or wrong, appeal the ban by **[clicking here](https://forms.gle/Pdig38H5gn6XfyW76)**.
  {.is-info}

> Making an appeal doesn't ensure you'll be unbanned, it only ensures that we'll thoroughly review your case.
  {.is-warning}

# What actions are banned?

> Not all actions are listed here for security reasons.
  {.is-warning}

## Excess 429 errors[^3]

Our service has two types of rate limits:
- **Individual or specific** (API): They are different for each endpoint and restrictive in the short term. Exceeding these ratelimits doesn't result in a Cloudflare ban.
- **Global or common** (Generic): They are the same for each endpoint and restrictive in the long term. Exceeding these ratelimits does result in a Cloudflare ban.

Respect the ratelimits regardless of what they are. The API isn't publicly accessible, so we don't expect you to use it, but if you do, check the `X-RateLimit` headers to make sure you respect the rate limits.

> If you repeatedly receive a **429 errors**, there is a good chance that a Cloudflare ban will be issued. If it happens frequently you'll receive a permanent Cloudflare ban.
  {.is-danger}

[^1]: We refer to the company that provides you with the internet connection service.
[^2]: You can find out your IP address range by **[clicking here](https://www.calculator.net/ip-subnet-calculator.html)**.
[^3]: 429 errors tell browsers and applications making requests of any kind to our website that your rate limit is being exceeded.
