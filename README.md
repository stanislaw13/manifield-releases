# Manifield — releases

Manifield is a native macOS app for developing mathematics with AI agents. Your theory —
definitions, lemmas, theorems, conjectures — lives as plain Markdown files, and the agents work
over *your* definitions rather than a blank chat: answering questions grounded in your library,
checking conjectures with sandboxed Python that keeps the script and output behind every claim,
and drafting proofs that an adversarially-prompted reviewer then attacks.

Nothing is ever marked "correct". The best status a result can reach is *review found no errors*.

**This is a private beta.** It has bugs, it is not feature-complete, and some corners are
unfinished. If you are not one of the invited testers you are still welcome to it — just know
what you are getting.

## Download

[Latest release](../../releases/latest)

## Requirements

- macOS 15 or later — Apple Silicon or Intel
- A paid ChatGPT plan, plus either the ChatGPT desktop app or the Codex CLI installed.
  Manifield runs models through your own Codex login, so there is no API bill.
- A few hundred MB of disk for the optional Python environment

## Installing

1. Open the DMG and **drag Manifield to Applications**. Do not run it from the disk image —
   macOS then runs it from a randomised read-only path, and bundled resources and the Python
   sandbox misbehave in ways that look like unrelated bugs.
2. Launch it from Applications. macOS asks once whether to open an app downloaded from the
   internet; that is expected. The app is signed and notarised, so there is no security warning
   beyond that one question.
3. Allow access to your Documents folder when asked — projects live in `~/Documents/Manifield`.

## Reporting problems

**Help → "Report a Bug…"** in the app. It shows you exactly what will be sent before anything
leaves your machine, and it never includes your mathematical content.

## Source

Not public yet. Manifield will be released under the GNU General Public License v3.0 when it
leaves private beta.
