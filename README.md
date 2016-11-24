**Note:** This is a customized fork of the Material Design Lite project. You
might be looking for the [original project](https://github.com/google/material-design-lite.git).

## Modifications

  - [x] Patched `src/layout/_layout.scss` to match react-mdl’s
        [`_layout.scss`](https://github.com/react-mdl/react-mdl/blob/master/extra/_layout.scss).
  - [x] Customized palette colors in `src/_variables.scss`.

## Setup

```
git clone git@github.com:StyraInc/material-design-lite.git
cd material-design-lite
npm install
```

## Build

```
gulp
```

## Install

```
cp dist/*.css* /path/to/your/asset/folder
```
