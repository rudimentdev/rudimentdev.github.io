---
title: Migrate to Cloudflare Email Routing
date: 2022-05-15 12:36:18 +7
snippet: Migrating from free G Suite legacy for custom domain email service needs
tags:
    - cloudflare
    - email routing
    - google workspace
---

I've been using free G Suite which was formerly known as Google Apps for my wife's small commerce business since 2013, our needs are just for the email service with a custom domain, but not mission-critical, nothing fancy, I don't even activate any non-default extensions/apps at all.

For years the free email service has been more than sufficient for our simple needs, there is not much traffic for our day-to-day emailing activities, we don't even use any other services besides the email service, our combined usage spaces for the email storage is less than 1 GB last I check.

Fast-forward to this year, Google decided to remove the grandfathered free subscription tier and urge people to migrate to Google Workspace, they have time until June 1st to undergo the migration process for a discounted subscription fee, or the transition will be done automatically following by service suspension after August 1st if there are no actions taken.

After considering the cost & benefit of upgrading to Google Workspace against our needs, I realize that we don't even need the email service with a custom domain, all we need is just to receive emails for the domain name, I can just use a simple email forwarding service for that instead.

I coincidently stumbled upon Cloudflare Email Routing one day, which happens to be exactly what I need, at the time still in closed beta and you need to join the waiting list. A month after the Google G Suite free subscription removal announcement, Cloudflare announces the open beta for their email routing service where you no longer need to be on the waiting list.

Today I decided to migrate the email service from the G Suite legacy to use the Cloudflare Email Routing to forward the emails from our domain email address to our GMail email address respectively. The process is painless since I already use Cloudflare to manage the DNS for the domain name, simply just follow the wizard instruction to remove the old MX entries, then the new MX entries are added automatically.

For the G Suite legacy, I'm planning to cancel the subscription, but first I need to retrieve all the email data and whatnot. All can be done by initiating the data export process, then waiting for the download link to be available.

I am grateful for the free service that Google has been providing all those years for our needs, although people could argue that all the resources spent for the free services provided seem to be minuscule for Google scale, there's no excuse for a free service to be provided forever for a for-profit company even as big as Google is, I think we need to understand that.