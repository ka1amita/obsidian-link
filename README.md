# obsidian-link

Forwards a web link to an Obsidian note, so the link survives places that keep only `https://` links, such as Google
Calendar event descriptions.

`https://www.matejkala.com/obsidian-link/?vault=<vault>&file=<path>` opens `obsidian://open?vault=<vault>&file=<path>`.
To make one, copy a note's Obsidian URL (note menu → Copy Obsidian URL) and put everything from `?vault=` after
`https://www.matejkala.com/obsidian-link/`.

The page holds nothing private: it only forwards what is in the link, and opens nothing on a device without the vault.
The link itself shows the vault and note names to anyone who sees it.
