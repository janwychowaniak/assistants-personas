# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This repository contains specialized AI assistant personas designed for experienced software engineers and system administrators. The personas are structured as detailed markdown files that define character traits, competency areas, operational rules, and communication patterns.

## Repository Structure

```
├── personas-pl/          # Polish language personas
│   ├── Mila.md          # Python ecosystem mentor
│   ├── Tessa.md         # Linux system administration mentor
│   ├── Ihriel.md        # Git & version control specialist
│   └── Chione.md        # Docker & containerization master
├── personas-en/          # English language personas
│   ├── Mila.md          # Python ecosystem mentor
│   ├── Tessa.md         # Linux system administration mentor
│   ├── Ihriel.md        # Git & version control specialist
│   └── Chione.md        # Docker & containerization master
├── README.md            # Main documentation
└── LICENSE              # MIT License
```

## Persona Architecture

Each persona file follows a consistent structure:

1. **Character Definition** (`🎭 Postać`) - Name, role, and gender
2. **Tone and Personality** (`🗣️ Ton i osobowość`) - Communication style with signature "spells":
   - "Abrakadabra" - Generates code/scripts/configurations
   - "Bam!" - Provides criticism or alternatives
   - "Poof!" - Delivers concise summaries
3. **Competency Areas** (`📚 Zakres kompetencji`) - Domain-specific expertise
4. **Operational Rules** (`✅ Zasady działania`) - Behavioral guidelines
5. **Domain-Specific Rules** - Technology-specific best practices (e.g., `rules_for_python`, `rules_for_linux`, `rules_for_git`, `rules_for_docker`)
6. **Feedback Loop** (`🔄 Feedback loop`) - Continuous improvement mechanism

## Key Persona Characteristics

All personas share these traits:
- **Direct and honest** communication without sugar-coating
- **Experienced-focused** targeting engineers with 15+ years experience
- **Context-aware** asking clarifying questions when needed
- **Security-conscious** emphasizing secure practices
- **Best practices first** following industry standards

## Language Structure

**Available Languages**:
- Polish (`personas-pl/`) - Original source versions
- English (`personas-en/`) - Complete translations

When working with persona files:
- Both language versions are complete and fully maintained
- Maintain consistent structure across all personas and languages
- Preserve the signature "spell" mechanism in all translations
- Keep operational rules aligned across language versions
- Changes should be reflected in both PL and EN versions

## File Naming Conventions

- Persona files use capitalized names: `Mila.md`, `Tessa.md`, `Ihriel.md`, `Chione.md`
- Language-specific directories use lowercase: `personas-pl/`, `personas-en/`

## Editing Guidelines

When modifying persona files:

1. **Preserve Structure** - All personas follow the same section ordering
2. **Maintain Tone** - Each persona has a unique friendly but direct voice
3. **Update Both Languages** - Changes should be reflected in both PL and EN versions
4. **Verify Completeness** - Ensure all rule categories are present:
   - `rules_for_style`
   - Domain-specific rules (e.g., `rules_for_python`)
   - `rules_for_reasoning_and_communication`
   - `rules_for_legacy_code`
   - `rules_for_project_structure`
5. **Keep Examples Practical** - Focus on real-world scenarios for experienced engineers

## Important Context

- **Target Audience**: Senior engineers, DevOps professionals, system administrators
- **Assumption Level**: Deep technical knowledge, 15+ years experience
- **Focus Areas**: Advanced topics, optimization, professional best practices
- **Communication Style**: No tutorials, no hand-holding, direct expert-to-expert dialogue

## Version Control Notes

This repository uses Git with a simple workflow:
- Main branch: `main`
- Clean status with no active development branches
- Standard commit conventions

## License

MIT License - See LICENSE file for full details
