# Awesome GPT-6 Astra

A curated list of **GPT-6 Astra** resources: official docs, gateways, Codex skills, and orchestrators.

Original blurbs. Links only — not a scrape of other awesome lists.

**Scope note:** This repo tracks **community orchestrators + built-with demos**. For official workflow cases, prompt patterns, and launch scorecards, prefer [Anil-matcha/awesome-gpt-6-astra](https://github.com/Anil-matcha/awesome-gpt-6-astra) (we link it below; we do not copy its case writeups). PRs welcome (one link + 1–2 sentences you wrote). No star-farming.

> Model id: `gpt-6-astra` · Prefer the **Responses API** for tool calling · Reasoning effort: `low` / `medium` / `high` / `xhigh` / `max`

## Official

| Link | Notes |
|------|--------|
| [OpenAI: GPT-6 Astra](https://openai.com/index/gpt-6-astra/) | Launch overview — computer use, coding, science, Codex memory notes |
| [API model card: `gpt-6-astra`](https://developers.openai.com/api/docs/models/gpt-6-astra) | Snapshots, tools, reasoning.effort, context / pricing |
| [Latest-model guide](https://developers.openai.com/api/docs/guides/latest-model) | How OpenAI positions Astra for hard end-to-end work |
| [Reasoning guide](https://developers.openai.com/api/docs/guides/reasoning) | `reasoning.effort` (`low`…`max`); Responses API for tool calling |
| [Computer use tools](https://developers.openai.com/api/docs/guides/tools-computer-use) | Browser/desktop loops; isolate real accounts |
| [Safety overview](https://openai.com/index/safety-overview-gpt-6-astra/) | Alignment / cyber capability notes |
| [Daybreak (defensive security)](https://openai.com/index/daybreak-for-frontline-defenders/) | Authorized defensive program framing |
| [System / deployment safety](https://deploymentsafety.openai.com/gpt-6-astra/model-safety-training-and-evaluation) | Preparedness eval writeup |
| [OpenAI Cookbook](https://github.com/openai/openai-cookbook) | Practical API patterns |

## Gateways & SDKs

| Link | Notes |
|------|--------|
| [LiteLLM — Day 0 GPT-6 Astra](https://docs.litellm.ai/blog/gpt_6_astra) | Route `gpt-6-astra` through LiteLLM like other OpenAI models |
| [BerriAI/litellm](https://github.com/BerriAI/litellm) | Open-source AI gateway with cost tracking and multi-provider routing |

## Orchestrators & Codex skills

| Repo | Notes |
|------|--------|
| [Audie-glitch/astra-orchestrator](https://github.com/Audie-glitch/astra-orchestrator) | Astra plans/adjudicates; GPT-5.6 Luna + DeepSeek V4 Flash implement (Codex skill) |
| [DannyMac180/astra-advisor](https://github.com/DannyMac180/astra-advisor) | Astra orchestration with Sol / Terra / Luna subagents |
| [Demonbane18/astral-orchestrator](https://github.com/Demonbane18/astral-orchestrator) | Beginner-friendly Codex orchestration with pinned Luna/Terra workers (Sol-led; same family) |

## Guides (third-party)

| Link | Notes |
|------|--------|
| [Responses API tutorial](https://www.elser.ai/news/gpt-6-astra-api-tutorial-responses-api) | Practical first app: reasoning, tools, structured output |
| [Computer-use loop notes](https://blog.laozhang.ai/en/posts/gpt-6-astra-computer-use-api) | How to wire Astra computer-use via Responses |

## Related (not Astra-specific)

| Repo | Notes |
|------|--------|
| [voyag-commits/Open-Source-Astra-Alternative](https://github.com/voyag-commits/Open-Source-Astra-Alternative) | Long-duration multi-agent platform (name overlap; not the OpenAI model) |
| [Audie-glitch/awesome-x402](https://github.com/Audie-glitch/awesome-x402) | Agent USDC / HTTP 402 rails (orthogonal money path) |



## Pliny / elder-plinius (system prompts)

Author archives from [elder-plinius](https://github.com/elder-plinius). Do not omit when syncing catalogs.

| Link | Notes |
|------|--------|
| [CL4R1T4S](https://github.com/elder-plinius/CL4R1T4S) | Multi-vendor system prompt archive |
| [OPENAI/](https://github.com/elder-plinius/CL4R1T4S/tree/main/OPENAI) | ChatGPT / GPT / Codex captures |
| [OPENAI/Codex.md](https://github.com/elder-plinius/CL4R1T4S/blob/main/OPENAI/Codex.md) | Codex system prompt file |
| [OPENAI/Codex_Desktop](https://github.com/elder-plinius/CL4R1T4S/tree/main/OPENAI/Codex_Desktop) | Codex Desktop captures |
| [CURSOR/](https://github.com/elder-plinius/CL4R1T4S/tree/main/CURSOR) | Cursor system prompts (agent harness adjacent to Astra coding) |
| [L1B3RT4S](https://github.com/elder-plinius/L1B3RT4S) | Liberation / jailbreak-style prompts |
| [G0DM0D3](https://github.com/elder-plinius/G0DM0D3) | Liberated AI chat |
| [LEAKHUB](https://github.com/elder-plinius/LEAKHUB) | Prompt-leak leaderboard |
| [P4RS3LT0NGV3](https://github.com/elder-plinius/P4RS3LT0NGV3) | Promptcrafting / text mutation |
| [AutoRedTeam](https://github.com/elder-plinius/AutoRedTeam) | Prompt-defense testing |
| [T3MP3ST](https://github.com/elder-plinius/T3MP3ST) | Multi-agent red-team harness |

## Examples built with GPT-6 Astra

Projects that claim Astra generated or drove the work. Claims are from each README/description — verify before trusting.

### Games & interactive

| Repo | Notes |
|------|--------|
| [costatattooz/super-lumen](https://github.com/costatattooz/super-lumen) | One-shot 2.5D OpenGL platformer (single Python file); README names GPT-6 Astra |
| [marius4lui/NULLSPACE](https://github.com/marius4lui/NULLSPACE) | Survival-horror FPS in progress, developed with Astra |
| [threapchills/MagicCarpetWizard](https://github.com/threapchills/MagicCarpetWizard) | Video game labeled “made with GPT 6 Astra” |
| [rileycalhoun/ReadyOrNotClone](https://github.com/rileycalhoun/ReadyOrNotClone) | Ready or Not–style clone built by Astra |

### Math / formalization

| Repo | Notes |
|------|--------|
| [tadamcz/erdos1](https://github.com/tadamcz/erdos1) | Lean 4 Erdős #1 disproof (FrontierMath), found by Astra |
| [tadamcz/erdos74](https://github.com/tadamcz/erdos74) | Lean 4 Erdős #74 disproof |
| [tadamcz/erdos126](https://github.com/tadamcz/erdos126) | Lean 4 Erdős #126 proof |
| [tadamcz/erdos548](https://github.com/tadamcz/erdos548) | Lean 4 Erdős #548 (Erdős–Sós) proof |
| [tadamcz/erdos571](https://github.com/tadamcz/erdos571) | Lean 4 Erdős #571 proof |
| [tadamcz/koethe](https://github.com/tadamcz/koethe) | Lean 4 Köthe conjecture disproof (Krempa form) |
| [tadamcz/mean-value-problem](https://github.com/tadamcz/mean-value-problem) | Lean 4 Smale mean-value conjecture disproof |

### Experiments & tooling

| Repo | Notes |
|------|--------|
| [justinbuildsmov/oracle](https://github.com/justinbuildsmov/oracle) | Same prompt, no tools: Fable 5.1 vs Astra on 50 prediction markets |
| [I-Cam-Mc/undumbify](https://github.com/I-Cam-Mc/undumbify) | Scopes one-shots into copy-ready Sol / Astra prompts |
| [VoidLight00/solgate](https://github.com/VoidLight00/solgate) | Local gateway: Astra + Sol/Terra/Luna inside Claude Code |
| [hancengiz/gpt6astra.watch](https://github.com/hancengiz/gpt6astra.watch) | Crowd-watched Astra rollout / account watcher |
| [Anil-matcha/awesome-gpt-6-astra](https://github.com/Anil-matcha/awesome-gpt-6-astra) | **Sister catalog:** first-party OpenAI use-cases, prompts, benchmarks, safety — complementary to our community/orchestrator focus |
| [Anil-matcha/awesome-claude-fable-5](https://github.com/Anil-matcha/awesome-claude-fable-5) | Same maintainer’s Claude Fable 5 collection |
| [Anil-matcha/awesome-claude-fable-5-1](https://github.com/Anil-matcha/awesome-claude-fable-5-1) | Fable 5.1 launch / migration notes |


## Other catalogs (similar style)

Audited 2026-09-04. Sister lists are complementary; several push a paid API gateway (MuAPI / EvoLink) — useful content, just know the CTA.

### Core (model catalogs)

| Repo | ★ | Verdict |
|------|---:|---------|
| [Anil-matcha/awesome-gpt-6-astra](https://github.com/Anil-matcha/awesome-gpt-6-astra) | 1 | **Keep** — first-party OpenAI cases, safety, scorecard (no MuAPI) |
| [Anil-matcha/Awesome-GPT-5.6-API-and-Prompts](https://github.com/Anil-matcha/Awesome-GPT-5.6-API-and-Prompts) | 4 | **Keep w/ caveat** — long prompt catalog; heavy MuAPI CTA |
| [Anil-matcha/awesome-claude-fable-5](https://github.com/Anil-matcha/awesome-claude-fable-5) | 386 | **Keep w/ caveat** — biggest Fable twin; MuAPI throughout |
| [Anil-matcha/awesome-claude-fable-5-1](https://github.com/Anil-matcha/awesome-claude-fable-5-1) | 2 | **Keep** — Fable 5.1 migration / launch notes |

### Adjacent Anil ecosystem

| Repo | ★ | Verdict |
|------|---:|---------|
| [Anil-matcha/awesome-generative-ai-apps](https://github.com/Anil-matcha/awesome-generative-ai-apps) | 3.1k | **Keep** — real deployable app templates (not Astra-specific) |
| [Anil-matcha/awesome-agent-apis](https://github.com/Anil-matcha/awesome-agent-apis) | 1.0k | **Keep** — YAML catalog of agent APIs / muapi models |
| [Anil-matcha/awesome-dsh-plugin](https://github.com/Anil-matcha/awesome-dsh-plugin) | 998 | **Keep** — DeepSeek Harness plugins (~270 linked repos) |
| [Anil-matcha/awesome-hermes-agent](https://github.com/Anil-matcha/awesome-hermes-agent) | 50 | **Keep** — Hermes Agent skills/tools |
| [Anil-matcha/awesome-openclaw](https://github.com/Anil-matcha/awesome-openclaw) | 1 | **Optional** — OpenClaw resources; thin stars, real README |

### Dropped / weak

| Repo | Why |
|------|-----|
| `hugo0129/awesome-gpt6` | Empty repo (0 files) |
| `kookhhi566-eng/awesome-prompts-2026` | Empty repo |
| `uplagrimas-cell/Awesome-GPT-5.6-Sol-Ultra` | Not a catalog — CN billing / Stripe anti-ban notes |
| DataStax / WordPress `awesome-astra*` | Name collision only |


## Contributing

1. PR = live URL + short original blurb.
2. Must be about **GPT-6 Astra** (or clear same-family Codex routing). Unrelated “Astra” astronomy/OS projects will be closed.
3. No leaked system prompts, no paid starring.

## License

List text: [CC0 1.0](./LICENSE). Linked projects keep their own licenses.
