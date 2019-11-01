# dependencies (not sure if the xml libs are really required...)
sudo apt install ruby ruby-dev libffi-dev libxml2-dev ruby-libxml 

# Gems
gem install jekyll bundler
gem install github-pages
bundler install

# run and build locally
bundle exec jekyll serve --incremental --trace

