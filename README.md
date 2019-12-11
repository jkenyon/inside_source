# inside_source

https://insideidaho.org/

## Search App Source
[https://github.com/uidaholib/inside-idaho-search-app](https://github.com/uidaholib/inside-idaho-search-app)

## To update the app section:

From the 'public' folder, move: 
* "bundle.css"
* "bundle.css.map"
* "bundle.js"
* "bundle.js.map"
* "main.css"

To '/assets/lib/inside' in this repo.

## To modify the app styles:

On your machine, you first need to:
* Install node.js
* Install yarn

Once installed:
* Run 'yarn install'

Access the src folder and edit whatever you need to. Save as usual. Most of it is in the components section.

If everything works:
* Run 'yarn build' from the inside-idaho-search-app home directory (should have a yarn.lock file).
* It may take a second the first time to install the necessary libraries, located at github.com/uidaholib/inside-idaho-lib.
* Go repeat the update section above.
