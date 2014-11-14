
# ExtensionHelper

A nicer way to work with chrome extension API methods

## Examples

```js
var helper = require('stevenmiller888/extension-helper')();
helper.inject('index.js', 1);
```

```js
helper.setIcon('images/icon.png');
```

```js
helper.changeUrl('https://www.github.com');
```
## API

#### .onMessage(fn)
When a message is received, execute a callback.

#### .getCurrentTab(fn)
Get the current tab and execute a callback with the current tab passed in

#### .inject(name, id)
Inject a content script.

#### .onIconClicked(fn)
Execute a callback when the icon is clicked.

#### .onTabUpdated(fn)
When the tab is updated and the status is complete, execute a callback with the tabId passed in.

#### .setIcon(path)
Set the icon.

#### .onAddressBarChanged(fn)
When the address bar is changed, execute a callback

#### .changeUrl(url)
Change the current tab url

## License

```
WWWWWW||WWWWWW
 W W W||W W W
      ||
    ( OO )__________
     /  |           \
    /o o|    MIT     \
    \___/||_||__||_|| *
         || ||  || ||
        _||_|| _||_||
       (__|__|(__|__|
```
