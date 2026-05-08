# discourse

This repository powers the comment section for my personal website and blog at [yentl.dev](https://yentl.dev).

I have decided to use the GitHub Discussions backend with [Giscus](https://giscus.app), which is embedded on my blog posts.

## How comments work

Each blog post can be mapped to a GitHub Discussion through Giscus. When a reader leaves a comment on the site, it is stored here as a discussion or discussion reply rather than in a custom database.

## Why this setup

Using Giscus keeps the comment system simple and durable:

- No separate comment backend to maintain
- Comments are stored on GitHub
- Moderation can happen through GitHub Discussions
- The website can stay mostly static while still supporting discussion
