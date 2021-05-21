ruby '3.0.0'

source "https://rubygems.org"

git_source(:github) {|repo_name| "https://github.com/#{repo_name}" }

# webrick is not included in Ruby 3.0.0
gem "webrick", "~> 1.7"

gem "jekyll", "~> 4.2.0"

gem "minima", git: "https://github.com/jekyll/minima", :ref => '3cdd14d'

group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
end
