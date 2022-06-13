# [verbose](https://verbose.crispychat.tech)
A lightweight Image Proxy for Crispy

## What's this?
**verbose**, a lightweight Image Proxy with full `size`, `width` and `height` modifiers.

completely embeddable, request-only with per-image requests, verbose resizes content to fit mobile or desktop Crispy users screen's.

no cookies nor tracking data comes out from verbose.

this also removes tracking data from 3rd party images (they stop at verbose itself).

## What uses verbose?
**verbose** is currently being used for:
- [Crispy](https://crispychat.tech) and [Nightly](https://nightly.crispychat.tech)
- [Bottom](https://bottombots.xyz)

# How can I implement verbose to my project?
for HTML apps and websites, just embed an `iframe` with verbose's url and your image request in the `url_src` parameter.

a nice example to get started with is:
- `https://verbose.crispychat.tech/#url_src=https%3A%2F%2Fhttp.cat%2F404` original full-size image from [http.cat](https://http.cat)/404
- `https://verbose.crispychat.tech/#url_src=https%3A%2F%2Fhttp.cat%2F404&size=45` 45% of the original size (same image)
- `https://verbose.crispychat.tech/#url_src=https%3A%2F%2Fhttp.cat%2F404&height=45&width=45` resized version (45px*45px)
