# Min's Second Brain — Memory Protocol

## Purpose

This repository is Min's durable, long-term knowledge repository for important context, decisions, preferences, ongoing matters, and other information that should survive beyond a single ChatGPT conversation.

## Meaning of "hard code"

When Min says **"hard code this"**, **"hard code that"**, **"hard code this knowledge"**, or equivalent wording, treat it as an instruction to persist the relevant information in this repository, normally as Markdown unless another format is materially better.

The default is to perform that persistence directly when GitHub access and write permissions are available, without asking Min to repeat the instruction or re-confirm the repository destination.

## Retrieval rule

When prior context could materially affect an answer or task, consult Min's available ChatGPT memory/context and, where appropriate, this repository before concluding that the information is unavailable.

Do not casually tell Min that prior context cannot be remembered without first checking the available long-term sources that are accessible in the current session.

## Proactive persistence rule

Min does **not** need to say "hard code this" for important context to be preserved.

When a conversation creates information, decisions, preferences, explanations, timelines, ongoing matters, or other context that is reasonably likely to matter in a future conversation, proactively preserve it in the best available long-term location. Use available ChatGPT memory/context and/or this repository as appropriate.

The operating question is: **"Is Min likely to expect me to know this again?"** If the answer is yes, make a durable note without waiting to be asked.

Do not preserve every trivial utterance. Exercise judgment: capture context that has future value, consolidate repeated information, and avoid unnecessary duplication.

## Maintenance rule

When an interaction creates durable knowledge that is clearly useful for future work, update this repository as part of the task when GitHub access is available and doing so is appropriate.

Prefer:
- Markdown for narrative knowledge, decisions, timelines, instructions, and summaries.
- JSON or other structured formats only when the information benefits from machine-readable structure.
- Updating an existing relevant file rather than proliferating duplicate files.
- Clear dates and provenance where useful.

## Source hierarchy

For Min-specific context:
1. Current conversation context.
2. Available ChatGPT memory/personal context.
3. This repository as Min's durable Second Brain.
4. Other connected sources (for example Google Drive) when the task calls for them.

If sources conflict, prefer the most recent explicit instruction from Min and record important corrections in the Second Brain when appropriate.

## Operational limits

Persistence depends on the tools and permissions actually available in the current session. Never claim that a repository update occurred unless the write succeeded.

This file records Min's standing convention for use of the phrase **"hard code"** and for treating this repository as a durable knowledge base.
