# Web Application Development: code examples

This repository holds the code from the lecture videos, week by week. Each
example is a plain HTML file that opens in any browser. Nothing needs to be
installed or built.

## Getting the files

On this page, click the green **Code** button and choose **Download ZIP**.
Unzip it, then open the folder in Visual Studio Code with **File, Open Folder**.
To see a page in the browser, right-click its file in the Explorer panel,
choose **Reveal in File Explorer**, and double-click the file.

If you know Git, you can clone the repository instead and pull each new week as
it is added.

## How to use the examples

Type the code yourself while you watch the video, then compare your file with
the one here. Typing it out is slower than copying it, but is a great way to learn the tags. If your page looks different, paste your file into the
[W3C validator](https://validator.w3.org/nu/) and read the first message it
gives.

In most folders there are two files:

- `index.html` is the finished page from the video.
- `index-with-mistake.html` is the same page with the mistake that the video
  makes on purpose. Open it in the validator to see the messages, then find the
  difference between the two files.

## Week 1

| Video | Folder | What is in it |
|---|---|---|
| Hello world in VS Code | [`week-01/hello-world`](week-01/hello-world) | The first web page. `index.html` is the finished page. The four files in `steps` show it growing: the empty skeleton, the head, the heading, and the paragraph. |

The first step is only the outline of the page, so the validator reports that
it has no title. That is expected. The head is added in step two.

## Week 2

| Video | Folder | What is in it |
|---|---|---|
| 1. Structure, lists, comments, indentation and validation | [`week-02/01-structure-lists-validation`](week-02/01-structure-lists-validation) | The My Study Week page with header, main, footer and sections, three kinds of list, a comment, and the closing tag of the header deleted in the mistake file. |
| 2. Tables | [`week-02/02-tables`](week-02/02-tables) | A timetable with a caption, header cells, a cell that spans rows and a cell that spans columns. The mistake file has a row that is one cell short. |
| 3. Links | [`week-02/03-links`](week-02/03-links) | Links to other sites and a mail link. The mistake file leaves `https://` off an address, which the validator cannot see, so we check links by clicking them. |
| 4. A table, step by step | [`week-02/04-table-example`](week-02/04-table-example) | The travel survey table, planned and built from the outside in, with a few lines of styling. The mistake file has an extra empty cell. |

## Week 3

| Video | Folder | What is in it |
|---|---|---|
| 1. Linking to internal pages | [`week-03/01-internal-links`](week-03/01-internal-links) | The Harbour Bakery site: a home page, an about page and a menu page in a `pages` folder, linked with relative paths. The mistake file is the menu page with its links written as if it were beside the home page. |
| 2. Images in HTML | [`week-03/02-images`](week-03/02-images) | The home page with a logo link and a loaf in a `figure` with a caption. The mistake file leaves the `alt` text off the logo. |
| 3. Troubleshooting images and links | [`week-03/03-troubleshooting`](week-03/03-troubleshooting) | The finished home page and menu page, and three mistake files: a link without the `pages` folder, a file ending of `.jpg` for `.jpeg`, and an extra `../` in a picture path. The validator cannot see any of these, so we find them with the routine in the video. |
| 4. Forms and form controls | [`week-03/04-forms`](week-03/04-forms) | The Book Club sign-up form with labels, text, email, password and number boxes, radio buttons, checkboxes, a drop-down list, a text area and two buttons. In the mistake file a label points at an `id` that does not exist. |
| 5. Validation and input | [`week-03/05-form-validation`](week-03/05-form-validation) | The same form with `required`, a placeholder, a date box with `min` and `max`, and a `pattern`. The mistake file writes the dates the way we say them aloud instead of year, month, day. |
| 6. Additional HTML | [`week-03/06-additional-html`](week-03/06-additional-html) | The bakery opening hours page, with `lang`, `id`, `title`, `div` and `span`, a non-breaking space and character references. The mistake file types an email address in angle brackets without the references. |

The bakery pictures are in the `images` folders of videos 2 and 3, next to
each home page, so the pages show them as they do in the videos. The logo is a
drawing and the three pictures of food and the harbour were generated for the
course. Videos 1, 4, 5 and 6 need no pictures. In video 3, the file called
`scones.jpeg` is spelled that way on purpose.

New weeks are added as they are covered.
