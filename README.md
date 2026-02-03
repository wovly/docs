# Wovly Documentation

Documentation for Wovly - your autonomous communication agent.

## Structure

```
docs/
├── docs.json              # Mintlify configuration
├── index.mdx              # Home page
├── quickstart.mdx         # Getting started
├── installation.mdx       # Installation guide
│
├── features/              # Feature documentation
│   ├── chat.mdx
│   ├── tasks.mdx
│   ├── skills.mdx
│   ├── memory.mdx
│   ├── voice-mimic.mdx
│   ├── llm-providers.mdx
│   └── settings.mdx
│
├── integrations/          # Integration guides
│   ├── overview.mdx
│   ├── google-workspace.mdx
│   ├── slack.mdx
│   ├── imessage.mdx
│   ├── whatsapp.mdx
│   ├── telegram.mdx
│   ├── discord.mdx
│   ├── x-twitter.mdx
│   ├── notion.mdx
│   ├── github.mdx
│   ├── asana.mdx
│   ├── reddit.mdx
│   ├── spotify.mdx
│   ├── browser-automation.mdx
│   └── credentials.mdx
│
└── reference/             # Technical reference
    ├── architecture.mdx
    ├── tools.mdx
    ├── security.mdx
    ├── faq.mdx
    └── troubleshooting.mdx
```

## Development

### Prerequisites

Install the [Mintlify CLI](https://www.npmjs.com/package/mintlify):

```bash
npm i -g mintlify
```

### Running locally

```bash
cd docs
mintlify dev
```

Open http://localhost:3000 to preview.

### Deployment

Docs are automatically deployed to Mintlify when pushed to the main branch.

## Adding Documentation

1. Create a new `.mdx` file in the appropriate folder
2. Add frontmatter with `title` and `description`
3. Add the page path to `docs.json` navigation
4. Preview locally with `mintlify dev`

## MDX Components

Mintlify supports various components:

- `<Card>` / `<CardGroup>` - Feature cards
- `<Accordion>` / `<AccordionGroup>` - Collapsible content
- `<Note>` / `<Tip>` / `<Warning>` - Callouts
- `<Tabs>` / `<Tab>` - Tabbed content
- Code blocks with syntax highlighting

See [Mintlify docs](https://mintlify.com/docs) for full component reference.
