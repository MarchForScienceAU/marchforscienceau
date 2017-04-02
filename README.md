# March for Science Australia

## SCIENCE, NOT SILENCE

The March for Science celebrates the public discovery, distribution, and understanding of scientific knowledge as crucial to the freedom, success, health, and safety of life on this planet.

We are a nonpartisan group, marching to demand action in the following areas:
Literacy, Communication, Policy, and Investment.

## About this site

This is a jekyll site hosted for free using [GitHub Pages](https://pages.github.com/) with SSL provided for free by [Cloudflare](https://www.cloudflare.com). The domain was purchased via [Name Silo](https://www.namesilo.com) and the theme is a modified fork of the free [New Age](https://github.com/BlackrockDigital/startbootstrap-new-age) template created by [Start Bootstrap](https://startbootstrap.com/).

Google Analytics is also used.

Feel free to fork this repository to create your own March for Science website.

More information about how to get started:

  * [Setting up Github Pages for your organistation](https://help.github.com/articles/user-organization-and-project-pages/)
  * [Using a custom domain with GitHub Pages](https://help.github.com/articles/using-a-custom-domain-with-github-pages/)
  * [Setting up SSL for Github pages with Cloudflare](https://blog.cloudflare.com/secure-and-fast-github-pages-with-cloudflare/)


## Installation

###Gulp

This is used to compile the JS and CSS.

```BASH
npm install gulp-cli -g
npm install gulp -D
```

### Jekyll

Used to generate the static site for local development and testing.

```BASH
gem install jekyll bundler
```

### Testing

Once these are installed, from the root of the site you can run:

```BASH
gulp && bundle exec jekyll serve
```

This will both compile the JS/CSS and generate the static site files for local testing.

If you change any JS or CSS you will need to restart this service. HTML/MD files will be automatically regenerated on save.
