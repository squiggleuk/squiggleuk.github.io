# William Hill Tech Blog

This is the source code that is used to build $techBlogURL. We're using Jekyll on GitHub Pages, with Sass for building stylesheets

---

## How to contribute
* Log in to GitHub with your own account, and create a [fork](https://help.github.com/articles/fork-a-repo/) of [this repo](http://repo.url)
* Clone the newly forked repo to your local machine
* Run `gem install bundler jekyll` to install Jekyll
* Run `bundle exec jekyll serve` from the local repo. This should build the site and run a webserver on [http://localhost:4000]
* Make your changes (Jekyll should rebuild the site when a file is modified)
* Commit and push your changes to your forked repo
* Create a [pull request](https://help.github.com/articles/creating-a-pull-request/) from your repo, to the main one we forked from
* Wait for your changes to be merged in

## Adding a new post
* If it's your first post, add your details to `_data/authors.yaml`
* If it's your first post, add an avatar image as `images/avatar-FIRSTNAME_LASTNAME.jpg` (100*100px)
* Create a new markdown file as `_posts/CHANNEL/YYYY-MM-DD-page-title.md`, this must contain the following attributes: title, categories, excerpt, author (referencing authors.yaml), layout=article, image:feature, image:teaser.
* Feature image should be 1024*256 and added to `images` with same name as the title attribute, and a `-feature.jpg` suffix
* Teaser image should be 534*334 and added to `images` with same name as the title attribute, and a `-teaser.jpg` suffix
