# evote-movie-2019-04-common-header-footers

The project has been refactored as follows:

- remove common header and nav content to `_header.php`

- remove common footer content to `_footer.php`

- add `require_once` to all pages to read in common header and footer

- NOTE: we have lost title page name and current page nav indicator - we'll fix this soon :-)
