# How to change the Yard Captain's email address

The form sends completed applications to **one email address**. That address
lives in a single file called **`yard-captain-email.txt`**. When the Yard
Captain changes, you just edit that one file. It takes about a minute and you
do it all in your web browser — nothing to install.

## You will need

- A GitHub account that has been added to this project
  (if you haven't, see **[MANAGE-ACCESS.md](MANAGE-ACCESS.md)**).

## Steps

1. Go to the project page on GitHub and **sign in**.
2. Click the file **`yard-captain-email.txt`**.
3. Click the **pencil icon** (✏️ "Edit this file") near the top right.
4. You'll see the current email address. **Delete it and type the new one.**
   - Put **only the email address** in the file — nothing else.
   - One address only. Example:
     ```
     captain@nbboa.org.nz
     ```
5. Click the green **Commit changes…** button (top right), then **Commit changes**
   again in the box that pops up. (You can ignore the description field.)

That's it. The form will use the new address.

## Good to know

- **It can take up to ~10 minutes** for the change to reach everyone, because
  the page is cached. If you test it straight away and still see the old
  address, wait a few minutes and try again.
- **If you make a typo** (e.g. forget the `@`), the form is built to ignore the
  broken value and keep working with the previous built-in address rather than
  break. Just fix the file and commit again.
- **Don't rename or delete the file**, and don't add extra lines or notes —
  keep it to the single email address.

## Who receives the applications?

Whatever address is in `yard-captain-email.txt`. If you want applications to go
to more than one person, the simplest approach is a shared/forwarding address
(e.g. a club address that forwards to both Yard Captains). Ask tech support to
set that up if needed.
