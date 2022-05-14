## ToC

- [v6.0](#v60)
- [v5.0](#v50)
- [v4.0](#v40)
- [v3.0](#v30)
- [v2.0](#v20)
- [v1.0](#v10)

---

### v6.0

[Compare v5.0...v6.0](https://github.com/adityatelange/hugo-PaperMod/compare/v5.0...v6.0)

- Added Feature `ShowCodeCopyButtons` - Adds a button to copy code block contents.
- Added Feature `ShowFullTextinRSS` - Adds Full Text content in RSS feeds.
- Added Feature `ShowAllPagesInArchive` - To show all pages in archives.
- Added Feature `Originally published at` when `canonicalUrl` and `ShowCanonicalLink` is set .
- Theme colors are converted from `rgba` to `hex`.
- Added option to customize Social-Media Share buttons `ShareButtons: ["linkedin", "twitter"]`
- Added option to hide copyright/footer text
- Added `summary` in section pages, `Content` on list pages, `description` can now be in markdown on list pages.
- Added `placeholder` param in Search to customize placeholder in search input box.
- Added option to disable Anchored headings `disableAnchoredHeadings`
- Updated internal Hugo templates.
- Add Translations of `Ukrainian`, `Russian`, `Esperanto`, `Vietnamese`, `Turkish`, `Mongolian`, `Polish`, `Bengali`, `Dutch`, `Chinese`, `Kurdish`, `Italian`, `Danish`, `Korean`.
- Add social icons of `hackerone`, `xda`, `goodreads`, `splotify`, `flicker`, `librepay`, `matrix`, `serverfault`, `researchgate`, `googlescholar`, `ycombinator`, `polywork`, `cv`, `xing`, `phone`.
- Fixed Emojis affected by theme opacity values.
- Fixed line highlighting in code-blocks.
- Fixed `params.fuseOpts` being ignored by Fuse.js.
- Miscellaneous improvements, fixes and accessibility enhancements.

### v5.0

[Compare v4.0...v5.0](https://github.com/adityatelange/hugo-PaperMod/compare/v4.0...v5.0)

- Add Feature `ShowPostNavLinks` - shows Prev Next post links on single post page
- Add Feature `BreadCrumbNavigation` - adds Breadcrumb navigation above title of single page/post
- Add feature `editPost` - adds option to show link in meta data for editing posts
- Add support for `rtl` and `ltr` shortcodes
- Add Translations of `Japanese`, `Hungarian`, `Catalan`, `Uzbek`, `Hebrew`, `Arabic`, `Portuguese`
- Add social icons of `snapchat`, `gitea`, `unsplash`, `itchio`, `ctftime`
- Add browser-level lazy-loading of images
- Improve overall design to fit Prev Next post links and remove borders
- Improve scrollbar styling
- Tweak Fuse options for search
- Improve theme changes when JS is disabled
- Fix code highlight when HLJS is disabled
- Fix colors in embeded gist
- Fix `...` being shown for smaller summary in posts
- Update internal templates from hugo
- Miscellaneous improvements, fixes and accessibility enhancements

### v4.0

[Compare v3.0...v4.0](https://github.com/adityatelange/hugo-PaperMod/compare/v3.0...v4.0)

- Added `AccessKeys`
- Improve `theme-switch` logic
- Port `Anchored Headings` from [Codex](https://github.com/jakewies/hugo-theme-codex)
- Added social-icons for `Discord, Mastodon, Keybase, Ko-Fi, Kakaotalk, Nuget, Reddit`
- Update `HLJS to v10.2.1`
- Added `Search` feature with fuse.js and options to tweak search & keyboard navigation in search results
- Add `emojify` in Language-Switch
- Load stylesheet resource with wildcard
- Unset line-clamp in Home-Info mode, content can be as long as one wants it to be
- Disable indexing website when not in production
- Social-Icons name can match even when case does not match with set name
- Add option to `disable fingerprinting`
- Add option to `disable highlight.js`
- Retain `anchor link '#'` in URL when clicked on anchored headings
- Add support for `custom taxonomy URLs`
- Add option to hide cover images from list, single but retain in structured-data and share links
- `Extended css` can be directly added to asset bundle, all .css under `assets/css/extended/`
- Do not smooth-scroll when user has preferred to not
- Fix `broken anchor Link` scroll for Table of Contents and non-ASCII chars
- Fix Lang Name hidden when LanguageName was unset
- Fix scroll-bar track on various conditions
- Fix menu items overflow instead of horizontal scroll
- Fix Trailing slash in menu urls
- Fix figure captions added to Table of Contents
- Fix embeded gist colored dark
- Fix wrong load stylesheet and JS on multihost (multilingual)
- Fix Go-To-Top button not shown on code-background in light mode
- Translations added: Bahasa(id), Italian(it), improvements to german(de)
- Miscellaneous improvements, fixes and accessibility enhancements

---

### v3.0

[Compare v2.0...v3.0](https://github.com/adityatelange/hugo-PaperMod/compare/v2.0...v3.0)

- enhanced templates a/c to theme for `social-meta`
- add support for `Rich Results`
- add option to customize `NavBar Label`
- i18n: more translations (thanks to contributors)
- add support for `extended_head` and `extended_footer`
- add support for `Right Aligned Text` for multilingual mode
- add support for `responsive cover image`
- add support for `multiple authors`
- add automatic `#hashtag` generator for twitter share with `tags` from a post
- add `Language switch`, an improvement to multilingual feature
- miscellaneous improvements, fixes and accessibility enhancements

---

### v2.0

[Compare v1.0...v2.0](https://github.com/adityatelange/hugo-PaperMod/compare/v1.0...v2.0)

- added support for `cover image` with captions
- add option to allow `disabling of special 1st post`
- improved `taxonomy` pages
- added option to `open toc` by deafult(for each post)
- theme: `automatic` based on browser theme
- update `HLJS to v10.2.0`
- `ToC`: improvements, fixes (custom implementation)
- Archives: improvements
- added `Menu Location indicator`
- i18n: more translations (thanks to contributors)
- profile-mode: subtitle
- added `theme-toggle` to switch between dark and light
- footer: user-defined copyright
- `favicon` can be set to custom path
- comments can be disabled for a page
- miscellaneous improvements, fixes and accessibility enhancements

---

### v1.0

[Compare ...v1.0](https://github.com/adityatelange/hugo-PaperMod/compare/4330c8b...v1.0)

- use of `hugo's asset generator with pipelining`
- asset `fingerprinting`, `bundling` and `minification` by default
- seperated `layouts` and `partials` into more readable parts
- separated `css stylesheets` into parts
- added `archive` layout
- added `Home-Info` Mode
- added `Table of content` genration
- added `smooth scroll` between in page tags
- added `Taxonomy pages` (tags, categories)
- added themed `scrollbar`
- added `Scroll-to-Top` button
- added post `Share` buttons
- added `draft` page indicator
- added google siteverification tag vars
- add option to disable post meta
- save `menu scroll position` in browser's storage
- added `Profile-Mode` with buttons
- added `Social Icons`
- updated `HLJS`
- added `multilingual support`
- micellaneous `additions`, `improvements` and `fixes`
