---
title: Chaiseraugschter Fasnacht
tags:
  - Content Creation
  - Templating
  - Performance
  - Communication
  - Design
  - Development
  - Redesign
  - Build Processes
technologies:
  - HTML
  - CSS
  - Sass
  - JavaScript
  - PHP
  - Handlebars
pattern:
  gradient: linear-gradient(135deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%) -50px 0, linear-gradient(225deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%) -50px 0, linear-gradient(315deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%), linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%), rgb(189, 40, 94)
  size: 100px 100px
type: client
link: http://chaiseraugschter-fasnacht.ch
client: Fasnachtscomité Kaiseraugst
---

The local carnival (or "Fasnacht", as it's called in German) is a big deal, even in small Swiss towns. It is a long and proud tradition that's cherished by both younger and older people.

For a while, the organising comittee wanted to offer the residents of Kaiseraugst a better way to get information about the carnival so in 2012 they asked me if I wanted to create a website for the event.

The schedule was tight. We wanted to be ready for the 2012 carnival season, starting late February so a basic version of the site needed to be complete in a short amount of time. This first version relied on bad techniques and its design wouldn't win any awards, but it worked just fine. The people of Kaiseraugst liked the new website and they appreciated the ease of finding information.

However, I was not content. So later that year, I decided to drop the old version in favour of a simplified, modern design that would be fast, usable and suited to the spirit of the event. Towards the end of 2013 the new design was ready and people loved it. It was faster, information was easier to find and the site was a joy to use. The design is still the same to this day.

# Things I've learned

{% include tags.html tags = page.tags %}

I was responsible for much of the content and free to decide which information needs to be included and which doesn't. This was interesting, considering I'm not that involved with the carnival itself, and using my outside perspective I was able to streamline the site very much. Of course, the comittee had its own ideas and official texts that ended up on the site, but other than that I was free to create the site however I wanted.

On the development site I learned the most when I started work on the second version of the site. I started using templating to make the site more maintainable, I used a build system to automate common tasks and I did lots of performance optimisation.

# Technologies I've used

{% include tags.html tags = page.technologies %}

The first version of the site used PHP, mainly for things like including parts of the site. It was a bit of an overkill, because the rest of the site was mostly static.

That's why I decided to drop the old approach in favour of a static setup, heavily relying on [Grunt](http://gruntjs.com), which was the new shiny thing back then. With Grunt, combined with [Assemble](http://assemble.io), I was able to automate most of the site's generation, allowing me to forget about PHP's includes.

Nowadays, the site is a bit of a playground for me. I can use new technologies (right now I'm thinking of switching over the project to [gulp](http://gulpjs.com)) and optimise performance as much as I like. All this means that the site is highly maintainable and very fast, two of my key priorities for the project.