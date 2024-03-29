# Nuxt Food App
A fun and interactive website that gets restaurants data from a mock API and allows users to see their menus and add items (with / without addons) to cart, then giving individual and total cost of chosen items.

🌐 [visit the deployed website](https://nuxt-food-asser.netlify.app/) 

![welcome section](./assets/main_GIF.gif)

***
### 🏆 This project was done as a part of completeing a Nuxt.js course on [frontendmasters](https://frontendmasters.com/)
**I developed this website to challenge my knowledge and understanding of Vue.js and its meta framework Nuxt.js and some of their features such as:**
- global state management using vuex
- watchers
- computed 
- vuelidate 
- NuxtLink 

****

### 📔 Tech stack & External libraries:
- vue.js 3 
- Nuxt 2
- vuex for global state managament
- vuelidate
- uuid
****
### 🗝 Key features: 
- integration with an external API for restaurants data (this API was created on AWS by Sarah Draisner one of Vue.js maintainers).
- toasts to prompt user to choose add-ons if they are obligatory, and to notify when an item is added
- filtering restaurants by cuisine
- cart calculates total price.

![features](./assets/features.gif)

*****
### Build Setup

```bash
# install dependencies
$ yarn install

# serve with hot reload at localhost:3000
$ yarn dev

# build for production and launch server
$ yarn build
$ yarn start

# generate static project
$ yarn generate
```

For detailed explanation on how things work, check out the [documentation](https://nuxtjs.org).

### Special Directories

You can create the following extra directories, some of which have special behaviors. Only `pages` is required; you can delete them if you don't want to use their functionality.

#### `assets`

The assets directory contains your uncompiled assets such as Stylus or Sass files, images, or fonts.

More information about the usage of this directory in [the documentation](https://nuxtjs.org/docs/2.x/directory-structure/assets).

#### `components`

The components directory contains your Vue.js components. Components make up the different parts of your page and can be reused and imported into your pages, layouts and even other components.

More information about the usage of this directory in [the documentation](https://nuxtjs.org/docs/2.x/directory-structure/components).

#### `layouts`

Layouts are a great help when you want to change the look and feel of your Nuxt app, whether you want to include a sidebar or have distinct layouts for mobile and desktop.

More information about the usage of this directory in [the documentation](https://nuxtjs.org/docs/2.x/directory-structure/layouts).


#### `pages`

This directory contains your application views and routes. Nuxt will read all the `*.vue` files inside this directory and setup Vue Router automatically.

More information about the usage of this directory in [the documentation](https://nuxtjs.org/docs/2.x/get-started/routing).

#### `plugins`

The plugins directory contains JavaScript plugins that you want to run before instantiating the root Vue.js Application. This is the place to add Vue plugins and to inject functions or constants. Every time you need to use `Vue.use()`, you should create a file in `plugins/` and add its path to plugins in `nuxt.config.js`.

More information about the usage of this directory in [the documentation](https://nuxtjs.org/docs/2.x/directory-structure/plugins).

#### `static`

This directory contains your static files. Each file inside this directory is mapped to `/`.

Example: `/static/robots.txt` is mapped as `/robots.txt`.

More information about the usage of this directory in [the documentation](https://nuxtjs.org/docs/2.x/directory-structure/static).

#### `store`

This directory contains your Vuex store files. Creating a file in this directory automatically activates Vuex.

More information about the usage of this directory in [the documentation](https://nuxtjs.org/docs/2.x/directory-structure/store).
