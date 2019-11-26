## 1.1.1 (2019-11-20)

### Bug fixes

The file referred to in the package's `module` field now is compiled down to ES5.

Rename ES module files to use a .js extension, since Webpack gets confused by .mjs

## 1.1.0 (2019-11-08)

### New features

Add a `module` field to package json file.

## 1.0.5 (2018-07-19)

### Bug fixes

Fix issue where menu items would still execute their command when clicked even if disabled.

## 1.0.4 (2018-03-09)

### Bug fixes

Fixes a bug that prevented the menu bar from properly unregistering its `"scroll"` event handlers when destroyed.

## 1.0.3 (2018-02-15)

### Bug fixes

The floating menu bar now works better in a scrollable parent node.

## 1.0.2 (2018-01-17)

### Bug fixes

Make the `render` property of a menu item spec work as documented again.

## 1.0.1 (2017-10-18)

### Bug fixes
    
The menu no longer flips enabled/disabled styles on each update in IE11.

## 1.0.0 (2017-10-13)

First stable release.