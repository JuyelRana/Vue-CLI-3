# Vue CLI Version 3

## Vue-CLI3-Tutorial#02-Using the new cli

### 01. [Download](https://nodejs.org/en/download/) and install Nodejs 
```
Check nodejs version: node -v
```
### 02. Install and uninstall Vue CLI
```
 npm install -g @vue/cli
```
```
npm uninstall vue-cli -g 
```
### 03. Create new project
```
vue create project-name 
```
## Vue-CLI3-Tutorial#03-Using the new cli
### 04. Run command
```
Service run: npm run serve
```
```
Production Build: npm run build
```
```
Finding Errors: npm run lint
```
## Vue-CLI3-Tutorial#04-Custom Presets
### 05. Create new custom project
```
vue create project-name
```
```
Please pick a preset: Manually select features
```
```
Check the features needed for your project: Babel, Router, Vuex, CSS Pre-processors, Linter
```
```
Use history mode for router? (Requires proper server setup for index fallback in production) Yes
```
<p>
Pick a CSS pre-processor (PostCSS, Autoprefixer and CSS Modules are supported by default): Sass/SCSS (with node-sass)
</p>

```
Pick additional lint features: (Press <space> to select, <a> to toggle all, <i> to invert selection)Lint on save
```
```
Where do you prefer placing config for Babel, PostCSS, ESLint, etc.? In dedicated config files
```
```
Save this as a preset for future projects? Yes
```
```
Save preset as: juyel-custom2
```
## Vue-CLI3-Tutorial#05-Plugins
### 06. Add a new plugins

```
vue add plugin-name : vue add vuetify
```
## Vue-CLI3-Tutorial#06-Build and Deploy to Firebase
### 07. Go to [Firebas](https://firebase.google.com/) create a free account

- Create a new project
- Install firebase tools: npm install -g firebase-tools
- Check firebase version : firebase --version 
- Sign in to google : firebase login
- Initiate your project : firebase init 
- Deploy your website : firebase deploy

## Vue-CLI3-Tutorial#07-Instant Prototyping
- Global run vue: npm intall -g @vue/cli-service-global
- Run a global vue file : vue serve filename.vue --> vue serve online.vue

