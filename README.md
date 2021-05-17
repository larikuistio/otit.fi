# otit.fi

Website for Oulun Tietoteekkarit ry (University of Oulu CSE student guild)

Made with the [Hugo static site generator](https://gohugo.io/) and a slightly modified version of the [Hugo Mainroad theme](https://themes.gohugo.io/mainroad/).

Found at https://otit.fi

## Usage

- [Install Hugo](https://gohugo.io/getting-started/installing/)
  - Tested with version v0.80.0

- Run for development by issuing command *hugo server -D* in the root directory of this repository

- Generate the site for deployment by issuing command *hugo* in the root directory of this repository
  - The ready website is stored in the *public* directory. This is the website as served by the web server in production

## Basic repo structure
- *content* directory contains the website content in Markdown (.md) files
- *data* directory contains optional data files for the website. Not needed atm
- *archetypes* directory can be used to define default content types
- *layouts* is meant for html templates, but we don't need it now because we are using the Mainroad theme. A corresponding directory is found inside the theme directory.
- *static* contains static files such as images
- *resources* is meant for things such as css files, but like with *layouts* we don't need it because a corresponding directory is in the theme directory
- *public* directory contains the production ready website. This is the website as served by the webserver at https://otit.fi
  - Automatically generated by running the *hugo* command at the root directory of this repository
- *themes* is meant for hugo themes. *themes/mainroad* contains a slightly modified version of the [Mainroad theme](https://themes.gohugo.io/mainroad/), and that is used for this website.


There is extensive documentation of Hugo available at https://gohugo.io/documentation/