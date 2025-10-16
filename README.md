# Chrome Extensions samples

Official samples for Chrome Extensions and the Chrome Apps platform. (Chrome Apps are deprecated. Learn more [on the Chromium blog](https://blog.chromium.org/2020/08/changes-to-chrome-app-support-timeline.html)).

For more information on extensions, see [Chrome Developers](https://developer.chrome.com).

## Explore samples

The directory structure is as follows:

- [api-samples/](api-samples/) - extensions focused on a single API package
- [functional-samples/](functional-samples/) - full featured extensions spanning multiple API packages
- [\_archive/apps/](_archive/apps/) - deprecated Chrome Apps platform (not listed below)
- [\_archive/mv2/](_archive/mv2/) - resources for manifest version 2

You can also use the [Samples](https://developer.chrome.com/docs/extensions/samples/) page to discover extensions by type, permissions, and extension API.

## Installation

To experiment with these samples, please clone this repo and use 'Load Unpacked Extension'.
Read more on [Development Basics](https://developer.chrome.com/docs/extensions/mv3/getstarted/development-basics/#load-unpacked).

## Local development

The repository ships with an ESLint configuration that can be used to check every JavaScript
sample for common issues. After installing dependencies with `npm install`, run the linter with:

```bash
npm run lint
```

The command reports any formatting or syntax problems across the repository and exits with a
non-zero status if any issues are found.

## Contributing

Please see [the CONTRIBUTING file](/CONTRIBUTING.md) for information on contributing to the `chrome-extensions-samples` project.

## License

`chrome-extensions-samples` are authored by Google and are licensed under the [Apache License, Version 2.0](/LICENSE).
