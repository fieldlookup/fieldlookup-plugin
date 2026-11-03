# fieldlookup plugin

[fieldlookup](https://fieldlookup.com) brings Reddit research into Grok Bot and Cursor. Ask a question, get posts and comments with dates and links, in a short brief. The same connection also finds local businesses, Shopify stores and suppliers.

## What is included

| Capability | Skill | Tools |
| --- | --- | --- |
| Reddit research brief | `fieldlookup-reddit-research` | `search_reddit`, `get_result` |
| Account status and credit | guided by the skill | `account_status`, `start_topup`, `checkout_status` |

The skill turns a question into a bounded research plan, keeps the number of searches small, checks your allowance first, and writes a brief that uses only returned links and dates.

## Install

**Grok Bot:** open Connect apps, search for fieldlookup and choose Connect. A Bot can also add the server by URL:

```
https://fieldlookup.com/mcp
```

**Cursor:** install from the Cursor Marketplace, or add only the tools to `.cursor/mcp.json`:

```json
{
  "mcpServers": {
    "fieldlookup": {
      "url": "https://fieldlookup.com/mcp"
    }
  }
}
```

No key to copy. The first search opens a sign-in page; choose Connect free and your account is ready with 50 free searches each month. Details and credit options: [fieldlookup.com/grok/reddit](https://fieldlookup.com/grok/reddit).

## Quick start

```
Find up to five recent Reddit posts about pricing in r/shopify. Include titles, dates and links.
```

```
Search r/saas for comments about onboarding. Give me a short brief with dates and links.
```

```
Show my remaining fieldlookup searches and credit.
```

## Good to know

- Results are a bounded sample, not complete coverage of a topic.
- One delivered search counts as one search, including an empty result. Collecting a running job is free.
- Comment search finds comments by keyword. It does not fetch the replies of one thread.
- Date filtering and scheduled routines are not part of this version.

## Links

- Setup page: https://fieldlookup.com/grok/reddit
- Account and recovery: https://fieldlookup.com/account
- Documentation: https://fieldlookup.com/docs
- Terms: https://fieldlookup.com/terms, Privacy: https://fieldlookup.com/privacy
- Support: support@fieldlookup.com

## License

MIT. The skill and manifests in this repository are open; the hosted service has its own terms.
