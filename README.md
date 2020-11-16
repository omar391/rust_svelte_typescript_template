# 🚧 Svelte Template

> Svelte + Rust WebAsm + Typescript + Parcel + Express

This repository is a template to allow Svelte to import a rust crate directly in it.

A change on the rust files on the crate triggers the Hot Module Reloading[HMR] and automatically reflects on the browser the changes done.

It is based on the awesome work by [hmmhmmhm](https://github.com/hmmhmmhm/svelte-template).

## Installation

You can install this template in at least three different ways:

1. Using `degit`:

`npx degit HugoDaniel/svelte-template my-svelte-project`

2. Using the "Use this template" GitHub button above

3. Just fork and clone it

After one of the above steps have been made, you have to:

-   `cd my-svelte-project`
-   `npm install`
-   `npm start`

## Command

-   npm start

    > Run the development server. This command creates a path accessible through HTTP and HTTPS. HTTP is applied with Hot Module Replacement (HMR). HTTPS has a built-in certificate for testing.

-   npm run build

    > Generate production build results. Minify is applied to the result and hmr is excluded.

-   npm run watch

    > Same as the npm start command, but does not serve the code with HTTP and HTTPS.

-   npm run clean

    > This command deletes all files in the 'dist' folder. However, the folder below the list is not deleted. If there is a static resource that should not be deleted, create a folder in the folder and use it.

## License

MIT Licensed

