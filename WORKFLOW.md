# Website Workflow

This document explains how to add content to the site.

---

## Adding a New Project

1. Copy the project template:
   - `projects/_template`
2. Rename the copied folder to a URL-friendly name:
   - Example: `my-new-project`
3. Edit:
   - `projects/my-new-project/index.html`
4. Replace all placeholder text.
5. Add the project link to:
   - `projects/index.html`

### Publish
git add .
git commit -m "add <project name>"
git push


---

## Adding a New Blog Post

1. Create a new folder under `blog/`:
   - Example: `my-blog-post`
2. Create:
   - `blog/my-blog-post/index.html`
3. Write the post content.
4. Add the link to:
   - `blog/index.html`

### Publish
git add blog
git commit -m "add blog post: <title>"
git push



---

## Editing Existing Content

1. Open the relevant `index.html`
2. Make edits
3. Commit and push

---

## Notes

- The site is hosted via GitHub Pages.
- Pushing to `main` automatically publishes the site.
- No additional build steps are required.
