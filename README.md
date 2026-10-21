# twl.today

Source for **[twl.today](https://twl.today)** — the public surface of ThinkWell Labs.

Hand-written static HTML. No build step, no trackers, no analytics, no cookies.

## Layout

    index.html            main page (CSS and JS inline)
    program.html          program statement
    papers.html           all papers
    ocs.html              OCS framework
    invisible-text.html   invisible text attack explainer
    privacy.html, terms.html
    assets/               logos, Errorfect logo gallery
    papers/               PDFs
    CNAME                 twl.today
    .nojekyll             serve files as-is on GitHub Pages

## Hosting

GitHub Pages (free), from `main` at the repository root.

DNS for `twl.today` at the registrar:

    A     @    185.199.108.153
    A     @    185.199.109.153
    A     @    185.199.110.153
    A     @    185.199.111.153
    CNAME www  sugarcypher.github.io.

Leave the MX and SPF (`privateemail.com`) records alone — they carry the email.

## Local preview

    python3 -m http.server 8000
