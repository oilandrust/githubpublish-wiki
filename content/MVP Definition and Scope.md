# Pitch
Publish your vault for free in 60s

# Template
The output should look like Obsidian or Obsidian publish
On the left a browser with folders and notes, and other files like images that can be viewed in the main document view, skip the right panel, skip search for now
![[Screenshot 2026-06-30 at 15.59.53.png]]
# Tech
Pluggin allow to publish changes: commits to main via GitHub API (see [Publish Architecture.md](2%20-%20Git%20Publishing%20Architecture.md)), triggers GitHub Actions
Repository contains copy of the published notes + scripts + web template
Script on push/merge: Notes X Template -> build static website, github actions make visible
Static website/template: React based, maybe using next.js, can start as a single page with embeded json to populate

Next.js + react + hydration + router → better for analytics
Cheaper solution? nest.js + react
→ make sure I get the idea correctly

Example of portfolio project hosted on github to inspire from:
portfolio/
portfolio-psy/
# Onboarding in the pluggin
1. Choose folder you want to publish
2. Choose a name for your website
3. authenticate in github, give autorisations
4. Create or choose repository
5. App automatically creates PR, merges, clones template, build website, install github actions, sets the repository as Github Page, publish
6. Site is live
# Validation
✅ The plugin pushes creates allows to login to github, asks for authorisations
✅ Creates repository, update permissions
✅ Push Notes and triggers build and publish, monitor progress
# Analytics
- Unique users
- Publish actions
- Live / Active sites
# Steps:
- [x] Build a simple template and build script, test it on catsnake-web 
- [x] Publish it on github IO, gather data
- [x] Define / Refine push / branch / update process → [Publish Architecture.md](2%20-%20Git%20Publishing%20Architecture.md)
- [x] Build the pluggin prototype and test the whole pipeline
	- [x] Implement Notes update, page status tracking
- [ ] ~~Implement Analytics~~
- [ ] Polish
	- [x] Use Quartz template instead of homemade
	- [ ] Status UI
	- [x] Don't allow to resent publish changes if update is pending
	- [x] Content is push, site is building
	- [ ] Chose files to exclude?
- [ ] Marketing Strategy
- [ ] Ship

# Polish List

**Include link to github action page in the status and upload wizard**

**Wizard**
Start by selecting folder
Suggest Site name based on selected folder
Suggest repository name based on site name
Enter to continue

Indication about publish time
link to github actions

**Fix warnings**

**Not Desktop Only**

Out of Scope:
**Trim Quartz pluggins**
# Premium
Choose from a few built-in templates
Custom CSS
Page customization by coding agent
Login from portfolio page, automatic via github login, only for the user
Subscription on my website
Set site icon






