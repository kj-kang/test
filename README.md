---
title: a
  - TEST
summary: We've introduced the concept of future flags to give you a smooth upgrade path for your Remix app.
featured: false
date: 2023-03-17
image: /blog-images/headers/the-future-is-now.jpg
imageAlt: The Future is Now
authors:  

  - TEST
  
  - TEST
    - SUB1
  - SUB2
published: false
---

At Remix, we know first-hand just how painful it can be to go through a major version upgrade. Especially for something as foundational to your application as the framework or router it's built on. We want to do our very best to provide you a best-in-class upgrade experience -- let's talk about **"Future Flags"**.

## Status Quo

Every[^1] framework (or library) out there will _at some point_ have to introduce a breaking change. Something that will cause your code _as it's written today_ to break on the new version. This could result in a build-time (or even worse, a run-time) error. But these changes are good! It's how our frameworks evolve, get faster, adopt new platform features, implement community-driven feature requests, and so-on.

Out of this inherent need for breaking changes came the [Semantic Versioning][semver] (SemVer) specification which defines that breaking changes dictate a new _major_ release version. This is great because it lets application developers know when they should expect their code to require changes on an upgrade, versus when they should expect the upgrade to "just work". Remember though, you should always be reading the release notes and not just blindly upgrading 😉.

[^1]: "Every" and not "All" because I'm sure there's _some_ library out there like `add` that has been humming along at v1.0.0 for years without breaking changes because ... well the semantics of mathematics don't change all that frequently. But you get the idea - things evolve and require breaking changes, unless you're the [DOM][dom] which does a wonderful job with backwards-compatibility.
