# Svelte TypeScript Rollup Mocha BoilerPlate!

This is intended to be a BoilerPlate starter kit to get up and running with
the following technologies wrapped into a ready to deploy project.

Svelte 3, TypeScript, Rollup, Babel, Prettier, GitHub Actions, Firebase Hosting, Mocha/Chai Testing

## Dependencies

The only requirements to run this template is to have node and npm installed.

## Setup

```zsh
git clone https://github.com/lineville/svelte-typescript-template
mv svelte-typescript-template <YOUR-PROJECT-NAME>
cd <YOUR-PROJECT-NAME>
npm i
npm run dev
```

## Testing

You can run tests in debug mode by using VSCode debugger with Ctrl F5 or running these commands.

```zsh
npm t
npm run coverage
```

## GitHub Actions w Firebase CI/CD

Create a new firebase project.

Copy Project ID to .firebaserc

Copy secret token by running this command and paste it into GitHub repo settings secrets.

```zsh
firebase login:ci
```
