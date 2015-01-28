# Installation

Installing Visir requires to have both
[mongodb](http://docs.mongodb.org/manual/installation/) 2.4+ and
[nodejs](http://nodejs.org/) 0.10 installed.

Although their installation is simple, it is different from one environment to
another.

Below are some suggestions, according to the Operating System you are using.

- [Linux](#linux)
- [Windows](#windows)
- [MacOS](#macos)

## Linux

### MongoDB

- [Red Hat, CentOS, Fedora or Amazon Linux](http://docs.mongodb.org/manual/tutorial/install-mongodb-on-red-hat-centos-or-fedora-linux/)
- [Ubuntu](http://docs.mongodb.org/manual/tutorial/install-mongodb-on-ubuntu/)
- [Debian](http://docs.mongodb.org/manual/tutorial/install-mongodb-on-debian/)
- [other Linux Systems](http://docs.mongodb.org/manual/tutorial/install-mongodb-on-linux/)

Warning: only versions 2.4+ of Mongo were tested, these are not versions
avaible by default on Ubuntu 12.04, for example.

### NodeJS

Use a 0.10.* version of [nodejs](http://nodejs.org/).

Tip: use [nvm](https://github.com/creationix/nvm) to be able to choose
nodejs's version.

## Windows

In general, pay attention to the version of Windows you use (32-bit or 64-bit), and download an MSI installer.

### MongoDB

See [install MongoDB on Windows](http://docs.mongodb.org/manual/tutorial/install-mongodb-on-windows/).

Don't forget to create a `\data\db` at the root of the partition where you
installed Mongo, it will prevent the need to give parameters to the
`mongod.exe`.

Note: if you did not choose `C:\`, use the Custom install process of mongodb to set the right installation path. Example: `D:\mongodb`.

Warning: only versions 2.4+ of Mongo were tested.

Running `bin\mongod.exe` (in the installation directory) may require that you give network
authorizations (only the first time).

Once MongoDb is running, you can skip the following steps to install NodeJS.

### NodeJS

On [nodejs's downloads page](http://nodejs.org/download/), get the Windows MSI Installer, and use it.

### Command Prompt

To launch VISIR, you'll need to open the command prompt.

## MacOS

Install [Homebrew](http://brew.sh/), and then use it to install
[mongodb](http://docs.mongodb.org/manual/tutorial/install-mongodb-on-os-x/)
and [node](https://github.com/joyent/node/wiki/Installing-Node.js-via-package-manager#osx).
