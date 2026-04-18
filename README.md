# MindThread

A local-first note-taking app built around one core idea: **thinking in threads**.

---

## The Core Feature — Threads

Most note apps treat notes as isolated entries. MindThread treats them as the beginning of a conversation with yourself.

Every note can become the root of a **MindThread** — a vertical chain of connected thoughts that branch and evolve from a single idea. Write a note about a book highlight, then thread your reactions, contradictions, and insights directly beneath it. One idea, one place, one continuous line of thought.

Threads can go deeper. Any note inside a thread can spawn its own **sub-thread** — a new chain that branches off from that specific thought while staying connected to its origin. A note about scarcity in a business thread can open a whole new thread about personal development, without ever leaving its original context.

---

## Spotlight — Find Anything, Fast

The Spotlight search (`⌥S`) is the fastest way to navigate your notes.

- **Full-text search** — just start typing
- **Title filter** — `t: your title`
- **Tag filter** — `tag: concept`
- **Natural date search** — type `abril 14`, `april 14`, `14 abril`, `ayer`, or `yesterday` to find notes by date without memorizing formats
- **Smart keywords** — `hoy`, `today`, `esta semana`, `orphans`, `tasks`

---

## Other Features

- **Three note types** — LIT (thoughts), SRC (sources & highlights), threads
- **Local vault sync** — notes saved as `.md` files with YAML frontmatter to any folder on your system
- **Wikilinks** — connect notes with `[[Note Title]]` syntax, with backlink tracking
- **Clickable stats** — filter the feed by note type, threads, or orphans directly from the sidebar
- **Calendar** — browse notes by day
- **Pinned notes** — keep important notes at the top of the feed
- **Markdown support** — full inline formatting with a toolbar

---

## Local-First & Private

All data lives in your browser's IndexedDB. No accounts, no servers, no sync to the cloud. If you connect a vault folder, notes are written as plain `.md` files you own completely.

---

## Getting Started

1. Open `index.html` in any modern browser (Chrome or Edge recommended for vault sync via File System Access API)
2. Start writing in the composer at the top
3. Press `⌥S` to open Spotlight at any time
4. Click the thread badge on any note to open or start a thread

---

## PWA Install

MindThread works as a Progressive Web App. When hosted (e.g. GitHub Pages), your browser will offer an install option to run it as a standalone app.
