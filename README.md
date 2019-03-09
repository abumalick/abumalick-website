[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg)](https://github.com/prettier/prettier)

# ASBAB website

> Our company website

Bootstraped with https://github.com/EmaSuriano/gatsby-starter-mate

## Features 🛠

- [Gatsby v2](https://www.gatsbyjs.org/)
- [Rebass 3.0 🎉](https://rebassjs.org/): styled component system
- [React Reveal](https://www.react-reveal.com/)
- Dynamic content from [Contentful](https://contentful.com)
- Offline support
- PWA ready
- SEO
- Responsive design
- Icons from [font-awesome](https://fontawesome.com/)
- [Netlify](https://www.netlify.com) Deployment Friendly
- Developer tools:
  - eslint
  - prettier
- Google Analytics

## How to start ▶️

You will need our contentful token to be able to build the site locally

If you never used Gatsby before, I highly recommend you to [Set up your development environment](https://www.gatsbyjs.org/tutorial/part-zero/)!

You can start developing on the project with

```bash
yarn start
```

## Update from upstream 💡

In case you cloned this repository before and you want all the latest changes of it, you can execute the following command to update the code in your repository with the one in this repository:

```bash
# Add repository remote entry
$ git remote add mate https://github.com/EmaSuriano/gatsby-starter-mate

# Get changes from master branch of gatsby-starter-mate
$ git pull mate master --allow-unrelated-histories

# Reset changes in unnecesary folder/files
$ git reset media/ bin/ README.md manifest-config.js

# Remove files affected by the reset
$ git checkout .

# In this step you migth need to fix a lot of conflicts, you can do fix manually or use just accept all the changes from mate
$ git checkout --theirs .

# WATCH OUT that some configuration can be overwritten in this last step, like package.json, colors, etc. I highly recommend to do an overall look up at the end of fixing the conflicts.

# Install in case there is any new dependency added to the starter
$ yarn

# Build the project to see if everything is working as expected
$ yarn build
```

## License 📝

MIT.
