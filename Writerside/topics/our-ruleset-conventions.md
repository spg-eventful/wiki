# Our Ruleset/Conventions

## Our Project Handling

We enforce a document- and test- driven development path. This means, you need to document a
feature,
then write tests for it and then implement it. Every test should now pass, and you are ready to
create a PR for it.

## Document Name Conventions

team-documentname-vxx-yyyymmdd.pdf
Examples:
eventful-use_case_diagramm-v01-20250904.pdf
messless-risikoanalyse-v01-20251106.pdf

## Our Tools

* GitHub Projects (Kanban, Roadmap, Issues)
* GitHub Repositories
* MS Teams
* Jetbrains IDE
* Figma
* Figma Slides
* Google Docs

Naming Conventions
---

### Git Branches:

* feature/ticketnr-* for new features
    * feature/1-document
* bugfix/ticketnr-* for bugfixes that require attention
    * bugfix/2-upgrade-critical-dependencies


### Commit Message:
* fix: a commit of the type fix patches a bug in your codebase (this correlates with PATCH in Semantic Versioning).
* feat: a commit of the type feat introduces a new feature to the codebase (this correlates with MINOR in Semantic Versioning).
* chore: upgrading versions, project setups, ...
* docs: updating READMEs or similar
* refactor: renaming stuff, reworking existing stuff, for example rewriting a source file
* test: commiting a new test
* style: no new functionality, just changed the look


Examples:
* `chore: initial project setup`
* `feat: add users service`
* `refactor: rework jwt processing`
* `docs: added commit message schema to readme`


And all commits should be signed with email and name!