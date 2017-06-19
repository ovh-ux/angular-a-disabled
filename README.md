# angular-a-disabled
_How to disable my link ?_

## Features

 * Disable `href`/`sref`/`ng-href` link event

## How to use it?

``` bash
bower install ssh://git@github.com:ovh-ux/angular-a-disabled.git --save
```

Include the module `angular-a-disabled` in your project and follow the example below.

### Example

```html
<!-- Link disabled if myCondition === true -->
<a a-disabled="myCondition"
    href="myLink">
    Go to my link
</a>
```

```css
a.disabled {
    background-color: grey;
    cursor: not-allowed;
}
```
