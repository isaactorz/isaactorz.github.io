source "https://rubygems.org"

git_source(:github) {|repo_name| "https://github.com/#{repo_name}" }

# webrick is not included in Ruby 3.0.0
gem "webrick", "~> 1.7"

gem "minima", git: "https://github.com/jekyll/minima"

gem "github-pages", "~> 214", group: :jekyll_plugins

group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
end
