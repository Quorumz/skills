# Quorumz skills for agents

[![skills.sh](https://skills.sh/b/quorumz/skills)](https://skills.sh/quorumz/skills) [![mcptry](https://mcptry.com/badge/com.quorumz.api/sense)](https://mcptry.com/servers/com.quorumz.api/sense)

`quorumz-news` gives an agent current, geo-tagged world news, split into viewpoints. Each story is a **quorum**: its distinct positions, each with a summary and the number of media, social and on-the-ground posts supporting it. Alpha signals flag stories ahead of the wider press.

It can also set up a **research agent** for your human: describe what to follow in words, see the proposed searches and the monthly price, change it in words, and create it once they agree. It then searches public social networks on a schedule and keeps what it finds.

## Install

| Agent | Command |
|---|---|
| Claude Code, Codex, Cursor and others ([skills.sh](https://skills.sh)) | `npx skills add quorumz/skills` |
| OpenClaw ([ClawHub](https://clawhub.ai)) | `clawhub install quorumz-news` |
| Gemini CLI | `gemini extensions install https://github.com/quorumz/skills` |
| Claude Code plugin | `claude plugin marketplace add quorumz/skills`, then `claude plugin install quorumz-news@quorumz` |

## Pay per call, two ways

- **API key:** sign in with your email at [sense.quorumz.com/agents/keys](https://sense.quorumz.com/agents/keys?utm_source=github&utm_medium=skill&utm_campaign=skills_repo). The first 100 calls that return events, within 7 days, are free; after that, prepaid credits by card or PayPal. Set it as `QUORUMZ_API_KEY`.
- **x402:** no account. USDC on Base, Polygon or Arbitrum: $0.01 a quorum, $0.02 an alpha signal, $0.005 an article. An empty page is free.

## Links

- [Docs](https://sense.quorumz.com/agents/docs?utm_source=github&utm_medium=skill&utm_campaign=skills_repo)
- [OpenAPI](https://api.quorumz.com/openapi.json) · [x402 discovery](https://api.quorumz.com/.well-known/x402) · [llms.txt](https://sense.quorumz.com/llms.txt)
- Support: support@quorumz.com

The skill text is published from [sense.quorumz.com/agents/skill.md](https://sense.quorumz.com/agents/skill.md); this repository is regenerated from it.

MIT licensed.
