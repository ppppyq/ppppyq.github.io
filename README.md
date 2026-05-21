# Personal Academic Homepage

This repository is a personal academic homepage based on the Academic Pages template.

## What to edit

- `_config.yml`: site title, name, email, avatar, affiliation, GitHub, Google Scholar, ORCID, and other profile links.
- `_pages/about.md`: homepage biography, research interests, news, selected publications, and projects.
- `_pages/cv.md`: CV content.
- `_publications/`: one Markdown file per paper.
- `_talks/`: one Markdown file per invited talk, conference presentation, or seminar.
- `_teaching/`: one Markdown file per course or teaching activity.
- `files/`: PDFs such as CV, papers, slides, and other downloadable files.
- `images/profile.png`: sidebar profile photo. Replace this file with your own image using the same filename.

## Publish on GitHub Pages

Create a public GitHub repository named:

```text
ppppyq.github.io
```

Then push this local project:

```powershell
git remote set-url origin https://github.com/ppppyq/ppppyq.github.io.git
git push -u origin master
```

After the push finishes, your site should be available at:

```text
https://ppppyq.github.io
```

GitHub may take a few minutes to build the site the first time.

## Local preview

This project needs Ruby and Bundler to preview locally:

```powershell
bundle install
bundle exec jekyll serve -l -H localhost
```

Then open:

```text
http://localhost:4000
```
