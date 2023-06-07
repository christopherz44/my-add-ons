## Adobe Express Add-on Developer Docs
Step by step guide to building add-ons for Adobe Express.

### Static Site
We've provided the a pre-built docs site in the `site` folder you can run offline in your favorite browser by simply opening the `site/index.html` to begin exploring the docs.

**Note:** The site runs in a fully operational manner in the offline mode, with the exception of the search feature. If you want to enable search we suggest using one of the serve options below.

### Run with http-server
`cd` into the `site` folder and simply run:

    http-server . -o

or - from the root folder, run:
    
    http-server -o site/index.html

Or, if you do not have `http-server` installed, use the `npx` command below to directly run the script without installing it first:

    npx http-server -o site/index.html


### Serve with mkdocs
Since the site was built with MkDocs, you could also choose to serve it using that instead if you prefer. Install [MkDocs](https://www.mkdocs.org/user-guide/installation/) and run the following command:

    mkdocs serve

### Browser
Please note, this site works best in Chrome and Safari.