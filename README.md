# Blog
Powered by [Ghost](http://ghost.org) and [Buster](https://github.com/axitkhurana/buster/).

Gotchas:
* Weird Buster glitch for static pages: You need to "buster generate" a static page as a regular post first, and then generate it a second time after marking the post as a static page. If you neglect to generate it as a regular blog post, Buster will skip the static file and you'll end up with a 404 for that page.