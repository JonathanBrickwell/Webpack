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

## Creating a bundle

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
