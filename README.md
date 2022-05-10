# Template Symfony 6 + Vue 3

   This is a template to get started on a new Symfony/Vue3 project, everything is already set up and good to go.

## Symfony Setup

```symfony
composer install
```

### Compile and Hot-Reload for Development

```symfony
symfony serve
```

## Vue Setup

```vue
npm install
```

### OR

```vue
yarn install
```

### Compile and Minify for Production

```vue
npm run watch
```

---

## FYI

1. #### Parse error: syntax error, unexpected '?'

   Create a ` .php-version ` file and simply type in your php version to fix the error

   Example : ` 8.1.3 `

2. #### Database

   Change the database path in the ` .env ` file, and don't forget to add the ` .env ` file to your .gitignore

3. #### Aliases

   ` @ ` refers to ` /{DIRECTORY}/assets ` path
   
4. #### PROD

   ` yarn run encore production ` to build
