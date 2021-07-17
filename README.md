# Elixir Book Club Landing Page

A simple web page for the Elixir Book Club.

### Getting Started

1) Run `yarn` to install dependencies
2) Run `npx live-server`


### Update Tailwind Styles
Whenever you update the `tailwind.js` file to add or adjust a style, you will need to regenerate the `assets/style.css` file by running:

```zsh
yarn build:css

# or for production

yarn build:prod:css
```