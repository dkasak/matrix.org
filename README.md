# Matrix.org Website

To discuss maintenance of this site, please come talk to the team in [#matrix.org-website:matrix.org](https://matrix.to/#/#matrix.org-website:matrix.org).

### How to build

0. Make sure you have the prerequisites:
   - [Yarn](https://yarnpkg.com/en/)
   - [Gatsby](https://www.gatsbyjs.org/): `npm i -g gatsby-cli`
   - `git clone https://github.com/matrix-org/matrix.org && cd matrix.org`
1. `cd gatsby`
1. Run `yarn` to install dependencies
1. `gatsby develop`

Now you can visit the page you want to work on in the browser. For example: http://127.0.0.1:8000/docs/projects/try-matrix-now/

### How to add your project to Try Matrix Now

0. Prerequisites:
   - Text editor or web IDE ([MDX](https://mdxjs.com/) support is nice to have
     but not necessary)
   - `git clone https://github.com/matrix-org/matrix.org && cd matrix.org`
1. `cd gatsby`
1. `cp project-template.mdx content/projects/date-project-name.mdx` The name of the file should be the start date of your project followed by the name of the project. For example: `2019-03-13-pattle.mdx`
1. Edit the file to include information about your project
1. To include images in your posting, add them to `static/docs/projects/images/`. Avoid linking to images on other websites.
1. To check how the rendered result looks (strongly recommended), follow "How to build" steps.
1. Once it looks good, submit a pull request!
