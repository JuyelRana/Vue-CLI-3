# Vue CLI Version 3

**Vue CLI is a full system for rapid Vue.js development** (https://cli.vuejs.org/)

## Creating a Project

Old cli: 
> vue init webpack-simple myapp

new cli: 
> vue create myapp

**Webpack Configuration**
- Webpack config abstracted away (hidden)
- Tweak webpack config in vue.config.js
- Plugins can edit the webpack config too

## Plugins
- Extend the config & functionality of our app
- Like normal dependencies, but can also:
      - Edit the webpack config
      - Edit source files (e.g. templates)
      - Add extra commands to the CLI	 

## Instant Prototyping 
- Rapidly protype single, standalone components
- No need to set up a Vue project to develop single components
- Good when you quicly want to work on an idea 	  

## Graphical User Interface
- Easily create and manage projects
- Manage and install dependencies & plugins.