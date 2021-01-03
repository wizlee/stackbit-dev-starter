---
stackbit_url_path: posts/migrate-to-netlify-from-github-page-custom-domain-53o8
title: Migrate to Netlify from Github Page Custom Domain
date: '2020-12-13T04:08:42.023Z'
excerpt: >-
  https://github.com/wizlee/portfolio is official archived! It's now using the
  Github page instead of h...
thumb_img_path: >-
  https://res.cloudinary.com/practicaldev/image/fetch/s--LjdgnCqj--/c_imagga_scale,f_auto,fl_progressive,h_420,q_auto,w_1000/https://dev-to-uploads.s3.amazonaws.com/i/qyzz4vxtqzbue8ozjja1.png
comments_count: 2
positive_reactions_count: 5
tags:
  - portfolio
  - netlify
  - github
  - webdev
canonical_url: 'https://dev.to/wizlee/migrate-to-netlify-from-github-page-custom-domain-53o8'
template: post
---

https://github.com/wizlee/portfolio is official archived! It's now using the [Github page](https://wizlee.github.io/portfolio/) instead of https://wizlee.dev. 

### The steps are as briefly documented as follows:
1. Remove all Github page ALIAS and CNAME records from my web registrar site.
2. Remove custom domain from github page setting and then making sure the usual github page link is active.
3. Add custom domain in my existing Netlify project. 
4. Get the nameservers for the Netlify DNS zones and add them into my registrar site as custom DNS nameserver.
5. Verify in my site's domain setting that the new site DNS is configured successfully and the SSL cert propagated.
 
### The reasons for migrating are:
1. to utilize Netlify features such as deploy preview, functions, etc for future projects. 
2. to temporarily use private Github repo to host a static site before publishing the source code to prevent exposing keys or other sensitive information. 

During this migration there's downtime of the site, even after the SSL cert and DNS verification is done in Netlify. My assumption for this is the [Time To Live(TTL)](https://en.wikipedia.org/wiki/Time_to_live) value of the Github DNS/CDN cache. May be someone from the dev.to community can help to verify my assumption? 😉

Next up, adding this archive site as one of the projects in my live portfolio site. Stretch goal - automatically publish my latest dev.to posts onto the site using GraphQL query!

*[This post is also available on DEV.](https://dev.to/wizlee/migrate-to-netlify-from-github-page-custom-domain-53o8)*


<script>
const parent = document.getElementsByTagName('head')[0];
const script = document.createElement('script');
script.type = 'text/javascript';
script.src = 'https://cdnjs.cloudflare.com/ajax/libs/iframe-resizer/4.1.1/iframeResizer.min.js';
script.charset = 'utf-8';
script.onload = function() {
    window.iFrameResize({}, '.liquidTag');
};
parent.appendChild(script);
</script>    
