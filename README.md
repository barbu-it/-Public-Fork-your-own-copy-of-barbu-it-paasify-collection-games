<p align='center'>
<img src="https://github.com/barbu-it/paasify/raw/main/logo/paasify_collection.svg" alt="Paasify Collection">
</p>

# Paasify Collection: games

This collection is contains self hosted games and games servers

## Quickstart

In your `paasify.yml` configuration, add in your sources:
```
sources:
  - name: games
    remote: https://github.com/barbu-it/paasify-collection-games.git
```

Then you can reference any apps in your stacks:
```
stacks:
  - app: games:posio
```

Then apply your changes with paasify:
```
$ paasify apply
```


## Project

### Requirements

The following requirements must be installed for this project:

* docker

To modify this project:

* paasify
* git

### Paasify documentation

Quicklinks:

* [Paasify Documentation](https://barbu-it.github.io/paasify/)
* [Paasify Sources](https://github.com/barbu-it/paasify)
* [Paasify Gitter](https://gitter.im/barbu-it/paasify)


## Project Informations

Paasify project maintened by:

* Author: mrjk
* License: GPLv3
* Repository: [github.com/barbu-it/paasify-collection-games](https://github.com/barbu-it/paasify-collection-games.git)

