# Contributing Guide

Thank you for taking the time to contribute to this project!

If you are not familiar with or do not want to use git, submit a new issue requesting the change. If you are already familiar with git, follow the steps in the section Setup.

## Setup

1. Fork the project locally by clicking the **'Fork'** button at the top of the repository to create a fork of `document-parser-list` to your GitHub account.

2. Clone it on your local machine. In order to do this, make sure you have [Git](https://git-scm.com) installed, then run the following commands:

```bash
# Replace 'YOUR-USERNAME' with your GitHub username
git clone https://github.com/YOUR-USERNAME/document-parser-list.git
cd md-badges
```

2. Create a branch to work on your changes by running these commands:

```bash
# Replace '[NAME]' with the name of your branch
git branch [NAME]
git checkout [NAME]
```

3. You can now start working locally on the project.

4. When you decide you are ready to commit your changes, and want to push them to remote, run:

```bash
git add .
git commit -m "✨ feat: [commit message here]"
git push
```

5. You can now create a [pull request](https://github.com/GiftMungmeeprued/document-parsers-list/pulls) to the repository with your changes.

## Adding Parser

If you would like to add more parser, just edit the table in `README.md`. Please gather the following information:

- Name of the parser (text in the column `Models` )
- Link to homepage (clickable link in the column `Models` ) or link to Github page if not found.
- Link to GitHub repository (clickable badge in the column `Source` ) or add '-' if it's closed source. The clickable badge can be created using the following code. Please make sure to replace `AUTHOR` and `REPO_NAME`.

```
[![GitHub Repo stars](https://img.shields.io/github/stars/AUTHOR/REPO_NAME?style=social)](https://github.com/AUTHOR/REPO_NAME)
```

- Link to Huggingface (clickable badge in the column `Source`) if available.
- The rest of the columns can be left blank if you don't have time for testing.

Then add a row to the tables in `README.md`.

## Testing Parser

1. Download test documents. Please find links below

   - [Table](https://github.com/GiftMungmeeprued/document-parsers-list/blob/main/results/table/table.pdf)
   - [Equation](https://github.com/GiftMungmeeprued/document-parsers-list/blob/main/results/equation/equations.pdf)
   - [Printed handwriting](https://github.com/GiftMungmeeprued/document-parsers-list/blob/main/results/handwriting-printed/handwriting-printed.jpg)
   - [Cursive handwriting](https://github.com/GiftMungmeeprued/document-parsers-list/blob/main/results/handwriting-cursive/handwriting-cursive.png)
   - [Two columns](https://github.com/GiftMungmeeprued/document-parsers-list/blob/main/results/two-column/two_column.pdf)
   - [Multiple columns](https://github.com/GiftMungmeeprued/document-parsers-list/blob/main/results/multi-column/multiple-column.pdf)

2. Parse the test documents to your parser of interest. Save the output as .md or .txt file.
3. Add the output file in the corresponding folder:
   - [Table](https://github.com/GiftMungmeeprued/document-parsers-list/blob/main/results/table)
   - [Equation](https://github.com/GiftMungmeeprued/document-parsers-list/blob/main/results/equation)
   - [Printed handwriting](https://github.com/GiftMungmeeprued/document-parsers-list/blob/main/results/handwriting-printed)
   - [Cursive handwriting](https://github.com/GiftMungmeeprued/document-parsers-list/tree/main/results/handwriting-cursive)
   - [Two columns](https://github.com/GiftMungmeeprued/document-parsers-list/blob/main/results/two-column)
   - [Multiple columns](https://github.com/GiftMungmeeprued/document-parsers-list/blob/main/results/multi-column)
