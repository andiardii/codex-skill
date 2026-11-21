---
name: start
description: Rename the current Codex chat to the title supplied in an explicit $start command.
---

# Rename the current chat

Use `$start Judul Chat` to rename the current Codex chat. The brackets in `$start [Judul Chat]` indicate where to type the title. If the user wraps the entire title in a single pair of square brackets, remove that outer pair and trim surrounding whitespace.

1. Use the text after the skill mention on the same line as the title. Preserve capitalization, punctuation, and internal spacing. If the title is empty, ask the user to supply it.
2. Call the Codex app tool `set_thread_title` with `title` set to the supplied text. Omit `threadId` so the tool targets the current chat. Discover the tool if it is deferred.
3. Confirm the new title after the tool succeeds. If the tool is unavailable or returns an error, report that the chat could not be renamed.
