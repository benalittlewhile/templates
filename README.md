# templates

Degit-compatible templates to help spin up new projects!

## Usage

### Requirements

- [npm](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm) (and
  by extension [node](https://nodejs.org/en/))

### Usage

Pick a template from [ the branches menu ](https://github.com/benalittlewhile/templates/branches) for this repo and make a
note of the branch name.

Open up your terminal and change to the directory you want to clone the template
into. The folder must be empty, as the contents of the template will be cloned
into the current directory.

Run the follwing command, substituting the branch name for the template you want
to clone:

    npx degit "benalittlewhile/templates#[branchName]"

For example, to clone the reactWind template I'd run `npx degit benalittlewhile/templates#reactWind` which would clone the contents of that
template inside the current directory. Note the double quotes if you're
using zsh, it doesn't like the # before the branch name so the quotes are required. (See the [ degit
](https://github.com/Rich-Harris/degit) repo for more information and other
syntax).

Wait a moment

Do the thing!

## Current Templates

| name      | branch                                                           | description                                                                                                                        |
| --------- | ---------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------- |
| reactWind | [branch](https://github.com/benalittlewhile/templates/tree/reactWind) | Quick starter based on [create-react-app](https://create-react-app.dev/) with added [ tailwind ](https://tailwindcss.com/) support |
| tsSvelteWind | [branch](https://github.com/benalittlewhile/templates/tree/tsSvelteWind) | [ vite ](https://vitejs.dev) + [svelte](https://svelte.dev) + [typescript](https://www.typescriptlang.org/) + [tailwind](https://tailwindcss.com) oh my!
| toDO      | ~                                                                | PRs Welcome!                                                                                                                       |