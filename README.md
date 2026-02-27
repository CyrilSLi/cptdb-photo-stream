# cptdb-photo-stream

A web application which displays all photos from a given CPTDB forum user on a single scrollable page.

## Installation & Usage

This project consists entirely of static files; simply clone the repository and open `stream.html?userId=` followed by a CPTDB user ID in a web browser (e.g. `file:///path/to/stream.html?userId=41421-cyril`).

### NOTE - GitHub Pages

The file `404.html` is a redirection page which takes advantage of GitHub Pages' custom 404 error handling functionality. If using GitHub Pages or another service which serves `404.html` for a non-existent URL path, you can simply navigate to `[github-username].github.io/cptdb-photo-stream/[cptdb-user-id]` (e.g. [https://cyrilsli.github.io/cptdb-photo-stream/41421-cyril](https://cyrilsli.github.io/cptdb-photo-stream/41421-cyril)) to view the photo stream for that user.