---
title: Why I Don't Use Wordpress
image: /assets/images/wordpress.jpg
author: Graham
layout: single
tags: wordpress jekyll 
description: Wordpress powers around 40% of websites on the Internet. I chose not to use Wordpress, instead settling for Jekyll where possible. Here I discuss my reasons for doing so and why I think that Wordpress shouldn't be considered a "one box fits all" product.
---
## Why and How
While building a site recently, I did my usual routine - setup a development site on my development machine, with Wordpress, and a database for the content. This wasn't for some huge site with things like an online shop, or a members only area. It was a small site, just 3 or 4 pages and a contact form for prospective customers to contact the business owner. 

He wasn't interested in logging in to update content, or do any of the other things you can do on a Wordpress install. He just wanted to have a small website that got his name on the Internet, in the hope of snagging a few more local customers.
This got me thinking that maybe Wordpress was overkill for him - if he wanted any content updated, or added, sure he could contact me and I would do it for him. Maybe there was an easier way to make him a website that still looked good, loaded lightning fast (if you're not fast, you're last!) and was easy to maintain. 
At the time, I had been reading about _Next.js_ and its use as a _Static Site Generator_ (SSG), and this got me thinking that maybe I should build his site with _Jekyll_, another SSG that can create super fast sites. Another plus was the content is written in Markdown which is very easy to learn and quick to write. It meant if he did want to add any content, he could send me copy written in Word (or any text editor - even Notepad), and I could mark it up and push it to his site and it would be there ready to serve. No database lookups, no faffing about with blocks in the Wordpress backend. In a way it also gave him the chance to be involved in his own site and maybe he would enjoy that.

## Difficulty
For a lot of web developers who don't have a lot of technical ability, Wordpress allows them to build some really nice sites - they don't even need to write any code or CSS, if they're using a pre-built theme and a visual editor to layout the site. Jekyll on the other, does require some knowledge not only of markup languages (HTML/Markdown), but SASS and/or CSS for styling the site. It also uses _liquid syntax_ for outputing variables to the page and for control flow. It's a bit more involved, but the documentation is really good and there are plenty of tutorials available both on the [Jekyll](https://jekyllrb.com/) website, and on youtube, like [this tutorial by Kevin Powell](https://www.youtube.com/watch?v=jTlfPfTX64E).

## The Source
One of the main issues is that a Wordpress site is on the server and lives in the database. A Jekyll site is build like source code, from a project directory on your hard drive, from where you can push it to the server ready to be served. It raises the question of where do you keep the source? What if your hard drive fails? Common sense says keep it on backup media - either DVDs, USB sticks or maybe an online file storage like Dropbox. Personally I use a private Git repository, so that I can keep all my sites safe, and also I can branch when I'm building a new feature and it won't get added to the live site until I merge it back into the main stream. Thats a good thing especially where your client and their customers are concerned.

## Other Notes
Even although I've moved away from Wordpress, I do still follow good practice that follow across to any framework or method you decide to use. I still shrink all my images, [TinyPNG](https://tinypng.com/) shrinks them down so they load faster. No point of writing a site to load as fast as possible for an image to bottleneck the whole site and you get crucified by Google (and your client). SEO is still very important, although you need to write all the tags in the code by hand, and (I dont think) there's anything that can proof-read your documents beforehand and tell you how good it is (Yoast is the winner here I think).

## Final Thoughts
I'm glad I decided to use Jekyll to build most of my sites. It's put the fun back into doing it, and by writing some code, I feel like I'm being productive. I've I wanted to do drag and crop, I could just go to Wix or Squarespace and do it, but where would the fun be in that? 

Until next time,

Graham
