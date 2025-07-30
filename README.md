# website

This repo shares some of my personal information, and resources, in HTML format.
Sometimes referred to as "my personal corner of the internet".

It is setup to be a backing-store - with an index.html and standard(ish) assets.
To view the website, either use a remote:

1. `https://mergesort.net`

or a localhost:

1. In a terminal, run

        # Where this document itself is located.
        cd /path/to/git/dir

        # Python 3.0, or later, must be installed.
        python -m http.server

2. `http://localhost:8000`

## Pipeline

The view through a remote uses the Cloudflare network. To avoid Cloudflare, view
through a localhost; but some functions may be degraded or missing.

The source is not transformed before deployment.

## License

The ***code*** of this repo is licensed under the [0BSD](LICENSE). Includes CSS,
HTML element tag, JavaScript, and general tooling.

The ***content*** of this repo is multi-licensed, and the license is recorded in
the webpage footer - no license means all-rights-reserved. Includes HTML element
text, general icon, and general multimedia.
