# claude-chat-adhd-assist

An **ADHD accessibility mode for the regular Claude chat** (claude.ai and the Chat tab of the Claude app). While it is on, Claude answers in a shape an ADHD brain can act on: the next action first, short numbered steps, no tangents, a clear next move at the end.

It works on top of any style you pick.

> Using Claude Code? Get the Claude Code version, which also has an on/off switch: **[claude-code-adhd-assist](https://github.com/Nim-C/claude-code-adhd-assist)**

## Install (one file)

1. Download **[adhd-mode-plugin.zip](adhd-mode-plugin.zip)** (open it, then click the download button).
2. In Claude, open **Settings** → **Capabilities** → **Skills**.
3. Click **Upload skill** and choose `adhd-mode-plugin.zip`.

If you do not see Upload skill, turn on **Code execution** on the same screen first.

## Use

| Type | What happens |
| --- | --- |
| `/adhd-on` | Turns it on. Every reply then starts with `🔵 ADHD: ON` |
| `/adhd-off` | Turns it off (`⚪ ADHD: OFF`) |
| `/adhd-mode` | Shows whether it is on, and the options |

- It stays on for the whole chat, through topic changes, until `/adhd-off`.
- In a new chat it starts off.
- The regular chat does not allow custom buttons, so there is no switch here; the `🔵 ADHD: ON` line shows the state instead.

## What is inside

`adhd-mode-plugin.zip` holds the same files you see in this repository: `skills/adhd-mode`, `skills/adhd-on`, `skills/adhd-off`.

## Credits

The ADHD rules come from [ayghri/i-have-adhd](https://github.com/ayghri/i-have-adhd) (MIT License, see `LICENSE.txt`). Not made by Anthropic. It changes how Claude formats replies; it does not diagnose or treat anything.
