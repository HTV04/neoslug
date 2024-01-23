# NeoSLUG
This is the repository for the [RU SLUG](https://ruslug.org)
website. As a reimplementation the original 2001 version of the site,
it has been named "NeoSLUG."

## Goals
The history of the RU SLUG website is the history of switching between
site generators that were relevant at the time. In addition to
creating a site the replicates the original and avoids feature creep,
we impose the following requirements:
- Small
- Static; no CGI or JavaScript
- Written in modern HTML and CSS
- Friendly to as many browsers as possible, including text-based browsers

## Expanding
All new articles and changes to existing articles are to be done
within the `drafts` directory. They are standard HTML files that only
include the body.

## Generating
From the root directory, run `make`. The build will be located in the
directory `slug`.
