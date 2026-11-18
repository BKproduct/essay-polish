# essay-polish

A Claude Code plugin for students. It edits an essay and double-checks it.

- Argument check and blind spots
- Fact-check of every claim
- Verification of every reference (finds fake sources)
- Originality risk and style edit
- Double check of the final text with the Quetext and Originality.ai connectors

It does **not** run Turnitin. Quetext and Originality.ai are other products, and their scores are estimates. AI detectors give false positives. The student stays the author and follows the school's AI-use policy.

## Install (Claude Code)

```bash
claude plugin marketplace add BKproduct/essay-polish
claude plugin install essay-polish@essay-polish-marketplace
```

Restart Claude Code, run `/mcp`, and sign in to `quetext` (free account) and `originality` (paid account, optional). The plugin holds no keys. Both connectors use OAuth with your own account.

## Use

> Use essay-polish. Assignment: [question]. Level: [level]. Style: [APA/Harvard/MLA]. Check the argument, find blind spots, fact-check, verify every reference, improve the text, then double-check it with Quetext and Originality.

## Connectors

| Service | URL | Account |
|---|---|---|
| Quetext | `https://www.quetext.com/mcp` | Free tier works |
| Originality.ai | `https://mcp.originality.ai/mcp` | Paid, AI detection only |

## Privacy

The text goes to Quetext and Originality.ai under your account. Read their privacy policies before you scan an unpublished essay.
