Having slow links to your page assets can severely affect the loading time of your pages. You will risk user engagement, declining search engine ranking and possibly reduced income.


# How do I fix this ?

* Use a CDN for better caching and faster response and load times due to reduced latency.

Other options to consider include:

* Use image sprites.
* Optimize image files (compression).
* Reduce HTTP requests for resources.
* Only use media (images, video) that is essential.
* Make sure caching is enabled, even at page level.
* Keep styles at the top and scripts at the bottom of your pages.
* Use gzipping, minification and combine CSS and JavaScript files.
* Use HTML5's `prefetch` feature
>```html
<link rel="prefetch" href="/images/background.jpg">```
* Use DNS prefetching with resources from other domains
>```html
<link rel="dns-prefetch" href="//widget.foo.com">```


# Resources

* [Why use a CDN](https://gtmetrix.com/why-use-a-cdn.html)
* [Prefetching, preloading, prebrowsing
](https://css-tricks.com/prefetching-preloading-prebrowsing/)
* [Web Assets - Tips for Better Organization and Performance](http://code.tutsplus.com/articles/web-assets-tips-for-better-organization-and-performance--net-33950)
* [Speeding Up Page Load Times](http://blog.teamtreehouse.com/speeding-up-page-load-times)
* [Front-end performance](http://csswizardry.com/2013/01/front-end-performance-for-web-designers-and-front-end-developers#section:http-requests-and-dns-lookups)
* [Prefetching/Preloading and prerendering content with HTML](https://jack.ofspades.com/prefetching-preloading-and-prerendering-content-with-html/)
