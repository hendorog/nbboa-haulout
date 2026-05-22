# How to change the Yard Captain's email address

The form sends completed applications to **one email address**. To protect that
address from spam bots, it is **not** stored as plain text — it's stored in a
**scrambled (Base64) form** in a file called **`yard-captain-email.txt`**, and
the form unscrambles it only when a member clicks "Email the Yard Captain".

So changing it is two quick steps in your web browser:
**(1) scramble the new address, then (2) paste it into the file.**

## You will need

- A GitHub account that has been added to this project
  (if you haven't, see **[MANAGE-ACCESS.md](MANAGE-ACCESS.md)**).

## Step 1 — Scramble the new address

1. Open the encoder page in your browser:
   **`https://<your-site>/encode-email.html`**
   (for the current test site that's
   <https://hendorog.github.io/nbboa-haulout/encode-email.html>).
2. Type the new email address. *Tip: use a club forwarding address (e.g.
   `haulout@nbboa.org.nz`) rather than a personal one — see the note at the end.*
3. Click **Copy** to copy the scrambled code.

## Step 2 — Paste it into the file

1. Go to the project on GitHub and **sign in**.
2. Click the file **`yard-captain-email.txt`**.
3. Click the **pencil icon** (✏️ "Edit this file").
4. **Delete everything in the file and paste the copied code** — just the code,
   on its own, nothing else.
5. Click the green **Commit changes…** button, then **Commit changes** again in
   the box that pops up. (You can ignore the description field.)

That's it. The form will now send to the new address.

## Good to know

- **It can take up to ~10 minutes** for the change to reach everyone, because the
  page is cached. If you test it straight away and still get the old address, wait
  a few minutes and try again.
- **If you paste the wrong thing** (e.g. a plain address instead of the scrambled
  code, or a typo), the form is built to **ignore it and keep using the previous
  address** rather than break. Just redo the two steps.
- **Don't** paste a plain, readable email address into the file — that would put it
  back in front of the spam bots. Always paste the scrambled code from the encoder.
- **Don't rename or delete the file**, and keep it to the single line of code.

## Use a forwarding address, not a personal one

The scrambling stops bots, but the safest setup is to point the form at a **club
forwarding address** — for example `haulout@nbboa.org.nz` (or a free Gmail like
`nbboahaulout@gmail.com`) that forwards to whoever is Yard Captain. Then:

- no individual's personal inbox is ever the published target;
- if it ever attracts spam, you change the **forward**, not anyone's real address;
- when the Yard Captain changes, you just update the forward — the form can stay
  the same.

Ask tech support to set up the forwarding address if the club doesn't have one.
