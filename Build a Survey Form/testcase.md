# ✅ Survey Form Test Cases

1. **Title:**
   - You should have an `h1` element with an `id` of `title`.
   - Your `#title` should not be empty.
2. **Description:**
   - You should have a `p` element with an `id` of `description`.
   - Your `#description` should not be empty.
3. **Form Structure:**
   - You should have a `form` element with an `id` of `survey-form`.
4. **Name Input:**
   - You should have an `input` element with an `id` of `name`.
   - Your `#name` should have a type of `text`.
   - Your `#name` should require input.
   - Your `#name` should be a descendant of `#survey-form`.
5. **Email Input:**
   - You should have an `input` element with an `id` of `email`.
   - Your `#email` should have a type of `email`.
   - Your `#email` should require input.
   - Your `#email` should be a descendant of `#survey-form`.
6. **Number Input:**
   - You should have an `input` element with an `id` of `number`.
   - Your `#number` should be a descendant of `#survey-form`.
   - Your `#number` should have a type of `number`.
   - Your `#number` should have a `min` attribute with a numeric value.
   - Your `#number` should have a `max` attribute with a numeric value.
7. **Labels:**
   - You should have a `label` element with an `id` of `name-label`.
   - You should have a `label` element with an `id` of `email-label`.
   - You should have a `label` element with an `id` of `number-label`.
   - Your `#name-label` should contain text that describes the input.
   - Your `#email-label` should contain text that describes the input.
   - Your `#number-label` should contain text that describes the input.
   - Your `#name-label`, `#email-label`, and `#number-label` should be descendants of `#survey-form`.
8. **Placeholders:**
   - Your `#name`, `#email`, and `#number` should have a `placeholder` attribute and value.
9. **Dropdown:**
   - You should have a `select` field with an `id` of `dropdown`.
   - Your `#dropdown` should have at least two selectable (not disabled) option elements.
   - Your `#dropdown` should be a descendant of `#survey-form`.
10. **Radio Buttons:**
    - You should have at least two `input` elements with a type of `radio` (radio buttons).
    - You should have at least two radio buttons that are descendants of `#survey-form`.
    - All your radio buttons should have a `value` attribute and value.
    - All your radio buttons should have a `name` attribute and value.
    - Every radio button group should have at least 2 radio buttons.
11. **Checkboxes:**
    - You should have at least two `input` elements with a type of `checkbox` (checkboxes) that are descendants of `#survey-form`.
    - All your checkboxes inside `#survey-form` should have a `value` attribute and value.
12. **Textarea:**
    - You should have at least one `textarea` element that is a descendant of `#survey-form`.
13. **Submit Button:**
    - You should have an `input` or `button` element with an `id` of `submit`.
    - Your `#submit` should have a type of `submit`.
    - Your `#submit` should be a descendant of `#survey-form`.

---

> Make sure all these test cases pass for a successful Survey Form project!