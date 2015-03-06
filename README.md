# pandoc-csl

A Pandoc `csl` style based on Zotero's Generic `bibtex.csl` (<www.zotero.org/styles>).
I am currently using this to export citations from my reference manager to markdown documents as inline references as specified in [Rmarkdown](http://rmarkdown.rstudio.com/authoring_bibliographies_and_citations.html)

## Usage
Import this file to your preferred reference manager, export reference as 'Generic pandoc style'
Copy resulting code and paste it in your **references:** YAML header and remove the "\newline"s to make it look like this:

```yaml
---
references:
- title: One-click science marketing
  volume: '11'
  URL: http://dx.doi.org/10.1038/nmat3283
  DOI: 10.1038/nmat3283
  issue: '4'
  container-title: Nature Materials
  publisher: Nature Publishing Group
  author:
  - family: Fenner
    given: Martin
    orcid: 0000-0003-1419-2405
  page: 261-263
  id: fenner2012a
  type: article-journal
  issued:
    year: 2012
    month: 3
---
```

## To Do
- Figure out how to insert newlines
- Individualize authors  
- clean-up