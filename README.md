# shop-vue-vuex-cloudfront

See `develop` branch for development

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

### Run your unit tests
```
npm run test:unit
```

### Run your end-to-end tests
```
npm run test:e2e
```

### Lints and fixes files
```
npm run lint
```
- [S3 bucket](http://dragos-shop-vue-vuex-cloudfront.s3-website-us-east-1.amazonaws.com) to host and serve an application origin. Public access is denied via bucket policy.
- [CloudFront URL](https://d3q9u862kz1uu8.cloudfront.net) to serve the application from S3 bucket over HTTPs. 

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
