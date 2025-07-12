# Installing SASS: My Step-by-Step Guide

Here's how I installed SASS on my system using Node.js and npm.

## Step 1: I Installed Node.js

First, I went to the [Node.js official website](https://nodejs.org/) and downloaded the latest LTS version for my operating system.

After installation, I confirmed it worked by running:

```bash
node -v
npm -v
```

## Installing SASS Globally

Next, I installed SASS globally on my machine using npm. I ran the following command in the terminal:

```bash
npm install -g sass
```

## Confirmed the installation

Once the installation finished, I verified that SASS was installed by checking its version:

```bash
sass --version
```

## Compilation of the SCSS into CSS

I use the 'watch' flag to auto compile individual scss file and the all scss files contained in a directory

**For individual file:**

```bash
sass --watch style.scss:style.css
```

**For list of scss files contained in a directory**

```bash
sass --watch scss/:css/
```

## Uninstalling the SASS

The below command was used to uninstall the SASS

```bash
npm uninstall -g sass
```
