# Getting started with ezVIS and ezPAARSE

This repository has an example to quickly see what can be done with
[ezvis](https://github.com/madec-project/ezvis/) and [ezpaarse](https://github.com/ezpaarse-project/ezpaarse) CSV results (usage events).

## Requirements

- [mongodb](http://docs.mongodb.org/manual/installation/) (installed and running)
- [node](http://nodejs.org/) 0.10 or 0.12(just install it)

Then, open a shell, and type 

```sh
$ npm install -g ezvis
```

This step may take time as it gets files from the internet.
Some logs should scroll the window, and you should return to the prompt.

## Get example

To get the example, use `git clone` for this repository, or get it from
[releases](https://github.com/ezpaarse-project/getting-started-with-ezvis/releases),
or [zip](https://github.com/ezpaarse-project/getting-started-with-ezvis/archive/master.zip),
or [tar.gz](https://github.com/ezpaarse-project/getting-started-with-ezvis/archive/master.tar.gz) and unzip it.

ezPAARSE results (CSV data) are located in this folder: 

```
ezpaarse/
└── ec-3j-bibliovie-anonymes.csv
```

## Visit one example

Then go into the repository from the Command Prompt:

```sh
$ cd getting-started-with-ezvis
```

Then launch ezVIS's web server:

```sh
$ ezvis ezpaarse
```

and point your browser to [http://localhost:3000/](http://localhost:3000/).
