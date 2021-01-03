---
stackbit_url_path: posts/using-dev-as-cms-by-connecting-with-stackbit-h
title: Using DEV as CMS by connecting with Stackbit
date: '2021-01-03T08:31:31.907Z'
excerpt: "Table Of Contents    Confession Frontmatter  Stackbit                  Confession \U0001F5E3    This is a c..."
thumb_img_path: >-
  https://res.cloudinary.com/practicaldev/image/fetch/s--fxejJdvm--/c_imagga_scale,f_auto,fl_progressive,h_420,q_auto,w_1000/https://dev-to-uploads.s3.amazonaws.com/i/s2c6rms3k5aqf40933di.png
comments_count: 0
positive_reactions_count: 0
tags:
  - webdev
  - portfolio
  - stackbit
  - frontmatter
canonical_url: 'https://dev.to/wizlee/using-dev-as-cms-by-connecting-with-stackbit-h'
template: post
---

<iframe class="liquidTag" src="https://dev.to/embed/details?args=Table%20Of%20Contents" style="border: 0; width: 100%;"></iframe>

  * [Confession](# Confession)
  * [Frontmatter](# Frontmatter)
  * [Stackbit](# Stackbit)

<iframe class="liquidTag" src="https://dev.to/embed/enddetails?args=" style="border: 0; width: 100%;"></iframe>


---

### Confession 🗣 <a name="Confession"></a>
This is a confession - I deviated from my goal of automatically redeploy my site whenever I posted a new DEV article. I became a wanderer👨‍🚀. I wander into admiring with how clean https://www.emgoto.com/ looks, and the elegant background of https://coffeecodeclimb.com...

OK, wanderer is an exaggeration because everything mentioned below is the result of attempting to achieve the goal. Nonetheless, I did feel that I moves at a 🐌 speed as compared to the progress made in my previous posts in the series. 

With the mini venting out of the way, I did learnt about Frontmatter and Stackbit during the process of figuring out how to redeploy my static site whenever a new article is posted. These two are the sharing of this article.

### Frontmatter <a name="Frontmatter"></a>
Shall keep this section short as found that [this article by coffeecodeclimb](https://coffeecodeclimb.com/what-is-frontmatter/) explained it nicely. 

In a single sentence - Frontmatter is the first and topmost section of a markdown document enclosed in two triple dash 
`---`
 lines, with YAML syntax content. Example as below:

```YAML
---
title: Frontmatter as short as possible
tags: [code, frontmatter, blog, yaml]
---
```


### Stackbit <a name="Stackbit"></a>

I first came across [Stackbit](https://www.stackbit.com/) when reading beeman's dev article on automating your dev posts using github-actions.

<iframe class="liquidTag" src="https://dev.to/embed/link?args=beeman%2Fautomate-your-dev-posts-using-github-actions-4hp3" style="border: 0; width: 100%;"></iframe>


The majority of the articles online intend to ultimately use git as the content management system, including beeman's article above. However I am not yet ready for that step and I intend to still store my articles exclusively in DEV. 

This is where the mentioned of Stackbit in the article becomes of interest. Quoted:
> The build on Netlify happens in one of two occasions: 
> when my content on DEV updates or when the GitHub repo updates.

That is exactly what I aimed for and best still there's no need for an extra Github action, or [Travis CI](https://dev.to/maxime1992/manage-your-dev-to-blog-posts-from-a-git-repo-and-use-continuous-deployment-to-auto-publish-update-them-143j) and [Pipedream](https://dev.to/dylburger/publish-dev-articles-from-a-git-repo-with-github-pipedream-505j) as explained in other excellent articles.

At first I tried the "Import Site" feature of Stackbit in hope that it will work out of the box, unfortunately it failed and I yet to wrap my head around on the failure. 

Then, I attempted to create a fresh site from the Stackbit dashboard in order to understand more about how the DEV integration works. I only able to figure out how to do that after reading this DEV guide - https://dev.to/connecting-with-stackbit. 
- Use this DEV Stackbit flow - https://app.stackbit.com/create?ref=devto, only then DEV will show up as the choice in CMS.
- Or you can go to [dev extension settings](https://dev.to/settings/extensions) and enable Stackbit integration as showed below
![Alt Text](https://dev-to-uploads.s3.amazonaws.com/i/pbcs5tpgjvkdklalg0ta.png)

The rest of the steps are very intuitive, the site will be live after following the on-screen instructions by connecting to services such as Netlify & Github. Example site using the 'Fresh' theme - https://stackbit-dev-starter.netlify.app/. 

Next up, figure out how the Stackbit Dev Integration works and implement it into https://wizlee.dev!


*[This post is also available on DEV.](https://dev.to/wizlee/using-dev-as-cms-by-connecting-with-stackbit-h)*


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
