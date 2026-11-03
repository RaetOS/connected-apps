# RaetOS connected apps

Plugins and setup guides for using [RaetOS](https://raetos.com) with AI
assistants. RaetOS is your personal career record. A connected app can read the
records you allow and capture new work for your review. It cannot edit or delete
existing records, approve resume evidence or submit applications.

You need a RaetOS account and you approve every permission yourself. Disconnect
any time in RaetOS under Settings, Connected apps.

## Claude

Folder: [`claude`](claude). It contains a Claude plugin with four skills and the
RaetOS MCP connection, `https://raetos.com/api/mcp/rv1`.

- Read recorded roles, accomplishments, skills, credentials, ready projects and
  non-draft career stories.
- Read your career Profile preferences and jobs saved in My Queue.
- Capture work you completed in a conversation as one item with proposed bullets.
  You choose the role and confirm the exact content before it is saved. It lands
  in Needs your input, and nothing becomes resume evidence until you approve it
  in RaetOS.

Works in claude.ai on the web, Desktop, mobile and Cowork. Claude Code is not
supported yet.

Status: not yet submitted to Anthropic's directory. This folder is the source
for that submission.

## Other apps

Added here only when each one has been built and reviewed.

## Privacy and terms

- Privacy: https://raetos.com/privacy#connected-apps
- Terms: https://raetos.com/terms
- Support: https://raetos.com/contact

Nothing in this repository contains credentials. Each app's folder describes
exactly what it connects to.
