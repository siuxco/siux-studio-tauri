<p align="center">
  <a href="https://siux.studio">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://i.imgur.com/WupINxY.png">
      <img src="https://i.imgur.com/CLmAowE.png#gh-light-mode-only" width="320">
    </picture>
  </a>
</p>

# SIUX Studio + Tauri integration
This is a boilerplate integration of [SIUX Studio](https://siux.studio) and [Tauri](https://tauri.app/)


## Getting started

##### Install Rust
```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs/ | sh
```

##### Run the development server
```bash
npm i && npm run tauri dev
```

##### Preview your application in browser

```bash
http://localhost:3000
```


## Installation

##### Integrate your brand styles by replacing the following lines of code on `pages/_app.js` with your brand settings.

```html
<link href="https://cdn.siux.studio/static/brand/632213d5a467b1178b31dde0/latest/siux.main.css" type="text/css" rel="stylesheet">
<link href="https://cdn.siux.studio/static/brand/632213d5a467b1178b31dde0/latest/siux.main.responsive.css" type="text/css" rel="stylesheet">
```

## Development

Edit the page by modifying `pages/index.js`. The page auto-updates as you edit the file. The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/) from the creators of [Next.js](https://nextjs.org/).

## Build binaries
```bash
npm run tauri build
```


## API Routes

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages. This endpoint can be edited in `pages/api/hello.js`.

```bash
http://localhost:3000/api/hello
```