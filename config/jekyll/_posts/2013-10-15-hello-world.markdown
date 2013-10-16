---
layout: post
published: true
title: Hello, world!
---

# Hello, world! #

It's been a long month. I needed a personal website up to showcase some of the projects I've been working on while also getting some more experience in the process. What I thought would only be a week-long project ended up taking far, far longer than that. This was partly due to the fact that I hadn't quite planned things very well and also because I've been overwhelmed with work.

Rails was a natural starting point because that's what I'm most comfortable with. I could have used [GitHub Pages](http://pages.github.com/) but Rails allows me far more flexibility, in case I want to add features in the future.

I knew that the bulk of my website was going to consist of static pages. I started out by creating a 'Pages' controller and having a separate action for each page. This method worked fine, but it didn't seem very clean to me. That's when I found out about [High Voltage](https://github.com/thoughtbot/high_voltage) by [ThoughtBot](http://thoughtbot.com/). High Voltage provides a neat, clean way to organize and serve static pages. It also handles the routes for you and provides helper methods. Furthermore, you don't have to worry about duplicating headers and footers because it yields the pages in to a customizable layout.

Finally, I had to add a blog. After doing a bit of research, [Jekyll](https://github.com/mojombo/jekyll) seemed to be the obvious choice. So, I used [Bloggy](https://blog.engineyard.com/2012/introducing-bloggy-a-simple-way-to-add-a-jekyll-blog-to-any-rails-application) to add Jekyll to my site.

Well, that's about it. My site is far from complete. I still have to add my resume and also work on the project showcase page. Nonetheless, I'm happy to have something out.

In case you're interested, the source code is up on [GitHub](https://github.com/Mutinix/gauravjhaveri.com). Hello, world!