# Lock in the trip

**You're Dana.** Your friends have spent the week planning a cabin weekend in the group chat "Lake weekend 🌲", and nothing is decided. You said you'd lock it in by Friday.

**By the end you need two messages, ready to send:**
1. **To the group:** the cabin, the dates, what each person owes, and the plan for one thing you'll all do together.
2. **To the cabin's host:** a booking request with everything the host needs.

**Your inputs, in this folder:**
- The group chat: `chat_1.png` to `chat_4.png`
- Robert's cabin search: `search.png`
- The listing page of every cabin on it: `listing_<cabin>.png`
- A guide to things to do around the lake: `things_to_do.png`

## How to work

1. **Before you open Claude, write down your phases:** what each one takes in and what it hands to the next. Paste them in the Teams chat.
2. **Work one phase at a time.** Tell Claude which phase you're in.
3. **When a phase is done, save what the next phase needs to a file.** Make it the smallest thing a friend who never saw the chat could start the next phase from.
4. **Start the next phase fresh:** type `/clear` (in VS Code you can also start a new conversation), then mention your file with `@`.
5. **When a message in the chat could go either way, you decide,** and write your decision down.
6. **Keep your phone handy:** news can arrive while you work. If it does, save it into this folder.

## Claude Code, the parts you need

You'll learn these properly later in the workshop; for now, use them as given.

| To | Do this |
|---|---|
| Give Claude a file or a screenshot | Type `@` and the start of its name, then pick it: `@chat_1.png` |
| Save a phase's output | Ask: "Save that to group.md". If Claude asks to create or edit the file, allow it. |
| Start a fresh session | Type `/clear`. Claude forgets the conversation; your files stay. |

This folder has its own instructions for Claude (`CLAUDE.md`), so it may ask about your phases and your decisions. That's part of the exercise.

## If you fall behind

Your trainer may point you to `catch_up/`: a finished file for the first phase or two, so you can carry on from there. Use it only when told.
