# gatsby-source-contentful

## IMPORTANT NOTICE

This is a fork of the [original repository](https://github.com/gatsbyjs/gatsby) containing a bug fix specific to [this issue](https://github.com/gatsbyjs/gatsby/issues/11364).

Do not use this package unless you're encountering that specific issue.

## Install

`npm install --save @nearform/gatsby-source-contentful`

## How to use

Follow the instruction of the official plugin. The only difference is in the package name, which needs to reflect in the gastby configuration file.

```javascript
// In your gatsby-config.js
module.exports = {
  plugins: [
    {
      resolve: `@nearform/gatsby-source-contentful`,
      options: {
        spaceId: `your_space_id`,
        // Learn about environment variables: https://gatsby.app/env-vars
        accessToken: process.env.CONTENTFUL_ACCESS_TOKEN,
      },
    },
  ],
}
```
