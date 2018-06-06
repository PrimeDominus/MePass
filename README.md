<!-- (Australian spelling, names, and other terminology) spell-checker:ignore decentralised, authorisation, centralised, utilise, utilised, utilises,utilisation, organisation, organisations, Vitalik, Buterin, blockchain, Ethereum -->

# MePass

Decentralised Login/Access/Authority/ID People Actually Use

# Contents

1. [Brief Considerations for a Solution](#brief-considerations-for-a-solution)
2. [The problem with current decentralised practices in use today and in the past](#the-problem-with-current-decentralised-practices-in-use-today-and-in-the-past)
3. What we've learned from past centralised Permission+Access+Authorisation+Systems such as OpenID
4. Examples of currently "working" methods among the general public using centralised systems such as OAuth/Google Authenticator/WhatsApp Web
5. [The current approaches to solving this problem being explored in the decentralised world](#the-current-approaches-to-solving-this-problem-being-explored-in-the-decentralised-world)
6. General human and tech considerations to factor in for a successful decentralised MePass system

# Brief Considerations for a Solution

This system must incorporate all of the following:

1. Something that attracts users in large numbers. (One major reason Google/Facebook/Twitter OAuth methods won over OpenID is because of user familiarity and a large number of pre-existing users.)
2. Something a "drunk novice" is prepared and able to use. (One major reason Google/Facebook/OAuth is popular is because something as simple as "Login with Google" is *_stupidly_* easy, though more people these days are getting accustomed to multi-factor authentication.)
3. Something that works on desktop and mobile devices, and on websites and apps, without requiring a user to install a plugin or special software (e.g. MetaMask) other than maybe something simple for a multi-factor authentication process (i.e. something with similar user-interactions as Google Authenticator or WhatsApp Web).
4. Something that manages user credentials securely decentralised without the capacity for traditional centralised third-party "Admins" to view and manage private details. Granular privacy, sharing, and utilisation functions are manageable by ONLY the owner of the "account" or "ID" in accordance with the settings ONLY the owner specifies.
5. Something that attracts traditional business, organisations, and centralised systems to adopt and promote. (Possibly because of easy user-managed interoperability features, and easy system integration.)
6. Interoperable "account" or "ID" features e.g. for any website/app MePass is integrated with, the user can set what and how information can be accessed and utilised.
7. Safe, easy, quick, and effective (i.e. people will actually use it when needed) "account" recovery without dependence on a centralised key store.
8. Something that prevents (and ideally encourages) users against repeatedly entering their private keys.

# The problem with current decentralised practices in use today and in the past

## Let's start with a Twitter post by Vitalik Buterin

https://twitter.com/VitalikButerin/status/986101152235188224?s=20 (Note: this is a multi-tweet thread)

Images of the multiple tweet thread (clickable-linked to each post):

<a href="https://twitter.com/VitalikButerin/status/986101152235188224?s=20"><img src="./docs/multimedia/Screenshot-2018-6-5 Vitalik Not giving away ETH Buterin on Twitter.png"></a>
<a href="https://twitter.com/VitalikButerin/status/986101749286035456?s=20"><img src="./docs/multimedia/Screenshot-2018-6-5 Vitalik Not giving away ETH Buterin on Twitter(1).png"></a>
<a href="https://twitter.com/VitalikButerin/status/986103764300910593?s=20"><img src="./docs/multimedia/Screenshot-2018-6-5 Vitalik Not giving away ETH Buterin on Twitter(2).png"></a>
<a href="https://twitter.com/VitalikButerin/status/986104490402066432?s=20"><img src="./docs/multimedia/Screenshot-2018-6-5 Vitalik Not giving away ETH Buterin on Twitter(3).png"></a>
<a href="https://twitter.com/VitalikButerin/status/986104674229960704?s=20"><img src="./docs/multimedia/Screenshot-2018-6-5 Vitalik Not giving away ETH Buterin on Twitter(4).png"></a>
<a href="https://twitter.com/VitalikButerin/status/986105130197041152?s=20"><img src="./docs/multimedia/Screenshot-2018-6-5 Vitalik Not giving away ETH Buterin on Twitter(5).png"></a>

## The problem in plain English

### A _thank you_ to blockchain engineers

The blockchain community of software engineers have been excellent at creating highly technical works that are vital to the success of decentralised and secure technology. Yes, their work is indeed important, and none of this would be possible without their continued effort.

From a technical standpoint, it works, and its benefits over commonly used centralised services are clearly evident and revolutionary.

You are heros.

Thank you.

### The trouble is...

The trouble is that it is difficult to use for people who are new to it. Even for people coming from a technically experienced background. Worse still, for all the very evident benefits of blockchain over centralised systems, the difficulty of using it is more than enough for the so-called "average Joe" and "the general public" to be repulsed by it.

Heck, the basic concept of a wallet address is indeed "WTF" to most people. Add to this the notion of private keys and seed phrases. And, that's just getting started with only three concepts inherent to it all.

### Good security is causing bad security

It's the sheer technical excellence of these basic elements that enables the privacy, security, and control of ___your___ crypto property to indeed be in ___your___ control.

Ironically, the good security elements of blockchain technology, such as seed phrases and private keys, has in practice become the cause of bad security habits that are all too common. Some examples:

- Storing private keys and seed phrases online on services such as Dropbox or insecure/non-private mobile apps.
- Taking screenshots of private keys and seed phrases (which often get uploaded to cloud services in the background such as Google Photos).
- Repeatedly entering private keys and seed phrases just to try out a new wallet or link to another blockchain service.

A lot of people doing any of the above ___are___ indeed aware that what they are doing is in fact risking ___ALL___ of their assets associated with their wallet private keys. Thus, if a wallet has USD$1 million in assets, that's USD$1 million in assets they're risking.

### And that's just getting started...

Thus far we've only touched on the blockchain equivalent (loosely speaking) of logging in to Facebook on a new device.

We've yet to even begin talking about trivial things taken for granted in the centralised world such as recovering lost credentials.

### How do I "Forgot my password" in blockchain... Halp!

In short, the general advice is to write down your private key and seed phrase on a piece of paper, and store it somewhere secure such as a locked-up physical safe that no one else has access to.

If this piece of paper is lost, and you cannot remember your private key or seed phrase, which are purpose-built to be near impossible to remember, then access to your wallet and all assets contained therein are lost forever.

### Lost forever(?)

Yes. Lost. Forever.

### Oh but there must be services out there to retrieve something so valuable

There are services out there providing some form of storage and recovery; they're centralised and unregulated third-parties, with no solid mechanism to stop the people involved in said third-parties (who are effectively strangers) from having access to your private keys, seed phrases, and all the assets contained in your respective wallets.

They're like banks, but arguably worse.

### So I just have to be really careful

We must rely on ourselves to be as diligent as we humanly can. Though no one's perfect, and accidents do happen. Sometimes these accidents are out of our own control such as fires, floods, and other catastrophic disasters; that piece of paper you were advised to write your private stuff on may no longer be accessible to you.

Worse still, and a much, MUCH more common issue is that current blockchain software requires us to rely on repeatedly entering our private keys and seed phrases when wanting to load our wallet on a new device or app. This is being done with something we're told is meant to be locked away in a physical safe.

It's impractical, to say the least, and terribly insecure.

### Y u no have nice things

Tricky things that makes a ubiquitous solution technically difficult:

- If we're using a username and password kind of combination, where are these credentials stored and who has access to them?
- Ethereum DApps, for example, rely on "message signing" often through the wonderful browser plugin, MetaMask.

### MetaMask you say

MetaMask has made life MUCH easier for us. But, at least for our purpose here...

- MetaMask doesn't work on mobile devices.
- MetaMask functions mainly as a DApp wallet, so it still has the issue of repeatedly entering your private keys/seed phrase on a new device, even if your goal is simply to login to a DApp.
- While it DOES make life less difficult on desktop web browsers that are compatible, it's still too difficult for most people; even multiple usernames and passwords have proven to be too difficult for "most people" to utilise comfortably, and the MetaMask learning curve is considerably more difficult and different to that.

### Meh... "Most People" you say

We're here to make the WORLD a better place. The WORLD includes "most people" and even "most people" in first world countries with an abundance of many things still have problems with simpler methods of interaction than MetaMask. This is the real life.

## The problem as an acronym

It's ___NCRAP___&trade; &copy;

Meaning it's ___Not___-___Compelling___-enough-to-___Re___-___Align___-___People___

 Patent Pending: Me.

-= [Back to Contents](#contents) =-

# The current approaches to solving this problem being explored in the decentralised world

Read, watch, listen, and analyse the discussion/comments contained in the following links:

https://github.com/ethereum/EIPs/issues/1115

https://ethereum-magicians.org/t/erc-1077-and-erc-1078-the-magic-of-executable-signed-messages-to-login-and-do-actions/351

https://auth0.com/blog/an-introduction-to-ethereum-and-smart-contracts-part-3/

https://keybase.io/docs/server_security

Just so you know this problem has been around for a while, even before Bitcoin: http://dig.csail.mit.edu/2007/06/ieee-ic-decentralized-identity-weitzner.html