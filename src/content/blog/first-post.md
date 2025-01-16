---
title: 'Does Bevy support turn-based games?'
description: 'Lorem ipsum dolor sit amet'
pubDate: 'Jul 08 2022'
heroImage: '/blog-placeholder-3.jpg'
---

I recently saw this question posted in the [Help channel on bevy's discord](https://discordapp.com/channels/691052431525675048/1019697973933899910), this is something I've thought about implementing myself, so this seemed as good a time as any to take a crack at it, and detail my thoughts on the implementation in a blog post

// Picture of help post if given permission //

## 1. What is a turn?

With something like this, I feel it helps to zoom out and think about what we're really trying to accomplish before diving into the implementation.

```rust
    pub struct Turn;
```

