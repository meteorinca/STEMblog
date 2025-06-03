# STEM Blog

This repository contains the source for my GitHub Pages powered blog. Posts are written in Markdown and generated with [Jekyll](https://jekyllrb.com/).

## Running locally

1. Clone the repository
   ```bash
   git clone https://github.com/meteorinca/STEMblog.git
   cd STEMblog
   ```
2. Install dependencies and start the Jekyll server
   ```bash
   bundle install
   bundle exec jekyll serve
   ```

The site will be available at `http://localhost:4000/STEMblog/`.

## Adding posts

Create new Markdown files in the `_posts` directory using the `YYYY-MM-DD-title.md` naming convention. Images such as scans of sticky notes can be placed in `assets/images/` and referenced with the `relative_url` filter:

```markdown
![Alt text]({{ '/assets/images/my-note.png' | relative_url }})
```

Happy hacking!
