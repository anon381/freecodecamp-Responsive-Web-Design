# ✅ Technical Documentation Page Test Cases

1. **Main Content:**
   - You should have a `main` element with an `id` of `main-doc`.
   - You should have at least five `section` elements with a class of `main-section`.
   - All of your `.main-section` elements should be `section` elements.
   - You should have at least five `.main-section` elements that are descendants of `#main-doc`.
   - The first child of each `.main-section` should be a `header` element.
   - None of your `header` elements should be empty.
   - All of your `.main-section` elements should have an `id`.
   - Each `.main-section` should have an `id` that matches the text of its first child, having any spaces in the child's text replaced with underscores (`_`) for the id's.
   - You should have at least 10 `p` elements (total) within your `.main-section` elements.
   - You should have at least five `code` elements that are descendants of `.main-section` elements.
   - You should have at least five `li` elements that are descendants of `.main-section` elements.
2. **Navigation:**
   - You should have a `nav` element with an `id` of `navbar`.
   - Your `#navbar` should have exactly one `header` element within it.
   - You should have at least one `a` element with a class of `nav-link`.
   - All of your `.nav-link` elements should be anchor (`a`) elements.
   - All of your `.nav-link` elements should be in the `#navbar`.
   - You should have the same number of `.nav-link` and `.main-section` elements.
   - The `header` element in the `#navbar` should come before any link (`a`) elements also in the `#navbar`.
   - Each `.nav-link` should have text that corresponds to the header text of its related section (e.g. if you have a "Hello world" section/header, your `#navbar` should have a `.nav-link` which has the text "Hello world").
   - Each `.nav-link` should have an `href` attribute that links to its corresponding `.main-section` (e.g. If you click on a `.nav-link` element that contains the text "Hello world", the page navigates to a section element with that id).
3. **Layout & Style:**
   - Your `#navbar` should always be on the left edge of the window.
   - Your Technical Documentation project should use at least one media query.

---

> Make sure all these test cases pass for a successful Technical Documentation Page project!