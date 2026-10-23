# Broche Ballet

Find Broche classes and programs from your AI chat. Search is free for everyone. Member tools are for Broche members.

Ask for a class, a program, what is free, or a live event. After you sign in, you can also see today's class, your programs, pointe, and your week.

The full guide, including what each request can return, is on [Find your classes from your AI chat](https://brocheballet.com/connect-with-ai).

This plugin connects Cursor and Grok Bot to the Broche server at `https://api.brocheballetonline.com/mcp`. The package is the manifest, that server address, and the logo.

## What you can ask

Free for everyone. No account needed:

- Search ballet classes. Choose programs when you want a multi-week course. You can narrow by category, level, topic, and class length.
- See which classes are free.
- Check upcoming live events.

For Broche members, after you sign in:

- Today's class, your programs, pointe, and your week.
- Your favorites.
- Add or remove a class or program on a day of your week.

Signing in shows your favorites, what you have watched, and what is on your week. Searching classes stays free either way.

## Install

### Cursor

When Broche Ballet is on the marketplace, open Customize, find **Broche Ballet**, and select Install.

To load this repository before it is listed:

1. Copy this repository into `~/.cursor/plugins/local/broche-ballet`. The copy needs `.cursor-plugin/plugin.json`, `mcp.json`, and `assets/logo.png`.
2. Restart Cursor, or run **Developer: Reload Window**.
3. Open Customize and confirm Broche Ballet is there.

Cursor skips a symlink in `~/.cursor/plugins/local` when the target sits outside that folder, so copy the files in. On an Enterprise team, an admin may have local plugin imports turned off.

### Grok Bot

The same plugin is for Grok Bot. Grok Bot uses your Cursor account.

1. Select **Connect apps** in the sidebar. In the Grok Bot mobile app, tap your avatar, then **Connect apps**.
2. Find **Broche Ballet** and add it.
3. When Grok Bot asks you to authorize, finish sign-in in the browser.
4. Confirm Broche Ballet appears under Installed.

If the plugin says it needs auth, open it and choose Authenticate.

## Sign in

Cursor and Grok Bot register themselves with Broche. Sign in with your Broche email and password, then tap Allow.

If the app asks you to sign in again later, that is normal. Sign in the same way. A chat that was already open will not know about Broche yet, so start a new chat and try something like "Find me a turns class."

If the app says you need a membership, you can still search classes for free. Your week, favorites, and pointe are for members.

## Privacy and terms

- [Privacy Policy](https://brocheballetonline.com/privacy-policy)
- [Terms of Service](https://brocheballetonline.com/terms-of-service)

## Support

Email [hello@brocheballet.com](mailto:hello@brocheballet.com).

Broche and the Broche logo are trademarks of Broche Ballet. The MIT license covers this plugin package.
