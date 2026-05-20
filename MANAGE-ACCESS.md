# Who can edit this, and how to add or remove a person

This explains how the club keeps control of the form over time, so it survives
people joining and leaving the committee.

## The idea in plain terms

- The form lives in a **GitHub Organization owned by the club** (not in any one
  person's personal account). Think of the Organization as "the club's locker";
  the form is a folder inside it.
- **Each person has their own GitHub login.** Nobody shares a password.
- People are given access to the club's Organization. When someone leaves, you
  remove their access — the form is unaffected because it belongs to the club,
  not to them.

## The roles

- **Owner** — full control. Can change the form, change who has access, and
  manage the Organization. *Keep at least TWO Owners at all times* (e.g. tech
  support **and** a club officer) so the club is never locked out if one person
  is unavailable.
- **Member / Maintainer** — can edit files (like the email address) but not
  change who has access. Good for a committee person who only needs to update
  the Yard Captain's email.

## One-time setup (done once by tech support)

1. Create a **free GitHub Organization** for the club (e.g. `nbboa`), signed up
   under a **club-owned email** (such as a secretary@ or committee@ address) so
   it isn't tied to an individual.
2. Put this project inside that Organization.
3. Add a **second Owner** so there are always two.
4. **Turn on the live site:** Settings → Pages (see the README).

## Add a person

1. Ask the person to create a free account at **github.com** and tell you their
   **username**.
2. An Owner goes to the **Organization → People → Invite member**.
3. Enter their username, choose their role:
   - **Member** for someone who only edits the email address.
   - **Owner** only for trusted long-term admins (keep these few).
4. They accept the email invitation. Done.

## Remove a person (e.g. they leave the committee)

1. An Owner goes to **Organization → People**.
2. Find the person → **Remove from organization**.
3. The form keeps working; they simply lose the ability to edit it.

## Important: two-factor authentication (2FA)

GitHub **requires every account to have 2FA turned on** (a code from a phone app,
or a passkey). This is the fiddliest part for a non-technical person, so:

- Set up 2FA **with** the committee member the first time, using an authenticator
  app (e.g. Google Authenticator / Microsoft Authenticator) or a passkey.
- When GitHub shows the **recovery codes**, save them somewhere safe in the
  **club's permanent records** (not just on one person's phone). These are the
  backup if they lose their phone.

## Keeping control long-term — checklist

- ✅ The Organization is signed up under a **club-owned email**, and the committee
  knows how to access that mailbox.
- ✅ There are **at least two Owners**.
- ✅ **2FA recovery codes** for the club account are stored in club records.
- ✅ When someone leaves, **remove them** from the Organization.
