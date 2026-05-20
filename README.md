# NBBOA Haul Out Application form

This repository hosts the **online Haul Out Application form** for the
Northcote & Birkenhead Boat Owners Association.

Members open it in any web browser — phone, tablet or computer — fill it in,
download a PDF, and email that PDF (plus their insurance certificate) to the
Yard Captain. No app, no login, nothing to install.

## The live form

➡️ **https://REPLACE-AFTER-PUBLISHING/**

(That link is filled in once the site is published — see *Publishing* below.)

Send members **that link**, not a file. A link opens the form straight away;
an emailed file makes them download it first.

## What's in here

| File | What it is | Who edits it |
| --- | --- | --- |
| `index.html` | The whole form (works on its own; the PDF engine is built in) | Tech support only |
| `yard-captain-email.txt` | **Just the Yard Captain's email address**, on one line | Committee — see guide below |
| `CHANGE-EMAIL.md` | How to change the Yard Captain's email address | — |
| `MANAGE-ACCESS.md` | Who can edit this, and how to add/remove a person | — |

## The two everyday tasks

- **Change the Yard Captain's email** → see **[CHANGE-EMAIL.md](CHANGE-EMAIL.md)**
- **Add or remove who can edit** → see **[MANAGE-ACCESS.md](MANAGE-ACCESS.md)**

## ⚠️ Never put personal information in here

This repository is **public**. Only the blank form and the address file belong
here. **Do not** upload completed applications, insurance certificates, bank
details, member lists, or any other personal information.

## Publishing (one-time, tech support)

1. The form is served by **GitHub Pages** from this repository.
2. In the repo: **Settings → Pages → Build and deployment → Source: "Deploy from a branch"**, branch **`main`**, folder **`/ (root)`**, then **Save**.
3. After a minute the live URL appears at the top of that Pages settings screen.
   Put that URL into the "live form" line above, and that's the link you give members.
4. **Before sharing it**, set the real Yard Captain address — see
   [CHANGE-EMAIL.md](CHANGE-EMAIL.md).

## How a member uses it

1. Open the link.
2. Read the Terms & Conditions and fill in the form.
3. Click **Download my completed application** — a PDF is saved to their device.
4. Email that PDF to the Yard Captain with their **insurance Certificate of
   Currency** attached (the **Email the Yard Captain** button starts that email
   for them; they just attach the files and send).
