# lab-checklists

Phone and print checklists for NeLy lab protocols, served with GitHub Pages:
<https://nely-epfl.github.io/lab-checklists/>

Each checklist is one self-contained HTML file (no build step, no external
scripts). Tick boxes are kept in the viewer's own browser (`localStorage`),
so everyone who opens a page gets their own copy; nothing is sent anywhere.

| File | What |
|---|---|
| `2p.html` | 2P imaging session checklist (phone, tick boxes) |
| `2p-quickstart.html` | 2P rig quickstart, one A4 page to print; its QR codes open `2p.html` and the wiki protocol |

The full protocols live on the lab wiki (private), e.g.
[Technique: 2-Photon Imaging with Octacam](https://github.com/NeLy-EPFL/knowledge-base/wiki/Technique:-2-Photon-Imaging-with-Octacam).
This repo is public: only put generic steps here, never data paths,
hostnames, credentials or anything about animals/people.

## Adding a protocol

Add `<protocol>.html` (and `<protocol>-quickstart.html` if there's a wall
sheet), link it from `index.html`, and link it from the wiki page. If a page
has a QR code, regenerate it when the URL changes.
