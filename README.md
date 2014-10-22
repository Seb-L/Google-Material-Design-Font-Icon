Google-Material-Design-Font-Icon
================================

Font Icon based on Google Material Design Icon set (http://google.github.io/material-design-icons/).

## Install

```
bower install Google-Material-Design-Font-Icon
```

## Using

```
<link rel="stylesheet" href="bower_components/google-material-design-font-icon/material-design-font-icon.css">
```

## SASS Settings

in your main scss file:

```
@import 'bower_components/google-material-design-font-icon/scss/material-design-font-icon';
```

some variables can be overide (available in the _settings.scss file):

```
$md-general-class-name: 'mdi';
$md-prefix: 'ico';
$md-font-name: 'material-icons';
$md-font-path: './fonts';
```

You can also comment icon catégories to disable them in the _settings.scss file:

```
@import 'settings/categories/action';
@import 'settings/categories/alert';
@import 'settings/categories/av';
@import 'settings/categories/communication';
@import 'settings/categories/content';
@import 'settings/categories/device';
@import 'settings/categories/file';
@import 'settings/categories/hardware';
@import 'settings/categories/image';
@import 'settings/categories/map';
@import 'settings/categories/navigation';
@import 'settings/categories/notification';
@import 'settings/categories/social';
@import 'settings/categories/toggle';
```
