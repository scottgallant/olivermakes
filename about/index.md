---
title: 'About'
layout: singel
option:
  - no-title
  - hero-srcset
  - code
date: 2014-10-31 18:25
image:
  - src: 2011-11-10-oliver-bench-jeancflanagan-ccbync.jpg
    alt: 'Oliver Pattison sitting on a bench'
    caption: 'Photo credit: [Jean Flanagan](http://jeancflanagan.com) – CC BY-NC'
    date: 2011-11-10
    camera: 'Nikon D3000'
    lens: 'Nikon DX 55-200 mm f/4.0-5.6'
    focal: '55mm'
    aperture: 'f/4.0'
    shutter: '1/40'
    iso: 200

---

I am Oliver Pattison, a designer focused on the future of the web. My main interests are archiving, the web, usable and universal design, mobile technology and photography.

I currently live in Washington, DC. I am originally from New York City.

<div class="feature">I am available for hire for small projects. <a href="mailto:{{ site.author.email }}" rel="me">Get in touch</a> by email if you have a project in mind.</div>

## About this site

This website is an archive for my work, featuring:

- **[Writing](/writing)**, a collection of my serious writing and less-serious notes
- **[Photography](/photos)**, a selection of some of my best work
- **[Projects](/projects)**, which includes portfolio work as well as open source one-offs

### Under the hood

- **[Jekyll](http://jekyllrb.com)** for building.
- **[Amazon S3](http://aws.amazon.com/s3)** for hosting.
- **[s3_website](https://github.com/laurilehmijoki/s3_website)** for deploying.
- **[GitHub](https://github.com/opattison/olivermakes)** for version control.

{% capture influences %}
# Influences

These people and their creative works inspired elements of the site – in particular: typography, proportion and design process.

## People

- [Jeremy Keith](https://adactio.com)
- [Mandy Brown](http://aworkinglibrary.com)
- [Paul Robert Lloyd](http://paulrobertlloyd.com)
- [Anna Debenham](http://maban.co.uk)
- [Heydon Pickering](http://www.heydonworks.com)
- [Simon Foster](http://simonfosterdesign.com)
- [David Bushell](http://dbushell.com)
- [Trent Walton](http://trentwalton.com)

## Websites and apps

- [Art=Work](http://artequalswork.com) by Nathan Ford
- [Works That Work](https://worksthatwork.com)
- [Code for America Style Guide](http://style.codeforamerica.org)
- [CSS Zen Garden #221](http://www.csszengarden.com/221/) by Andrew Lohman
- [Jim Ramsden](http://jimramsden.com)
- [Ableton](https://www.ableton.com/en)
- [STET by Editorially](http://stet.editorially.com)
- [MapBox](https://www.mapbox.com)
- [VSCO](http://vsco.co)
- [Instapaper](https://www.instapaper.com)
- [Reeder](http://reederapp.com)
{% endcapture %}

<aside class="ancillary">
{{ influences | markdownify }}
</aside>

### Design and development

It is difficult to design for yourself. After spending too many months planning and delaying, I worked alone on designing this site for a few weeks in October and November 2014. I would like to thank [Jean]({{ site.link.jean }}) for editing and design input.

My process for designing the site begins with a handful of sketches and notes. As soon as I can, I start work in a text editor and browser and come up with a typographic measure and fundamental ratios. I avoid mockups and high-fidelity compositions in favor of sketching, followed by iterative HTML/CSS prototyping that can be worked into finished code as the project progresses.

I target small-screens first (commonly known as “mobile-first”), so I make sure to test on a variety of devices as I go along. The first browser width I look at is under `20em` (less than ~320 pixels). Working with fewer assumptions about device types informs the design process; it is easier to design with empathy and flexibility with a responsive and iterative process.

A significant part of my process this time was working with a [pattern page](/patterns) with reference examples of general HTML and specific use cases for my own designs. I plan to expand it and turn it into a pattern library and style guide for the site.

### Typography

The fonts on the site (300, 400 and 500 weights of [the Ratio typeface](http://cargocollective.com/pstype/Ratio) and 400 weight of [Source Code Pro](http://adobe-fonts.github.io/source-code-pro/)) are [hosted by Typekit](https://typekit.com/colophons/ojm0eig). This site uses responsive typography based on pixel density, so if you have a higher resolution display, you will see different variants of Ratio. Only pages that include monospaced fonts conditionally incur a request for Source Code Pro.

## Copyright

All writing and photography on the site is my original work and is licensed under [Creative Commons Attribution-NonCommercial 4.0 (CC BY-NC)]({{ site.link.attribution }}){:rel="license"}. All design and code is under conventional copyright (as opposed to CC-style “copyleft” copyright), but is available for fair use [on GitHub]({{ site.link.source }}){:rel="source"}. If you are looking at the repository, almost everything in the `_static` and `_posts` folders is CC BY-NC and the most of the rest of it is under copyright, where applicable.

I designed the site myself, so most of the source was written by me by hand. Exceptions where I derived inspiration or an approach from another source are noted inline. An example of copyright violation would be copying all of the source code outright and using it to make a public website that could be confused for this one.

### Attribution

Proper CC BY-NC attribution with a link and credit would look like this:

> “The title” [Oliver Pattison]({{ site.url }}) [CC BY-NC]({{ site.link.attribution }})

Or in HTML:

{% highlight html %}
“The title” <a href="{{ site.url }}">Oliver Pattison</a> <a href="{{ site.link.attribution }}">CC BY-NC</a>
{% endhighlight %}

If you have any questions about licensing or use of content from the site, please [contact me by email](mailto:{{ site.author.email }}).

- - -

## Elsewhere on the web

Nearly every significant thing I read or look at is archived on **[Pinboard]({{ site.link.pinboard }})**. It is my external brain and my favorite thing on the web. It is as complete an archive as I can keep of my reading online.

I am **[@olivermakes on Twitter]({{ site.link.twitter }}){:rel="me"}**.

My open source code (including this site) is on **[GitHub]({{ site.link.github }}){:rel="me"}**.

Some of my design experiments are posted on **[CodePen](http://codepen.io/opattison/){:rel="me"}**.

I share some of my mobile photography to **[VSCO Grid]({{ site.link.vsco }}){:rel="me"}**.

I post less frequently to:

- [Tumblr]({{ site.link.tumblr }}){:rel="me"}
- [Google+]({{ site.link.googleplus }}){:rel="me"}
- [Panoramio]({{ site.link.panoramio }}){:rel="me"}
- [Flickr]({{ site.link.flickr }}){:rel="me"}