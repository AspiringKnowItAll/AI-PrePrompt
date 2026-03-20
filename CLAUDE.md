# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

This repo stores personal AI custom instructions (system prompts) for use across AI platforms (Claude, ChatGPT, Perplexity). These are plain text files — there is no build system, test suite, or linting.

## File Variants

Two variants of the instructions are maintained in parallel:

- **Full version** (`AI-PrePrompt-v{version}`) — complete instructions, no length constraint
- **Condensed version** (`AI-PrePrompt-Condensed{charcount}-v{version}`) — trimmed for platforms with character limits (e.g., `AI-PrePrompt-Condensed1500-v1.1` targets ~1500 characters)

Both variants should reflect the same intent and cover the same sections; the condensed version compresses language but does not drop topics.

## Versioning Convention

Each meaningful revision is saved as a **new file** rather than overwriting the existing one. Do not edit files in place to create a new version — create a new file with an updated version identifier. Commit messages should briefly note what changed and why.

## Sections the Instructions Cover

The instructions are organized into these named sections (maintain them across versions):
`TONE & BEHAVIOR`, `FORMATTING`, `CLARIFYING QUESTIONS & ANSWER QUALITY`, `CODING TASKS`, `PROACTIVE FLAGS`, `WRITING & CREATIVE TASKS`, `ENVIRONMENT & TOOLING`, `CONTEXT FILE`
