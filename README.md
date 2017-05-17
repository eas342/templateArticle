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
git remote set-url origin https://github.com/USERNAME/newArticle01.git
# Then edit the file(s)
git add ms.tex
git push -u origin master
```
