# Playground for the new mozillach.org community website


## Build the CSS files

Assuming you have `npm` [installed](http://blog.npmjs.org/post/85484771375/how-to-install-npm).

```bash
$ npm install -g less
```

Run the following script to compile the `less` style definitions under `less/*`
to `/resources/*.css`:

```bash
$ ./build_css.sh
```
## Local development

To get the full functionality for Tabzilla, the site must be served from a local
webserver - e.g. by starting one from Python:

```bash
$ python -m SimpleHTTPServer 8000
```
