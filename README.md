# Marrow

A local-first markdown notes app for one person. Notes are plain `.md` files on your own disk. Marrow adds a fast editor, search and linking, and optionally syncs your notes across your own devices and publishes the ones you choose as a public read-only site.

## Goals

- **Local-first.** Notes are plain markdown files in a folder you choose. The app works fully offline, and you are never locked in.
- **Single user.** Marrow has one owner: you. There is no public sign-up and no shared or collaborative editing.
- **Fast.** Search and navigation stay instant, even with thousands of notes.
- **Linked thinking.** `[[wiki-links]]`, backlinks and a graph view.

## Planned features

- [ ] Markdown editor with live preview
- [ ] Folders and tags
- [ ] Full-text search
- [ ] `[[wiki-links]]`, backlinks and graph view
- [ ] Attachments (images, files)
- [ ] Import and export
- [ ] Light and dark themes, keyboard shortcuts
- [ ] Note version history
- [ ] **Self-hosted sync** between your own devices, through a Marrow server you run yourself
- [ ] **Owner login** to protect your server: one owner account, with device tokens for your own devices
- [ ] **Publish** selected notes as a public, read-only website (no visitor accounts, no tracking)
- [ ] Mobile companion app

## Stack

- **Backend:** Go. It serves the API, watches the notes folder and handles sync and publishing.
- **Frontend:** React and TypeScript.

## Status

Early development.

## License

[MIT](LICENSE)
