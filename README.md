
# Build Locally
## dependencies (not sure if the xml libs are really required...)
sudo apt install ruby ruby-dev libffi-dev libxml2-dev ruby-libxml 

## Gems
gem install jekyll bundler
gem install github-pages
bundler install

## run and build locally
bundle exec jekyll serve --incremental --trace

# Build with Docker

docker run --rm -it --volume="$PWD:/srv/jekyll" --volume="$PWD/vendor/bundle:/usr/local/bundle" --env JEKYLL_ENV=development -p 4000:4000 jekyll/jekyll:3.8.5 jekyll serve --watch --incremental --trace

## References
 
 * https://github.com/envygeeks/jekyll-docker
 * https://michaelsoolee.com/compile-jekyll-site-docker/
 * https://ddewaele.github.io/running-jekyll-in-docker/

