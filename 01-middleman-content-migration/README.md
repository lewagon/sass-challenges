## Background & Objectives

The objective of this challenge is to migrate our poor HTML website into a nice Middleman project with templates and SASS. Start with a fork/clone of our [middleman boilerplate](https://github.com/lewagon/middleman-boilerplate)

## Start and deploy scripts

In this boilerplate, we provide you two scripts (for Mac and for Windows)

- **`osx_start.command`** (resp. **`windows_start.command`**) will start a local server to run your website and listen for change in your code. Just double-click this file to launch the server.
- **`osx_deploy.command`** (resp. **`windows_deploy.command`**) enables to deploy you website on Github Pages. Deployment is a bit trickier than before as your are now coding with templates and SASS. For this reason, your code has to be processed into pure HTML and CSS before being published. That's why we provide you this nice little script.

## Specs

In this challenge, you have to:

1. Migrate your home page **content** into the `index.html.erb` Middleman page
1. Create a new `contact.html.erb` page with team and contact infos

Before coding, **start your server** with the start script. Once you're done

1. Commit and publish you change using Github app.
1. Deploy your site with the deploy script.

## Tips & Resources

1. Don't forget to put all common HTML parts in the `layout.html.erb`
1. Don't forget to replace all `<a>` tags and `<img>` tags by **correct helpers**
