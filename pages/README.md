
# Directory of All Pages (@ rsssf.org)

Find all 40000+ (html) pages
of the rsssf.org website
listed in the pages.csv datasets (filed by directory).


For examples, the root (`/`) directory pages.csv
ìn [pages/pages.csv](pages.csv) reads:

``` csv
path,               links, title
/archive.html,      14/13, The RSSSF Archive
/career-index.html, 272/1, Index of Coaches' and Players' Careers
/charter.html,        1/4, RSSSF Charter
/colour-index.html, 223/1, Club Colours -- Countrywise Index
...
```


The path (e.g. `/archive.html`) is the complete path of the page url
(e.g. `https://rsssf.org/archive.html`),
the first part of links is the number of linked pages (e.g. 14)
and the second part is number of backlink pages (e.g. 13),
title (e.g. `The RSSSF Archive`) is the title of the page `
or `-` if not available (n/a).


Note - To get an all-in-one pages.csv dataset merge / concat all
split-up per directory pages.csv dataset.


For linked pages returning 404 not found, see pages_404.csv
and for formats other than html, see  pages_pdf.csv and pages_other.csv.


> [!TIP]
>   You can browse the pages directory / index online @
>    <https://rsssf.github.io/mirror>
