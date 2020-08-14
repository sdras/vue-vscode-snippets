# Vue VSCode Snippets

![vue-snippet-hero](https://s3-us-west-2.amazonaws.com/s.cdpn.io/28963/vue-snippet-hero.gif)

## Description

These snippets were built supercharge a workflow in the most seamless manner possible.

This repo was built particularly for real world use. It doesn't catalogue the API definitions, rather, it focuses on developer ergonomics from the point of Vue of real world use. Included are the pieces I personally get sick of typing, and boilerplate that is helpful to stub out quickly.

_Versions Supported: Vue 2 and Vue 3_

![SnippetDemo](https://s3-us-west-2.amazonaws.com/s.cdpn.io/28963/SnippetDemo.gif)

## Installation

_Either_

- click the extensions button (lowest square icon in the editor), and type in Vue VSCode Snippets, select the one by sdras

_or_

- go here [vscode Extensions Marketplace](https://marketplace.visualstudio.com/items?itemName=sdras.vue-vscode-snippets)

```javascript
ext install Vue VSCode Snippets
```

You can enable tab completion (recommended) by opening `Code > Preferences > Settings` (on a Mac) and applying `"editor.tabCompletion": "onlySnippets"` to your personal settings

## Snippets

### Vue

| Snippet            | Purpose                                                      |
| ------------------ | ------------------------------------------------------------ |
| `vbase`            | Single file component base with SCSS                         |
| `vbase-3`          | Single File component Composition API with SCSS              |
| `vbase-3-reactive` | Single File component Composition API with Reactive and SCSS |
| `vbase-css`        | Single file component base with CSS                          |
| `vbase-pcss`       | Single file component base with PostCSS                      |
| `vbase-styl`       | Single file component base with Stylus                       |
| `vbase-ts`         | Single file component base with Typescript                   |
| `vbase-ts-class`   | Single file component base with Typescript Class Format      |
| `vbase-3-ts`       | Single File component Composition API with Typescript        |
| `vbase-ns`         | Single file component with no styles                         |
| `vbase-sass`       | Single file component base with SASS                         |
| `vbase-less`       | Single file component base with LESS                         |

### Template

| Snippet           | Purpose                             |
| ----------------- | ----------------------------------- |
| `vfor`            | v-for directive                     |
| `vmodel`          | Semantic v-model directive          |
| `vmodel-num`      | Semantic v-model number directive   |
| `von`             | v-on click handler with arguments   |
| `vslot-named`     | Named slot                          |
| `vel-props`       | Component element with props        |
| `vsrc`            | Image src binding                   |
| `vstyle`          | Inline style binding                |
| `vstyle-obj`      | Inline style binding with objects   |
| `vclass`          | Class binding                       |
| `vclass-obj`      | Class binding with objects          |
| `vclass-obj-mult` | Multiple conditional class bindings |
| `vanim`           | Transition component with JS hooks  |
| `vnuxtl`          | Nuxt Routing Link                   |
| `vroutename`      | router-link Named Routing           |
| `vroutenameparam` | router-link Named with Parameters   |
| `vroutepath`      | router-link Path Routing Link       |
| `vemit-child`     | Emit event from child component     |
| `vemit-parent`    | Emit event to parent component      |

### Script

| Snippet           | Purpose                                                                  |
| ----------------- | ------------------------------------------------------------------------ |
| `vdata`           | Component data as a function                                             |
| `vmethod`         | Vue method                                                               |
| `vcomputed`       | Vue computed property                                                    |
| `vwatcher`        | Vue watcher with new and old value args                                  |
| `vbeforecreate`   | beforeCreate lifecycle method                                            |
| `vcreated`        | created lifecycle method                                                 |
| `vbeforemount`    | beforeMount lifecycle method                                             |
| `vmounted`        | vmounted lifecycle method                                                |
| `vbeforeupdate`   | beforeUpdate lifecycle method                                            |
| `vupdated`        | updated lifecycle method                                                 |
| `vbeforedestroy`  | beforeDestroy lifecycle method                                           |
| `vdestroyed`      | destroyed lifecycle method                                               |
| `vprops`          | Props with type and default                                              |
| `vimport`         | Import one component into another                                        |
| `vimport-dynamic` | Import one component that should be lazy loaded by webpack               |
| `vcomponents`     | Import one component into another within the export statement            |
| `vimport-export`  | Import one component into another and use it within the export statement |
| `vmapstate`       | import mapState from Vuex into vue component component                   |
| `vmapgetters`     | import mapGetters from Vuex into vue component component                 |
| `vmapmutations`   | import mapMutations from Vuex into vue component component               |
| `vmapactions`     | import mapActions from Vuex into vue component component                 |
| `vfilter`         | Vue filter                                                               |
| `vmixin`          | Create a Vue Mixin                                                       |
| `vmixin-use`      | Bring a mixin into a component to use                                    |
| `vc-direct`       | Vue create a custom directive                                            |
| `vimport-lib`     | Import a library                                                         |
| `vimport-gsap`    | Import GreenSock                                                         |
| `vanimhook-js`    | Using the Transition component JS hooks in methods                       |
| `vcommit`         | Commit to Vuex store in methods for mutation                             |
| `vdispatch`       | Dispatch to Vuex store in methods for action                             |
| `vtest`           | A simple unit testing component                                          |

### Vue Composition API

| Snippet             | Purpose                                               |
| ------------------- | ----------------------------------------------------- |
| `v3reactive`        | Vue Composition API - reactive                        |
| `v3reactive-setup`  | Vue Composition API - reactive with setup boilerplate |
| `v3computed`        | Vue Composition API - computed                        |
| `v3watch`           | Vue Composition API - watcher single source           |
| `v3watch-array`     | Vue Composition API - watch as array                  |
| `v3watcheffect`     | Vue Composition API - watchEffect                     |
| `v3ref`             | Vue Ref                                               |
| `v3onmounted`       | Lifecycle hook - onMounted                            |
| `v3onbeforemount`   | Lifecycle hook - onBeforeMount                        |
| `v3onbeforeupdate`  | Lifecycle hook - onBeforeUpdate                       |
| `v3onupdated`       | Lifecycle hook - onUpdated                            |
| `v3onerrorcaptured` | Lifecycle hook - onErrorCaptured                      |
| `v3onunmounted`     | Lifecycle hook - (destroyed) onUnmounted              |
| `v3onbeforeunmount` | Lifecycle hook - (beforeDestroy) onBeforeUnmount      |
| `v3useinoptions`    | Use Composition API in Options API                    |

### Vuex

| Snippet         | Purpose                        |
| --------------- | ------------------------------ |
| `vstore`        | Base for Vuex store.js         |
| `vgetter`       | Vuex Getter                    |
| `vmutation`     | Vuex Mutation                  |
| `vaction`       | Vuex Action                    |
| `vmodule`       | Vuex Module                    |
| `vstore-import` | Import vuex store into main.js |
| `vstore2`       | Updated Base for Vuex store    |

### Vue Router

| Snippet              | Purpose                                       |
| -------------------- | --------------------------------------------- |
| `vrouter`            | Vue Router base                               |
| `vscrollbehavior`    | Vue Router scrollBehavior                     |
| `vbeforeeach`        | Vue Router global guards beforeEach           |
| `vbeforeresolve`     | Vue Router global guards beforeResolve        |
| `vaftereach`         | Vue Router global guards afterEach            |
| `vbeforeenter`       | Vue Router per-route guard beforeEnter        |
| `vbeforerouteenter`  | Vue Router component guards beforeRouteEnter  |
| `vbeforerouteupdate` | Vue Router component guards beforeRouteUpdate |
| `vbeforerouteleave`  | Vue Router component guards beforeRouteLeave  |

### Vue Config

| Snippet   | Purpose                                                              |
| --------- | -------------------------------------------------------------------- |
| `vplugin` | Import a plugin to main.js or plugins file                           |
| `vconfig` | vue.config.js file, example imports a sass file into every component |

### Nuxt Config

| Snippet | Purpose                                                 |
| ------- | ------------------------------------------------------- |
| `nfont` | link to include fonts in a nuxt project, in nuxt-config |
| `ncss`  | link to css assets such as normalize                    |

### Nuxt Page

| Snippet      | Purpose           |
| ------------ | ----------------- |
| `nasyncdata` | Nuxt asyncData    |
| `nfetch`     | Nuxt Fetch        |
| `nhead`      | Nuxt Head         |
| `nparam`     | Nuxt Route Params |

### Extra (plaintext)

| Snippet     | Purpose                 |
| ----------- | ----------------------- |
| `gitignore` | .gitignore file presets |

## Contributing

This is an open source project open to anyone. Contributions are welcome [github](https://github.com/sdras/vue-vscode-snippets)

If you are contributing a snippet, please be sure to add the documentation for it in the tables in the README, the pull request cannot be accepted without this addition. Thanks!
