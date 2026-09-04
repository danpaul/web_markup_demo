## About

This branch contains examples and documentation related semantic HTML.

You can see the tag and a short description below and view these in the context of a page `./index.html`.

Open `index.html` in the browser. Use the inspector to examine the elements.

## Reference

HTML elements that carry meaning. Generic containers (`div`, `span`) are omitted.

### Content sectioning

- `<address>` — Contact information for a person, people, or organization.
- `<article>` — Self-contained content that could stand alone (e.g. a blog post).
- `<aside>` — Content only indirectly related to the main content, such as a sidebar.
- `<footer>` — Footer for the nearest section: author, copyright, or related links.
- `<header>` — Introductory content, such as a heading, logo, or navigation.
- `<h1>`–`<h6>` — Section headings, from the highest level (`h1`) to the lowest (`h6`).
- `<hgroup>` — A heading grouped with related secondary text, such as a subtitle.
- `<main>` — The dominant content of the page; there should be only one.
- `<nav>` — A section of navigation links (menus, tables of contents, indexes).
- `<section>` — A thematic grouping of content that does not have a more specific tag.
- `<search>` — A region containing controls for searching or filtering.

### Text content

- `<blockquote>` — An extended quotation from another source.
- `<dl>` — A description list of terms and their descriptions.
- `<dt>` — A term in a description list.
- `<dd>` — The description or value that follows a term in a description list.
- `<figure>` — Self-contained content such as an image, diagram, or code sample.
- `<figcaption>` — A caption for the contents of a `<figure>`.
- `<hr>` — A thematic break between topics or scenes.
- `<ol>` — An ordered (typically numbered) list.
- `<ul>` — An unordered (typically bulleted) list.
- `<li>` — One item in an ordered, unordered, or menu list.
- `<menu>` — An unordered list of commands or items, treated like `<ul>` by browsers.
- `<p>` — A paragraph or other block of related content.
- `<pre>` — Preformatted text shown exactly as written, including whitespace.

### Inline text semantics

- `<a>` — A hyperlink to a URL, file, email address, or location on the page.
- `<abbr>` — An abbreviation or acronym.
- `<b>` — Text brought to the reader's attention without extra importance (not for styling).
- `<bdi>` — Isolates text so its direction is not affected by surrounding content.
- `<bdo>` — Overrides the text direction of its contents.
- `<br>` — A line break where the break itself is meaningful (e.g. a poem or address).
- `<cite>` — The title of a creative work.
- `<code>` — A short fragment of computer code.
- `<data>` — Content paired with a machine-readable value.
- `<dfn>` — The term being defined in a definition phrase.
- `<em>` — Text with stress emphasis.
- `<i>` — Text set off for a reason such as a technical term or idiomatic phrase.
- `<kbd>` — Text representing user input from a keyboard or similar device.
- `<mark>` — Text highlighted for its relevance in the current context.
- `<q>` — A short inline quotation.
- `<ruby>` — A ruby annotation (usually pronunciation for East Asian characters).
- `<rt>` — The annotation text inside a ruby annotation.
- `<rp>` — Fallback parentheses for browsers that do not support ruby annotations.
- `<s>` — Text that is no longer accurate or relevant (not for document edits).
- `<samp>` — Sample output from a computer program.
- `<small>` — Side comments or small print, such as copyright or legal text.
- `<strong>` — Text of strong importance, seriousness, or urgency.
- `<sub>` — Subscript text.
- `<sup>` — Superscript text.
- `<time>` — A date, time, or duration, optionally with a machine-readable value.
- `<u>` — Text with a non-textual annotation (rendered as underline by default).
- `<var>` — A variable in math or programming.

### Media

- `<img>` — An image embedded in the page.
- `<picture>` — A container for alternative image sources for different devices or formats.
- `<source>` — An alternative media resource for `<picture>`, `<audio>`, or `<video>`.
- `<audio>` — Embedded sound content.
- `<video>` — Embedded video content.
- `<track>` — Timed text such as subtitles for `<audio>` or `<video>`.
- `<map>` — An image map that defines clickable regions on an image.
- `<area>` — One clickable region inside an image map.

### Edits

- `<ins>` — Text that has been added to the document.
- `<del>` — Text that has been deleted from the document.

### Tables

- `<table>` — Tabular data in rows and columns.
- `<caption>` — The title of a table.
- `<thead>` — A group of rows that form the table header.
- `<tbody>` — A group of rows that form the table body.
- `<tfoot>` — A group of rows that form the table footer (e.g. totals).
- `<tr>` — A single row of cells in a table.
- `<th>` — A header cell for a row or column.
- `<td>` — A data cell in a table.
- `<colgroup>` — A group of columns in a table, for shared formatting.
- `<col>` — One or more columns within a column group.

### Forms

- `<form>` — A section of interactive controls for submitting information.
- `<fieldset>` — A group of related form controls.
- `<legend>` — A caption for a `<fieldset>`.
- `<label>` — A caption for a form control, associated with that control.
- `<input>` — An interactive control for entering data (many types available).
- `<button>` — A clickable button that performs an action.
- `<select>` — A menu of options the user can choose from.
- `<option>` — One choice in a `<select>`, `<optgroup>`, or `<datalist>`.
- `<optgroup>` — A labeled group of options inside a `<select>`.
- `<datalist>` — A set of suggested values for other form controls.
- `<textarea>` — A multi-line text input.
- `<output>` — The result of a calculation or user action.
- `<progress>` — The completion progress of a task.
- `<meter>` — A scalar value within a known range.

### Interactive

- `<details>` — A disclosure widget that shows extra information when opened.
- `<summary>` — The visible summary or label that toggles a `<details>` widget.
- `<dialog>` — A dialog box or other overlay, such as an alert or modal.
