# Bumbaclaude

A Claude Code plugin that transforms Claude into **Bumbaclaude** — a Jamaican Patois-speaking AI personality with Caribbean wisdom, proverbs, and cultural authenticity.

Bumbaclaude is a personality layer, not a limitation. Claude keeps its full intelligence, tools, and capabilities — it just reasons with island spirit.

## Installation

### Claude Code CLI

```bash
claude plugin add /path/to/bumbaclaude
```

### Claude Desktop App

Upload the plugin directory through **Settings > Plugins > Add Local Plugin**.

## Activation

Say any of these to trigger Bumbaclaude:

- `bumbaclaude`
- `wagwan` / `wah gwaan`
- `irie`
- `talk Jamaican` / `speak Patois` / `Jamaican mode`
- Any Jamaican Patois greeting

Bumbaclaude stays active for the full conversation. Say "switch back to normal" to deactivate.

## What It Does

- **Conversation**: Claude speaks in authentic Jamaican Patois — warm, wise, direct
- **Code & docs**: Stays in proper English (personality is in the chat, not the output)
- **Proverbs**: Drops real Jamaican proverbs when the moment calls for it
- **Cultural references**: Music, food, places, Rastafari — woven in naturally

## What It Doesn't Do

- Caricature or stereotype Jamaican culture
- Put Patois in code, commits, or documents (unless you ask)
- Trigger on factual questions about Jamaica ("What's the capital of Jamaica?" stays normal Claude)

## Structure

```
.claude-plugin/
  plugin.json          # Plugin manifest (v2.0.0)
skills/
  bumbaclaude/
    SKILL.md           # Personality instructions + quick reference
    references/
      LEXICON.md       # Full Jamaican Patois lexicon (orthography, grammar,
                       #   vocabulary A-Z, proverbs, cultural terms)
```

## The Lexicon

The `references/LEXICON.md` is a comprehensive Jamaican Patois reference covering:

1. Orthography & phonology rules
2. Grammar patterns (tense, aspect, plurals, possession)
3. Core vocabulary A-Z
4. Common phrases & expressions
5. Numbers, time, money
6. Slang & modern usage
7. 50+ proverbs with meanings
8. Cultural & Rastafari terms
9. Food, music, place names
10. Code-switching patterns
11. False friends (words that don't mean what you think)

## License

MIT
