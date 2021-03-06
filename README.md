# 🆗 OK.css

**OK.css** is a
[classless CSS framework](https://css-tricks.com/no-class-css-frameworks/) that adds sensible styling defaults to your web page. Adding it into your HTML will make your page look decent — no need to reference documentation, think about responsiveness, or account for browser differences as long as your markup is semantically-correct.

To use it, you can [download the CSS file directly](https://okcss.netlify.app/ok.min.css) or add the following line to your HTML `<head>`:

```
<link rel="stylesheet" href="https://okcss.netlify.app/ok.min.css" />
```

**OK.css** is somewhere between a CSS normalizer and a full-fledged framework like [Bootstrap](https://getbootstrap.com/)</a> or [Tailwind](https://tailwindcss.com/)</a>. It's great for blogs or small single-page applications, but might not be so great for large, interactive apps that require JavaScript or custom elements.

## Development

Install dependencies with `yarn install`.

You can start a local server with `yarn start`. By default, the page will be available at `http://localhost:5000`.

Make updates to the CSS file in `./src/ok.css` and `yarn build` to create a minified version available in `./dist/ok.min.css`.

This repo is set up with [Netlify's continuous deployment](https://docs.netlify.com/configure-builds/get-started/). `yarn deploy` copies files into a `.gitignore`d directory called `_site` and `_site` is hosted on Netlify.

## Contributing

Pull requests are welcome! If you find a bug or have a feature request, please submit a GitHub issue.
