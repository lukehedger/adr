# Architecture Decision Log

## Overview

An Architecture Decision Log allows us to record the motivation and impact behind certain decisions, throughout the life of a project. It is often crucial to refer to these logs when making new decisions to avoid regressions and repetition of work. Access to such records can also be useful when assessing existing decisions, particularly for those who may be new to the project or have leaky memories.

> We will keep a collection of records for "architecturally significant" decisions: those that affect the structure, non-functional characteristics, dependencies, interfaces, or construction techniques.
>
> [Documenting Architecture Decisions](http://thinkrelevance.com/blog/2011/11/15/documenting-architecture-decisions)

## Architecture Decision Record

The Architecture Decision Log (ADL) is a collection of Architecture Decision Records (ADR). An ADR captures the detail of an architectural decision, as well as the context and consequences of that decision.

Some tips for writing an ADR:

- Each ADR should be a short document formatted per the (template)[doc/architecture/decisions/x_template.md]
- Write each ADR as if it is a conversation with a future developer
- Bullets are acceptable only for visual style, not as an excuse for writing sentence fragments
- ADRs can be created as part of feature pull requests or as a meeting's output. The important thing is decisions are documented accurately and promptly.

### File name convention

We prefer to use a file name convention that has a specific format.

Examples:

- choose_database.md
- format_timestamps.md
- manage_passwords.md
- handle_exceptions.md

Our file name convention:

- The name has a present tense imperative verb phrase. This helps readability and matches our Git commit message format.
- The name uses lowercase and underscores. This balances readability and system usability.
- The file format is Markdown. Markdown's formatting makes files accessible to all project members.

## Additional resources

- [Michael Nygard post](http://thinkrelevance.com/blog/2011/11/15/documenting-architecture-decisions)
- [joelparkerhenderson/architecture_decision_record](https://github.com/joelparkerhenderson/architecture_decision_record)
