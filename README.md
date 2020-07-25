# ckeditor5-eskwela-app

## A custom CKEditor 5 build for Eskwela App.

-   Built from Balloon Block editor type.
-   Added Image Resize apart from plugins bundled with official ckeditor Balloon Block build.

### Installation

If you would like to try my custom build, get it here:

> yarn add @jayjaydluffy/ckeditor5-eskwela-app

### Addressing Heap Size Error on yarn build

-   Create a custom build (a balloon block type) using the instructions [here](https://github.com/ckeditor/ckeditor5/blob/72a64b941da2933d2e90ec3b1fab04d06500d3c7/docs/builds/guides/integration/advanced-setup.md).
-   Update **react** and **react-scripts** to latest (16.13.1 and 3.4.1, respectively, as of this writing). Node version should be 12 and up.
-   Deleted **node_modules** and **yarn.lock** then ran **yarn install** to reinstall all dependencies.
