# RedBot — Know where to start

Saved something useful, but still do not know which thing to read when you need it?

Describe what you are trying to get done. RedBot chooses **one supported starting point** from your saved material, explains why, shows the observations or passage to read and gives a next action. A broad or mixed goal asks one clarification first. Unread links are labeled **Needs reading**, not disguised as reviewed recommendations.

[Open RedBot](https://m1nga.github.io/redbot/) · [Download the blank app](https://github.com/m1nga/redbot/releases/latest/download/RedBot-Starter.html)

## Try it

Open the public example and enter: `My page looks cheap and cluttered.`
You will get one route, its source note, the useful part and one next step. Try `Improve my website` to see a plain-language clarification. Keep a plan to return to it; Not a fit is remembered only for that exact goal. Returning visitors can choose Load updated examples without replacing their own saves or notes.

## Your own library

Download `RedBot-Starter.html`, open it in a modern browser and choose Add save. Paste a link or app share text; titles and notes are optional. Shelf-format backups still import. Library & backups exports a portable copy. Browser, file and Mac storage are separate; back up before clearing data or changing devices. If a browser restricts local-file storage, serve this directory with `python3 -m http.server 8080 --bind 127.0.0.1` and open http://127.0.0.1:8080.

## What the chooser actually knows

This version uses local goal wording and curated task-guide routes. It is **not model-based semantic ranking**, a comparison of every original video, or an automatic transcription service. Recommendations can use only the saved research/text and imported guides. Title-only matches request reading before a useful part can be selected. No supported match means an explicit gap, rather than an invented answer. The demo uses two original example notes, not private user material.

Task guides connect goal, method, steps, source and limits. Their sources stay separate from tool installation or execution. Copying instructions does not run anything. The public browser edition does not sign into Xiaohongshu or scan an account. No AI key, account or cloud sync is needed for core use; original pages may require their own sign-in.

## Other library features

Editable topics, optional collections, favorites, read state, archive and recoverable trash; saved-text search; grid/list; JSON, bookmark HTML and CSV import; JSON backup/restore; keyboard and mobile layouts. Simple title rules suggest topics and can be changed.

## Verification and limits

13 core tests passed, including goal clarification, source anchors, unread-content boundaries, unsupported requests, discarded sources and scoped feedback. Builder-aware live Chrome checks cover goal → one route → useful source, saving a plan, clarification, no-match and mobile behavior. This is not an unaided nontechnical human trial. The single-file artifact receives static checks; browser file-page behavior remains user-browser dependent.

## Name and compatibility

RedBot was previously named Shelf. Existing browser storage keys and the Mac data directory remain stable to preserve saves and notes. Old source repositories redirect here; prior releases remain history. The current public page is /redbot/.

## Author and license

Built by [Ming](https://github.com/m1nga). MIT licensed. This is the clean browser distribution; no personal library, cookies, access tokens or connector credentials are included.
