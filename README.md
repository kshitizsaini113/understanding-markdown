# Markdown (for documentation)

```
GitHub Readme used for documentation also used .md (markdown) files for documentation.
Note, for all webpages containing any number of md files, GitHub only renders the README.md file on current page if present.
```
**Note**   
```
Markdown files can include <html> language code as both are compatible.
```

## Table of Contents:

[1. Heading](https://github.com/kshitizsaini113/understanding-markdown/blob/master/Heading)

[2. Paragraph](https://github.com/kshitizsaini113/understanding-markdown/tree/master/Paragraph)

[3. Codeblocks](https://github.com/kshitizsaini113/understanding-markdown/tree/master/Codeblocks)

[4. Emphasis](https://github.com/kshitizsaini113/understanding-markdown/tree/master/Emphasis)

[5. Blockquote](https://github.com/kshitizsaini113/understanding-markdown/tree/master/Blockquote)

[6. Lists](https://github.com/kshitizsaini113/understanding-markdown/tree/master/Lists)

[7. Code](https://github.com/kshitizsaini113/understanding-markdown/tree/master/Code)

[8. Horizontal rules](https://github.com/kshitizsaini113/understanding-markdown/tree/master/Horizontal%20Rule)

[9. Links](https://github.com/kshitizsaini113/understanding-markdown/tree/master/Links)

[10. Images](https://github.com/kshitizsaini113/understanding-markdown/tree/master/Images)

[11. Tables](https://github.com/kshitizsaini113/understanding-markdown/tree/master/Tables)

[12. Emojis](https://github.com/kshitizsaini113/understanding-markdown/tree/master/Emojis)


## Open for Contribution

1. Fork the repository and then clone it. For cloning command is:
```
$ git clone "https://github.com/<username>/understanding-markdown"
```

3. Do changes and stage them.
```
$ git add <filename>
```

4. Commit you changes with a commit message.
```
$ git commit -m "<message>"
```

5. Push changes to your forked repository
```
$ git push -u origin branchname
```
6. Create a pull request to the upstream repository.

## Synchronize forked repository with Main repository (Needed if creating a branch)

1. Create upstream as our repository
```
$ git remote add main "https://github.com/kshitizsaini113/understanding-markdown"
```

2. Fetch changes from main repository
```
$ git fetch main
```

3. Merge changes after being fetched
```
$ git merge main/master
```

5. Push changes to your forked repository
```
$ git push -f origin master
```
