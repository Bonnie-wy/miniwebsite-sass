## Mini website with SASS

Traversy Media's Sass Crash Crouse tutorial on the fundamentals of Sass working with variables, mixin, functions, if else, looping etc. Click [link](https://youtu.be/nu5mdN2JIwM) to the tutorial.

### General Rules
1. When writing CSS, classes should be used, while IDs should be avoided.
2. Use the SCSS syntax, never the SASS syntax.
3. Use two spaces for indentation.
4. When using multiple selectors in the rule declaration, give each selector its own line.
5. When a margin or padding helper class needs to be used, first see if it could be incorporated into the elements CSS rules, to avoid having too many classes added to a single element.
6. Do not nest selectors more than 2 levels deep.

### setup
**In the terminal**
```
sudo npm i -g sass
sass --watch scss/style
```

**VS code extension**
Download Live Sass Compiler extension
Click `Watch Sass` to compile to css live

### References & Further readings
- [RSCSS](https://rscss.io/)
- https://dev.to/neshaz/basic-rules-of-rscss-and-bem-systems-4cpc