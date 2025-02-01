## Git

Requires certificates to be updated to actually use it, so get your PEM/CRT from somewhere, maybe [curl](https://curl.se/docs/caextract.html), and then configure git to use it: `git config --global --add http.sslCAInfo <absolute path to CACert.PEM or CRT>`