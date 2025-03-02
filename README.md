# This is a class note to demonstrate directory structure, file trees, linking dois, and editing a README.md file

This is my first time editing a readme. 
It demonstrates structures, file trees, linking and editing a README.md file

## 1. links to analysis

These are the links to the analysis file  on Github (.md). The .Rmd files and .html rendered files also available

- [Analysis 1](Nneka_Iduu_RMarkdown_Note.md)

You can preview on save or push to github to view

## 2. file Tree
To start, install fs package
Run fs::dir_tree() in your console to get your tree directory then copy to your README.md
You can alsio add descriptions to help viewers understand
```r
fs::dir_tree()
```

```bash
├── BacterialAlpha.csv            # Raw data for Analysis
├── ClassExample.Rproj            # Top level working directory
├── Coding Challenge 3.R
├── DataVisualizationNote.R
├── DataVisualizationNote2.R
├── Home_Practice_intro.R
├── MycotoxinData.csv
├── NnekaIduuRMarkdown.Rmd
├── NnekaIduuRMarkdown.docx
├── NnekaIduuRMarkdown.html
├── NnekaIduuRMarkdown.md
├── NnekaIduuRMarkdown_files
│   └── figure-gfm
│       ├── pressure-1.png
│       └── unnamed-chunk-2-1.png
├── Nneka_Iduu_RMarkdown_Note.Rmd
├── Nneka_Iduu_RMarkdown_Note.html
├── Nneka_Iduu_RMarkdown_Note.md
├── Nneka_Iduu_RMarkdown_Note_files
│   └── figure-gfm
│       ├── pressure-1.png
│       └── unnamed-chunk-2-1.png
├── README.html
├── README.md                       # Top level directory README
├── RMarkdownNote.R                 # Top level directory RMarkdown Note
├── diff_abund.csv
└── zam5103.pdf
```

## 3. Zenodo

- First you have create an account or sign in to zenodo using your github account then confirm access via email
- Next go to your settings and click on github to connect
- Flip the switch of your repository of interest, by scrolling down and turning on
- Then reload page
- Go to github, to the repository and click release
- You can also click on tag and a description
- Go back to zenodo and refresh to get badge
- When you click on the badge, you will see a zenodo markdown doi that you can include in your repository
