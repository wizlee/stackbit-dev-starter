---
stackbit_url_path: posts/exploring-graphiql-and-adding-netlify-contentful-webhook-i9h
title: Exploring GraphiQL and adding Netlify Contentful Webhook
date: '2020-12-19T16:10:00.913Z'
excerpt: >-
  Adding my old portfolio site as one of the project in my current portfolio
  site took much less time t...
thumb_img_path: >-
  https://res.cloudinary.com/practicaldev/image/fetch/s---6BfIhVu--/c_imagga_scale,f_auto,fl_progressive,h_420,q_auto,w_1000/https://dev-to-uploads.s3.amazonaws.com/i/6esdryujk5rz41dqu4it.png
comments_count: 0
positive_reactions_count: 2
tags:
  - webdev
  - netlify
  - graphql
  - contentful
canonical_url: >-
  https://dev.to/wizlee/exploring-graphiql-and-adding-netlify-contentful-webhook-i9h
template: post
---
Adding my [old portfolio site](https://github.com/wizlee/portfolio) as one of the project in my [current portfolio site](https://wizlee.dev/) took much less time than expected. Thus, quickly proceed with the stretch goal mentioned in previous post. 

First, proceed with triggering Netlify deploy whenever content is published in Contentful. The steps are well stated in [this netlify blog post - Automate Contentful Deploys With Netlify Webhooks](https://www.netlify.com/blog/2020/04/24/automate-contentful-deploys-with-netlify-webhooks/).

Then, I continue with exploring the [Gatsby GraphiQL explorer](https://www.gatsbyjs.com/docs/how-to/querying-data/running-queries-with-graphiql). Despite some getting used to at the start, got the graphql query for dev.to articles to work quickly by using the gatsby-source-dev gatsby plugin. 
![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/0xkx114a89ym5v7pro3l.png)

The cover image of this post shows the graphql query that will be used to automatically show my latest articles in wizlee.dev. Next is to implement these as a static query!
 



*[This post is also available on DEV.](https://dev.to/wizlee/exploring-graphiql-and-adding-netlify-contentful-webhook-i9h)*


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
