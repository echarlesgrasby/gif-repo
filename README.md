# gif-repo

![Send Mail!](./kenshin_mail.gif)

Repo to house a bunch of old-style GIFs that I want to keep around. These were _all over_ the Internet when I was a kid, and I would like to keep some of them around for nostalgia :smiley:. I might even use some of these in personal projects. 

I only keep these in a root folder, but if I end up saving a bunch I may organize them into legitimate folders (e.g. video_games, anime_manga, history, etc.). I do make it a point to give each one a pragmatic name, as well as log them in the `descriptions.tsv` file (also in the root folder) with a description of what the GIF is.

Most of these will likely be pulled from the following *Internet Archive* project: [GIF Cities](https://gifcities.org/). The name "GIF Cities" comes from the platform "Geocities" (never used it, but it was essentially 90s Tumblr). If you are searching for old GIFs for a project, this is a great resource to check.

## Suggested Conventions

* All GIFs in added to this repo shall bear all lowercase names
* GIF names should only contain underscores for separation (no hyphens or spaces)
* All GIFs should be logged in the `descriptions.tsv` file (1 line per GIF) and contain some sort of decsriptive statement about the GIF
* If GIFs are moved to subfolders, the relative path (from the `descriptions.tsv` file) should be used as the filename
	* e.g. GIF stored in `cats` should be logged in `descriptions.tsv` as: `./cats/tuxedo_cat_runs.gif	Tuxedo cat running through the house`
* Make commits to this repo atomic
	* Add GIFs one at a time so that their history is preserved in the commit tree.
	* Ideally, each commit should contain 2 changes: 1 entry added to `descriptions.tsv` and 1 GIF added to the repo


