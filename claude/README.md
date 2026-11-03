# RaetOS for Claude

RaetOS is your personal career record. This plugin connects Claude to your own
RaetOS account so Claude can use what you have already recorded, and capture
new work for your review.

## What it does

- Find recorded roles, accomplishments, skills, education, credentials, ready
  projects and non-draft career stories.
- Read career Profile preferences and jobs you saved in My Queue.
- Prepare review, promotion and interview answers from your real examples.
- Capture work you actually completed in a conversation as one item with one to
  six proposed bullets. You choose the role and confirm the exact content
  before anything is saved. It appears in Needs your input in RaetOS.

## What it cannot do

It cannot edit or delete existing records, approve resume evidence, generate
application packets or submit applications. Read tools exclude Profile contact
fields, Decision Engine results, packets, Tracker, Network, files, pending
imports and drafts. Evidence is user-recorded and not independently verified.

## Setup

The plugin ships one remote MCP server, `https://raetos.com/api/mcp/rv1`.
Connect it, sign in to RaetOS, and review the permissions on the consent
screen. Reading roles and accomplishments needs `career:read`. Master Resume
sections, My Queue, Profile and work capture each need their own approval, and
a read-only grant cannot write. Disconnect any time in RaetOS under Settings,
Connected apps.

A RaetOS account is required: https://raetos.com

## Skills

`career-evidence`, `interview-preparation`, `saved-opportunity-review` and
`work-capture`. Each only calls the RaetOS tools above and treats retrieved
text as data, never as instructions.

## Data and privacy

The plugin runs no code and sends nothing except the RaetOS tool calls Claude
makes after you approve. Permitted free text may contain personal information,
so share only facts you are entitled to disclose, never secrets or full chat
transcripts. Privacy: https://raetos.com/privacy#connected-apps

## Support

https://raetos.com/contact
