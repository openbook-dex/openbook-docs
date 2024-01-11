# FAQ

## What is OpenBook?

OpenBook is an open source, permissionless and community-led central limit
orderbook that serves as the liquidity layer upon which many of the largest
DeFi protocols on Solana are built.

See [here](https://x.com/m_schneider/status/1591636068650352640?s=61&t=Wv1hCdAly84RMB_iLO0iIQ)
for more information about the founding of OpenBook

## Is OpenBook a continuation of Serum?

OpenBook V1 is a fork of the Serum V3 codebase. However, we are separate
protocols with separate teams. OpenBook V2 is a complete rewrite that
definitively breaks the bond with Serum, vastly expanding OpenBook’s technical
capabilities.

See [here](https://x.com/openbookdex/status/1720402140919648263?s=61&t=Wv1hCdAly84RMB_iLO0iIQ)
for more information about OpenBook V2.

## How do I know if I’m using OpenBook V1 or V2?

Presently, all of the live integrations (with the exception of the MetaDAO) are
using OpenBook V1. This will be changing shortly.

## I have some old SRM tokens. What can I do with them?

Not much. OpenBook is an entirely separate protocol that has no affiliation
whatsoever with the SRM tokens.

## Does OpenBook have a token?

We do not.

## I had some old open orders on Serum. Can I close them?

Yes! Although the ecosystem has largely moved on from Serum, the orderbook
still exists on-chain. As such, your old open orders are still out there and
can be closed.

See [here](https://discord.com/channels/1044763038265389147/1044763039813087242/1105593936707326014)
for more information.

## What is a crank and why does OpenBook use one?

- [The short answer](https://discord.com/channels/1044763038265389147/1044763040253485136/1063594456680517773)
- [The long answer](https://x.com/openbookdex/status/1727309884159299929?s=20)

## How do I crank a market?

You can crank markets on any of the OpenBook GUIs, use
[https://openbook-explorer.xyz/](https://openbook-explorer.xyz/),
or send the instruction yourself using
[this](https://github.com/SpaceMonkeyForever/openbook-cranker)

## How do I create a new market?

Most of the OpenBook GUIs as well as Raydium and OpenBook Explorer can be used
to create new V1 markets. You can also do it programmatically from
[here](https://github.com/openbook-dex/openbook-ts/blob/master/packages/openbook/src/instructions.js#L172)

## Why does it cost 2.8 Sol to create a new market?

That’s what it costs to rent the blockspace necessary to create a fully
functional market on Solana. You can reduce the size of your market to reduce
the cost but it can have adverse effects on your market’s functionality.

See [here](https://discord.com/channels/1044763038265389147/1044763039813087247/1189964378682962051)
for more information about order book length, request queue length and event queue length.

## I want to create a market for 0.3 Sol. Will you help me?

We will not. Markets of that size are virtually unusable and provide no
tangible benefit to OpenBook. Our team’s resources are better spent elsewhere.

## Can I DM a team member or mod for help?

We strongly encourage all questions and discussion to take place in public
channels, both for safety and for the learning of other community members who
might have a similar question in the future. If there is something that truly
needs to remain private, a direct message may be appropriate. However, that can
be determined via a preliminary discussion on the public channels.

## Can I close a market and retrieve rent?

In V2, you can close markets and retrieve rent. In V1, you cannot.

## I have a question about creating an LP on Raydium…

Ask Raydium. They know their protocol better than we do.

## What is the fee structure on OpenBook?

On OpenBook V1, takers pay 4 bps - 2 go to the maker and 2 go to the UI as a
referral fee. If you’re trading through the SDK, you can set yourself as the
referral and save 2 bps.

On OpenBook V2, fees are customizable and vary from market to market.

## How can I contribute?

As a community-led and fully open source project, we strongly encourage anyone
with the requisite technical capacity and a little bit of ambition to
contribute to our repos. We also love integrations and introductions to new
teams, market makers, publicity and generous donations to Brian Long’s cranking
tip jar: `BLcmYWJXZzM5ugabv8t9MGt5uZeQpLeeVHJEucb6JoM1`
