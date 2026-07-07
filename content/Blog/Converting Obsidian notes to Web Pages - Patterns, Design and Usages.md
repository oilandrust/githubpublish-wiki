Somehow I’ve become quite interested in publishing technologies for Obsidian. There is something about the ease of editing Markdown, the comfort of having all the files locally, and the ability to easily convert Markdown to HTML that makes that design space appealing to me. Of course, behind that is also the desire to publish one's own thoughts, show our work, and have a dedicated, structured, and good-looking space to do that. It's about showing ourselves and our work.

Yet, most published websites based on Obsidian with tools like Obsidian Publish and static site generators such as Quartz do mostly look like an Obsidian vault, and not like a user-oriented, beautiful website such as a portfolio or a blog.

Though I’ve built a few portfolios ([here](https://oilandrust.github.io/portfolio/), and [here](https://www.olivier-psy.fr/fr/about/)) using Markdown as source, a few vibe-coded scripts, and a few React templates. I even built a [portfolio hosting service](https://lefolio.fr/) based on Markdown, but failed in trying to reproduce the editing ease of Obsidian in an online editor.
![[Screenshot 2026-07-06 at 14.09.12.png|500]]
![[Screenshot 2026-07-06 at 14.09.04.png|500]]


## Publishing Workflow
There are a couple of common solutions for converting notes or vaults into websites. Of course, there is Obsidian Publish, and a few other hosting solutions such as xxxx and xxxx. There is Quartz, which allows you to create a static website from notes, and there are common free hosting solutions, mainly GitHub Pages. There are a few plugins to bridge the gap between notes and the final hosted site. They typically push changes to a git repo and trigger a build that makes the website available to the world.

So the pattern is mostly: push your notes to a server, trigger a build to generate a static site, and you're done.
## Look and Feel of the published sites 
One thing I notice about all those solutions is that the output sites resemble an Obsidian vault or a Wiki: there are folders and notes on the left, links, and even a graph view on the right. While this is cool, I think it's a bit limiting and maybe misses the point. To be honest, I don't think those websites look very good. I don't care about the note connectivity or the graph view. And unless I am looking for information, such as a documentation website, I don't think they are very pleasant to visit. It might be satisfying for the author to have that home feeling of the Obsidian vault, but from a user perspective, this is not so interesting.

## A missing piece?
So I think those solutions are fine for wikis, documentation, and course notes, but lacking for building a portfolio, a project page, or a blog. But it is possible to create beautiful pages from Markdown; we just need a more structured and targeted approach, and a template that fits the use case, like my portfolios, or [this example](https://medium.com/haiiro-io/markdown-driven-portfolio-website-with-nuxt-js-a8d08ffe2712)](https://namika.hmsk.co/) I found on Medium.

What do you think?
What do you use publishing for?
Would you like to build a portfolio, a project page, or a blog, keeping your text on Obsidian but publishing with a beautiful template?
Would you rather vibe code it yourself, or use a tool like WordPress?