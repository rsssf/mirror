
> [!TIP]
>   You can browse the (rsssf.org) pages directory / index online @
>    <https://rsssf.github.io/mirror>




# rsssf.org  Mirror (& Text Corpus)


what?

the goal here is to mirror the rsssf.org site
and prepare a (slightly cleaned-up) text corpus
for an all-in-one download (see `corpus.zip` in [`/releases`](https://github.com/rsssf/mirror/releases))
to help along research and experimentation
with the 40000+ football archive rsssf pages


note - all scripts used are open-source (see [/scripts](https://github.com/rsssf/scripts))
along with documentation to update or start from scratch





The directory structure of the (mirrored) rsssf.org website
(about 40 000+ .html pages)


There are the `/tables[a-z]` a-z (26)  plus the `/tables`
"core" directories:


```
                               pages
└───rsssf.org                =>   66 (in /)
    ├───tables               =>  580
    ├───tablesa              => 3074
    ├───tablesb              => 1903
    ├───tablesc              => 2374
    ├───tablesd              => 1198
    │   └───dfbcup           =>    8
    ├───tablese              => 1427
    ├───tablesf              => 1099
    ├───tablesg              => 1398
    ├───tablesh              =>  636
    ├───tablesi              => 1565
    ├───tablesj              =>  527
    ├───tablesk              =>  959
    ├───tablesl              =>  895
    ├───tablesm              => 2222
    ├───tablesn              => 1696
    ├───tableso              =>  895
    ├───tablesp              => 1420
    ├───tablesq              =>   93
    ├───tablesr              =>  901
    ├───tabless              => 3017
    ├───tablest              => 1407
    ├───tablesu              =>  773
    ├───tablesv              =>  422
    ├───tablesw              =>  747
    ├───tablesx              =>   22
    ├───tablesy              =>   72
    └───tablesz              =>  853
```

plus about a dozen extras directories:

```
└───rsssf.org    (with /tables* hidden)
    ├───bvv                  =>  221
    ├───colours              =>  220
    ├───ec                   =>  190
    ├───engpaul
    │   └───FLA              =>  111
    ├───intldetails          =>  214
    ├───miscellaneous        => 6053
    ├───nedfer               =>   27
    ├───players              => 1943
    ├───rssbest              =>  218
    ├───sacups               =>  345
    ├───usadave              =>   56
    └───wk94                 =>   14
```


You can find all 40000+ (html) pages
of the rsssf.org website
listed in the pages.csv datasets (filed by directory).
For more see [`/pages` »](pages)



<!--

report number of indexed pages:

by type:
- .html
- .pdf
- spreadsheets (.xlsd?)
- images (.jpg)  - incl. scanned documents as images

by (charset) encoding  (only incl. .html):
- windows-1256?
- utf-8
- utf-16le
- ...


report broken links - 404 page not found:


## more

for notes on using the `wget` command-line tool to mirror the rsssf.org website,
see [/wget »](wget)

-->

