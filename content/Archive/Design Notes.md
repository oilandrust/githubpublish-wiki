Conversation with ChatGPT
https://chatgpt.com/c/6a37dfa4-d194-83eb-9741-8aed7912eb86

Alternatives:

| Tool                    | Type                          |                                                      |
| ----------------------- | ----------------------------- | ---------------------------------------------------- |
| Obsidian Publish        | Publishing Platform           |                                                      |
| Enveloppe               | Publishing Tool               |                                                      |
| Unmarkdown              | Markdown Converter / Platform |                                                      |
| flowershow              | Publishing Platform           |                                                      |
| Quartz Syncer           | Syncing Tool / Plugin         | https://community.obsidian.md/plugins/quartz-syncer  |
| Verdant                 | Plugin / GitHub hosting       | https://community.obsidian.md/plugins/verdant        |
| Obsidian Digital Garden |                               | https://github.com/oleeskild/obsidian-digital-garden |
| Forestry.md             |                               | https://forestry.md/                                 |
| VaultFolio              |                               | https://github.com/thedozcompany/VaultFolio          |

Your users are:

- Obsidian users
- knowledge workers
- developers
- students

Before writing much code, I would make a landing page that says:

> Publish your Obsidian vault to GitHub Pages in 60 seconds.
> 
> No YAML.  
> No GitHub Actions setup.  
> No static site generator.  
> Own your files.

Then show:

1. Install plugin.
2. Login GitHub.
3. Publish.

If you can get 100–200 email signups from Reddit, the Obsidian forum, and Hacker News, that's a much stronger signal than Enveloppe's download count.

My intuition is that the most valuable thing you already have is not the plugin idea. It's that you already have a React-based site generator working for CatSnake. That means you're much closer to a prototype than most people considering this idea.

What I would actually build:

### Release 0.1

- Publish button
- GitHub authentication
- Repo creation
- GitHub Pages deployment
- One decent-looking theme
- Wikilinks
- Images
- Callouts
- Tags
\
# Initial Ideation Notes
Analyse portfolio psy solution: how to host a static single page on github pages.
Next.js + react + hydration + router → better for analytics
Cheaper solution? nest.js + react
→ make sure I get the idea correctly

Then: Script to build and deploy on github page

Vault/
	.obsidian
	Project/
		.git
		Documentation/
			Readme.md
			FAQ.md
		DevLog/
			2026-10-10.md
		Build/

Questions:
Does it need to be a repository?
Outside of vault build?
2+ Folders? Documentation + DevLog vs 1 root