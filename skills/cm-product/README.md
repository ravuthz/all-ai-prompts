# CM Product — AI Commercial Production Skill

A reusable ChatGPT skill for a strict staged commercial-production workflow:

Character → Product → Location → 10 Concepts → Selection → Duration → Script → Storyboard Plan → Storyboard Image → Consistency Check → Final Flow AI Agent Prompt.

## Install

Upload `cm-product-skill.zip` to a ChatGPT environment that supports personal/custom Skills, or unpack the folder wherever your Skills runtime expects skill directories.

The entry point is `SKILL.md`.

## Quick command

- Preferred short identifier: `cm-product`
- On ChatGPT surfaces that list enabled skills in the slash-command picker: `/cm-product`
- Explicit skill selection on ChatGPT surfaces that use skill mentions: `@cm-product`

## Typical usage

- “Create a 60-second commercial for this product.”
- “Start a new commercial workflow.”
- “Continue my commercial project.”
- “Build a storyboard from these locked references.”
- “Create the final Flow AI Agent prompt.”

## Important behavior

The skill intentionally pauses at user-decision stages instead of generating the entire project at once.

Visual assets remain separate throughout production.

## Source note

This skill is a transformed, modular implementation inspired by the workflow described in:
https://github.com/ravuthz/all-ai-prompts/blob/master/commercial/MASTER.md

The repository prompt itself is not bundled verbatim; this package reorganizes the workflow into an installable skill controller with modular reference rules and templates.
