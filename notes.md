# Notes
This page will contain notes about the actual procedures for maintaining this web page.

## GitHub Pages Help
GitHub Pages works like a regulare repository. I can access it via my GitHub account; the actual page is browseable via this link [https://artanisx.github.io/](https://artanisx.github.io/). Using this link it'll open the index.md page. A user can access directly sub pages skipping index.md if he or she knows the url (i.e. [https://artanisx.github.io/AHLDocs](https://artanisx.github.io/AHLDocs)).

In order to operate on the website I have created a separate Branch called Dev. I'll put my commits there and merge the branch on Master (so "live") only when absolutely sure it works well. I'm using Git Desktop to handle commits in local, pushing the commits on GitHub and the actual merge procedure.

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/Artanisx/artanisx.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

## Github Desktop
This software, differs from SourceTree a lot. It is meant only to handle commits, push and pull from a repository and do simple merges. Using this I can't, for instance, revert to a previous commit so I must be careful or I need to revert (pardon the pun) to Git commands.

Use:
1. Edit a file locally
2. Open Git Hub Desktop and let it realize there are changes.
3. Commit those changes (**after local testing**) on the Dev branch
4. When I am satisfied there are no problems with a commit, Push the commit on GitHub (Dev branch).
5. If everything is really coming along nicely and I have no severe bugs, I can Merge the Dev branch on Master, thus publishing the changes online

I can forego using Github Desktop if I have to only edit .md file. In this case I can use GitHub web editor directly, but If I decide to commit on Dev (a good idea) only with GitHub Desktop I can do the merge on the Master branch to actually publish the changes. The good news is: i can preview the md changes online (not possible locally).

## Git 
Should I mess up, I need to use the GIT commands. I have installed Git already. I can invoke Git from GitHub Desktop with Repository > Open Command Prompt option. After that, Google is my friend!

## Markdown Help
```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).


# Back to [Index](https://artanisx.github.io/)
