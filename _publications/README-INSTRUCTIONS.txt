Publication files generated from publication_list(20261103-203546).tex (15 entries).

Copy the 15 .md files to your repository _publications/ directory.

In _config.yml update the publication_category section to:

publication_category:
  manuscripts:
    title: 'Peer-Reviewed Publications'
  preprints:
    title: 'Preprints'

The filename numeric prefixes are ordering keys only, not publication dates.
No `date:` field is included because exact publication dates are not specified in the source.
No actual PDF downloads or BibTeX files have been invented.
For the accepted chapter, the citation explicitly says Accepted in.
The DOI/arXiv links are transcribed from the user's LaTeX file, not independently externally verified.

After copying: git add _publications _config.yml && git commit -m "Add publications" && git push origin master
