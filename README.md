# W20 framework website 
[![Build status](https://travis-ci.org/w20-framework/website.svg?branch=master)](https://travis-ci.org/w20-framework/website)

This repository contains the sources of the W20 framework website. 
The site is hosted at [http://w20-framework.github.io](http://w20-framework.github.io).

# Usage

After clone, you must initialize all the submodules:

    git submodule update --remote --recursive --init && git submodule foreach --recursive git checkout docs

This Website is built with [Hugo](http://gohugo.io/). If you have Hugo in your path you can serve it locally:

    hugo server
    
Add the `-w` flag to automatically watch the changes in content and refresh the displayed page(s) accordingly.

# Publication

The generated Website is automatically published on the w20-framework organization GitHub pages repository.

# License

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work by <span xmlns:cc="http://creativecommons.org/ns#" property="cc:attributionName">the W20 authors</span> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
