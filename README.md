# Web Application Development: code examples

This repository holds the code from the lecture videos, week by week. Each
example is a plain HTML file that opens in any browser. From Week 4 a page also
has a CSS file beside it. Nothing needs to be installed or built.

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

From Week 4, `styles.css` holds the CSS and `index.html` links to it, so keep
the two files together in the same folder. A mistake may be in the CSS, in a
file such as `styles-with-mistake.css`. To try it, change the `href` in the
`link` element of `index.html` to the name of the mistake file, then change it
back. The CSS validator is at
[jigsaw.w3.org/css-validator](https://jigsaw.w3.org/css-validator/).

From Week 5, the last two videos use JavaScript. The script is inside the HTML
file, between `script` tags at the end of the `body`, so each page is still one
file. `prompt` and `alert` open small boxes over the page, so open these pages
in Chrome and answer the boxes as the videos do.

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

## Week 4

| Video | Folder | What is in it |
|---|---|---|
| 1. CSS: an introduction | [`week-04/01-css-introduction`](week-04/01-css-introduction) | The Harbour Bakery home page, linked to `styles.css`, which holds one rule that makes the `h1` brown. The two files in `steps` show the other ways of writing the rule: an inline `style` attribute, and a `style` element in the head. There is no mistake file. |
| 2. Selectors, inheritance and the cascade | [`week-04/02-selectors-and-cascade`](week-04/02-selectors-and-cascade) | The finished page and style sheet: rules for `body`, for `h1` and `h2` together, for the links inside `nav`, for the class `special`, for `main` and for `footer`. There is no mistake file. |
| 3. Colour and text | [`week-04/03-colour-and-text`](week-04/03-colour-and-text) | The page and style sheet at the end of the video, with named, hex, `rgb` and `hsl` colours, a font stack, sizes, spacing and alignment. This page has its own `index.html`, because its text is a little different from the other three. In `styles-with-mistake.css` the footer text is a light orange, `hsl(30, 60%, 55%)`, on the brown background. The contrast is only 2.6 to 1, below the 4.5 to 1 that the guidelines ask for. The validators accept it, so we measure it with a contrast checker. |
| 4. Inspecting and fixing CSS in the browser | [`week-04/04-devtools`](week-04/04-devtools) | The finished page, and a style sheet with the `line-height` added in the video and the three fixes made. The first `main ul .special` rule is the grey one that the video treats as written by someone else, and the second is our fix. The video has three faults, one file each: `styles-with-mistake-colour.css` spells `color` as `colour`, which the CSS validator reports; `styles-with-mistake-specificity.css` has a `main ul .special` rule that turns the lemon drizzle cake grey and beats our `.special` rule, which no validator sees; and `index-with-mistake-link.html` links to `style.css` instead of `styles.css`, which the HTML validator cannot see. Chrome DevTools shows all three. |

None of the Week 4 pages uses a picture, so there are no `images` folders. The
navigation links on these pages go to the About and Menu pages from Week 3,
which are not copied into the Week 4 folders, so those two links do not open
anything.

## Week 5

| Video | Folder | What is in it |
|---|---|---|
| 1. Layout with flexbox and positioning | [`week-05/01-layout`](week-05/01-layout) | The Harbour Bakery home page and style sheet at the end of the video. The header and the navigation are flex containers, the three cards sit in a row and share the space with `flex: 1`, and a New label sits on the third card, with `position: relative` on the card and `position: absolute` on the label. |
| 2. Responsive design | [`week-05/02-responsive-design`](week-05/02-responsive-design) | The same page made to adapt to small screens: sizes in `rem`, an image with `max-width: 100%` and `height: auto`, and a media query at the end of the style sheet that stacks the navigation and the cards when the window is `40rem` wide or narrower. The `viewport` line is in the `head` of `index.html`. |
| 3. Introduction to JavaScript | [`week-05/03-introduction-to-javascript`](week-05/03-introduction-to-javascript) | `hello.html`, the page at the end of the video: a heading, and a script at the end of the body that keeps a message in a variable and writes it to the page with `document.write`. |
| 4. The basics of JavaScript | [`week-05/04-basics-of-javascript`](week-05/04-basics-of-javascript) | Three pages. `basics.html` keeps two numbers in variables and writes their sum. `greeting.html` asks for a name with `prompt` and greets the user. `adding.html` asks for two numbers and writes their sum. `adding-with-mistake.html` leaves out `Number`, so 23 and 34 give 2334, as in the video, instead of 57. |

`images/loaf.jpg` in the responsive folder is a drawing made for the course. As in
Week 4, the navigation links on the two bakery pages go to the About and Menu
pages from Week 3, which are not copied into the Week 5 folders, so those two
links do not open anything.

## Week 6

| Video | Folder | What is in it |
|---|---|---|
| 1. Decisions in JavaScript | [`week-06/01-decisions`](week-06/01-decisions) | `score.html` asks for an exam score and says You passed or Try again with `if` and `else`, and `grade.html` is the finished page at the end of the video: a chain of `else if` tests for the bands, with a check that the score is valid (`score < 0 \|\| score > 100`). In `score-with-mistake.html` the test is `score > 40`, so a score of exactly 40 gets Try again, as in the video. The fix is `>=`. |
| 2. Loops in JavaScript | [`week-06/02-loops`](week-06/02-loops) | `counting.html` is the finished counting page: a `for` loop whose last number the user chooses with `prompt`, and a `<br>` after each number. `attempts.html` asks for a password up to three times and leaves the loop with `break` when the answer is right. In `counting-with-mistake.html` there is no line break, so the three numbers run together as 123. |
| 3. Functions in JavaScript | [`week-06/03-functions`](week-06/03-functions) | `functions.html` defines a function and calls it from a button with `onclick`, and `counter.html` has two buttons, Add one and Show total, that share one variable. In `functions-with-mistake.html` the function uses `document.write`, so clicking the button replaces the whole page. |
| 4. Passing values to functions and getting values back | [`week-06/04-passing-values-and-returning-values`](week-06/04-passing-values-and-returning-values) | `area.html` is a function with parameters that returns its answer, called with variables and shown with `alert`. `result.html` is a function that decides and returns a message, which the page writes with `document.write`. In `area-with-mistake.html` the call has no `alert` around it, so the returned value is thrown away and nothing appears. |

These pages use `prompt` and `alert`, so open them in a browser; a code editor's preview may block the pop-up boxes.

New weeks are added as they are covered.
