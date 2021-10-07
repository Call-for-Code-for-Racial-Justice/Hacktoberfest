[![Community](https://img.shields.io/badge/Join-Community-blue.svg)](https://callforcode.org/slack) [![Hacktoberfest](https://img.shields.io/badge/Celebrate-Hacktoberfest-orange.svg)](https://call-for-code-for-racial-justice.github.io/Hacktoberfest/#/?id=main)

# Hacktoberfest

[Handbook for Call for Code for Racial Justice Hacktober Projects](https://call-for-code-for-racial-justice.github.io/Hacktoberfest)

## Prerequisites

- `Node.js`

  Version 14.x is the current LTS (2021-09-29)

- `npm`

## Run locally

1. Clone the repo.

2. It is recommended to install docsify-cli globally, which helps initializing and previewing the website locally.

   ```
   npm install docsify-cli -g
   ```

   **Optional 1**: if you prefer to install `docsify` locally.

   ```
   npm install
   ```

   **Optional 2**: you can also use docsify without installing the package, later on, with `npx docsify <command>`.

3. Preview the site

   ```
   npm start
   ```

   **Optional 1**: without docsify globally installed, use the following command

   ```
   npx docsify serve docs
   ```

4. You can preview your site in your browser on `http://localhost:3000`

## Check with prettier

For a simple check you can use

```
npm run prettier
```

If you want prettier to try and fix problems, use

```
npm run prettier-fix
```
