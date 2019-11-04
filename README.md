# Webpack 
_______________________

## What is this?

This repository is dedicated to me learning **webpack** .
I will try to do a summary of what I've learned, what I've done and what I plan on doing with the knowledge I've gathered. 

The plan is to learn as much as I can and document my trip down the webpack lane. 

## 1. Basic setup

The first thing I did was to create a directory.
Navigate to your desired folder and do the following : 
> **mkdir webpack-demo**

Navigate into your created folder :
> **cd webpack-demo**

Initialize your package.json with : 
> **npm init -y**

And lastly, we need to install **webpack** locally, which will initially install the webpack-cli as well. 
> **npm install webpack webpack-cli --save-dev** 

## 2. Creating a bundle

After setting up my directory and file structure, I had to separate the **/dist** from the **/src** - or better yet, *distribution* from *source* files. 

Afterwards, my folder structure looked like : 

```
  webpack-demo
  |- package.json
+ |- /dist
+   |- index.html
  |- /src
    |- index.js
```

We're going to install **lodash** library as a dependency, it'll help us to execute certain JavaScript functionalities with ease.

```npm install --save lodash```

> When installing a package that will be bundled into your production bundle, you should use npm install --save. If you're installing a package for development purposes (e.g. a linter, testing libraries, etc.) then you should use npm install --save-dev. More information can be found in the npm documentation.

After this, the only script we need in our index.html is : 

> <script src="main.js"></script>

With that said, when we run **npx webpack**, which will take our script at **src/index.js** as the entry point, and will generate **dist/main.js** as the output.

## 3. Modules

View [Modules](https://webpack.js.org/guides/getting-started/#modules) for more information!

## 4. Webpack.config