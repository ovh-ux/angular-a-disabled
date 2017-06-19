
How to disable my link

:warning: Deprecated
 
[![Build Status](https://travis-ci.org/ovh/angular-a-disabled.svg)](https://travis-ci.org/ovh/angular-a-disabled)

```javascript
angular.module("myApp", ["angular-a-disabled"]);
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

    bower install ssh://git@github.com:ovh-ux/angular-a-disabled.git --save

## NPM

    npm install ssh://git@github.com:ovh-ux/angular-a-disabled.git --save
 
## Get the sources
 
```bash
    git clone https://github.com/ovh/angular-a-disabled.git
    cd angular-a-disabled
    npm install
    bower install
```
 
You've developed a new cool feature ? Fixed an annoying bug ? We'd be happy
to hear from you !

Have a look in [CONTRIBUTING.md](https://github.com/ovh-ux/angular-a-disabled/blob/master/CONTRIBUTING.md)
 
## Run the tests
 
```
npm test
```
 
## Build the documentation
 
```
grunt docs
```
 
# Related links
 
 * Contribute: https://github.com/ovh/angular-a-disabled
 * Report bugs: https://github.com/ovh/angular-a-disabled/issues
 * Get latest version: https://github.com/ovh-ux/angular-a-disabled
 
# License
 
See https://github.com/ovh/angular-a-disabled/blob/master/LICENSE