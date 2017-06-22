# ovh-angular-a-disabled

![OVH component deprecated](https://user-images.githubusercontent.com/3379410/27423263-520b94d8-5731-11e7-996a-f8579e70c33b.png)

![deprecated](https://img.shields.io/badge/status-deprecated-red.svg) [![Build Status](https://travis-ci.org/ovh-ux/ovh-angular-a-disabled.svg)](https://travis-ci.org/ovh-ux/ovh-angular-a-disabled)

[![NPM](https://nodei.co/npm/ovh-angular-a-disabled.png?downloads=true&downloadRank=true&stars=true)](https://nodei.co/npm/ovh-angular-a-disabled/)

How to disable my link

```javascript
angular.module("myApp", ["ovh-angular-a-disabled"]);
```

```html
<!-- Link disabled if myCondition === true -->
<a a-disabled="myCondition"
    href="myLink">
    Go to my link
</a>
```

# Installation

## Bower

    bower install ovh-angular-a-disabled --save

## NPM

    npm install ovh-angular-a-disabled --save

## Get the sources

```bash
    git clone https://github.com/ovh-ux/ovh-angular-a-disabled.git
    cd ovh-angular-a-disabled
    npm install
    bower install
```

You've developed a new cool feature ? Fixed an annoying bug ? We'd be happy
to hear from you !

Have a look in [CONTRIBUTING.md](https://github.com/ovh-ux/ovh-angular-a-disabled/blob/master/CONTRIBUTING.md)

## Run the tests

```
npm test
```

## Build the documentation

```
grunt docs
```

# Related links

 * Contribute: https://github.com/ovh-ux/ovh-angular-a-disabled
 * Report bugs: https://github.com/ovh-ux/ovh-angular-a-disabled/issues
 * Get latest version: https://github.com/ovh-ux/ovh-angular-a-disabled

# License

See https://github.com/ovh-ux/ovh-angular-a-disabled/blob/master/LICENSE
