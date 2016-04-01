---
layout: post
title:  Webfont licensing 101
source: Cognition
source-url: http://cognition.happycog.com/article/webfont-licensing-101
date:   2015-01-29
categories:   article
---

Choosing a type palette goes beyond considering aesthetics, legibility, browser support, and performance. For fonts to truly be appropriate for your project, they must also be technically and financially sound solutions. No one wants to be surprised by the outrageous cost of a font package *after* all designs have been delivered.

If you’re working client-side and are trying to evaluate whether a palette will break your bank, here are some nuances that will help ensure both your chosen fonts and license fit your project needs.

##But first, your budget

Your webfont budget (even if that’s zero) is like any other business requirement—reasonable and justified, so long as it’s made known early in the project (ideally before any formal graphic design begins). Consider how costs may run across years, and whether the fonts will be used for any subdomains. For some licensing, using webfonts across a lot of small sites can be more expensive than the sum of their usage on a single domain.

##And second, your pageviews

No matter how your fonts will be loaded onto your site, most often, your cost will be based on pageviews. A pageview is a request to load a single page on your site—this includes hitting refresh, as well as navigating away then returning to the original page. Each [foundry](http://en.wikipedia.org/wiki/Type_foundry) and webfont service has its own formula for translating pageviews to a licensing fee, but pageviews—and therefore costs—can rack up quickly. It’s important to understand your current and future traffic, and how they may drive the cost of your webfonts.

##To self-host or host through a service

There are currently two main methods to serve fonts on your site: host the files yourself, or host them through a webfont service. Neither option is outright “better” than the other—each carries its own pros and cons.

When you self-host your webfonts, you purchase a license to use the font files, most often from a foundry or from sites that represent multiple foundries. In return, you receive installable font files to embed in your CSS. Alternatively, many webfont providers offer to host your fonts for you. Instead of receiving installable font files, you’ll receive a specific snippet of code to add to your site. This snippet of code will load an additional JavaScript file and render font data from the provider’s server.

Hosting services frequently guarantee uptime and provide customer support, but you are still relying on an external service to keep your fonts working. With self-hosting, because *you* serve the font files, there’s never a danger that they will not show up due to another company’s interrupted service. But since you download actual files, you will not automatically receive any updates to the fonts or be able to switch fonts around like you may be able to with a hosting service. If you plan on changing up your font palette over time or would like to trial certain fonts first before opting to self-host, hosting through a service would give you that flexibility.

If you’re expecting a lot of traffic and not using a [CDN](http://en.wikipedia.org/wiki/Content_delivery_network)-based server—or speed in general is a concern—hosting through a service can be a more performance-friendly option. By hosting your font files elsewhere, you’re alleviating your server of an extra resource drain.

In many cases, both of these options—but more often hosting solutions—require some kind of tracking tool to make sure your sites stay within your pageview limit. If you’d prefer not to share your traffic with other companies, keep an eye out for this language as you decide from where to purchase your webfonts.

In terms of which option is cheaper, hosting solutions can often mean a lower price, because there is less risk involved for foundries if they know exactly where the fonts will be used. But, it’s really dependent on your traffic, the number of fonts you’re looking to license, the foundry, and how each company structures its fee schedules.

##Fee schedules

If you’re unsure how to host your fonts, figuring out your available payment methods may sway you one way or the other. For each typeface you’re interested in, you can expect one of the following fee schedules:

* **Ongoing payment**—you pay a monthly or yearly fee based on your monthly pageviews. This fee can either be a subscription to a library of fonts that you to choose from (e.g. [Fonts.com](http://www.fonts.com/), [Typekit](https://typekit.com/fonts)), a recurring fee per font style (e.g. [Webtype](http://www.webtype.com/)), or some combination of the two (e.g. [Cloud.typography](http://www.typography.com/cloud/welcome/), [Fontdeck](http://fontdeck.com/)). Typically, this is the only pricing option available if you’d like to host your fonts elsewhere. With a monthly or yearly fee schedule, you’ll be able to distribute your licensing costs over time. This is especially attractive if you’re beholden to an annual budget. A subscription to a library of fonts, in particular, can be perfect for projects that call for a large number of font styles.
* **One-time fee**—you pay a one-time fee per font style based on your anticipated monthly pageviews. This option is well-suited for sites with consistent month-to-month traffic, or for sites that don’t project significant growth in size or pageviews. If your traffic consistently outpaces your pageview limit, you’ll be asked to purchase an upgrade. Paying a one-time fee for your fonts will be convenient if you’re working under a grant or have allotted a budget for webfonts in your initial project scope but aren’t sure if you’ll be able to continue to devote resources to it. This type of fee schedule is offered by [Process Type Foundry](https://processtypefoundry.com/) and [Underware](http://www.underware.nl/), as well as other foundries selling their webfonts directly to consumers. [Fontspring](http://www.fontspring.com/) also offers a one-time fee without any traffic constraints.
* **Pay as you go**—you buy a bucket of pageviews per font style to use over time. When you run out, you purchase more. Because more cumulative pageviews drive higher costs, this model is best suited for lower-trafficked sites and situations where you’re creating a new site from scratch and are unsure of your projected traffic. Paying as you go also makes more sense for websites that have a significant range in traffic depending on the time of year. For example, if you’re an organization known for running a conference in June, but otherwise your traffic is quite low, you’d be better off only paying for the pageviews you actually use—not at the rate of your highest-trafficked month. Schools with application-cycle rushes might also find paying as you go a more cost-effective option. This type of fee schedule is offered by [Linotype](http://www.linotype.com/) and [MyFonts](http://www.myfonts.com/), to name a few.
* **Free**—you download your font styles or host them with a service free of charge. It’s hard not to argue with free, especially if like in the case of [Google Fonts](https://www.google.com/fonts), your fonts would be served from a CDN. Free fonts are budget-friendly, though perhaps at another type of cost to you. When hosting elsewhere and not paying for a service, companies have no legal obligation to continue offering your font (or their service as a whole). Secondly, in general, the design quality of free fonts is lower than those that have been carefully designed (and in some cases even drawn specifically for the web); you may end up finding issues with certain letters, kerning pairs, or hinting, forcing you to restart your search.

##The metric is the model

I’d be remiss to end this post without taking a step back to point out that despite the nuances listed above, at their core, the majority of services today are heavily reliant on the same model. The webfont-delivery industry is not the first to base value on a single impression—think billboards, TV commercials, even stock photography. By revolving so closely around the pageview, there is a perceived correlation between the number of hits on a site and the value the fonts contribute. This assumes not only that every website wants to shoot for the highest traffic possible, but also suggests that pageviews are the most important metric for your site.

In the business world, companies must iterate on models in order to differentiate their offerings. There are plenty of metrics to choose from—unique pageviews, sessions, entrances, average length of visit, bounce rate, etc. Ultimately, some may move away from the pageview to more closely reflect how fonts are served up to users (keep caching in mind here) and better align with metrics that matter to you, the website publisher.
