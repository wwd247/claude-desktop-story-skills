# Story Skills for Claude Desktop

## Why this fork exists

Story Skills was built for Claude Code. I prefer the instant chat of the Claude Desktop and phone apps, so I restructured the skills so that all 24 can be uploaded to Claude Desktop as a single zip.

## What's in this folder

- `story-skills-ALL-IN-ONE.zip`: all 24 skills in one upload (recommended).
- One zip per skill (for example `chapter-writing.zip`), if you only want some of them.

## What I changed

- Combined all 24 skills into one skill, with an index that tells Claude which skill to use for each request and where to find its files.
- Included the story-checking tool inside the package. If it can't run, Claude does the same checks by reading the files.
- The instructions inside each skill are unchanged.

## How to install

1. Download `story-skills-ALL-IN-ONE.zip`.
2. In Claude Desktop, go to Settings > Capabilities > Skills and upload the zip.
3. Start a chat and ask for help with your story, for example "help me plan a new novel".

## Version

Built from the original project as of 14 November 2026 (commit 33085cc).

## Credit

Adapted from [Story Skills by Dan Dewhurst](https://github.com/danjdewhurst/story-skills), released under the MIT License (see LICENSE in the repository root). All credit for the skills belongs to the original author. This fork is not affiliated with the original project.
