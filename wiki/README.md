# Command Center website

_Started from the folder's own files on 2026-10-30. Keep this current._

## What it is
A small public web page for the Command Center app, plus its privacy policy. The home page says Command Center is a private app that runs only on Jason's Mac, is not offered to the public, and has nothing to sign up for or download. The privacy page explains what the app reads from Google Calendar and Gmail, and where its data is kept.

## How to run it
Not written down yet.

## Where things live
- `index.html`: the home page.
- `privacy.html`: the privacy policy (says "Last updated October 2026").
- `style.css`: the look shared by both pages.
- The Command Center app itself is in a different folder, `~/Claude Code Projects/command-center` (from the shared wiki page). This folder holds only the web pages.

## Key decisions
- Google access is read only for Gmail. The app never sends, deletes or changes email (`privacy.html`).
- Calendar is read, and events are added or changed only when the owner asks (`privacy.html`).
- Sign-in keys are kept in the Mac's Keychain. Only the text of one bill email may be sent to Claude to read the amount and due date (`privacy.html`).

## Status
Pages are dated October 2026 (file dates 2026-10-21). Nothing else is written down yet.
