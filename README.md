# Swig-Next  

This is an **unofficial, community-maintained fork** of [paularmstrong/swig](https://github.com/paularmstrong/swig). Our goal is to keep Swig’s original template syntax while bringing it up to date with the modern Node.js ecosystem. This fork provides:  

- Compatibility with **Node.js 18 and higher**  
- Security updates and dependency maintenance  
- **TypeScript** type definitions  
- Drop-in replacement for projects still using Swig v1  

## Features  

Swig-Next retains all of the original Swig features:  

- Available for Node.js and major web browsers  
- Express compatible  
- Object-oriented template inheritance  
- Filters and transformations within your templates  
- Automatic output escaping for safe HTML rendering  
- Flexible iteration and conditionals  
- Compact and robust core  
- Easily extended and customizable – see [Swig-Extras](https://github.com/paularmstrong/swig-extras) for examples  

## Installation  

Use npm to install the maintained version of Swig:  

```bash  
npm install swig-modern  
```  

Then require it in your project:  

```js  
const swig = require('swig-modern');  
// use swig.compile, swig.renderFile, etc.  
```  

## Migrating from `swig`  

To migrate from the original `swig` package:  

1. Replace `swig` in your `package.json` dependencies with `swig-modern`.  
2. Update your imports/`require` calls to use `swig-modern`.  
3. Run your test suite to ensure compatibility.  

## Documentation  

The original Swig documentation is still relevant and can be found on the [Swig Website](http://paularmstrong.github.io/swig/). We aim to maintain API compatibility, so existing guides should apply.  

## Contributing  

We welcome contributions! Please open an issue or submit a pull request if you have fixes, improvements or questions. This fork is community maintained; help keep Swig alive for projects that still depend on it.

## Project Homepage  
For documentation and updates, visit [lovart.info](https://lovart.info/).
