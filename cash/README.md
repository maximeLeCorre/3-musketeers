# Cash

Cash allow you to make convertion of currencies only with a command line

## Prerequisites

First of all if you need to have Node.js on your computer

* [Node.js](https://nodejs.org/en/)

## Installing

Open a commander console at the Cash project root and run the command :

* npm install

## Utilisation

In the Cash folder.

### Usage:

* node bin/index.js \<amount\> \<currency\>

* node bin/index.js \<command\>

### Commands:
* --save,  -s       Save currencies as default currencies
* --help,  -h       Display help message
* --version,  -v     Display version number

#### Examples

    node bin/index.js 1 usd eur // returns √ 0.81 (EUR) Euro
    node bin/index.js 1 usd aud rub cad // returns √ 1.28 (AUD) Australian Dollar √ 56.86 (RUB) Russian Rouble √ 1.29 (CAD) Canadian Dollar

All supported currencies are available here : [Currencies](https://github.com/xxczaki/cash-cli/blob/master/lib/currencies.json)

## Authors

* **Yassine AZZOUT** - *Initial work* - [3-musketeers](https://github.com/92bondstreet/3-musketeers)


