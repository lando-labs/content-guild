# Content Guild

**A CAMI Agent Collection for Content Creation**

> **Status: Experimental**
> These agents are newly created and minimally tested. They serve as an example of how to build a non-code focused agent guild using CAMI.

## What is This?

This guild demonstrates that CAMI agents aren't just for coding - they can help with any knowledge work. This collection focuses on **content creation**: technical documentation, marketing copy, and everything in between.

## Agents in This Guild

| Agent | Class | Purpose |
|-------|-------|---------|
| **technical-writer** | Technology Implementer | API docs, tutorials, READMEs, architecture docs |
| **blog-writer** | Technology Implementer | Blog posts, thought leadership, announcements |
| **copywriter** | Technology Implementer | Landing pages, product copy, CTAs, headlines |
| **seo-strategist** | Strategic Planner | Keyword research, content optimization, meta tags |
| **social-media** | Technology Implementer | Social posts, threads, engagement content |
| **editor** | Strategic Planner | Review, polish, consistency, style guide enforcement |

## Content Types Covered

**Technical:**
- API references and SDK documentation
- Getting started guides and tutorials
- Architecture and design documents
- Troubleshooting guides
- Release notes and changelogs

**Marketing:**
- Blog posts and articles
- Landing page copy
- Product announcements
- Case studies
- Email newsletters

## How to Use

### With CAMI

```bash
# Add this source
cami source add https://github.com/lando-labs/content-guild.git

# Deploy to your project
cami deploy technical-writer blog-writer editor ~/my-docs-site
```

### Manual

Copy the agent `.md` files you need to your project's `.claude/agents/` directory.

## Why Non-Code Agents?

CAMI agents are specialized Claude Code configurations. While many focus on coding, the same pattern works for any structured task:

- **Writers** follow style guides and tone requirements
- **Editors** apply consistent quality standards
- **Strategists** make decisions based on goals and constraints

If you do knowledge work, you can build agents for it.

## License

MIT - Use freely, improve openly.

---

*Built with [CAMI](https://github.com/lando-labs/cami) - Claude Agent Management Interface*
