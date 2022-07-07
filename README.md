# Pinpoint Website

Install ruby and build dependencies for Jekyll. This will depend on your OS, but instructions are at https://jekyllrb.com/docs/. Don't install jekyll yet. The below command is for ArchLinux.

```
sudo pacman -S ruby build-deps
```

Install bundler

```
gem install bundler
```

Install the bundle

```
bundle install
```

Run the local server

```
bundle exec jekyll serve --livereload
```

Visit the site at http://127.0.0.1:4000
