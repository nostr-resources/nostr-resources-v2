---
title: nostr Resources
description: "nostr is new and confusing but also really cool."
image: /images/cover.png
---

**TL;DR:** nostr[^fn-nostr] is a protocol that has the power to replace twitter,
Instagram, and all the other data silos that force various feeds down our
collective throats.

[^fn-nostr]: nostr = Notes and Other Stuff Transmitted by Relays

---

<div class="action-buttons">
  <div class="button">
    <a href="#get-started">🚀 Get Started</a>
    <a href="#learn-more">📖 Learn More</a>
  </div>
  <br/>
  <a href="#get-involved">💻 Get Involved</a>
</div>

---

> What is nostr?
>
><cite>You, probably</cite>

nostr is new and confusing but also really cool. It is **the simplest open protocol that is able to create a
censorship-resistant global "social" network** once and for all.

- It doesn't rely on any trusted central server, hence it is resilient.
- It is based on cryptographic keys and signatures, so it is tamperproof.
- It does not rely on P2P techniques, therefore it works.

It is free as in freedom and puts the user in control.

---

<center>
  <p><small><a href="#toc">↓ Table of Contents ↓</a></small></p>
</center>

---

# Get Started

While there are [many clients](#clients), the following three are currently
quite popular: Damus for iOS, Amethyst for Android, and noStrudel for Web.
Primal is often recommended too, as it works on all platforms.

Download a suitable client:

<div class="action-buttons">
  <div class="button">
    <a href="https://damus.io/" target="_blank">🍎 Damus</a>
    <a href="https://www.amethyst.social/" target="_blank">🤖 Amethyst</a>
  </div>
  <br/>
  <a href="https://nostrudel.ninja" target="_blank">🌐 noStrudel</a> &nbsp; · &nbsp;
  <a href="https://primal.net/" target="_blank">🌐 Primal</a> &nbsp; · &nbsp;
  <a href="https://coracle.social/" target="_blank">🌐 Coracle</a> &nbsp; · &nbsp;
  <a href="https://phoenix.social/" target="_blank">🌐 Phoenix</a> &nbsp; · &nbsp;
  <a href="https://iris.to/" target="_blank">🌐 Iris</a>
</div>

---

# FAQ

**What's the easiest way to create a profile?**
🦚 Going to [nstart.me](https://nstart.me/) is probably easiest. The wizard will walk you through every step.
There is also [nosta.me](https://nosta.me/), which introduces relays and other nostr activities.

**What is the best nostr client?**
🦚 There is no best. You'll have to [pick a client](#clients) according to your
tastes!

**What is the second best nostr client?**
🦚 This question is best answered by watching [this video](https://youtu.be/uDgnZn3SjLw).

**Is nostr just a twitter clone?**
🦚 No, it's way more than that. I'd suggest you browse
[nostrapps.com](https://nostrapps.com/) and try one of the more adventurous apps
yourself!

**Where do I store my "nsec" aka private key?**
🦚 Make sure read the [key management](#keys) section!

**What is an "npub"?**
🦚 Your "npub", or nostr public key, is your public identity. It is unique to
you and can be used to look up your profile and initiate a connection with you,
either via a follow, a DM, or a zap.

**What are zaps?**
🦚 Zaps are nostr's way of seamlessly transferring value between users. They are
neither "tips" nor "expensive likes," but a new way of expressing value and
counterfeit-resistant engagement. They are [sat-based][br] [tokens of appreciation](https://njump.me/nevent1qvzqqqqqqypzqmjxss3dld622uu8q25gywum9qtg4w4cv4064jmg20xsac2aam5nqy2hwumn8ghj7un9d3shjtnyv9kh2uewd9hj7qgwwaehxw309ahx7uewd3hkctcqyqx6hc4glxnhergs086yp77ne8cdt8zt5z99r4lcz88whfvtq23920ynxd7) with
perfect scarcity. They are, as one nostrich so beautifully put it, a way to say:
[keep doing you][kdy]. Zaps are flowing through the system at all times, as you
can clearly see via [zaplife.lol](https://zaplife.lol).

[br]: https://bitcoin-resources.com/
[kdy]: https://coracle.social/nevent1qqs2f66rxmq5xdcpfc4mdzded083zse8qy2mnqkayyvtzruknqmuf3gzyphydppzm7m554ecwq4gsgaek2qk32atse2l4t9ks57dpms4mmhfxaaw0q4

**How do I set up my client properly?**
🦚 Check out these guides:

- [Guide for Damus](https://nostr.how/guides/damus) (iOS)
- [Guide for Amethyst](https://nostr.how/guides/amethyst) (Android)
- [Guide for Iris](https://nostr.how/guides/iris) (Web)

**What are relays, and how do I find them?**
🦚 Read the [relays](#relays) section.

**Are all nostr apps available on the App Store?**
🦚 They are not. The existing monopolies are threatened by nostr and what it
represents. But fear not, we will build our own app stores. We have one on
Android already: [Zapstore](https://zapstore.dev/), an app store built on
nostr.

**Where do I find alternatives to existing stuff?**
🦚 Have a look at [noalt.app](http://noalt.app/)

**How do I find people to follow?**
🦚 Use various [search](#search) tools, browse [trending
notes](https://trending.relays.land/), or check out [Following._](https://following.space/) for convenient, user-curated packs of suggested follows.
You can follow topical hashtags like
[#introductions](https://nosey.vercel.app/?q=%23introductions), too. Yes, on nostr you can
follow hashtags. You can also visit [Npub.world](https://npub.world/) to search for
a specific person. Find your X/twitter friends by using this seach query: - [🔎 "verifying my account on nostr" (ppl you follow)](https://twitter.com/search?q=%22verifying%20my%20account%20on%20nostr%22&f=live&pf=1). This uses the [nostr.directory](https://www.nostr.directory/) verification
message, but the `&pf=1` limits the twitter search to only people you follow.


**I have more questions. Who can help me?**
🦚 Consult this [external FAQ](https://uselessshit.co/resources/nostr/), [asknostr](https://asknostr.site/) or use the
[#asknostr](https://nosey.vercel.app/?q=%23asknostr) hashtag in a note from any client.

---

# Learn More

nostr's design is very basic:

- There are two components: **clients** and **relays**. Each user runs a client. Anyone can run a relay.
- Every user is identified by a public key. Every post is signed. Every client validates these signatures.
- Clients fetch data from relays of their choice and publish data to other relays of their choice. A relay doesn't talk to another relay, only directly to users.

To use nostr, you need a [key](#keys) and a [client](#clients).

- Everybody runs a client. It can be a native client, a web client, etc.
- To publish something, you write a post, sign it with your key and send it to multiple relays (servers hosted by someone else, or yourself).
- To get updates from other people, you ask multiple relays if they know anything about these other people.
- Anyone can run a relay. A relay is very simple. It does nothing besides accepting posts from some people and forwarding to others.
- Relays don't have to be trusted. Signatures are verified on the client side.

## Keys

Your keys are your identity. You can think of your public key (`npub...`) as
your username and your private key (`nsec...`) as your password.

Two quick things:

- ⚠️ **DO NOT PASTE YOUR PRIVATE KEY INTO WEBSITES**[^fn-xss] ⚠️
- Store your keys securely and do not share your private key


Keys exist in two formats, `hex` and the above mentioned npub/nsec. You can use
a [key converter tool](https://github.com/rot13maxi/key-convertr)[^fn-keys] to
convert between the two formats.

[^fn-keys]: There's also the [damus.io/key](https://damus.io/key/) but DO NOT use it for private key conversions. Don't paste your private key into websites. Just don't.

[^fn-xss]: You have to trust whoever is running the website, obviously, and some clients are vulnerable to XSS attacks. A lot of people got rekt already, and had to re-build their nostr identity because of it.

Use [Alby](https://getalby.com) or [nos2x](https://github.com/fiatjaf/nos2x) to
generate your keys, or generate them using a dedicated tool like
[rana](https://github.com/grunch/rana). The aforementioned extensions will
store your keys safely (or at least more safely). Check out [this list](https://spatianostra.com/a-simple-list-of-nostr-signers/) for a sampling of key management tools.

- [Nostr in the Alby Extension](https://blog.getalby.com/nostr-in-the-alby-extension/)
- [The nos2x browser extension and why you should use it](https://youtu.be/IoLw-3ok3_M)

If you're on mobile, it is recommended to use a native signer like [Amber] on Android or
[Nostash] on iOS.

[Amber]: https://github.com/greenart7c3/Amber?tab=readme-ov-file#download-and-install
[Nostash]: https://apps.apple.com/us/app/nostash/id6744309333

You can also generate your keys by other means if you know what you're doing.[^bip85]
It's still early days, so be prepared to get rekt.

[^bip85]: [BIP-85](https://bip85.com/) is an option, for example.

## Clients

Periodically check [nostr.net](https://www.nostr.net/) which keeps a curated
list of clients or have a look at the [client comparison table](https://github.com/vishalxl/Nostr-Clients-Features-List).

Mobile clients:

- [Damus (iOS & Android)](https://damus.io/) - Twitter-style iOS/Android client, also works on MacOS[^fn-mac]
- [Amethyst (Android)](https://www.amethyst.social/) - Twitter-style Android client
- [Flotilla (Android)](https://play.google.com/store/apps/details?id=social.flotilla&hl=en_US) - DMs and group chats
- [Nostur (iOS)](https://apps.apple.com/us/app/nostur/id1672780508) - native iOS/iPad client with MacOS[^fn-mac] version
- [Openvibe (iOS & Android)](https://play.google.com/store/apps/details?id=com.plebstr.client) - Nostr, Threads, Bluesky, and Mastodon in one client.
- [Primal (iOS & Android)](https://primal.net/downloads) - Clean & performant, but not very feature-rich (yet)
- [Yakihonne (iOS & Android)](https://yakihonne.com/yakihonne-mobile-app) - Cross-platform Nostr client

There are more native clients in development, Nostros[^nostros] and Voyage[^voyage] being two of them.

[Nootti](https://nootti.com) is the first iOS native cross-posting client for Nostr, Bluesky and Mastodon. [Nos](https://nos.social/) is another iOS client that integrates with other social protocols.

Web clients:

- [primal.net](https://primal.net/) - Explore your tribe, network, and global trends
- [phoenix.social](https://phoenix.social/) - Simple interface with automatic image-upload
- [phoenix.deck](https://phoenix.social/deck) - A tweetdeck like version of the snort client.
- [noStrudel](https://nostrudel.ninja/) - Supports many NIPs inc communities, streams, blogs and more
- [coracle.social](https://coracle.social/) - Search, filters, and micro-apps
- [jumble](https://jumble.social/) - Explore content feeds by relay and create custom relay sets
- [iris.to](https://iris.to/) - Clean interface & rich in features
- [x21](https://x21.social/) - Clean interface
- [nostria](https://nostria.app/) - Explore relay feeds, topics, music, and more
- [grimoire](https://grimoire.rocks/) - A nostr client for magicians

On Android you can use the [Kiwi Browser](https://kiwibrowser.com/) to use the
[Alby](https://getalby.com) or [nos2x](https://github.com/fiatjaf/nos2x)
extension, which allows you to use any web client.

[^nostros]: [KoalaSat/nostros](https://github.com/KoalaSat/nostros)
[^voyage]: [dluvian/Voyage](https://github.com/dluvian/voyage)

There's also [Nostr Console](https://github.com/vishalxl/nostr_console),
[algia](https://github.com/mattn/algia), and
[nostr-commander](https://github.com/8go/nostr-commander-rs) if you're into CLI
stuff.

[^fn-mac]: Apple Silicone only (M1 or M2 chip)

Web clients for content creators:

- [ZapStream](https://zap.stream/) - Streaming on nostr allows for instant monetarisation of content.
- [Habla](https://habla.news/) and [yakihonne](https://yakihonne.com/) - Long-form posts on nostr similar to Medium.
- [Highlighter](https://highlighter.com/) - Client focused on reading and highlighting long-form content.
- [Shipyard](https://shipyard.pub/) - Write, schedule, and boost your notes.
- [Wavlake](https://www.wavlake.com/) - A music platform similar to Spotify.
- [Satellite.earth](https://satellite.earth/) - Focuses on reddit-like reading experience but also offers CDN media hosting and other nostr services.
- [Npub.pro](https://npub.pro/) - Nostr-based websites to show case creator content.
- [Pidgeon](https://pidgeon.lol/) - Compose and schedule notes.

Desktop clients:

- [Gossip](https://github.com/mikedilger/gossip) - Advanced, privacy-conscious Nostr desktop client with multi-relay support, secure key handling, and extensive moderation and customization options
- [Notedeck](https://damus.io/notedeck/) - Lightning fast, native, multi-account Nostr client for desktop (by Damus team)
- [more-speech](https://github.com/unclebob/more-speech) - Powerful Clojure-based Nostr client for desktop, focused on robust content moderation, curation, and advanced relay management

## Relays

Relays are simple servers that you can leave behind at any time ([so they can't
turn evil](https://youtu.be/5FbgDUQjziM)). You need to connect your client to a relay for it to work. There are
many relays & you can run your own. Check out [this video](https://youtu.be/TFH7Xr0cJ0w) for a quick tutorial on managing relays.

- [nostr.watch](http://nostr.watch/) - directory of paid and free relays
- [nostr.info](https://nostr.info/relays/) directory of known nostr relays
- [relay.tools](https://relay.tools/) - public relay browser

Run your own:

- [Set up a Nostr Relay server in under 5 minutes](https://andreneves.xyz/p/set-up-a-nostr-relay-server-in-under)[^fn-fork]
- Run a native, personal relay on Android with [Citrine](https://github.com/greenart7c3/Citrine?tab=readme-ov-file#download)
- Install [nostr-relay-tray](https://github.com/CodyTseng/nostr-relay-tray/releases) for a simple, local relay on your desktop.
- Easily host a powerful community relay with many features, on a cheap VPS with [Pyramid](https://github.com/fiatjaf/pyramid)

Paid relays:

Paid relays effectively deal with spam by charging users a small usage fee in
sats. You can set your global feed to paid relays only, which will get rid of
almost all spam.

[^fn-fork]: Fork with small modifications/fixes: [Install a nostr relay](https://www.massmux.com/install-a-nostr-relay/)

Unique relays:

Relays can also act as [content curators](https://youtu.be/CL34LnBs0OQ), unlock different ways of interacting, be the home of communities or groups, and more.
See an example of a human-curated feed [here](https://jumble.social/?r=relays.land/spatianostra).

## Tools

Managing your nostr keys AND your profile is as essential as backing up your private keys for Bitcoin!

- [Nostr Metadata](https://metadata.nostr.com/) - a profile and following list backup tool.
- [NostrSync](https://nostrsync.vercel.app/) - another service to backup profile AND nostr events.
- [Nostr Follows](https://follows.nostr.com/) - recover lost contacts/follows.
- [Nostr Delete](https://delete.nostr.com/) - request to delete any nostr event from its hosting relays.

nostr can do more than just social media.

- [Asknostr](https://asknostr.site) - Q&A platform (alternative to Quora/StackOverflow)
- [Listr](https://listr.lol/) - create and manage lists to use in supporting nostr apps.
- [nosbin](https://nosbin.com/) - pastebin over nostr.
- [Zap.Cooking](https://zap.cooking/) - create, explore or share recipes.
- [Badges](https://nostrsigil.com) - create badges and award them to your friends or followers.
- [Emojis](https://emojito.meme/) - create or use emoji packs supported on most nostr clients.
- [Pinja](https://www.yumyu.me/) - pin urls as bookmarks.
- [Lantern](https://chromewebstore.google.com/detail/lantern/jjoijlenmgefkaeiomoaelcljfibpcgh) - highlight, annotate, and discuss anything on the web.
- [Formstr](https://formstr.app/dashboard) - create custom or template forms that are accessible anywhere.
- [Gitworkshop](https://gitworkshop.dev/) - code collaboration over nostr.
- [Plektos](https://plektos.app/) - meetup and event calendar.
- [Wikifreedia](https://wikifreedia.xyz/) - wikis on nostr, filtered by your web of trust. Or not.
- [Boris](https://read.withboris.com/) - a full reader app, with a focus on local, offline reading and sharing highlights.

## Games

Games? WTF? Yes, games:

- [Jester](https://jesterui.github.io/) - Chess over nostr by theborakompanioni
- [Flappy Nostrich](https://flappy-nostrich.vercel.app/) - Navigate bitcoin price talk to find good content by [Ryan](nostr:npub1m64hnkh6rs47fd9x6wk2zdtmdj4qkazt734d22d94ery9zzhne5qw9uaks)
- [Word5](https://word5.otherstuff.ai/) - Just like Wordle, but on nostr
- [Puzzl35](https://puzzl35.com/) - Turn your photos and art into puzzles to share with your friends

---
