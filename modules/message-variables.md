<!-- Variable List -->
# Message Variables

The variables listed below have an effect on the **[Welcomes]({{LINKS_WIKI}}/modules/welcomes)** & **[Farewells]({{LINKS_WIKI}}/modules/farewells)** modules, specifically on the Message functionality.

## User Variables {.tabset}

### \{{@user}}

Returns the mention of the user.

**Example**: @DiscordUser#0000

### \{{user.id}}

Returns the ID of the user.

**Example**: 123456789123456789

### \{{user.name}}

Returns the name of the user.

**Example**: DiscordUser

### \{{user.discriminator}}

Returns the discriminator of the user.

**Example**: #0000

### \{{user.tag}}

Returns the username & discriminator of the user.

**Example**: DiscordUser#0000

### \{{user.avatar}}

Returns the avatar id of the user.

**Example**: Avatar_ID

### \{{user.avatarURL}}

Returns the avatar url of the user.

**Example**: https://cdn.discordapp.com/avatars/User_ID/Avatar_ID.<jpg/gif>

### \{{user.registrationDate}}

Returns the registration date of the user.

**Example**: 05/13/2021 @ 00:00 (x years ago)

### \{{user.url}}

Returns the url of the user.

**Example**: https://discord.com/users/User_ID

## Server Variables {.tabset}

### \{{server}}

Returns the name of the server.

**Example**: Awesome server

### \{{server.name}}

Returns the name of the server.

**Example**: Awesome server

### \{{server.id}}

Returns the id of the server.

**Example**: 123456789123456789

### \{{server.icon}}

Returns the icon id of the server.

**Example**: Icon_ID

### \{{server.iconURL}}

Returns the icon url of the server.

**Example**: https://cdn.discordapp.com/icons/Server_ID/Icon_ID.<jpg/gif>

### \{{server.owner}}

Returns the mention of the owner of the server.

**Example**: @DiscordUser#0000

### \{{server.ownerID}}

Returns the id of the owner of the server.

**Example**: 123456789123456789

### \{{server.members}}

Returns the member count of the server.

**Example**: 123,456

### \{{server.memberCount}}

Returns the member count of the server.

**Example**: 123456

### \{{server.inviteSplash}}

Returns the invite splash id of the server.

**Example**: Invite_Splash_ID

### \{{server.inviteSplashURL}}

Returns the invite splash url of the server.

**Example**: https://cdn.discordapp.com/splashes/Server_ID/Invite_Splash_ID.jpg

### \{{server.banner}}

Returns the banner id of the server.

**Example**: Banner_ID

### \{{server.bannerURL}}

Returns the banner url of the server.

**Example**: https://cdn.discordapp.com/banners/Server_ID/Banner_ID.<jpg/gif>

### \{{server.vanityURL}}

Returns the vanity url of the server.

**Example**: https://discord.gg/Vanity_Code

### \{{server.description}}

Returns the description of the server.

**Example**: An awesome server to chat!

### \{{server.discoverySplash}}

Returns the discovery splash id of the server.

**Example**: Discovery_Splash_ID

### \{{server.discoverySplashURL}}

Returns the discovery splash url of the server.

**Example**: https://cdn.discordapp.com/discovery-splashes/Server_ID/Discovery_Splash_ID.jpg

### \{{server.verificationLevel}}

Returns the verification level of the server.

**Example**: None

### \{{server.nsfwLevel}}

Returns the NSFW level of the server.

**Example**: None

### \{{server.afkTimeout}}

Returns the afk timeout of the server.

**Example**: 500 seconds

### \{{server.afkChannel}}

Returns the afk voice channel of the server.

**Example**: <#123456789123456789>

### \{{server.afkChannelID}}

Returns the afk voice channel id of the server.

**Example**: 123456789123456789

### \{{server.systemChannel}}

Returns the system channel of the server.

**Example**: <#123456789123456789>

### \{{server.systemChannelID}}

Returns the system channel id of the server.

**Example**: 123456789123456789

### \{{server.rulesChannel}}

Returns the rules channel of the server.

**Example**: <#123456789123456789>

### \{{server.rulesChannelID}}

Returns the rules channel id of the server.

**Example**: 123456789123456789

### \{{server.publicUpdatesChannel}}

Returns the public updates channel of the server.

**Example**: <#123456789123456789>

### \{{server.publicUpdatesChannelID}}

Returns the public updates channel id of the server.

**Example**: 123456789123456789

### \{{server.premiumTier}}

Returns the premium tier of the server.

**Example**: Tier 3

### \{{server.premiumSubscriptions}}

Returns the premium subscriptions count of the server.

**Example**: 123,456

### \{{server.premiumSubscriptionsCount}}

Returns the premium subscriptions count of the server.

**Example**: 123456

### \{{server.explicitContentFilter}}

Returns the explicit content filter of the server.

**Example**: Disabled

### \{{server.mfaLevel}}

Returns the mfa level of the server.

**Example**: Enabled

### \{{server.creationDate}}

Returns the creation date of the server.

**Example**: 05/13/2021 @ 00:00 (x years ago)

### \{{server.language}}

Returns the language of the server.

**Example**: en-US

### \{{server.features}}

Returns the features of the server.

**Example**: Community, news, animated icon
