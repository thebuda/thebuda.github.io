---
title: Cybersecurity, Internet Privacy, and What You Can Do About Them
layout: default
description: My current thoughts on cybersecurity and solutions to common man problems
---

# Cybersecurity, Internet Privacy, and What You Can Do About Them

We live in a scary world that is rapidly evolving.  As our connections to one another increase and communications around the world speed up, the risks of being a victim increase proportionally.  Many people do not understand how the Internet works[^1], nor do most people understand how to protect themselves. [^2]

[^1]: [https://www.youtube.com/watch?v=f99PcP0aFNE](https://www.youtube.com/watch?v=f99PcP0aFNE)

[^2]: [Americans and Digital Knowledge -Pew Research, Oct 2019)](https://www.pewresearch.org/internet/2019/10/09/americans-and-digital-knowledge/)

The terms "Cybersecurity" and "Internet Privacy" are sometimes used interchangeably, but they are not the same thing.  There are overlapping areas, but they must be addressed separately. Cybersecurity is defined as "measures taken to protect a computer or computer system (as on the Internet) against unauthorized access or attack."[^3] The privacy we're discussing is "freedom from unauthorized intrusion"[^4]. Similar but different in important ways

[^3]: https://www.merriam-webster.com/dictionary/cybersecurity](https://www.merriam-webster.com/dictionary/cybersecurity)
[^4]: [https://www.merriam-webster.com/dictionary/privacy](https://www.merriam-webster.com/dictionary/privacy)

Consider a house.  There are doors and windows in this house.  Both have locks to keep bad actors from gaining entry.  These locks are cybersecurity.  Windows often also have blinds. This is internet privacy.  There are things we don't mind outsiders seeing and things we restrict outsiders from seeing.  Further, the ability to see valuables through a window may lead a bad actor to work harder at gaining entry. Improper privacy controls can lead to security problems.

We have to use the same mindset when discussing how to be a safe resident on the Internet. First and foremost, doors need locks.

## Privacy and the Internet
Let's face it; you do a lot on the Internet now. It's no longer a hobby or a luxury; access to the Internet is a utility in this country. Not only do most homes have internet access, but it has become expected that many bars, restaurants, and coffee spots are hot spots where "free" wifi can be accessed.

But now that we're comfortable with using the web for everything from chatting with distant (and not so distant) friends, banking, shopping, searching for doctors, and researching daycare centers, we need to ask who else is aware of our movements on the web.

Most people don't understand how the Internet works. This isn't surprising. Much like the rest of our reliable utilities, we take their function for granted. The details of how the electricity or natural gas get from the supplier to the house are dull and seemingly not relevant to our lives.

Right up until there is an outage.

### The Basics

When information is sent over the Internet, it is broken into small manageable pieces that are numbered and reassembled at the destination. Each of these pieces is called a packet.

Packets are like pieces of mail, and your ISP is like the mailman. When you send unencrypted packets, as in the case with standard HTTP connections, you are sending postcards. The mailman needs to read the address, but he could also read the contents of your message because it's there for all to see. Everyone in line from your mailman, the mailroom, the sorters, and the delivering mailman can read the contents of your postcard.

Even a "secure" connection (Like HTTPS) is like sending a standard letter. The address is still visible so it can be delivered, but no one in the postal service knows what's in the letter. That's because the message is encrypted, except for the address, which is needed for delivery. That's a lot better, but a smart postal employee might keep track of every letter you send, and in doing so, can learn a lot about you. Like where you get your utilities from, where your family lives, your interests from the magazines and bills you get, maybe your work from your W2. We call this Metadata, and when gathered together, it can really tell you a lot about a person.

### The Threats

Sticking with the mail analogy, you can see there are two types of threats. The first is the knowledge of the rightful carrier of your mail. They see all of your mail, but you trust that they don't really care because of the vast quantities of mail they process.

The second threat would be someone looking through your mail, say a nosy neighbor. You don't control your mailbox, so it's easy for someone to see. In the tech world, this is snooping and is usually done via Man in the Middle hacks. Common in coffee shops, hotels, airports, etc.

This information could be aggregated for legal and less than legal reasons. A term life salesperson looking for older people might want a list of all the houses that get AARP mail, or a thief might want to know who is getting a lot of mail from cruise lines and airline memberships. 

### Public "free" wifi

Before we move on, we have to pause and talk about all the wifi hotspots you encounter. Most of these are set up by legitimate businesses who use it as a draw for customers or because it comes bundled with their business Internet service (as is the case with many Xfinity connections.) The biggest problem is that your phone, trying to be efficient and helpful, is programmed by default to reconnect to any network with the same name as a previous connection. So, is that a real Xfinity hotspot, or did I name my router Xfinity to collect all your traffic?

### Your Rights

You have very few. And despite the recent headlines, you never have. While phone call logs are protected and require a warrant, your surfing data isn't treated that way and can be monitored, intercepted, and perhaps worst, sold.

### What's collected?

In many cases, we trade our privacy for the use of service, as in the case of Google. We all enjoy Google maps, Gmail, even this blogging platform. But rarely do we think about what information is collected.

Well, let's look at what Google acknowledges they collect. [^4]
[^4]: [https://privacy.google.com/your-data.html](https://privacy.google.com/your-data.html)

- Name
- E-mail address and password
- Birthday
- Gender
- Phone number
- Country
- Things you search for
- Websites you visit
- Videos you watch
- Ads you click on or tap
- Your location
- Device information
- IP address and cookie data
- E-mails you send and receive on Gmail
- Contacts you add
- Calendar events
- Photos and videos you upload
- Docs, Sheets, and Slides on Drive

The same applies to Facebook, Twitter, and other major on-line companies. There are no free lunches.

Stepping a bit closer to home, what is my ISP (in this case Xfinity/Comcast) collecting [^5]
[^5]: [https://www.xfinity.com/Corporate/Customers/Policies/CustomerPrivacy.html#What%20kind%20of%20personally%20identifiable%20information%20and%20CPNI%20does%20Comcast%20collect?](https://www.xfinity.com/Corporate/Customers/Policies/CustomerPrivacy.html#What%20kind%20of%20personally%20identifiable%20information%20and%20CPNI%20does%20Comcast%20collect?)

>Comcast transmits, and may collect and store for a period of time, personally identifiable and non-personally identifiable information about you when you use our high-speed Internet and phone services to:
send and receive e-mail, video mail, and instant messages;
transfer and share files;
make files accessible;
visit websites;
place or receive calls;
leave and receive voice mail messages;
use the applicable communications center or voice center;
establish custom settings or preferences;
communicate with us for support; or
otherwise, use the services and their features.

The concerning thought with ISP collection is that, unlike Google, the ISP sees everything. Further, there are few or no options for ISP, so unless you give up Internet access, you're locked in.

## Securing your on-line presence

Now that I've scared you into unplugging from the world and going off the grid, lets talk about how you can take back some control.

### Passwords and Password Keepers

A 2019 Google-Harris Poll survey found that 66% of respondents used the same passwords for multiple accounts.  I tend to think this is an underestimation, and the number is much closer to 100% based on my acquaintances.  I know people who have to keep upwards of a dozen passwords just for work, let alone the various personal online accounts (email, social media, shopping, forums, etc.).  

Lets be clear.  If you use the same password for multiple sites, a single hack into one is a hack into multiple accounts. This on top of the simple passwords people use, is the number 1 threat.

But good passwords are hard to remember.  And while a Pass-Phrase is [more secure](https://www.xkcd.com/936/) most websites are not interested in that kind of security. Password requirements often require anywhere from 8 to upwards of 30 characters, and have various requirements for complexity.  You are also warned against writing down your passwords (although this advise is rarely headed due to the inability of people to quickly memorize long strings of unconnected letters and numbers. 

So what you need is a passwork keeper.  These are generally highly encrypted tools that store usernames and passwords.  Many if not all will have additional fields for URLs and notes.  There are many good ones in both the free and paid variety.  I personally prefer [BitWarden](https://bitwarden.com/) because it is free and cross platform, but there are many to chose from.  And one fo the best features available in almost all keepers is the password generation feature.  An instant, long, complex, unique password for every website.

*Quick note: I don't trust the built in browser password keepers anymore.  It seemed overly simple to export in plain text my saved passwords and they don't require any sort of verification of who I am before they are willing to log me in.*








### Two Factor Authentication

What is two-factor authentication? It is a system that requires you to have two pieces of information to log into an account. In general, it is "something you have and something you know." For example, when I log into a Google Account, I put in my user name and password as usual. If it is the first time I'm logging into my account from a computer (say at a hotel or a friend's house), I get a text message sent to my phone with a six-digit number I need to enter. If someone has my user name and password, they still can't log into my account unless they also have my cell phone as well. 

- Something I have: **my cell phone**
- Something I know: **my password**

This is a reliable means of securing a system. A google study in May of 2019 found "SMS code sent to a recovery phone number helped block 100% of automated bots, 96% of bulk phishing attacks, and 76% of targeted attacks" [^6]

[^6]: [https://security.googleblog.com/2019/05/new-research-how-effective-is-basic.html](https://security.googleblog.com/2019/05/new-research-how-effective-is-basic.html)


Many businesses use two-factor authentication, especially in the world of national defense. Employees are issued access cards and a PIN. It is not good enough to know the PIN without also having the card. 

- Something I have: **my access card**
- Something I know: **my PIN**

Some other businesses use a rotating access number and give you a hardware FOB (often like a key chain). There are other USB hardware devices with fingerprint readers and hardcoded certificates.

Many standard e-mail providers now offer two-factor authentication, including Gmail, Outlook, and Yahoo! Mail. When you consider that your e-mail address is the means you reset passwords for banks and credit card accounts, your e-mail needs to be as secure as possible.

For a more complete and updated list of providers of two-factor authentication, please see this website: [https://twofactorauth.org/](https://twofactorauth.org/).








### HTTPS, TLS, and VPNs

While the primary risk to your security is the use and reuse of passwords, the second risk you face is the passing of information in an unsecured environment.  Easy to use, open-source tools allow anyone to see the contents of every packet that flows on a network.  If that data is not encrypted, the information passes as plain text and can be reassembled easily.  

This means that while you may type your password on a website, and it shows up at asterisks or dots, if the connection is not secure, anyone on the network can know what you typed.

There are two primary guards against spying: Transportation Layer Security (or TLS) and Virtual Private Networks (VPNs). One of these you likely use all the time and don't know it.  The other is something either you use for work or need to seek out and use as your needs arise.

Transportation layer Security using [Public Key cryptography](https://en.wikipedia.org/wiki/Public-key_cryptography) to authenticate and encrypt transmitions between you and the server you are accessing.  The easiest way to check is to look for "https" at the beginning of the URL and a closed lock icon next to the URL at the top of your browser.  While you ma not have ever noticed it, you can actualy click on that icon and see the autheticated name of the website.  You should also wach for this when accessing critical information (like your bank or your email account.)

Virtual Private Networks are much more advanced but have because very commonplace and easy to use recently.  These services create an encrypted tunnel to pass all your web traffic out to a distant server and then access the public internet from there.  The benefit to you is that all of the servers between you and the VPN can not read you traffic.  There are plenty of free and paid VPNs out there, and this is too big a topic to include here, but I recommend you [read up](https://us.norton.com/internetsecurity-privacy-what-is-a-vpn.html). I personally use [NordVPN](https://nordvpn.com/) because it is easy and rather inexpensive if you bite the bullet for a longer subscription.  But there are some [free VPNs](https://www.techradar.com/vpn/best-free-vpn) worth considering depending on your use case.  My rule of thumb if to always run a CPN when I'm on a public wifi (hotels, coffee shop, etc)









