---
layout: documentation
title:  Building Applications TODO
order: 1000
---

**WARNING**: This information may be out of date.
If you know what is currently correct, please make a PR.

grunt task: `grunt build [--application=<application>] [--context=<context>]`

* application: the main script file of the application which is normally provided as parameter to the `phovea_web.js` file
* context: since absolute links are used, this may specify a context path, e.g. `/test` where the website is located

folder structure:

```bash
/config-gen.js ... generated
/phovea_web.js ... generated
/index.html ... generated
/bower_components/<libs>
/<plugins> ... compile css and ts and exclude them from making them public
```

