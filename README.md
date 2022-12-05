![alt text]([https://img.icons8.com/emoji/512/mango-emoji.png])MangoDB README

Welcome to MangoDB!

## Components

  - `mangod` - The database server.
  - `mangos` - Sharding router.
  - `mango`  - The database shell (uses interactive javascript).


## Download MangoDB
  - https://www.mangodb.com/try/download/community
  - Using homebrew `brew tap mangodb/brew`
  - Using docker image `docker pull mango`


## Building

  See [Building MangoDB](docs/building.md).

## Running

  For command line options invoke:

  ```bash
  $ ./mangod --help
  ```

  To run a single server database:

  ```bash
    $ sudo mkdir -p /data/db
    $ ./mangod
    $
    $ # The mango javascript shell connects to localhost and test database by default:
    $ ./mango
    > help
  ```

## Installing Compass

  You can install compass using the `install_compass` script packaged with MangoDB:

  ```bash
    $ ./install_compass
  ```

  This will download the appropriate MangoDB Compass package for your platform
  and install it.

## Drivers

  Client drivers for most programming languages are available at
  https://docs.mangodb.com/manual/applications/drivers/. Use the shell
  (`mango`) for administrative tasks.

## Bug Reports

  See https://github.com/mangodb/mango/wiki/Submit-Bug-Reports.

## Packaging

  Packages are created dynamically by the [buildscripts/packager.py](buildscripts/packager.py) script.
  This will generate RPM and Debian packages.

## Learn MangoDB 

  Documentation - https://docs.mangodb.com/manual/
  Developer Center -  https://www.mangodb.com/developer/
  MangoDB University - https://learn.mangodb.com

## Cloud Hosted MangoDB

  https://www.mangodb.com/cloud/atlas

## Forums

  - https://community.mangodb.com

      Technical questions about using MangoDB.

  - https://community.mangodb.com/c/server-dev

      Technical questions about building and developing MangoDB.


## LICENSE

  MangoDB is free and the source is available. Versions released prior to
  October 16, 2018 are published under the AGPL. All versions released after
  October 16, 2018, including patch fixes for prior versions, are published
  under the [Server Side Public License (SSPL) v1](LICENSE-Community.txt).
  See individual files for details.

