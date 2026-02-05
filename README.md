# URL Pattern Blocker (Chrome Extension)

A lightweight Chrome extension that blocks matching URLs using Chrome’s `declarativeNetRequest` rules. Handy for filtering out specific pages or query variants, like Google Search URLs containing `udm=50`.

## Install
- **Chrome Web Store:** [URL Pattern Blocker](https://chromewebstore.google.com/detail/url-pattern-blocker/mfihmecpcneikcfmekdgcjcahmgdfhcg)

## What it does
- Block URLs by pattern (rules based)
- Uses `declarativeNetRequest` for fast, native blocking
- Great for removing annoying page variants or parameter based URLs

## Example
If you want to block Google Search result pages that include `udm=50`, you can add a rule that matches URLs containing:

- `udm=50`

## How it works (high level)
This extension creates `declarativeNetRequest` blocking rules. When a request URL matches a rule, Chrome blocks it automatically.

## Tips
- Start with **narrow** patterns to avoid blocking too much.
- Chrome enforces limits on the number of rules and some rule types.



