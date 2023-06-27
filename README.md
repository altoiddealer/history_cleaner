# history_cleaner
Purges message history from each prompt in oobabooga/text-generation-webui.

This was already possible by default using "Chat Prompt Size" setting, but as of oobabooga commit: c52290d that setting has been stripped out.

Truncation setting cannot accurately achieve the same result without inadvertently trimming your character context or message.

Credit to oobabooga for providing this simple code https://www.reddit.com/r/oobaboogazz/comments/14jzi7n/comment/jpo7k24/?utm_source=share&utm_medium=web2x&context=3


Installation:

Install to text-generation-webui/extensions

Load via webui ("Interface Mode" tab) or using CMD flag --extensions history_cleaner
