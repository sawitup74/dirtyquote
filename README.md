dirtyquote.com static site, packed as zip parts and deployed by GitHub Actions.

The workflow unpacks parts/*.zip into the Pages site and copies CNAME
(dirtyquote.com). To publish an update, refresh core.zip (HTML, assets,
feeds) and add any new images as an extra img*.zip, then push to main.
Do not remove CNAME or the deploy workflow.
