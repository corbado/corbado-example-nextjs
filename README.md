# Passkey-First Authentication Example for Next.js (TypeScript) with Corbado

This is a sample implementation of the Corbado web component being integrated into a web application built with Next.js.

Please see the [full blog post](https://www.corbado.com/blog/nextjs-passkeys) to understand the detailed steps needed to integrate passkeys into Next.js apps.

## File structure

- `src/app/page.tsx`: the file where the web component is embedded
- `pages/profile.tsx`: displays user information if the user has successfully authenticated
- `declarations.d.ts`: contains type declarations you need to add as well to make the web component work in TypeScript
- `.env`: add relevant environment variables that you can obtain
  from [Corbado developer panel](https://app.corbado.com/signin#register)

## Setup

### Prerequisites

Please follow the steps in [Getting started](https://docs.corbado.com/overview/getting-started) to create and configure
a project in the [Corbado developer panel](https://app.corbado.com/signin#register).

You need to have [Node](https://nodejs.org/en/download) and `npm` installed to run it.

### Configure environment variables

Use the values you obtained in [Prerequisites](#prerequisites) to configure the following variables inside an `.env`
file you create in the root folder of this project:

```sh
NEXT_PUBLIC_PROJECT_ID=<YOUR PROJECT ID>
API_SECRET=<YOUR API SECRET>
```

## Usage

Run

```bash
npm i
```

to install all dependencies.

Finally, you can run the project locally with

```bash
npm run dev
```
