# NPM package POC (Prove Of Concept)

## NPM [full official docs](https://docs.npmjs.com/packages-and-modules)

---

## Packages used

1. [short-itt](https://github.com/safwat-fathi/short-itt) package.

## Changes history

1. using the package after publishing to NPM & installing it in our project.

![using package](./screenshots/using-package.png)

2. update the package from **node_modules** within our project. Which will not make any diffrence in our package on NPM.

**Note: if these changes applied to the package codebase itself skip to step 4.**

![edit the package 1](./screenshots/edit-the-pack-1.png)

![edit the package 2](./screenshots/edit-the-pack-2.png)

3. copy the cahnges and paste it on our package codebase.

![edit the package](./screenshots/update-the-pack-in-main-codebase.png)

4. update package version.

![update package version](./screenshots/update-pack-version.png)

![update pack to latest](./screenshots/update-pack-to-latest.png)

---

**Note: that the package is entirley seperate from our codebase, meaning that any change made on package within node_modules directory must be copied & pasted by hand.**
