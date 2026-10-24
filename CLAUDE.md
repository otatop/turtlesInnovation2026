# Project instructions

## Prompt log

Every prompt the user gives is recorded in `prompts.txt` in this directory.

For each new message from the user, **before doing any other work**:

1. Append one line to the end of `prompts.txt` in this format:

   `[N] YYYY-MM-DD  <the user's message>`

   - `N` is the next number after the last entry in the file.
   - `YYYY-MM-DD` is today's date, taken from the current date in the session context.
   - Copy the message word for word, including typos, capitalisation and punctuation. Do not fix, shorten or summarise it.
   - If the message is long or has several lines, keep it on one entry and put each extra line directly under it, indented by two spaces.
2. Add only to the end of the file. Never reorder, edit or delete earlier entries.
3. Log everything the user types, whether it is a command, a request or a question. Do not log tool results, system reminders, or messages the user pastes in as reference material, unless the user is asking you to act on them.
4. If the user sends a message while you are mid-task, log it too, in the order it arrived.
5. Do not mention the logging in your reply unless something goes wrong with it.
