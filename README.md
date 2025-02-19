[Vue Socket.io]: https://github.com/MetinSeylan/Vue-Socket.io
# Nuxt-Sails

a [Sails](https://sailsjs.com) + [Nuxt](https://nuxtjs.org/) + [Vuetify](https://vuetifyjs.com/) application


This project was made as a concept proof of sails + nuxt working together and using Vuetify
as the ui framework

Prerequisites as far as I know:
- node 8
- eslint

and any other prerequisites of sails, nuxt and vuetify
the easiest way to give it a spin on dev mode is running it as the following

- `git clone https://github.com/hc-ekarisch/sails-nuxt.git`
- `npm install`
- `NODE_ENV=development node app.js --log.level=sily`

on windows just omit the `NODE_ENV` part
if you want to reload the serverside part of the framework consider `pm2` or `nodemon`

if you are using vscode it is pretty easy to debug the serverside
just press <kbd>F5</kbd> *(after npm install of course)* and that should get you up and running

### Production
After you have followed [Sails's Team Recomendations for production](https://sailsjs.com/documentation/concepts/deployment) just
run the `npm start` command and this should just work.


### Sails Links

+ [Sails framework documentation](https://sailsjs.com/documentation)
+ [Version notes / upgrading](https://sailsjs.com/documentation/upgrading)
+ [Deployment tips](https://sailsjs.com/documentation/concepts/deployment)
+ [Community support options](https://sailsjs.com/support)
+ [Professional / enterprise options](https://sailsjs.com/studio)

### Nuxt Links
- [Official Website](https://nuxtjs.org/)
- [Github Repos](https://github.com/nuxt)
- [twitter](https://twitter.com/nuxt_js)
- [Gitter Channel](https://gitter.im/nuxt/nuxt.js)
- [Vue (of course)](https://vuejs.org/)

### Vuetify Links
- [Official Website](https://vuetifyjs.com/)
- [Gitter Channel](https://gitter.im/vuetifyjs/Lobby/~chat#)
- [Twitter](https://twitter.com/vuetifyjs)
- [Github Repos](https://github.com/vuetifyjs/vuetify)
