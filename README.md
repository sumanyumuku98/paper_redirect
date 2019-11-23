## Embeded link redirection Steps:

- Fork the repo
- In the settings page of your repository enable github pages and publish to master branch e.g if github repo name is **temp** then the
link to which is to be embedded in a PDF is *http://www.gh-username/github.io/temp/file_redirect.html*
- Embed this link
- In order to change the page to which it is redirected to update the link in `<meta>`, `<script>`, `<a>` tags in *file_redirect.html*
- Commit the changes and jekyll will build the page automatically
- In order to view the changes do clear your history first.
