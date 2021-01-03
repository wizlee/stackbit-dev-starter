---
stackbit_url_path: posts/netlify-deployment-about-section-392d
title: Netlify deployment + About Section
date: '2020-12-06T14:32:52.680Z'
excerpt: "Great news! At least for myself \U0001F609.  In my previous post, my goal for this next update is to get the N..."
thumb_img_path: >-
  https://res.cloudinary.com/practicaldev/image/fetch/s--UucR-oYr--/c_imagga_scale,f_auto,fl_progressive,h_420,q_auto,w_1000/https://dev-to-uploads.s3.amazonaws.com/i/d7h580a8ixni8jclsqp8.png
comments_count: 0
positive_reactions_count: 6
tags:
  - portfolio
  - netlify
  - resume
  - contentful
canonical_url: 'https://dev.to/wizlee/netlify-deployment-about-section-392d'
template: post
---
Great news! At least for myself 😉.

In my previous post, my goal for this next update is to get the [Netlify](https://www.netlify.com/) deployment working. That is done, together with the About Section as shown in the cover image above.

The about section now briefly introduce myself (of course it did 🤷‍♂️), has a link to my resume PDF, and the motivations behind creating the portfolio site.

This update is the first update that I didn't push any changes to Github. All update done in this post is via the [Contentful CMS](https://www.contentful.com/), including my profile picture. There's still much more other features to explore in Contentful, including an auto deploy in Netlify if there's any content published. I believe that is achievable via webhook. Though, that's a lower priority item as of now. 

Next up, adding my existing projects in the project section! One of them is my old static site which is now live at https://wizlee.dev. 

Adding a liquid tag of my previous post because it looks cool 😎

<iframe class="liquidTag" src="https://dev.to/embed/link?args=https%3A%2F%2Fdev.to%2Fwizlee%2Fcreating-portfolio-site-2-5ang" style="border: 0; width: 100%;"></iframe>


*[This post is also available on DEV.](https://dev.to/wizlee/netlify-deployment-about-section-392d)*


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
