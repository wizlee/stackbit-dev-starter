---
stackbit_url_path: posts/creating-portfolio-site-2-5ang
title: Personalizing Landing Page
date: '2020-12-05T16:19:44.838Z'
excerpt: >-
  The cover image above shows the gatsby-starter-mate working locally on my PC.
  The landing page custom...
thumb_img_path: >-
  https://res.cloudinary.com/practicaldev/image/fetch/s--JMxa50aC--/c_imagga_scale,f_auto,fl_progressive,h_420,q_auto,w_1000/https://dev-to-uploads.s3.amazonaws.com/i/faoemgmj0c6hahg795er.png
comments_count: 0
positive_reactions_count: 4
tags:
  - portfolio
  - rebass
  - netlify
  - gatsby
canonical_url: 'https://dev.to/wizlee/creating-portfolio-site-2-5ang'
template: post
---
The cover image above shows the [gatsby-starter-mate](https://gatsby-starter-mate.netlify.app/) working locally on my PC. The landing page customization is done by setting up my own [Contentful CMS account](https://app.contentful.com).

Learn about [Rebass](https://rebassjs.org/) (a react primitive UI components built with [Styled System](https://styled-system.com)) when trying to make the [React TextLoop component](https://www.npmjs.com/package/react-text-loop) to work properly. I was not able to make the text inside of the TextLoop component to wrap around to the next line. The solution is to set the 
`noWrap`
 props of the component to 
`false`
. 

Another great learning when working using Rebass is [responsive styles](https://styled-system.com/responsive-styles), specifically on how [array props](https://styled-system.com/guides/array-props) works. The syntax of using array 
`[]`
 to represent media query breakpoints needs some getting used to, but once I did it looks so clean and sweet 🍬! 

Next post - deploying using [Netlify](https://app.netlify.com). 

*[This post is also available on DEV.](https://dev.to/wizlee/creating-portfolio-site-2-5ang)*


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
