# tamnd/blog

Personal blog at [tamnd.github.io/blog](https://tamnd.github.io/blog).

Built with [Hugo](https://gohugo.io) and the [Bear Blog theme](https://github.com/janraasch/hugo-bearblog). Deployed automatically to GitHub Pages on every push to `main`.

## Local development

```sh
git clone --recurse-submodules https://github.com/tamnd/blog
cd blog
hugo server -D
```

Open http://localhost:1313/blog/

## Writing a post

```sh
hugo new content posts/my-post.md
```

Edit the file, set `draft: false` when ready, then push.

## Tags

`hugo` · `blog` · `github-pages` · `bear-theme` · `writing`
