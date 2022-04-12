# ICPC Bolivia official site

This site uses [Hugo](https://gohugo.io/) static site generator.

## Cloning
This repository uses [Ananke Theme](https://github.com/theNewDynamic/gohugo-theme-ananke) as a git sub-module. In order to fully clone this repository make sure to use the recursive option of cloning, choose one of the next depending on your version of Git.

```
$ git clone --recurse-submodules https://github.com/Veuge/icpc
# For older versions of Git
$ git clone --recursive https://github.com/Veuge/icpc
```

After cloning make sure to create a directory `public` referencing the `master` branch for publishing to Github Pages.

```
$ git worktree add -B master public origin/master
```


## Development
Hugo includes a development server, to start it run:

```
$ hugo server --watch -D
```

Which makes the site available at `http://localhost:1313` and when a change is done it will be reflected instantly on the already mentioned URL.
