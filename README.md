Simple Node.js example app using [kickstart](https://github.com/semu/node-kickstart) for rapid development. [kickstart](https://github.com/semu/node-kickstart) adds handy settings to express with support for jade template rendering, less css processing and optional support for including ssl certificates.

    npm install kickstart
    node app.js

See app.js for setting application port and domain name.

### Preconfigured features

[kickstart](https://github.com/semu/node-kickstart) comes with some handy default configuration:

- jade template engine for files in `views/`
- automatic less processing for files in `/public/styles/`