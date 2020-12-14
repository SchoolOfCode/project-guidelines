# Coding Practices

## Folder Structure

Below are two examples of typical folder structures for a CRA and an Express app. If using different technologies then remember to separate concerns so that your code is easy to navigate and easy to test.

### Front-end - Create React App

```
public/
src/
  components/
    App/
      App.module.css
      App.test.js
      App.stories.js
      index.js
    ...
  config/
    ...
    index.js
  utils/
    ...
    index.js
  index.css // global css rules
  index.js // root level (attaching with ReactDOM)
  serviceWorker.js
.gitignore
package.json
README.md
```

Notes:

- Folders are `camelCased`
  - Except for component folders, which are `PascalCased` so that we know components live in there
- You may wish to have a `pages/` folder (similar to gatbsy) where using React router you can contain pages and render them when needed. In this case, you may want a `Routing` folder which contains all of the routing logic.

### Back-end - Express

```
bin/
  www
data/
models/
public/
routes/
app.js
package.json
```
