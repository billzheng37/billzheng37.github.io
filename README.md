# Your academic website

Website: https://billzheng37.github.io/

This site uses AcademicPages and has Home, Research, and CV pages. Personal details are intentionally left as placeholders.

## Edit your information

Open one of the links below, click the pencil icon, make your changes, and click **Commit changes**. Save to the `master` branch to update the website automatically.

| What to change | File |
| --- | --- |
| Your name, position, institution, email, profile links, and photo filename | [Edit profile settings](https://github.com/billzheng37/billzheng37.github.io/edit/master/_config.yml) |
| Welcome text, research interests, and background | [Edit homepage](https://github.com/billzheng37/billzheng37.github.io/edit/master/_pages/about.md) |
| Papers, projects, coauthors, and abstracts | [Edit Research](https://github.com/billzheng37/billzheng37.github.io/edit/master/_pages/research.md) |
| Education, experience, teaching, and awards | [Edit CV](https://github.com/billzheng37/billzheng37.github.io/edit/master/_pages/cv.md) |
| Navigation links | [Edit menu](https://github.com/billzheng37/billzheng37.github.io/edit/master/_data/navigation.yml) |

In `_config.yml`, change `name` once; the sidebar uses that same name. Set `title` to your name too. Put your position in `bio` and institution in `employer`. An empty optional field hides that link. Keep indentation and quotation marks when editing settings. Keep the text between the initial `---` lines at the top of page files.

To add a paper link in Research, use `[Paper](/files/paper.pdf)` after uploading the file. Duplicate a paper entry for additional papers, or remove sections you do not need.

## Add your photo

1. Open the [images folder](https://github.com/billzheng37/billzheng37.github.io/tree/master/images).
2. Choose **Add file → Upload files**, then upload your photo, for example `portrait.jpg`.
3. In `_config.yml`, change `avatar` to `"portrait.jpg"`.

## Add your CV PDF

1. Upload `cv.pdf` to the [files folder](https://github.com/billzheng37/billzheng37.github.io/tree/master/files).
2. In `_config.yml`, set `cv_pdf` to `"/files/cv.pdf"`.
3. A download link will appear on the CV page. You can remove the text sections if you prefer the PDF alone.

## Publishing

Under [Settings → Pages](https://github.com/billzheng37/billzheng37.github.io/settings/pages), set **Source** to **GitHub Actions**. The included workflow builds and publishes the website when you save changes on `master`. Follow progress in the [Actions tab](https://github.com/billzheng37/billzheng37.github.io/actions).

## Theme

Built with [AcademicPages](https://github.com/academicpages/academicpages.github.io), based on [Minimal Mistakes](https://github.com/mmistakes/minimal-mistakes). Original licenses are retained.
