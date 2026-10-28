# Public journal website

Static files only; no local database, agent configuration, credentials or private logs.

Deploy the contents of this directory to the root of a separate GitHub repository and connect it to Cloudflare Pages with no build command and output directory `.`. For GitHub publishing, use a fine-grained token restricted to that repository with Contents read/write only. The local agent publisher is restricted to the `posts.json` file. Keep auto-publishing disabled until you have reviewed drafts.
