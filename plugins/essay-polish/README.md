# essay-polish plugin

Edits an essay and double-checks it. One skill, two connectors.

- Skill `essay-polish`: argument check, blind spots, fact-check, reference verification, originality risk, style edit.
- Connector `quetext` (`https://www.quetext.com/mcp`): plagiarism report and AI detection. Free account works.
- Connector `originality` (`https://mcp.originality.ai/mcp`): AI detection, model 5.0. Needs a paid Originality.ai account.

Both connectors use OAuth. You sign in with your own account. The plugin holds no keys.

## Use
Paste the essay in the chat and write:

> Use essay-polish. Assignment: [question]. Level: [level]. Style: [APA/Harvard/MLA]. Check the argument, find blind spots, fact-check, verify every reference, then double-check the final text with Quetext and Originality.

## Limits
- It does not run Turnitin. Quetext and Originality.ai are other products. Their scores are estimates.
- AI detectors give false positives. A score is a signal to re-read, not a verdict.
- You stay the author. Follow your school's AI-use policy.

## Privacy
The text goes to Quetext and Originality.ai under your account. Read their privacy policies before you scan an unpublished essay.
