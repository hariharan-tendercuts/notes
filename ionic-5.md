Ionic 4 to 5 changes:

Package changes: 
https://ionicframework.com/docs/reference/migration#migrating-from-ionic-4-x-to-ionic-5-x

Breaking changes:
https://github.com/ionic-team/ionic-framework/blob/master/BREAKING.md#version-5x

Ionic 3 to 4 changes:

Full guide:
[https://ionicframework.com/docs/reference/migration#migrating-from-ionic-3-0-to-ionic-4-0](https://ionicframework.com/docs/reference/migration#migrating-from-ionic-3-0-to-ionic-4-0)

Package Change:
https://ionicframework.com/docs/reference/migration#changes-in-package-nam

Josh Morony Guide: 
https://www.joshmorony.com/my-method-for-upgrading-from-ionic-3-to-ionic-4/

1. Module Structure.
2. All dependencies should to upgraded to LTS

Modules:
1. Orders tab -> Go Online,Store Picker,Go Offline, Order Scan, Order viewing, Order Complete, Cash Collection
2. Trips tab -> 
3. Trip Sheets tab -> 
4. Profile tab -> 

Our app specific changes:
HTML:
1. change all tap events to click.

SCSS:
color: color($colors, 'primary') to var(--ion-color-primary)
color: color($colors, 'mid-light') -> var(--ion-color-mid-dark)
color: color($colors, 'mid-dark')` -> `var(--ion-color-mid-light);
