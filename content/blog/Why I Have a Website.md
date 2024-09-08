---
title: 'Why I Have a Website'
date: 2024-09-04T21:35:49-06:00
type: blog
draft: true
---

I have heard that a personal website is a way to express yourself openly on the web, both by what you present and how you present it. A website that you own is free from filtering, unless you so choose. Free from ads, unless you so choose. And so on. The potential for an unfiltered voice, if you will. 

I know this, and have heard this, and have thought about it many times, but it always seemed more tedious than interesting and I've never felt that what I have to say was particularly worth the effort.

However, my feelings changed dramatically when LinkedIn seized my account just a couple of weeks ago.

### How it began

Things at work had started to take a turn for the worse politically at my company. Nothing world-ending, but hugely demoralizing for many of my fellow engineers and myself. I decided it was time to pursue a couple of leads that had been hanging around, and so I took a couple of weeks to get my resume together, solicit feedback, make updates, update my LinkedIn password since I have a password manager now, and so on.

One of the things I did along the way was customize my LinkedIn URL, removing the trailing alpha-numeric gobbledegook at the end to make it easier to navigate to, in case the viewer didn't realize that my URL was also a link, e.g.:
``` md
from: `linkedin.com/in/daniel-register-a8713712a`
to:   `linkedin.com/in/daniel-register`
```
and later I made a matching [bitly shortcut](https://bit.ly/daniel-register) to further simplify typing if it came to that.

Right after I'd finalized and sent my resume off to one of those leads, I decided to perform one last test run and noticed that my link wasn't working and directed to a no-match-found page. I figured that maybe my configuration was faulty, so I tried to log in, and was presented with a ReCAPTCHA and then an identity challege, requiring me to send a photo of my ID to a company called `Persona`.

The recent data broker breach of [National Public Data](https://techcrunch.com/2024/06/11/the-mystery-of-an-alleged-data-brokers-data-breach/) was fresh on my mind and I didn't want to send a photo of my ID off to access my account, so I stewed overnight about my apparent blunder and weighed my options. I found out the next morning that I could get a notarized affidavit of my identity in order to restore access, but that the only way to contact LinkedIn help was via X (the artist formerly known as Twitter).

### LinkedIn help desk

I made an X account, DM'd the help channel, had my humanity questioned by X (which is fair), and waited and wondered for four days. When the X customer service team got back to me, they repeated the same two options for identity verification and said that a different "safety" team handles the actual account access requests and would get in touch with me within another 3-5 business days.

I gritted my teeth for the wait, but got an email early the next morning (saturday), from someone named Alexa. The conversation wwent as follows:

> Alexa: We no longer accept IDs via email attachment. ... Alternatively, if you don't wish to provide your ID, you can print the following Affidavit of Identity and sign before a Notary Public. Once notarized, this form can be scanned and attached in your response to this message. ...

> Me: I do not wish to use Persona to verify my identity and got my affidavit notarized this morning (Please see it attached). If there's any more information you need, please let me know. Att: LinkedIn Member Identity Verification (Notarized).pdf

> Alexa: Thanks for providing the requested document. Unfortunately, we were not able to approve the identification you've submitted due to the ID's: Specification. Please provide a scanned image of a government issued ID (for example: a driver's license, passport, or country ID), using this secure link: ...

What? Are they going to strong-arm me into using this service? That's exactly what I am trying to avoid by jumping through these hoops.

> Me: I'm afraid I don't understand: what "ID specification" are you referring to?

> Alexa: Thanks for providing the requested document. Unfortunately, we were not able to approve the identification you've submitted due to the ID's: Specification. Please provide a scanned image of a government issued ID (for example: a driver's license, passport, or country ID), using this secure link:...

Is that the exact same email? It is. This is a bot. Fan-flipping-tastic. Maybe it choked on the file name? I really do not want to use Persona. I hope I didn't break my chance.

> Me: I would really prefer not to use the Persona ID validation. If there is something wrong with the affidavit I submitted, I would like to fix it. What's do you mean \[sic\] by there being something wrong with the ID's specification?

> Alexa: I'm sorry for the inconvenience, but it seems that we haven't successfully received your ID verification. If you're having problems submitting your ID via the link, please consider signing the affidavit of identity form before a Notary Public: https://www.linkedin.com/help/linkedin/answer/3629

*I rename the file, reattach, and hope.*

> Me: Please see the attached notarized Affidavit. Please let me know if there is anything more I can do.

> We've determined that the activity on your account is in violation of LinkedIn's User Agreement at: https://www.linkedin.com/legal/user-agreement and Professional Community Policies at: https://www.linkedin.com/legal/professional-community-policies (collectively, our Terms). Per our terms, you agree that you won't misrepresent your identity or post inaccurate profile information. Your appeal has been denied and your account will remain restricted.

WTF? I haven't changed anything in my profile in years. I thought I'd been locked out for security reasons since I touched multiple security settings.

> Me: What content on my profile is deemed inaccurate? I would love to regain access to my profile.

> Alexa: Due to our Privacy Policy, we are unable to release our additional findings, or any actions taken. For more information, please review LinkedIn's Terms of Service: https://www.linkedin.com/legal/user-agreement and Professional Community Policies: https://www.linkedin.com/help/linkedin/answer/34593. However, this will be our final communication concerning this matter.

Didn't you just verify my identity? Why can't you tell me what's going on with my account? and, I guess, how could I fix it without access? 

So, there goes my account. Lost to the gods of zero-strike policy.

### Thoughts

While it is disappointing to be served by a bot and get rejected outright while trying to regain access to my own legitimate and accurate profile, I realize that the customer service burden on LinkedIn must be immense. Having even one customer service agent per 100,000 consumers would mean they'd need 8300 full-time employees to service their 830 million platform users. And 100,000 seems like a highly unreasonable number [to begin with](blog/10-rules/#take-a-wag-with-10). So a bot makes sense. It does leave me at a dead end though, being a legitimate user that got mistakenly flagged.

I think that the reason I got flagged was actually because I customized my URL. I remember thinking that it was odd (and very fortunate) that no one had the non-gobbledegook URL reserved before I got there. But, it would not surprise me if there had been another account that was flagged for content at that URL, and that this was a case of mistaken identity. It wouldn't be the first time [something like this had happened](https://www.wired.com/story/null-license-plate-landed-one-hacker-ticket-hell/)

I am both:
* glad that LinkedIn will accept an affidavit, rather than a photo, and
* glad that LinkedIn has stopped requesting photos of government ID over email, since
    * email is not private (encryped) communication
    * it is safest to regard anything in your email as public information. 
    * Anyone sniffing traffic on the internet can read any email that is sent