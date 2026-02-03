c# ThinkMate

A personal knowledge management system in Obsidian for capturing ideas, reading notes, and building interconnected knowledge.

## Purpose

ThinkMate is a digital second brain that leverages Obsidian's capabilities:
- Full-text search across all notes
- Backlinks and graph visualization
- Tags for flexible categorization
- AI assistance for organizing and connecting ideas

## Folder Structure

```
ThinkMate/
├── Fleeting Notes/     # Quick captures, daily thoughts, raw ideas
├── Permanent Notes/    # Refined, atomic notes with clear concepts
├── Sources/            # Notes from books, articles, videos, podcasts
├── Projects/           # Active project-related notes
└── Templates/          # Note templates
```

## Note Conventions

### Fleeting Notes
- Filename: Descriptive title (e.g., `Critical Thinking.md`, `KYC Basics.md`)
- Include frontmatter with `captured:` date and `status: #fleeting`
- Quick, unprocessed thoughts
- Review regularly to extract permanent notes
- Add footer reminder: `*To process: Extract key concepts into permanent notes*`

### Permanent Notes
- Filename: Descriptive title (e.g., `Critical Thinking.md`)
- One idea per note (atomic)
- Written in your own words
- Include links to related notes using `[[Note Title]]`

### Source Notes
- Filename: `Author - Title.md` or `Title (Source).md`
- Include metadata: author, date, source URL/reference
- Capture key ideas and your reactions

## AI Assistant Guidelines

When helping with ThinkMate:

1. **Capture ideas**: Help write fleeting notes from conversations
2. **Refine notes**: Transform fleeting notes into permanent notes
3. **Find connections**: Suggest links between related concepts
4. **Summarize sources**: Help process reading materials into source notes
5. **Query knowledge**: Search and synthesize information across notes
6. **Maintain consistency**: Follow the naming and formatting conventions

## Tags

Use tags for cross-cutting themes:
- `#idea` - Original thoughts
- `#question` - Things to explore
- `#insight` - Key realizations
- `#todo` - Action items to process

## Linking

- Use `[[Note Title]]` for internal links
- Create hub notes for major topics that link to related notes
- Don't be afraid to link liberally - connections are valuable
