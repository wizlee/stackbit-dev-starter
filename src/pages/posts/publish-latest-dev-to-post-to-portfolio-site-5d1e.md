---
stackbit_url_path: posts/publish-latest-dev-to-post-to-portfolio-site-5d1e
title: Publish Latest Dev.To Post to Portfolio Site
date: '2020-12-27T06:21:47.499Z'
excerpt: >-
  "We are one", says wizlee.dev to dev.to/wizlee.  That's 'humanification' of my
  portfolio site after g...
thumb_img_path: >-
  https://res.cloudinary.com/practicaldev/image/fetch/s--SZXDwrQY--/c_imagga_scale,f_auto,fl_progressive,h_420,q_auto,w_1000/https://dev-to-uploads.s3.amazonaws.com/i/m492x7rfpykhwnuifq6g.png
comments_count: 2
positive_reactions_count: 4
tags:
  - portfolio
  - graphql
  - webdev
  - netlify
canonical_url: 'https://dev.to/wizlee/publish-latest-dev-to-post-to-portfolio-site-5d1e'
template: post
---
"*We are one*", says [wizlee.dev](https://wizlee.dev) to [dev.to/wizlee](https://dev.to/wizlee).

That's 'humanification' of my portfolio site after gaining the ability to list my posts from dev.to ;)

Due to the ground work done in Ema Suriano's [gatsby-starter-mate](https://github.com/EmaSuriano/gatsby-starter-mate), after the work done in the previous post only the following are needed:
1. Get data from GraphQL query using Gatsby's [useStaticQuery](https://www.gatsbyjs.com/blog/2019-02-20-introducing-use-static-query/). 
2. Add empty response in case there's no user defined in Contentful CMS. 
3. Replace the original Medium posts integration with Dev posts mainly by modifying 
`src/sections/Writing.ts`
 & 
`src/components/Post.ts`


Next up, figuring out how to trigger Netlify deploy when a new dev article is posted!

*[This post is also available on DEV.](https://dev.to/wizlee/publish-latest-dev-to-post-to-portfolio-site-5d1e)*


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
