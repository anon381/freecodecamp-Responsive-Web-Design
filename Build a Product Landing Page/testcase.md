# ✅ Product Landing Page Test Cases

1. **Header:**
   - You should have a `header` element with an `id` of `header`.
   - You should have an `img` element with an `id` of `header-img`.
   - Your `#header-img` should be a descendant of the `#header`.
   - Your `#header-img` should have a `src` attribute.
   - Your `#header-img`’s `src` value should be a valid URL (starts with http).
   - You should have a `nav` element with an `id` of `nav-bar`.
   - Your `#nav-bar` should be a descendant of the `#header`.
   - You should have at least 3 `.nav-link` elements within the `#nav-bar`.
   - Each `.nav-link` element should have an `href` attribute.
   - Each `.nav-link` element should link to a corresponding element on the landing page (has an `href` with a value of another element's id, e.g. `#footer`).
2. **Video:**
   - You should have a `video` or `iframe` element with an `id` of `video`.
   - Your `#video` should have a `src` attribute.
3. **Form:**
   - You should have a `form` element with an `id` of `form`.
   - You should have an `input` element with an `id` of `email`.
   - Your `#email` should be a descendant of the `#form`.
   - Your `#email` should have the `placeholder` attribute with placeholder text.
   - Your `#email` should use HTML5 validation by setting its type to `email`.
   - You should have an `input` element with an `id` of `submit`.
   - Your `#submit` should be a descendant of the `#form`.
   - Your `#submit` should have a type of `submit`.
   - Your `#form` should have an `action` attribute of `https://www.freecodecamp.com/email-submit`.
   - Your `#email` should have a `name` attribute of `email`.
4. **Navigation & Layout:**
   - Your `#nav-bar` should always be at the top of the viewport.
   - Your Product Landing Page should use at least one media query.
   - Your Product Landing Page should use CSS Flexbox at least once.

---

> Make sure all these test cases pass for a successful Product Landing Page project!