---
categories: [Blogging]
tags: [github-pages, blog, personal blog, jekyll]
description: Host free personal blogging website on github with simple steps. Creating blog post with simple markdown files and display it with build-in beautiful responsive ui design.

image:
  path: /assets/img/blog-page-screenshot.png
  alt: blog page screenshot
---
# Want to setup personal blog page like this?
## Copy template 
- Go to this repo <br>
    🔗 [https://github.com/cotes2020/chirpy-starter](https://github.com/cotes2020/chirpy-starter)
    

- Click on `Use this template` button and then `Create a new repository`
- Give the repo name as `<your_github_username>.github.io`

## Run it locally
- Clone the repo 
- Install Ruby on your machine and verify using this code 
    ```bash
    ruby --v
    ```
- Open the repo directory in terminal and run the code to install the dependencies
    ```bash
    bundle
    ```
- Run the website locally for testing
    ```bash
    bundle exec jekyll serve
    ```

## Update the blog profile
- Open `_config.yml` file in any code editor
    ```
    .
    ├── _config.yml <------- this file
    ├── _data
    ├── _plugins
    ├── _posts
    ├── _site
    ├── _tabs
    ├── assets
    ├── Gemfile
    ├── Gemfile.lock
    ├── index.html
    ├── LICENSE
    ├── README.md
    └── tools
    ```
- Change the `title`, `tagline`, `description`, and your social usernames
- Set `url` as 
    ```
    https://<your_github_username>.github.io
    ```
- Push the updates to Github

# Add your first blog
- Create new markdown file inside `_posts` directory
    ```
    .
    ├── _config.yml 
    ├── _data
    ├── _plugins
    ├── _posts <------- this directory
    ├── _site
    ├── _tabs
    ├── assets
    ├── Gemfile
    ├── Gemfile.lock
    ├── index.html
    ├── LICENSE
    ├── README.md
    └── tools
    ```
- file name should be in this format
    ```
    <YYYY-MM-DD>.your_blog_title.md
    ```
- Open the file in editor (like `vscode`) and these two lines at the top
    ```md
    ---
    categories: [Your, Categories]
    tags: [tags, related, to, your, blog]
    ---
    ```
- Then add rest of the content as write a markdown file
- Preview the blog post locally using this command
    ```bash
    bundle exec jekyll serve
    ```
- Commit the changes and push updates on Github
- Check your live website on 
    ```
    https://<github_username>.github.io
    ```
    