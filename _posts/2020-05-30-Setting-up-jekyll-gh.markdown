---
layout: post
title:  "Setting up Github pages and Jekyll"
date:   2020-05-30 21:00:02 -0400
categories: jekyll github pages
---

I knew Github is awesome, i use it at work day in and day out. They have especially been killing it since Mirosoft bought them.
[Github Sponsor][github-sponsor],[Github Free for Teams][github-free],[Github's Codespace][github-codespace] and [Github's mobile apps][github-mobile] to name a few. 
However, how quick and easy(in its league) was it to set this blog with Github pages and Jekyll just blew my mind away 🤯(Ready made 
solution like Wordpress, Medium, Ghost are easier but Github pages gives you more control and more importanly also gives me the 
weird feeling i own the my data)

Now here's what i did to set this blog up.

- Create your github account(duh!) and new repo. Name of the repo should be [username].github.io. Mine was nf17.github.io.
- Install Ruby, Gems, and Jekyll. These are to the most part covered here --> [About GitHub Pages and Jekyll][github-page-install]
- Clone your repo locally and CD into it.
- Run the command `Jekyll new . --force`
- Open the gem file(not gemlock) and follow the instruction on it. (you have to uncomment the line for github pages)
- Git push it

Your blog should be up and running on your-username.github.io. Looks for the _post folder in your repo to add / modify new posts. Also you
might want to update your About and other pages.

[github-sponsor]: https://github.blog/2020-05-12-github-sponsors-is-out-of-beta-for-sponsored-organizations/
[github-free]: https://github.blog/2020-04-14-github-is-now-free-for-teams/
[github-codespace]: https://github.blog/2020-05-06-new-from-satellite-2020-github-codespaces-github-discussions-securing-code-in-private-repositories-and-more/#codespaces
[github-mobile]: https://github.com/mobile/
[github-page-install]: https://help.github.com/en/github/working-with-github-pages/about-github-pages-and-jekyll
