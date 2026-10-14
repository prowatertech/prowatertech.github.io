
# Prowater Technologies website

This site uses GitHub Pages' Jekyll processing to render shared page templates.

- `_layouts/default.html` contains the document shell and shared metadata.
- `_includes/header.html` and `_includes/footer.html` contain the shared site header and footer.
- Root-level HTML pages contain page-specific content and YAML front matter for their title, description, and active navigation item.

Keep `.nojekyll` absent so GitHub Pages processes the layouts and includes. Edit the shared include files to update the header or footer across all pages.
