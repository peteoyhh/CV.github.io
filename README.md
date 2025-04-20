# Pete Chen's Personal Website

Welcome! This is the source code for my personal website, built using [Jekyll](https://jekyllrb.com/) and hosted via GitHub Pages.

## 👋 About Me

I'm Pete Chen, a graduate student at the University of Illinois Urbana-Champaign studying Information Management. My interests lie in data analytics, visualization, and applying machine learning to real-world problems. This website is a place where I share selected projects, academic work, and some of my research interests.

## 🛠️ Features

- Project portfolio with visuals and descriptions
- Custom homepage with personal bio
- Responsive layout
- Built with Jekyll and Markdown
- Fully hosted on GitHub Pages

## 🚀 Getting Started

To build and run this site locally:

1. Install Ruby and Bundler
2. Clone the repo
3. Run `bundle install` to install dependencies
4. Run `bundle exec jekyll serve` to preview the site at `http://localhost:4000`

## 📁 Folder Structure

- `_projects/`: Project showcase content
- `_posts/`: Blog posts (if applicable)
- `_layouts/`, `_includes/`: Layout templates and components
- `assets/`: Images, CSS, and other static files
- `_config.yml`: Site settings

## 🌐 Live Website

You can view the site at: [https://yourusername.github.io](https://yourusername.github.io)

## 📫 Contact

If you'd like to connect, feel free to reach out via [email](mailto:xc24502@gmail.com).

## Sources

This is an amalgamation of [portfolYOU](https://github.com/YoussefRaafatNasry/portfolYOU) and [4dcu.be](https://github.com/4dcu-be/4dcu.be).

[portfolYOU](https://github.com/YoussefRaafatNasry/portfolYOU) was used for:
 * overall style, taking off a few elements -- Blog, About, Projects all are included here
 * also progress bars for skills are modified to contain words, not percentages
 
[4dcu.be](https://github.com/4dcu-be/4dcu.be)
 * vega-lite additions -- found in the `_plugins` folder and the vega-added things in `assets/js`


# ------------- Old ramblings below -------------

# Info for how this was created

1. Start by searching for Jeykll themes: https://github.com/topics/jekyll-theme
2. pick the following: https://github.com/YoussefRaafatNasry/portfolYOU
3. clone and follow the "Installation" instructions here: https://youssefraafatnasry.github.io/portfolYOU/docs/
4. Added port
5. remove Gemfile.lock if needed
trying to install with: bundle install --path ~/.gem
5. `bundle install` in directory 


bundle exec jekyll serve --> without the l for live reload if something else is running?

NOTE!!! it is quite likely that you have to serve the site locally and/or delete _site before pushing for your changes to go live.  I AM NOT SURE.  Have to re-start after you do a change to the config.yml file


