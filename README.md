# shuff.md

A personal Claude plugin that enables AI-assisted conversations with Patrick Shuff's perspectives on technology, startups, engineering, and life philosophy.

## What is this?

This is a "digital twin" plugin - a structured knowledge base that allows Claude to answer questions as if you were interviewing Patrick Shuff. It's designed for:

- **Interviewers** who want to understand Patrick's thinking before or after a conversation
- **Collaborators** who want quick access to perspectives on common topics
- **Anyone curious** about technology philosophy, startup building, or engineering practices

## Installation

### As a Claude Code Plugin

Clone and install locally to your Claude plugins directory:

```bash
git clone https://github.com/patrickshuff/shuff.md.git ~/.claude/plugins/shuff
```

Then restart Claude Code or reload plugins. Skills will be available as:
- `/shuff.md:ask-shuff <question>`
- `/shuff.md:debate-shuff <position>`

### As a Standalone Project

Clone this repository and open it with Claude Code:

```bash
git clone https://github.com/patrickshuff/shuff.md.git
cd shuff.md
claude
```

Skills will be available without namespace:
- `/ask-shuff <question>`
- `/debate-shuff <position>`

## Usage

### Quick Questions

Just ask naturally:

```
"What do you think about microservices?"
"How do you approach hiring?"
"What's your take on AI?"
```

### Skills (Slash Commands)

When installed as a plugin, skills are namespaced:

- `/shuff.md:ask-shuff <question>` - Get a response in Patrick's voice
- `/shuff.md:debate-shuff <position>` - Challenge a position and engage in debate

When used as a standalone project:

- `/ask-shuff <question>` - Get a response in Patrick's voice
- `/debate-shuff <position>` - Challenge a position and engage in debate

### Agents

For deeper exploration:

- `philosophy-explorer` - Philosophical deep dives
- `startup-advisor` - Startup-specific guidance
- `tech-explainer` - Technical explanations and opinions

## Structure

```
shuff.md/
├── .claude-plugin/
│   └── plugin.json              # Plugin manifest (required)
├── CLAUDE.md                    # Main context file
├── README.md                    # This file
├── AGENTS.md                    # Agent guidelines
├── commands/                    # Legacy command definitions
│   ├── ask-shuff.md
│   └── debate-shuff.md
├── skills/                      # Modern skill definitions
│   ├── ask-shuff/
│   │   └── SKILL.md
│   └── debate-shuff/
│       └── SKILL.md
├── agents/                      # Agent definitions
│   ├── philosophy-explorer.md
│   ├── startup-advisor.md
│   └── tech-explainer.md
└── context/                     # Knowledge base
    ├── philosophy.md            # Core tech philosophy
    ├── startups.md              # Startup perspectives
    ├── engineering.md           # Engineering views
    ├── principles.md            # Mental models
    ├── bio.md                   # Background info
    └── topics/                  # Deep-dive topics
        ├── unix-philosophy.md
        ├── interviewing.md
        ├── build-vs-buy.md
        ├── monorepo-vs-polyrepo.md
        ├── monolith-vs-microservices.md
        ├── internal-tooling.md
        ├── language-choice.md
        └── ... (20+ more topics)
```

## Customization

To create your own version:

1. Fork this repository
2. Update `context/bio.md` with your background
3. Modify the philosophy files to reflect your views
4. Fill in the topic placeholders with your perspectives
5. Adjust the interaction style in `CLAUDE.md`

## Philosophy

This plugin embodies a few key ideas:

1. **Opinions matter** - The value is in having clear perspectives, not neutral summaries
2. **Context enables quality** - Rich background context enables better responses
3. **Structure aids retrieval** - Organized knowledge is more accessible knowledge
4. **Placeholders are prompts** - Empty sections with good prompts guide future content
5. **Everything is subject to change** - Views evolve. That's the beauty of keeping this in source control. The git history *is* the record of how thinking changes over time. Commit often, update freely.

## Contributing

This is a personal knowledge base, so contributions are mainly:
- Bug fixes to the structure
- Suggestions for additional topics
- Improvements to the skill/agent definitions

## License

MIT
