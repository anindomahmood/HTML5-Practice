#  <i>HTML5 Foundational Practice Repository</i>
---

## Repository Blueprint & Directory Guide

The practical codebase is divided into clear, modular layout files. You can navigate directly to each project component to explore the structural markup implementations:

| Working File | Core Structural Focus & Concepts | Primary Components Used |
| :--- | :--- | :--- |
| **[`index.html`](./index.html)** | Project main dashboard featuring localized text modules, inline paragraph structures, relative layout images, and cross-file anchor routing navigation. | `<h1>`, `<p>`, `<img>`, `<ul>`, `<a>`, `<mark>` |
| **[`education.html`](./education.html)** | Chronological layout sections for qualifications alongside traditional data matrix layout structures. | `<header>`, `<section>`, `<hr>`, `<table>`, `<th>`, `<td>` |
| **[`sign.html`](./sign.html)** | Accessible user profile form controls, text/password masks, gender radio structures, city select arrays, and textareas. | `<form>`, `<input>`, `<label>`, `<select>`, `<option>`, `<textarea>` |
| **[`content.html`](./content.html)** | Advanced multimedia rendering frames incorporating third-party site embeds and live YouTube players. | `<iframe>`, `<header>`, `<main>`, `<footer>` |
| **[`block.html`](./block.html)** | Structural grouping, block-level line flow limits versus inline flow text wrapping behaviors. | `<div>`, `<span>`, `<h1>`, `<p>`, `style` |
| **[`final.html`](./final.html)** | Deeply nested list arrangements, advanced semantic tables with column spans, and action form controls. | `<ul>`, `<ol>`, `<table colspan>`, `<input type="radio">`, `<input type="checkbox">` |
| **[`follow.html`](./follow.html)** | Semantic layout architecture showcasing structure frames, portfolio highlights, and anchor target configurations. | `<main>`, `<section>`, `<article>`, `<aside>`, `<a target="_main">` |
| **[`frame.html`](./frame.html)** | Isolated site context presentation windows alongside HTML5 native media controller engines. | `<iframe>`, `<video controls>` |

---

## Deep-Dive Technical Implementations

<details>
<summary><b>1. Core Semantics & Document Structure (Click to Expand)</b></summary>

* **Layout Containers:** Applied functional layouts to properly partition the DOM structure utilizing standard element landmarks including `<header>`, `<main>`, `<section>`, `<article>`, and `<footer>`.
* **Side Annotations:** Implemented `<aside>` containers to handle secondary layout segments detached from the primary content stream.
* **Thematic Dividers:** Deployed native `<hr>` rule attributes to indicate major topical changes or clear visual breaks inside scrolling sections.
</details>

<details>
<summary><b>2. Typography & Inline Presentation Mechanics (Click to Expand)</b></summary>

* **Hierarchical Headings:** Integrated cascading text nodes ranging from major titles `<h1>` down to functional headings `<h3>` to define clear information hierarchies.
* **Text Formatting Utilities:** Used `<b>`, `<i>`, and `<u>` elements for structural font modifiers, alongside chemical or mathematical indices using the `<sub>` subscript element.
* **Text Highlights:** Utilized the `<mark>` tag to provide precise textual spotlight highlights for key contact coordinates.
* **Source Formatting Preservation:** Managed literal code snippets or raw text patterns with `<pre>` tags to maintain white-spaces and font constraints exactly as authored in code.
</details>

<details>
<summary><b>3. Element Box Behavior & Styling Controls (Click to Expand)</b></summary>

* **Block vs. Inline Flows:** Mapped out the operational boundaries separating block containers (`<div>`) that claim 100% of the display width from inline components (`<span>`) that sit smoothly inside text paragraphs.
* **Inline Property Adjustments:** Practiced style property applications using the `style="..."` property hook to handle elements like background variables (`background-color`) and typography shades (`color`) directly on the tags.
</details>

<details>
<summary><b>4. Interactive Forms & User Data Captures (Click to Expand)</b></summary>

* **Input Type Formatting:** Set up secure input lines using `<input type="text">` for username values and `<input type="password">` to obscure passwords automatically.
* **Mutually Exclusive Radio Trees:** Created grouped selector elements by sharing matching `name` parameters, letting users toggle precise single choices cleanly.
* **Dropdown Option Scopes:** Structured select drop-down items (`<select>`) containing multi-item menu elements (`<option>`) to let users select cities effortlessly.
* **Multi-Value Validation Lists:** Built user checkbox lists (`type="checkbox"`) allowing separate multiple choices alongside expanded text boxes (`<textarea rows="5">`) to record multi-line text submissions.
</details>

<details>
<summary><b>5. Structured Matrices & Data Tables (Click to Expand)</b></summary>

Organizing multi-column analytical parameters is managed via standard matrix frameworks:

```html
<table border="1">
    <caption>Major Course</caption>
    <thead>
        <tr>
            <th>Code</th>
            <th>Course</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>303</td>
            <td>Web Technologies</td>
        </tr>
    </tbody>
</table>
