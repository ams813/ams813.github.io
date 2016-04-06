---
layout: post
title:  From my head to the browser
source: Cognition
source-url: http://cognition.happycog.com/article/from-my-head-to-the-browser
date:   2013-10-31
categories:   article
---

As the web evolves, there will always be two ever-growing lists: one of all the pieces of content that will need to appear on any given site over time and another with all the ways we can access that content. Creating flexible, modular design systems makes both of these lists a little less daunting and a lot more manageable.

At Happy Cog, we pride ourselves on empowering clients to take ownership of their content, and we provide a framework and all the building blocks to help them do so. These building blocks range depending on a project’s needs. One could be a video carousel; another a contact form. But, the most fundamental building block that’s on every site and we have to get right every time is typography.

We design our sites with content in mind first, because that’s what our users arrive looking for. Our fonts, and their relative sizes and styles, provide structure to this content. A restrained, logical type system guides users in analyzing and interpreting what’s on the page. Throughout my design process, I have to make sure that my typography respects its content, is easy to read, and balances homogeneity with visual interest. So, I’ve started using a few methods to help me visualize my entire design system and see how it will behave in a realistic context.

## Vetting the options

While I’m trying to choose between typefaces for a site, I dedicate some time to studying the forms in renderings and, using tools like [Typecast](http://typecast.com/), styling type directly in the browser. This step is even more crucial if I don’t have access to a desktop equivalent of the face to predict how well a typeface renders my content. If the typefaces are legible and crisp across viewing environments and they have enough styles and characters for my content, I’m setting myself up for success.

## Keeping better track

By their nature, modular design systems involve inductive reasoning. I have to see enough styles in action in order to assess how my system functions. This can make it especially difficult early on to spot inconsistencies or sense if I’ve over-styled my modules to the point where clients wouldn’t understand which styles to apply, or readers wouldn’t be able to parse content quickly.

My coworker Yesenia Perez-Cruz taught me to [use a “Working Styles” document](http://cognition.happycog.com/article/sweet-systems) as a single place to track the modules, type, and styles that are used across my pages. In the past, I’ve often used paper and pencil, but a Photoshop document lets me see the variation in order to wrangle it. I’m also making an effort to assemble a “General Styles” document earlier in my design process. This file summarizes the hierarchy of the type system and provides style and structure for a long-form content page. It doesn’t feature all the styles used on the site but rather tries to account for anything that hasn’t been styled yet and might be needed later. Considered together, the Working Styles and General Styles documents are a hefty reference for the inner design workings of a site, because they provide the most comprehensive illustration of the site’s parts—in two places instead of 25.

## Writing variables

Once I have a solid grasp on my type, I like to get into code as soon as possible by writing some Sass variables and classes for my color palette, grid, and type styles. Writing more code has brought me in closer collaboration with developers, because we’re sharing a common language and starting point for any changes. It has also prompted me to boil down my type system to its essence—this time for the sake of cleaner code. Testing my type system in action reminds me to consider all the scenarios in which my content will be read. My type will need to stand up to the task.

Ultimately, the sooner I’ve been able to realize the parts of my system, the sooner I’ve been able to adjust pieces globally and refine sizing and spacing across screen sizes. Evaluating type in browser simulators, aggregating styles in Photoshop, and learning to write Sass variables each get me to that point a little faster and ensure I’ve been making the right choices for my content and my readers all along.
