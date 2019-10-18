# packages

## Publish

```
// package.json
// ------------
"name": "@drivetopurchase/public-package-name",
"publishConfig": {
    "registry":"https://npm.pkg.github.com/"
},
"repository" : {
    "type" : "git",
    "url": "ssh://git@github.com/drivetopurchase/packages.git"
},
```

## Get packages
```
// .npmrc
// ------
registry=https://npm.pkg.github.com/drivetopurchase
// or
@drivetopurchase:registry=https://npm.pkg.github.com
```
