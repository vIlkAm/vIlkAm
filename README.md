# Tyler Andrew Natorca

Co-founder and technical lead at [Clipping Cartel](https://clippingcartel.com), based in Vienna. I build the systems behind creator onboarding, video tracking, campaign reporting, Discord operations and payout accounting.

**Python · TypeScript · React · PostgreSQL · self-hosted infrastructure · local AI**

## What I build and operate

| System | The work behind it |
|---|---|
| **CAAR video tracking** | Multi-platform discovery and polling, shared provider rate limits, upload-date checks and evidence for payout eligibility. The platform tracks 27,000+ videos. |
| **Payout accounting** | Integer-cent calculations, reproducible snapshots and database guards that lock closed periods. |
| **Fred / Discord operations** | Local AI ticket triage, approved-policy answer gates, manager review and evaluation against labelled examples. |
| **Clip originality review** | Perceptual hashes, frame embeddings and audio evidence, with a human making the final decision. |
| **Infrastructure and reporting** | Self-hosted Supabase/PostgreSQL, tested recovery, least-privilege monitoring and reconstructed view timelines. |

I use AI-assisted development and own architecture, evaluation and production operation.

## Engineering notes

Read the [creator infrastructure showcase](https://github.com/vIlkAm/creator-infrastructure): architecture diagrams and technical decisions from the systems above.

- How tracked views become evidence for a payout calculation.
- The conditions before a local AI can answer a support ticket.
- Why repeated prompts made a performance benchmark misleading.
- How clip similarity becomes a review task, with humans deciding.

## Research and tools

- **TRIBE video engagement research:** a pre-registered study on 1,486 clips. The primary improvement was +0.009 Spearman against a +0.020 threshold: a no-go result.
- **clip-moments:** transcript-based matching of short clips to long-form source timestamps. An internal experiment matched 89% of clips with speech in one creator's catalogue, with broad caption coverage.
- **[coding-memory](https://github.com/vIlkAm/coding-memory):** an open-source (MIT) episodic memory CLI for coding agents. It captures session debriefs and corrections, and offers scored keyword search and pattern consolidation over plain markdown files. [v0.1.0](https://github.com/vIlkAm/coding-memory/releases/tag/v0.1.0), 194 tests in CI.
- **agent-voice-bridge:** a local bridge for returning spoken decisions to coding agents. Release preparation is in progress.

I'm interested in creator tools, applied AI and founders who build and operate their own systems.

[LinkedIn](https://www.linkedin.com/in/tyler-andrew-natorca/) · [Clipping Cartel](https://clippingcartel.com)
