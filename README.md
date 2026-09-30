# SA2Real workshop website

A simple static website with separate pages, plain HTML and one CSS file.
No JavaScript, build process, package manager or installation is needed.

## Preview on your computer

Unzip the package, then double-click `index.html`. Keep all files together so
links and styling work. The navigation opens the other HTML pages.

## Publish to your GitHub repository

Repository: `sa2realworkshop/sa2realworkshop.github.io`

1. Unzip this package.
2. In the repository, choose **Add file > Upload files**.
3. Upload all six HTML files and `style.css` directly into the repository root.
   Do not upload the ZIP itself or place the files in a `public` folder.
   You may also upload this README and the empty `.nojekyll` file.
4. Commit to `main`.
5. Under repository **Settings > Pages**, select **Deploy from a branch**,
   branch **main**, folder **/ (root)**, then Save.
6. Once publishing finishes, open https://sa2realworkshop.github.io/

If the earlier `index.html` is already present, uploading this one replaces it.
GitHub does not need the `.gitlab-ci.yml` from the earlier package.

## What to edit

| File | Contents |
| --- | --- |
| `index.html` | Workshop description, topics and important dates |
| `schedule.html` | Programme and rotating group activity |
| `speakers.html` | Invited speakers and panelists |
| `organizers.html` | Organizing committee and contact address |
| `papers.html` | Accepted papers and workshop materials |
| `participate.html` | Submissions, registration and hybrid participation |
| `style.css` | Colours, fonts, spacing and mobile layout |

To edit on GitHub, open a file, click the pencil icon, change the text, and commit.
Changes to the published branch automatically update the site.

## Basic HTML editing

Edit the content between `<main>` and `</main>` in each page.
Comments mark the sections that will need updating. For example:

```html
<h2>Important dates</h2>
<p><strong>Submission deadline:</strong> 1 February 2027</p>
<a href="https://your-submission-link">Submit a paper</a>
```

The date and link above are examples only.

- `<p>...</p>` is a paragraph.
- `<h2>...</h2>` is a heading.
- `<li>...</li>` is a list item.
- `<a href="...">...</a>` is a link.
- `<!-- ... -->` is a comment and does not appear on the website.

Speaker and organizer pages include commented examples you can copy.
The navigation and footer are repeated in the six HTML files so everything works
without a build step. If you change their text or links, update all six files.
To adjust colours or the page width, edit the variables at the top of `style.css`.

## Before announcing

The site marks the workshop as proposed and uses the latest planned hybrid format.
Confirm acceptance, dates, venue, speakers, organizers, contact and submission
information before replacing those placeholders. No speakers are listed as confirmed.

The workshop contributions page is currently descriptive. Add the chosen shared
spreadsheet/form link later; static GitHub Pages does not store form submissions.
