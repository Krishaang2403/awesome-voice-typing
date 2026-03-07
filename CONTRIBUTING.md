# Contributing

Thanks for helping grow Awesome Voice Typing.

## Inclusion Criteria

To be listed, a project must meet **all** of the following:

1. **Open source** - Source code is publicly available under a recognized open-source license.
2. **Voice-to-text focused** - The primary purpose is voice typing or dictation (speaking into a microphone to produce text). Transcription libraries, APIs, and speech engines themselves are out of scope.
3. **≥ 50 GitHub stars** - A minimum signal of community interest.
4. **Active** - At least one commit in the last 12 months.

## Adding an Entry

1. Fork the repository and create a branch.
2. Add your entry to `README.md` in **alphabetical order** (case-insensitive) using this format:

   ```
   | [Name](https://github.com/user/repo) | ![](https://img.shields.io/github/stars/user/repo?style=flat-square) | Description | Platforms | Local/Hybrid | Engine | Languages | Notes |
   ```

   **Columns:**

   | Column | Format | Example |
   |--------|--------|---------|
   | Name | Linked project name, title case | `[VoiceInk](https://github.com/Beingpax/VoiceInk)` |
   | Stars | Shields.io badge with `?style=flat-square` | `![](https://img.shields.io/github/stars/user/repo?style=flat-square)` |
   | Description | One sentence, no trailing period | `Native macOS dictation with per-app Power Mode settings` |
   | Platforms | Comma-separated | `Linux, macOS, Windows` |
   | Transcription | `Local` or `Hybrid` | `Local` |
   | Engine | Speech-to-text engine(s) used | `Whisper.cpp, Faster Whisper` |
   | Languages | `Multilingual` if applicable | `Multilingual` |
   | Notes | Brief noteworthy details, if any | `Also available as Chrome extension` |

3. Add the project name to each relevant platform line in the **By Platform** section, in alphabetical order.
4. Place the table entry in **alphabetical order** (case-insensitive).
5. Open a pull request titled **Add [Project Name]**.

## Updating an Entry

If a project's details have changed (new platform support, engine change, etc.), submit a PR with the update. Include a link to the relevant release or commit in your PR description.

## Removing an Entry

If a project no longer meets the criteria (archived, deleted, no commits in 12+ months), open an issue or PR to remove it.

## Style Guide

- **Be concise.** One sentence is ideal. Two if the tool has important caveats.
- **Be objective.** Describe what the tool does, not how good it is.
- **No superlatives.** Avoid "best", "fastest", "most powerful", and similar.
- **Sentence case** for descriptions (capitalize the first word only).
- **End with a period.**
