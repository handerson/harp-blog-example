# A Simple Blog Example for Harp

* This is site is compiled using [harp](http://harpjs.com)
* [prism](https://prismjs.com/) for syntax highlighting
* [pico.css](https://picocss.com) for styling.
* rss feed
* prev/next post basic pagination
* index shows 3 newest posts
* posts/index shows list of all posts

## Get started

run `harp _harp` to start local server


run `harp _harp _build` to build

## Demo

[View repo example](https://handerson.github.io/harp-blog-example/) compiled and deployed to github pages

### How to deploy to Github pages 

#### build
`harp _harp ./`

#### move files to the gh-pages branch
`git add . && git stash && git checkout gh-pages && git rm -rf . && git stash pop && git checkout main .gitignore`

#### push to github
`git add -A && git commit -m "new build" && git push`