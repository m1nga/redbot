# Shelf — Find and use what you saved

A small, private browser library for people who save useful things and struggle to find them again.

Paste a link or app share text. Give it a name you will remember. Find it by title, creator, topic or your own notes. No AI key, account or folder setup is required for this browser edition.

[Try the public sample library](https://m1nga.github.io/shelf/) · [Download the blank single-file app](https://github.com/m1nga/shelf/releases/latest/download/Shelf-Starter.html)

## Start in one minute

1. Download `Shelf-Starter.html` and open it in a modern browser.
2. Choose **Add save** and paste a link or the text copied from an app's Share button.
3. Name it if you like, then **Save to library**. Search a word you remember later.

Your library stays in that browser. Use **Library & backups → Export** before clearing browser data or moving devices. File-page storage behavior varies between browsers; if your browser restricts local storage, serve this folder locally with `python3 -m http.server 8080 --bind 127.0.0.1` and open http://127.0.0.1:8080. Keep using the same address or transfer a backup.

## What works

- Forgiving app share text and several links in one paste; duplicate URLs are merged.
- Editable topics, optional project collections, favorites, read state, archive and recoverable trash.
- Search in saved text and personal notes; cover cards and a compact list view.
- Import Shelf JSON, bookmark HTML or CSV; export a portable JSON backup.
- Optional task guides in a compatible library: method, steps, source links and an editable execution prompt.
- English interface, original saved content preserved, keyboard support and a mobile layout.

The sample website contains original example entries, not anyone's private saves. Downloaded Starter begins empty. The core app is free and MIT licensed. A downloaded file and a hosted page have separate browser storage.

## Clear limits

This public browser edition does not sign into Xiaohongshu, read an account, resolve short links, fetch every post, transcribe video or run AI classification. It saves the links/text you provide. Original pages can require their own sign-in; signed media links can expire. Topic suggestions use simple title rules and can be changed. Task guides are curated/imported, not automatically created for every new save. There is no automatic cloud sync.

Core import and search tests passed. Live Chrome checks covered first save, invalid share text recovery, multi-link paste, return after refresh and 390-pixel layout. The author knew the product; this was not a recruited-human usability study. The downloadable single-file artifact received static checks; direct file-page browser testing was unavailable in the author's automation environment. The hosted sample is checked separately.

## Research and implementation

Karakeep and Linkwarden informed the value of fast capture, visible search, simple lists and reversible organization. This implementation was authored independently; their code is not bundled. Shelf focuses on a small browser library and task-led use, rather than matching their server, archival and AI features.

## Author

Built by [Ming](https://github.com/m1nga). Public source is an exported browser distribution of the maintained Shelf project. No personal library, cookies, connector credentials or private research are included.
