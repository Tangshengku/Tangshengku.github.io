# Blog framework

Pages are plain HTML with relative links, so both direct local file opening
and GitHub Pages hosting work without a local build or server.

Open `index.html` to preview the homepage, `blog/index.html` for the full list,
or `blog/layout-preview/index.html` for the sample article. All navigation uses
explicit `index.html` filenames so it also works with `file://` URLs.

The sample article is marked as a sample and has a noindex meta tag.
`_blog_entries/layout-preview.md` is retained only as a writing source; edits
to it do not automatically update HTML. For now, edit the article HTML and
the lists in the homepage and blog index together. The homepage scrolls once
entries exceed 240px. An automated publishing workflow can be added later.

Comments are a disabled placeholder. No comments are accepted or stored yet,
and no external comment service is contacted. Future integration belongs in
article pages, with an article's permanent path as its comment ID.
Service/database credentials must remain on the backend.

The framework provides responsive prose, images, quotes, tables, and code
blocks. Math rendering, copy buttons, and automatic contents navigation are
future enhancements. Publishing workflow and comment hosting are not yet fixed.
