---
title: Home page
home: true
actionText: VuePress Template →
actionLink: /
---
# How to install:
```
npm install
```

# How to run locally:
``` 
npm run dev
```

# How to contribute:
  1. If you are defining a new section just add a new folder
  2. Put new markdown file in appropriate folder
  3. Add the following to the header:
    ---
    title: {site title}
    ---
  4. Add remaining content to markdown file
    a. Run `git add .` to add any NEW files
  5. Run `git commit -am "{message explaining what was done}"`

  ::: tip
  Visit the vuepress [default-theme-config](https://vuepress.vuejs.org/default-theme-config/) for more information about YAML front matter configurations you can do per page.  
  **Note:** avoid the sidebar and navbar settings, we are currently using [vuepress-bar](https://www.npmjs.com/package/vuepress-bar) to generate our sidebar and navbar
  :::

# How to deploy:

For manual deployments just run the following command:
```
npm run deploy
```