# Documentation project instructions

## About this project

- This is the documentation site for **All One Thing Labs** and its projects (primarily **Sunschool**)
- Built on [Mintlify](https://mintlify.com)
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- Run `mint dev` to preview locally
- Run `mint broken-links` to check links

## Terminology

- Use "Sunschool" (capitalized S, one word)
- Use "All One Thing" or "AOT" for the parent organization
- Use "child" or "learner" for the student accounts (prefer "child" in parent-facing content, "learner" in technical content)
- Use "parent" for parent accounts
- Use "lesson" for AI-generated educational content
- Use "quiz" for the question/answer assessment after a lesson

## Style preferences

- Use active voice and second person ("you")
- Keep sentences concise — one idea per sentence
- Use sentence case for headings
- Bold for UI elements: Click **Settings**
- Code formatting for file names, commands, paths, and code references
- Do not include internal deployment details, secrets, or private repo information

## Content boundaries

- Document the **open source** public repo (`allonethingxyz/sunschool`) only
- Do not document internal admin features, deployment secrets, or private repository details
- Do not include API keys, database URLs, or other credentials even as examples
- API docs should use placeholder values that are clearly fake
- Architecture docs should reference source files by path for auditability
