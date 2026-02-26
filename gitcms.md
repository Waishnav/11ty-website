---
version: "1"
website_url: https://11ty.org
media_path: ""
ssg_framework: eleventy
frontmatter_format: yaml
publishing_mode: direct_publish
collections:
  - name: blogs
    git_path: /src/blog/
    file_extension: .md
    filename_pattern: ""
    frontmatter_schema:
      - name: newstitle
        type: text
        label: Newstitle
      - name: eleventyNavigation
        type: text
        label: Eleventy Navigation
---
