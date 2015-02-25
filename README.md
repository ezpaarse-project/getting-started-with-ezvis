# Getting started with ezVIS

This repository has an example to quickly see what can be done with
[ezvis](https://github.com/madec-project/ezvis/tree/).

## Requirements

- [mongodb](http://docs.mongodb.org/manual/installation/) (installed and running)
- [node 0.10](http://nodejs.org/) (just install it)

See [installation suggestions](./INSTALLATION.md) for details.

Then, open a shell, and type 

```sh
$ npm install -g ezvis
```

This step may take time as it gets files from the internet.
Some logs should scroll the window, and you should return to the prompt.

## Get example

To get the example, use `git clone` for this repository, or get it from
[releases](https://github.com/madec-project/getting-started-with-visir/releases),
or [zip](https://github.com/madec-project/getting-started-with-visir/archive/master.zip),
or [tar.gz](https://github.com/madec-project/getting-started-with-visir/archive/master.tar.gz) and unzip it.

## Visit one example

Then go into the repository from the Command Prompt:

```sh
$ cd getting-started-with-visir
```

Then launch visir's web server:

```sh
$ ezvis films
```

and point your browser to [http://localhost:3000/](http://localhost:3000/).
