# Create pdf from latex

#pre-publication #latex-and-pdf

- [ ] export the latex on PubPub
- [ ] replace the values in the lines below or, better yet, run the [HMS latex to pdf](shortcuts://run-shortcut?name=HMS%20latex%20to%20pdf) Shortcut and choose **Pull info from Airtable**
- [ ] Copy the values, and run the [Shortcut](shortcuts://run-shortcut?name=HMS%20latex%20to%20pdf) again, choosing **Extract the download**--selecting the exported latex file
- [ ] Paste the latex from Drafts into Overleaf
- [ ] Check for first page length, and add the \noindent
- [ ] Check links, including DOI
- [ ] Check for any overlong footnotes (fix with \marginnote{\textsuperscript{16}\setcounter{footnote}{16})
- [ ] if there's a figure, download from PubPub, upload to Overleaf, rename 'figureone.extension' and paste into \usegraphics. remove the \caption{}
- [ ] Check for long links in the bibliography
- [ ] add any orcid ids, with substitution the numbers for each (and adding after author name): \href{https://orcid.org/xxxx-xxxx-xxxx-xxxx}{\includegraphics[height=0.5cm]{orcid.png}}, before \par}
- [ ] download PDF, look over one more time
- [ ] rename with doi (replacing slash with dash).pdf and commit to /volume-one-2021
- [ ] paste the latex from overleaf into a new .tex file with the same name
- [ ] navigate to article's Pub Settings and upload pdf
- [ ] move the Pub to published in the [Kanban](x-icabmobile://x-callback-url/open?url=https://airtable.com/appXhmKzo4WMgQJnn/tblkbjPK1lfVmbzhY/viwXhseji8rljOBvU?blocks=hide)
- [ ] email reply to author

## Replace these values

shortitle % in latex, for the running header; defaults to full title; **make adjustment to Latex quotation marks and italics**``quotation''
article type % like "Launch essay" or "Article"
article title % full title; **make adjustment to Latex quotation marks and italics**
author 1 name;email address;affiliation
author 2 name;email address;affiliation % if none, replace with 'none'
author 3 name;email address;affiliation % if none, replace with 'none'
doi % just the doi, no https://doi.org/
