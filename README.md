# Template Symfony 6 + Vue 3

This is a template to get started on a new Symfony/Vue3 project, everything is already set up and good to go.

## Symfony Setup

```sh
composer install
```

### Compile and Hot-Reload for Development

```sh
symfony serve
```

## Vue Setup

```sh
npm install
```

### OR

```sh
yarn install
```

### Compile and Minify for Production

```sh
npm run watch
```

---

## FAQ

### 1. Parse error: syntax error, unexpected '?'

Create a .php-version file and simply type in your php version to fix the error

#### Example :
```sh
8.1.3
```

### 2. Database

Change the database path in the .env file, and don't forget to add the .env file to your .gitignore
