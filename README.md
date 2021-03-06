# [verbose](https://verbose.crispychat.tech)
A lightweight Image Proxy for Crispy

## What's this?
**verbose**, a lightweight Image Proxy with full `size`, `width` and `height` modifiers.

Completely embeddable, request-only with per-image requests, verbose resizes content to fit mobile or desktop Crispy users screen's.

No cookies or tracking data comes out from verbose.
All tracking data from 3rd party images stop at verbose itself.

## What uses verbose?
**verbose** is currently being used for:
- [Crispy](https://crispychat.tech)
- [Crispy Nightly](https://nightly.crispychat.tech)

# How can I implement verbose to my project?
For HTML apps and websites, just embed an `iframe` with verbose's url and your image request in the `url_src` parameter.

For other apps, similar methods can be used. Just use `verbose/#url_src` like the above in any way you feel. Tip: `size` keeps aspect ratio's. 

A nice example to get started with is:
- `https://verbose.crispychat.tech/#url_src=https%3A%2F%2Fhttp.cat%2F404` original full-size image from [http.cat](https://http.cat)/404
- `https://verbose.crispychat.tech/#url_src=https%3A%2F%2Fhttp.cat%2F404&size=45` 45% of the original size (same image)
- `https://verbose.crispychat.tech/#url_src=https%3A%2F%2Fhttp.cat%2F404&height=45&width=45` resized version (45px*45px)
