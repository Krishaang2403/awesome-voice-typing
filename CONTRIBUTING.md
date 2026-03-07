# Contributing

Thanks for helping maintain Awesome Voice Typing.

The goal is to keep the list useful for engineers comparing open-source dictation tools quickly.

## What Belongs Here

To be listed, a project should meet all of the following:

1. **Open source** - Source code is publicly available under a recognized open-source license.
2. **Voice typing or dictation focused** - The primary workflow is speaking and getting text into an active app, text field, keyboard, clipboard, or terminal workflow.
3. **Usable as a product** - Apps, keyboards, menu bar tools, and CLI tools belong here. Libraries, APIs, and raw speech engines do not.
4. **Still available** - The repository is public and not deleted, abandoned beyond practical use, or archived without a working path for users.

## What Does Not Belong Here

- Closed-source products
- Speech-to-text APIs, SDKs, model repos, or libraries without a usable dictation workflow
- Meeting bots, note takers, or general transcription tools that do not support voice typing
- Repositories that are only marketing pages, link farms, or download stubs without source code

## Adding an Entry

1. Fork the repository and create a branch.
2. Add the project to the `Directory` table in `README.md` in **alphabetical order** (case-insensitive) using this format:

   ```
   | [Name](https://github.com/user/repo) | Platforms | Mode | Engine | Summary |
   ```

3. Use these column rules:

   | Column | Format | Example |
   | --- | --- | --- |
   | Name | Linked project name, title case | `[VoiceInk](https://github.com/Beingpax/VoiceInk)` |
   | Platforms | Comma-separated | `Linux, macOS, Windows` |
   | Mode | `Local` or `Hybrid` | `Local` |
   | Engine | Speech-to-text engine(s) used | `Whisper.cpp, Faster Whisper` |
   | Summary | One concise sentence ending with a period | `Native macOS dictation with per-app tuning and custom dictionary support.` |

4. Add the project name to each relevant platform line in the `Browse by platform` block, also in alphabetical order.
5. Update the `Platform Snapshot` counts if the change affects Linux, macOS, Windows, Android, or iOS totals.
6. Open a pull request titled `Add [Project Name]`.

## Updating an Entry

If a project's details have changed, update the relevant row in the directory and any affected platform lists or counts. Include a link to the relevant release, commit, or documentation change in your PR description when possible.

## Removing an Entry

If a project no longer fits the scope, is no longer open source, has been archived beyond practical use, or the repository has disappeared, open an issue or PR to remove it.

## Writing Style

- **Be concise.** One sentence is ideal. Use a second clause only when a caveat matters for selection.
- **Be objective.** Describe what the tool does and where it fits.
- **No hype.** Avoid words like "best", "ultimate", "revolutionary", or similar marketing language.
- **Sentence case.** Use normal sentence casing for summaries.
- **End with a period.**
- **Link to the source repository.** Prefer the main repo over landing pages, app stores, or product sites.

## Notes

- Open-source repositories that also sell paid binaries or hosted features can still be listed.
- If a project supports `Web` in addition to desktop or mobile platforms, include `Web` in the directory row. The top-level snapshot currently tracks only Linux, macOS, Windows, Android, and iOS.
