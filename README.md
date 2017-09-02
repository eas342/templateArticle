# Sample LaTeX Template

### Mostly uses the sample from AASTeX 6.1, but with a few improvements:

* Less stuff to delete
* Uses BibTeX
* Automatically links to ADS for the references
* Includes my script for syncing with my master Bib file
* Has `.gitignore` and `.gitattributes` already started

One way to start a project is the following

```bash
git clone https://github.com/eas342/templateArticle.git
mv -i templateArticle newArticle01
cd newArticle01
```

#### New Github Repository
If you want to create a new page on github that tracks with this one, create a new repository on the github site.
Then, type the following commands:

```
git remote set-url origin https://github.com/USERNAME/newArticle01.git
# Then edit the file(s)
git add ms.tex
git push -u origin master
```

#### Remove Github Remote URL
If you are not going to post the repository online on github, you can remove the remote URL:

```
git remote rm origin
```
Now, the changes will be local and not visible on github, nor tracked against this template article.
