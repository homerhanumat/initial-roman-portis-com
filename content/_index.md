---
title: "Home"
---

# North Star Athletics

Welcome to my CSC course website.  
This site contains:

- A Home page
- An About page
- An Articles page
- Two articles explaining Eloquent JavaScript problems

**HSW**:  You were using the **bootstrap-bp-hugo-theme**, but when one serves the site with that theme once cannot navigate away from the home page.  Therefore I switched to the anake theme (see your `hugo.toml` to see where I did this).  I also renamed this file `_index.md` to avoid the rendering issue mentioned in my email earlier this week.  I deleted everything you had put in your layouts folder, as it was overriding things in ananke's layouts folder and causing the site not to render.  Now I can navigate to all of your content.  Lastly, finding no deployed site with the required name, I modified your `netlify.toml` file as per the directions in the [hugo docs](https://gohugo.io/host-and-deploy/host-on-netlify/), so I could be sure to be able to deploy on Netlify.
