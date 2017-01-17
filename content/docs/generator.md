---
title: "W20 generator"
type: "home"
zones:
    - "Documentation"
sections:
    - "W20Generator"
menu:
    W20Generator:
        weight: 999
---

To create a new W20 project from scratch, you need to have [NodeJS](https://nodejs.org) installed. 
To create a W20 application, run the following command:

```plain
npm install -g yo bower grunt-cli gulp generator-w20
 yo w20
```

{{% callout info %}}
This will install the `yo`, `bower`, `grunt-cli`, `gulp` and `generator-w20` NPM packages globally. You may prefer to
install some locally (in the project directory) by removing the `-g` option. The generator is based on [Yeoman](http://yeoman.io/).  
{{% /callout %}}

# Result

If the process is successful, you should see a structure similar to the following:

```plain
- bower_components       <-- dependencies
      
- fragments              <-- application fragments (one per directory)
    - ...
    
- bower.json
- index.html             <-- application master page
- w20.app.json           <-- application configuration
```

# More resources

* [W20 documentation](/docs).
* [Yeoman W20 generator](https://github.com/w20-framework/generator-w20).
