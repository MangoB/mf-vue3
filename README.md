# mf-vue3
This is an example micro-frontend application repository,
For demonstrating how to use [Single-SPA](https://single-spa.js.org/) in this [article](https://medium.com/@a.sinlapakorn/%E0%B8%AA%E0%B8%A3%E0%B9%89%E0%B8%B2%E0%B8%87-micro-frontends-%E0%B8%94%E0%B9%89%E0%B8%A7%E0%B8%A2-single-spa-part-1-beginner-level-6644bf407d93) and this [article](https://medium.com/@a.sinlapakorn/%E0%B8%AA%E0%B8%A3%E0%B9%89%E0%B8%B2%E0%B8%87-micro-frontend-%E0%B8%94%E0%B9%89%E0%B8%A7%E0%B8%A2-single-spa-part-2-intermediate-level-72b7622e0540).

## Setup
To run this project, install it locally:

```
$ git clone https://github.com/MangoB/mf-vue3
$ cd mf-vue3
$ yarn
$ yarn serve
```

Finally, you only have to open http://localhost:9002 in a browser to see the app running
But it's will show Single-SPA from text, which you must use with the root application to see the real app running in http://localhost:9000/vue3

## Single-SPA applications
This application is a registered application that inits a Single-SPA application must use with the root application:

#### [mf-root](https://github.com/MangoB/mf-root), [mf-root-2](https://github.com/MangoB/mf-root-2)
These applications are the root of a micro-frontends project,
After running the root application and "mf-vue3" application has to open http://localhost:9000/vue3 in a browser to see the app running
