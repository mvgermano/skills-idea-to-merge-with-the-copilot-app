# Mona's Bookmark Manager Roadmap

This roadmap outlines planned improvements and known risks for Mona's Bookmark Manager.

| Area | Item | Type | Priority |
| --- | --- | --- | --- |
| Discovery | Search and filter bookmarks | 🚀 | High |
| Bookmark management | Edit saved bookmarks | 🚀 | High |
| Organization | Tags or folders | 🚀 | Medium |
| Data portability | Import and export bookmarks | 🚀 | Medium |
| Bookmark identity | Duplicate slugs | 🐛 | Medium |
| Validation | Empty-URL validation | 🐛 | High |
| Data persistence | Bookmarks lost when localStorage is cleared | 🐛 | High |

## 🚀 Planned features

- 🚀 **Search and filter bookmarks** — Find saved links quickly by searching titles and URLs or filtering the bookmark list.
- 🚀 **Edit saved bookmarks** — Update a bookmark's title, URL, or description after it has been saved.
- 🚀 **Tags or folders** — Organize bookmarks into user-defined tags or folders for easier browsing.
- 🚀 **Import and export bookmarks** — Back up bookmarks to a portable file and restore them later.

## 🐛 Known bugs & risks

- 🐛 **Duplicate slugs** — Two bookmarks can produce the same slug, potentially causing collisions when identifying or displaying them.
- 🐛 **Empty-URL validation** — An empty URL may be accepted unless the form validates it before saving.
- 🐛 **Bookmarks lost when localStorage is cleared** — Clearing browser storage permanently removes locally saved bookmarks unless users export a backup.
