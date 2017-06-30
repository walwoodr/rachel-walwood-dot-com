---
layout: post
title:  "Falling in Love with Static Sites"
date:   2017-06-30 10:53:00 -0400
categories: code musings
---


I've built a lot of sites on wordpress. Not a working-at-an-agency, my-job-title-is-wordpress-developer number of sites, but a respectable number. And it's pretty easy to spin up a site in Wordpress. To customize what it looks like. It's not quite drag and drop, but if you're proficient in HTML and CSS, you can get a solid Wordpress site up and running in an afternoon.

The problems with Wordpress come three months down the line when the extensions you chose need updates, or Wordpress itself needs an update, and you're left with the realization that what was so easy is now...going to take some work to keep up.

So you ignore those updates, or maybe you update the extensions, hoping all the time that it doesn't completely break the site.

Enter static sites. Static sites (like the one you're looking at now) don't rely on any backend code. There's no database where your blog posts live, no PHP turning those database entries into pages that the server sends to your browser. There are only HTML documents (with some CSS and perhaps JavaScript) making things chug along. There are no extensions that need to be updated, only pages strung together with hyperlinks.

When I first heard about static sites, I thought: okay, sure, but then I have to copy and paste my header into every page, and if I change it, I have to change it on every page, and we run straight back into the reason we have database-driven blogs in the first place.

But no. That's not true at all. Instead, we have static site generators. And that's the magic.

Static site generators work by essentially hydrating the output of backend code so that you can publish it to the web as linked pages. The hydration happens one time (that's what makes it **static**), so they don't support interactive features like comments or an event calendar (however those can be added using third party microservices).

So far, my experience with static site generators has been engaging and exciting. It is an experience that a non-developer might be intimidated by, but let's not shield ourselves from reality: Wordpress is also pretty intimidating if you've never used it before. 
