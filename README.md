# Nuxt 3 Boilerplate

Look at the [Nuxt 3 documentation](https://nuxt.com/docs/getting-started/introduction) to learn more.

## Setup

Make sure to install the dependencies:

```bash
# yarn
yarn install

# npm
npm install

# pnpm
pnpm install --shamefully-hoist
```

## Commands

best practice to write clean code!

```bash
# check javascript / typescript linting
yarn lint:js

# check styles linting inside {css,scss,sass,html,vue} files
yarn lint:style

# check prettier in all project files; all but the files included inside `.prettierignore`
yarn lint:prettier

# check all three above options at once {lint:js, lint:style, lint:prettier}
yarn lint

# check and fix linting on all files
yarn lintfix

# install husky for git hooks `imporved commits and logs`
yarn prepare
```

## Editorconfig

you will need editorconfig plugin to use this option
[Install Editorconfig Plugin](https://editorconfig.org)

```bash
# edit .editorconfig file to adjuct to your needs
root = true

[*]
indent_style = space
indent_size = 2
end_of_line = lf
charset = utf-8
trim_trailing_whitespace = true
insert_final_newline = true

[*.md]
trim_trailing_whitespace = false
```

## Development Server

Start the development server on http://localhost:3000

```bash
npm run dev
```

## Production

Build the application for production:

```bash
npm run build
```

Locally preview production build:

```bash
npm run preview
```

Check out the [deployment documentation](https://nuxt.com/docs/getting-started/deployment) for more information.
