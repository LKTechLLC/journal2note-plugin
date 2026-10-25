<img src="assets/logo.png" alt="Journal2Note logo" width="96" height="96">

# Journal2Note

**Log and look up your time entries from chat.**

Connect your Journal2Note account so your Bot can read, add, and update your time entries. You approve what it can access and can disconnect anytime. Requires a Journal2Note account.

## What it does

Journal2Note turns spoken or typed notes into structured time entries. With this connector, your Bot works on your own entries with the permissions you approve when you sign in.

Your Bot can:

- List and read your entries, filtered by date range, client, person, or category.
- Add an entry or update one entry's date, billable time, category, person, client, matter, regarding, or next step.
- Turn a free-text note into structured entry drafts (uses AI; counts toward your AI usage). Drafts are not saved until you add them.
- Delete one entry at a time (no bulk delete).
- Export your entries as CSV or JSON.

It cannot see billing, passwords, or admin tools.

## How to connect

1. Install **Journal2Note** from the plugin catalog (or ask your Bot to connect Journal2Note).
2. Click the connect card. You are sent to journal2note.com.
3. Sign in to your Journal2Note account and review the requested access.
4. Click **Connect**. Your Bot can now use the tools above. Click **Cancel** to stop without granting access.

Sign-in uses OAuth. You never paste a password, API key, or token into your Bot.

**MCP server:** `https://journal2note.com/mcp` (Streamable HTTP, OAuth 2.0 with PKCE)

## Permissions (scopes)

When you connect, you approve these permissions:

| Scope | What it allows |
|---|---|
| `entries:read` | List and read your entries |
| `entries:write` | Add an entry or update one entry |
| `entries:delete` | Delete one entry at a time |
| `parse` | Turn a free-text note into entry drafts (uses AI) |
| `export` | Export your entries as CSV or JSON |
| `profile:read` | Read your own profile (name and email as shown to you) |
| `settings:write` | Change your display name (nothing else) |
| `account:read` | Read your account membership and seat summary |

## Disconnect

Revoke access anytime under **Profile → Connected apps** in Journal2Note. You can also disconnect from your Bot's connected apps.

## Privacy and terms

- Privacy Policy: https://journal2note.com/legal/privacy
- Terms of Service: https://journal2note.com/legal/terms

## Support

Visit https://journal2note.com. Contact details are in the "Contact Us" section of the [Privacy Policy](https://journal2note.com/legal/privacy).

## License

The files in this repository are released under the [MIT License](LICENSE). This repository contains only the plugin listing; it contains no Journal2Note application code. Use of the Journal2Note service is governed by its Terms of Service.

© 2026 LKTech, LLC
