# 90s-internet.com

The 90s Internet Webring — a webring for people who make simple websites about stuff they care about.

Not about literally using 1996 technology. More about the feeling: personal sites, made with love, about things you love. Use whatever HTML you want.

Hosted at [90s-internet.com](https://90s-internet.com) via GitHub Pages.

## Join!

We'd love to have you. Don't have a site yet? Check out our [5 Minute Website guide](https://90s-internet.com/guide.html).

[Open an issue](https://github.com/oatsandsugar/90s-internet/issues/new?title=Join%20the%20webring&labels=join&body=My%20site%3A%20%0A%0AA%20short%20description%3A%20%0A%0AI%20added%20the%20webring%20snippet%20to%20my%20site%3A%20yes%20%2F%20not%20yet) with:

- Your site URL
- A short description (e.g. "books for a baby", "honest brick reviews")
- Add the [webring snippet](https://90s-internet.com) to your site (shown on the homepage)

All contributions welcome — new members, bug fixes, ideas. Just open an issue or a PR.

## How it works

Members embed a small HTML snippet on their sites with links to `90s-internet.com/#prev`, `#next`, and `#random`. A script on the homepage reads the hash and `document.referrer` to figure out which member the visitor came from, then redirects to the right site.

The snippet is pure static HTML. All the navigation logic lives on the homepage.

## Adding a new member

1. Add their URL to the `members` array in the `<script>` at the bottom of `index.html`
2. Add them to the Ring Members list in the HTML

The member count in the title bar updates automatically from the `members` array.
