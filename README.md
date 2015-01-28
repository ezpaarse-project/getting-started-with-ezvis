# Getting started with Visir

This repository has an example to quickly see what can be done with
[visir 4.1.0](https://github.com/madec-project/ezvisir/tree/v4.1.0).

## Requirements

- [mongodb](http://docs.mongodb.org/manual/installation/) (installed and running)
- [node 0.10](http://nodejs.org/) (just install it)

See [installation suggestions](./INSTALLATION.md) for details.

Then, open a shell, and type 

```sh
$ npm install -g visir
```

This step may take time as it gets files from the internet.
Some logs should scroll the window, and you should return to the prompt.

## Get example

To get the example, use `git clone` for this repository, or get it from
[releases](https://github.com/madec-project/getting-started-with-visir/releases),
or [zip](https://github.com/madec-project/getting-started-with-visir/archive/master.zip),
or [tar.gz](https://github.com/madec-project/getting-started-with-visir/archive/master.tar.gz) and unzip it.

Then go in the repository:

```sh
$ cd getting-started-with-visir
```

## Visit one example

Launch visir's web server:

```sh
$ visir films
```

and point your browser to [http://localhost:3000/](http://localhost:3000/).
