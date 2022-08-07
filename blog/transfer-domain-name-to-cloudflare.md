---
title: Transfer domain name to Cloudflare
date: 2022-08-07 10:24:26 +7
tags:
    - domain name
    - domain registrar
    - cloudflare 
---

My wife started a small business selling hijab in 2012. I convinced her that she needed a domain name that matched her brand name, so I registered a domain name for the business, [kanayahijab.com](https://kanayahijab.com). I didn't have any experience registering a domain name before, so I decided to register with a well-known local web hosting company here at that time, [Master Web Network](https://www.crunchbase.com/organization/master-web-network). My rationale is that one of their founders is a famous tech figure in the web hosting community, [Steven Haryanto](https://twitter.com/stevenharyanto), so they must be good at what they are doing.

After years using their service, I have never encountered any problems whatsoever, whether it be with their uptime record or the ease of use of their management dashboard. The payment processing experience is also nothing but excellent. I can change the DNS records to use services like Blogger, G Suite, etc just fine.

In 2019, [they were acquired](https://www.exabytes.sg/blog/exabytes-acquires-master-web-network) by the Malaysian investment and holding group, Exabytes Capital Group Sdn. Bhd., which owns Exabytes Network Sdn. Bhd., which Master Web Network will be part of. The merging process is anything but smooth, at least with their payment processing. I got charged multiple times for my yearly renewal, with a different amount each. The good thing is that their new support team could help me solve the problems nicely.

Since then, I have been thinking of migrating the domain name. Last year, I learned that Cloudflare offers domain name hosting at a cost price, meaning that they don't charge anything on top of the base price that the registrar charges. Since I already use their DNS name server and email address forwarder services, I decided to transfer my domain name to them.

Two weeks ago, I started the transfer process. On the Cloudflare side, the process runs smoothly and without hiccups, whereas on the Exabytes side, the process is, to be honest, quite terrible. For some reason, their management dashboard behaves erratically; it keeps throwing error pages and signing me out most of the time. It is as if they can sense that I am trying to escape from them 🤣.

The most heinous thing they did, in my opinion, is the kind of dark pattern of not providing any clear option or menu anywhere to transfer out your domain name. I was looking for the auth code for the transfer process required by Cloudflare. Fortunately, I came across the "Get EPP code" menu on their dashboard and decided to look into it. Lo and behold, it is the auth code that I've been looking for. I am not sure why they decided to use the alternative name of the well-known Auth-code other than to obscure things a bit 😐.

According to Cloudflare, after successfully finishing the auth code step, all that is left is to wait for the Exabytes to move forward with finalizing the transfer process on their side. Or if I want to make the finalizing process move faster, I could approve the transfer process on the Exabytes side by responding to the email that was sent by Exabytes or on their management dashboard to confirm the transfer, as suggested by Cloudflare.

I waited for a while, hoping that Exabytes would send me an email to confirm the transfer, since I would not put any hope in that they would have any menu on their dashboard for it, but no email arrived. I contacted their support team and stated that they didn't send a confirmation email for the transfer and suggested I wait until the transfer was finalized automatically.

A couple of days ago, I received an email from Cloudflare informing me that the domain transfer process was completed. I just cancelled my account with Exabytes for the remaining web hosting services.

The key takeaway here is that any good web-hosting or domain registrar should provide a proper transfer out process option without hiding it somewhere. In Exabytes' case here, it contrasted with their domain name transfer-in process option, which is very clear and prominent on their management dashboard. They look like they are trying to confuse inexperienced people like myself who are looking to do quite complicated things like transfer their domain out behind some not-well-known term like EPP code instead of just the commonly known Auth-code in most big domain registrars.