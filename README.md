# What is it and why
This Conf-Boilerplate theme is an [Harmonic](https://github.com/JSRocksHQ/harmonic)'s theme aiming to be a simple replacement for the [Conf Boileplate](https://github.com/braziljs/conf-boilerplate) project.  
It is still in beta, but it's working just fine, like the old one.  
The original Conf Boilerplate was developed using [DocPad](https://docpad.org/). DocPad is awesome, but it covers a lot of features we don't want to use.  
Also, now we're using [Harmonic](https://github.com/JSRocksHQ/harmonic), a simple, but powerful static site generator built with the modern JavaScript.

# How to use it
First of all, you'll need to install Harmonic.  
As Harmonic is a [Node.js](http://nodejs.org/) based project, obviously, you'll need to install it.  
```shell
npm install harmonic -g
```
Now, init your new conference website:
```shell
harmonic init my_awesome_conf
```
Install conf boilerplate theme:
```shell
cd my_awesome_conf
npm install harmonic-theme-conf-boilerplate --save
```
Change your theme in `harmonic.json` file:
```json 
"theme": "harmonic-theme-conf-boilerplate"
```
Run:
```shell
harmonic run
```
