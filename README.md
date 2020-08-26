# vue-spas

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Run your tests
```
npm run test
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

Step By Step Process: Tip/Note:
install these dependency 

# npm i --save-dev @fortawesome/fontawesome-free @fortawesome/fontawesome-svg-core @fortawesome/free-solid-svg-icons @fortawesome/vue-fontawesome bootstrap jquery popper.js firebase

To start server in development mode

## npm run serve

```
 The router links still has # keep in mind
 ```
 
 add to src/views/Home.vue file
```
  <div class="container text-center">
    <div class="row justify-content-center">
      <div class="col-10 col-md-10 col-lg-8 col-xl-7">
        <h4 class="display-4 text-primary mt-3 mb-2">Meeting Log</h4>
        <p class="lead">
          This simple app creates meetings, allows people to check in, and
          picks random users to award giveaways. It's a good example of a
          Single Page Application which includes connection to a database and
          routing. It's a practical way to learn
          <a href="https://vuejs.org/">Vue.js</a>
          with
          <a href="https://firebase.google.com">Firebase</a>.
        </p>

        <router-link
          class="btn btn-outline-primary mr-2"
          to="/register"
        >Register</router-link>
        <router-link
          class="btn btn-outline-primary mr-2"
          to="/login"
        >Log In</router-link>
        <router-link
          class="btn btn-primary"
          to="/meetings"
        >Meetings</router-link>
      </div>
    </div>
  </div>
  ```
 

