# [verbose](https://verbose.crispychat.tech)
A lightweight Image Proxy for Crispy

## What's this?
**verbose**, a lightweight Image Proxy with full `size`, `width` and `height` modifiers.

## Features
- Full `height` & `width` modifiers
- `size` modifier for making images smaller (or larger) with minimal quality loss
- Completely embeddable
- Per-image requests
- No cookies or tracking data comes out from verbose.

## What uses verbose?
**verbose** is currently being used for:
- [Crispy](https://crispychat.tech)
- [Crispy Nightly](https://nightly.crispychat.tech)
- [BFC](https://bug-free-chat.netlify.app)
- [V1RU5](https://github.com/jodri-code)'s Anon Chat

# Usage
## Image Manipulation
- `verbose?url_src=<url>` to fetch any image from URL.
- `verbose?url_src=<url>&size<size>` to fetch image and resize (100 = default).
- `verbose?url_src=<url>&width=<width>&height=<height>` to fetch image and resize to specific width and height in pixels.
<!-- ## Metadata Scraper
Coming Soon! -->

## Getting started
A nice example to get started with is:
- `https://verbose.crispychat.tech/?url_src=https%3A%2F%2Fhttp.cat%2F404` original full-size image from [http.cat](https://http.cat)/404
- `https://verbose.crispychat.tech/?url_src=https%3A%2F%2Fhttp.cat%2F404&size=45` 45% of the original size (same image)
- `https://verbose.crispychat.tech/?url_src=https%3A%2F%2Fhttp.cat%2F404&height=45&width=45` resized version (45px*45px)
