# विश्वरूप स्टूडियो · Vishwaroop Studio

Tablet-first production studio for the **Vishwaroop 108** yatra.
A yatra is a project. A bead is an episode. Every bead walks eight stages and cannot publish until the maryada gate passes.

**Status:** v0.1 MVP — working build, not a specification.

---

## Deploy (GitHub Pages, ~3 minutes)

1. Upload `index.html`, `manifest.webmanifest`, `sw.js` and this `README.md` to the repo root of **vishwaroop-studio**.
2. Repo → **Settings → Pages** → Source: **Deploy from a branch** → Branch: `main`, folder: `/ (root)` → **Save**.
3. Wait ~1 minute, then open `https://vishwaroop108official.github.io/vishwaroop-studio/`.
4. On the Galaxy Tab S9, open that URL in Chrome → menu **⋮ → Add to Home screen / Install app**.

Installed, it launches full-screen, works offline, and stores everything on the tablet.

> The service worker and install prompt need HTTPS. GitHub Pages provides it. Opening `index.html` from local storage works too, but without install or offline caching.

---

## What v0.1 does

**Yatras and beads** — create a yatra, add beads, reopen anything. The rail shows completed beads out of the target as a filling gold thread.

**The stage mala** — eight beads on a thread: शोध → पटकथा → दृश्यक्रम → प्रॉम्प्ट → सामग्री → संपादन → परीक्षा → प्रकाशन. Tap any stage to work in it. Completed stages turn gold.

**Prompt Pack composer** — pick reusable blocks (global style, iconography lock, Trikaal, vertical modifier), write the shot line, and the full prompt assembles itself. Copy it, or add it to that bead's pack. This replaces hand-writing prompts.

**The maryada gate** — the QA stage holds the ten non-negotiable rules. Publish stays locked (🔒) until all ten are checked. Approval is a deliberate human act, by design.

**Memory** — prompt blocks, QA rules and the raga map live in one library. Edit once, every future bead inherits it.

**Backup** — the *Backup* button downloads the whole studio as JSON. `Ctrl+I` restores a backup file.

Seeded with Bead 1 (प्रथम पूज्य — verified Indonesia and Japan research), Bead 2 (कनिपकम), Bead 3 (त्रिनेत्र गणेश — research still open).

---

## ⚠️ Back up regularly

Data lives in the tablet's browser storage. Clearing browsing data, or uninstalling the app, erases it. Hit **Backup** after any real session and keep the JSON in Drive.

---

## Next builds (drive these from hands-on use, not from specs)

- **v0.2** — richer bead fields (raga, vaar, publish date); duplicate-a-bead; search across beads.
- **v0.3** — shot list as structured rows rather than free text, each row carrying its own prompt.
- **v0.4** — Temple and Deity objects as first-class memory, linkable to beads.
- **v0.5** — publish checklist with title/description/hashtag fields and a copy-all button.
- **Later** — bring the Jaap Studio counter in as a stage tool.

Build only what the tablet tells you is missing.

**ॐ गं गणपतये नमः · आपका — यात्री**
