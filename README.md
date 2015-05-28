Express & Nunjucks Boilerplate
===

Express and Nunjucks.  Pow!

1. Installation
---

```
clone repository
npm install
node app.js
```

...then you should see this if you go to: `http://localhost:3000`

<img src="http://i.imgur.com/cHUoULb.png?1" style="border: solid #eee 1px">

2. Template structure
---

```
/
--- views/
------- layout.html  (the main layout template)
------- index.html   (extends layout.html and inserts content using {% block body %})
------- example.html (extends index.html and adds to {% block content %})
```

