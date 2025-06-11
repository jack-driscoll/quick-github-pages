# Getting Started with Github Pages

## Introduction

- Getting started with GitHub Pages is easier than you think and easier than they
make it seem.  First, download skeleton.zip from my repo.  This will explain
almost everything.

- Next, make a repository, as in [this guide](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site) follow the instructions up until create your page.

- When you have studied the files, which should all be self-explanatory, you can delete the shameless self-promotion file, the two unnecessary posts, and make your own!

- You should [learn how to use markdown](https://www.markdownguide.org/), which is the default **language** the files are written in.  It's pretty easy, you may even use some of the shorthand already!

- Once you have modified the files `_config.yml`, and `index.md` (I would also suggest changing the files in `_posts`, `about.md` and `page.md`) re-upload the files to your github repo [as in this introductory hello world example](https://docs.github.com/en/get-started/start-your-journey/hello-world) or by uploading the individual files and folder.  All you *really* need is `index.md` and `_config.yml`, though.  Honest.  (In short, though, once you've got your credentials, usually after you've `git clone`-d the directory, you go into it, `git init`, then `git add . && git commit -m "comment on your commit" && git push origin main`  will do everything (add the files, "commit" them, upload them to github).

## quick-github-pages.zip

This file has all the files you really *need* in ***9KB***

That's ***ALL YOU NEED TO GET STARTED WITH GITHUB PAGES***

### _posts

Make new posts in this directory, following the examples shown.  These pages will be rendered into html files as your "blog", at the bottom of your page.

- `2023-11-29-complex.md` is a "complex" "blog post" note it is `layout: post`
- `2023-11-29-permalink.md` is a post with a permalink
- `2025-06-02-seriously.md` is my bio, which you should probably change or delete, but can read or leave in if you're feeling adventurous or promotional

### .gitignore

You can also safely ignore this

### _config.yml

This is the basics of your website, follow the directions inside, if it says
"replace this with your something" put your something there.

### about.md

An about page, linked as yourname.github.io/about/

### Gemfile and Gemfile.lock

Some ruby shit, you can ignore these.  TBH, not even sure if you need them, *but you might*.

### 404.html

An error webpage, you need this, but don't need to do anything with it.

### index.md

**Edit this file and replace with your content**.  This will be the `index.html`
file, **the root of your website**.  **This is what will show up** when you visit
`https://yourname.github.io`

### LICENSE

Edit this file and replace "YOUR NAME HERE" with your name.

### page.md

This is an example of a page, it will show up on top as a link titled "A page"

### README.md

This file, literally.

### _config.yml

It's up at the top, after posts, because you start there.
