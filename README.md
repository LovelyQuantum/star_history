# Star History

based on:https://github.com/timqian/star-history

## Website

![](https://raw.githubusercontent.com/timqian/images/master/star-history.gif)

## Extension

![](https://raw.githubusercontent.com/timqian/images/master/star-history-extension.gif)

> Note: You can [load the `./extension` folder to chrome](https://superuser.com/a/247654) to install the extension too.

## Access Token

Star-history use GitHub API to retrieve repository metadata. When user exceed the rate [limit of unauthenticated requests](https://developer.github.com/v3/#rate-limiting). Star-history will need your personal access token to unlimit it.

If you don't already have one, [create one](https://github.com/settings/tokens/new), and add to star-history (no scope to your personal data is needed)

## Before your first run
Make sure you have [nodejs](https://nodejs.org/en/) installed on your machine.
Then run following commands:
```bash
npm install
# If you are in china, try use cnpm to get fast experience
# https://github.com/cnpm/cnpm
cnpm insatll
```

## Develop

### Website

```bash
npm run startWebsite
```

### Extension

```bash
npm run buildExtension
# load the extension folder as unpacked extension into chrome to view it
```

## Build and Deploy
if you go there directly, install packages with above command first.

### Website

```bash
# deploy to star-history.t9t.io
npm run deployWebsite
```

### Extension

```bash
npm run buildExtension
# zip extension folder and publish to chrome web store
```

## Updates

- 2021-1-5: update README.md and some HTML change.
