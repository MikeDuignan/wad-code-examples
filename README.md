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
the one here. Typing it out is slower than copying it, and it is how the tags
get into your fingers. If your page looks different, paste your file into the
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

New weeks are added as they are taught.
