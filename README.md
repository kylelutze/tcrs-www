# don't run 3.1.3 all of the time because it screws with other mac stuff
rbenv shell 3.1.3

# update all dependencies
bundle lock --update
#get all of the plugin stuff
bundle install
#dev hot reload
bundle exec jekyll serve --livereload

# bundle dist
bundle exec jekyll build
