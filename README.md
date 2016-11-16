# Developer Induction
This repo contains the slides for developer induction, produced with prez/revealjs.

## Viewing the slides
### Viewing published slide deck
[Published slide deck available here](https://ukhomeoffice.github.io/developer-induction/build/index.html)

### Viewing html file locally
Open build/index.html with a web browser

### Running as a server with docker
```
docker build -t dev-induction . 
docker run -ti -p 8000:8000 dev-induction
```

## Editing the slides
### Pre-requisites
You must have node version 6+ installed
You must have prez installed
```
npm install -g prez
```

### Editing the slides
```
prez --serve --watch --print
```
This will serve the slides from localhost:9000 and open it in your browser. 
These will be reloaded automatically when changes are made to the slides. 
It will also update pdf versions of the slides as you make edits.

Edit the slides in the **slides** folder.
