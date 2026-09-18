# UUID Generator

A small, dependency-free UUID generator for creating UUID version 4 and version 7 values directly in your browser.

UUIDs are generated locally using cryptographically secure random bytes. No generated values are transmitted.

## Features

+ UUID version 4 — random UUIDs
+ UUID version 7 — Unix timestamp-based, time-ordered UUIDs
+ Generate between 1 and 1,000 UUIDs at once
+ New-line, comma or space separators
+ Optional hyphens
+ Optional braces
+ Optional uppercase output
+ Optional `urn:uuid:` representation
+ Copy all generated UUIDs
+ `Ctrl+Enter` / `Cmd+Enter` keyboard shortcut for generation
+ Cryptographically secure randomness with the Web Crypto API
+ Automatic light and dark mode
+ Responsive layout
+ No dependencies
+ No build step
+ Runs completely locally in the browser

## Privacy

All UUID generation happens locally in the browser.

The application has no backend, sends no generated UUIDs over the network, and requires no analytics or external libraries.

## Live version

The tool is deployed using [GitHub Pages](https://docs.github.com/en/pages/getting-started-with-github-pages/what-is-github-pages) and can be used directly in a modern web browser. 

[![Live version](https://img.shields.io/badge/Open%20UUID%20Generator-2563eb?style=for-the-badge)](https://openpotato.github.io/uuid-gen/)

## Development

The tool is intentionally implemented as a single HTML file using plain [HTML](https://html.spec.whatwg.org/), [CSS](https://www.w3.org/Style/CSS/) and [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript).

## Can I help?

Yes, that would be much appreciated. The best way to help is to post a response via the Issue Tracker and/or submit a Pull Request.
