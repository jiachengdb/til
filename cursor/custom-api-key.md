Custom API keys only support Chat. Edit/Agent does not support custom API keys.

With custom API keys, you can use your own OpenAI API key, and you can see every chat completion request Cursor sends in your OpenAI logging dashboard.

It makes sense that Edit/Agent doesn't allow this because the secret sauce of Cursor is in the prompt processing -- how it takes the raw context information, such as file content, the message that user can already see, into a set of new prompts and instructs, that will lead the models to find the right solution. This intellectual property, Cursor, certainly wants to protect and hide it.

Windsurf doesn't support custom API key.

The trend is that these close sourced AI editors will move to proprietary prompt processing.

Cline, on the other hand, allows using custom keys, so you can trace every step.

**Follow-ups**

How does Claude Code work? It's closed-sourced. Can you inspect network activities to find out what prompt messages it is sending?